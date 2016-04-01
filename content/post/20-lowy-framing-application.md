+++
date = "2010-01-01"

title = "Framing Application"
image = "frames/lowy.jpg" # optional

+++
<script src="/galleria/galleria-1.4.2.min.js"></script>

## Frame Search Tool
{{< figure src= "/images/frames/lowy.jpg" title="" caption="Above: The final tool with search contained within the sidebar">}}

Lowy specialises in fine art antique and reproduction frames. They work with top galleries and museums in New York and across the world. Their clients are often very busy, and once they have aquired a work of art, they simply want a frame that fits their decor, budget and the work of art itself.

This intranet tool allows high-quality capture of frames (through a SLR camera) and virtual compositing of customers’ works of art with Lowy’s frames. Lowy had built a compositing tool with IBM in the 90's, and this is the tool we built to replace it.

The purpose of the tool is to allow customers to envisualize their beautiful artwork in a selection of frames. This greatly assists the sales team, as they don't have to rely on customers imagination, they can show prospective customers exactly how their frames would look.

For customers, it reduces the risk, there's a lot less guesswork involved, and seeing your picasso in a photorealistic context in a few frames will help you narrow down to the best fit.

## Early Wireframes

<div class="galleria" style="width: 600px;height: 701px; background: #555; border:0; padding:0; margin:0;" >
    <img src="/images/frames/Frame-Finder-tabbed-1.png" data-title="Faceted Frame Search" data-description="Criteria from existing inventory used to populate the search page.">
    <img src="/images/frames/functioning-prototype.png" data-title="Early search prototype" data-description="Working prototype for the search.">
    <img src="/images/frames/framesView-action.jpg" data-title="Later search prototype" data-description="Later prototype is more compact.">
    <img src="/images/frames/Frame-Finder-tabbed-2.png" data-title="Search Results" data-description="Frames that match the search criteria">
    <img src="/images/frames/Frame-Finder-tabbed-3.png" data-title="Frame Detail" data-description="Summary information about an individual frame.">
    <img src="/images/frames/Frame-Finder-tabbed-4.png" data-title="Artwork Search/Upload" data-description="Sales team members could search for existing artwork or upload something new.">
    <img src="/images/frames/Frame-Finder-tabbed-5.png" data-title="Artwork Portfolio" data-description="Client's art works assembled together.">
    <img src="/images/frames/Frame-Finder-tabbed-6.png" data-title="Framed Art Composites" data-description="This screen shows art applied to frames, to be reviewed by the client.">
</div>


Once client requirements were understood, this initial wireframe shows workflow order: 

 * Search for frame using multiple criteria.
 * Select desired frames from grid.
 * Review frame detail.
 * Add artwork.
 * Review uploaded artwork.
 * Review completed composite artwork and frame combinations.

----
## Proposed Scope and Approach

{{< figure src= "/images/frames/lowy-workflow.png" title="" caption="">}}

This diagram helped decision makers understand the proposed setup and allowed them to double check our assumptions.


----

## Inventory Management

<div class="galleria" style="width: 700px;height: 600px; background: #555; border:0; padding:0; margin:0;" >
    <img src="/images/frames/Lowy-maintenance-edit.png" data-title="Initial Maintenance Screen" data-description="">
    <img src="/images/frames/delete-frame.png" data-title="Frame detail management" data-description="">
    <img src="/images/frames/Lowy-design-all-frames-view-sm.png" data-title="Inventory view" data-description="">
    <img src="/images/frames/Lowy-maintenance-import-sm.png" data-title="Frame import wireframe" data-description="">
</div>

Searching for frames relies on good metadata. The metadata is entered and managed through the manage frame screen (wireframe and finished screen are shown).

* Art Direction
* Client Contact
* Cloud setup
* In house hardware selection and setup
* Information Architecture
* Product Design
