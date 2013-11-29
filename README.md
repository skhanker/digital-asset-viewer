Image Viewer Thingy
=====================

The purpose of this project is to build a new (or extend an existing) digitized item viewer, that would allow content
managers to add annotations to content etc etc gosh I could explain this better later on.

Goor Read: http://alistapart.com/article/takecontrolofyourmaps

Test at: dev.bcbib.library.ubc.ca
- select an area
- option/alt click to add an annotation

Requirements
---------------

#### Digitised Content
+ Ability to specify a region to annotate
+ Ability for this annotated region to scale with underlying content

#### Users
- Identity/Access Management
- Users can store annotations and then recall one (or more) to overlay on image

#### COntextualisation
- Can users load annotations only relevant to their needs? Ideas atm would be a drop down list from which they select thge annotation they want to see

#### Packed Resources for Consideration
+ BCBib Viewer
+ MapHub (forked, is Rails but can convert to PHP)
+ NYT Viewer
+ Tile Mill
+ Document Cloud
+ Leaflet
+ OpenLayers
+ Whatever 1940snewyork.com used
+ MapServer

#### Individual Resources
+ Mapnik
+ MagickTiler
+ TileCache