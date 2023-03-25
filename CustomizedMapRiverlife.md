<h1 align="center" style="margin-top: 0px;">Bid Proposal</h1>

<p align="center" >Customized Riverfront Guide Basemap for Riverlife</p>
<p align="center" >Carnegie Mellon University, Keyi Chai</p>
<p align="center" >March 25, 2023</p>

**TO:**

*[Riverlife](https://riverlifepgh.org/)*

*One North Shore Center, 12 Federal Street, Suite 130*

*Pittsburgh, PA 15212*

*412-258-6636*

## **Project timeline and cost**

The estimated completion time is approximately six hours after the start, with an estimated client cost of $600. 

## **Screenshots for preview at 3 different zoom levels**

![riverlife(1)](https://user-images.githubusercontent.com/127965922/227678457-e7a67792-8ce2-4dc4-81dc-876a35367c22.jpg)

![riverlife](https://user-images.githubusercontent.com/127965922/227637214-bb181e1f-f6f1-47fb-8869-38a9bd9c78e2.jpg)

![riverlife(3)](https://user-images.githubusercontent.com/127965922/227678463-75c0e127-8ae4-4f55-9d02-65c63e95cae3.jpg)

## **Color palette**

The color palette I used was extracted via Canva which perfectly matches the Riverlife website.

![colorpanel](https://user-images.githubusercontent.com/127965922/227637290-507a45df-80bb-4b79-b0de-bd3f883ce4bd.jpg)

## **Here's how I made my design decisions**

1. In the [Google Maps Styling Wizard](https://mapstyle.withgoogle.com/), I started with the Standard theme that matched the overall style I wanted to emulate in the map.
2. I changed the color of the water to Paradiso(#2b6376). By doing so, I emphasized the body of water and reduced the weight of vehicular traffic in the map by changing the color of the roads to white to highlight the green spaces and pedestrian system along the river. At the same time, I applied the green color from the palette to other ground features such as man-made landscapes (Aqua Haza #e9f2f0).
3. To make the attractions on the river stand out, I chose to hide some labels for non-public attractions and improve the font style by adding borders and changing the color of the font fill (Tussock #c98d3a for Neighborhood labels) to highlight the parks and trails along the river.

Overall, I redesigned the base image to be less saturated, in order to better highlight bodies of water and riverlife-related items. 

## **JSON code**
Here's the link to my [JSON file](RiverlifeStyle.json) and you can easily download and my JSON code and import via [Google Maps Styling Wizard](https://mapstyle.withgoogle.com/) and get the exactly same style I designed!

## **Lookup Table**
In addition, I provide this lookup table that documents the feature type, element type and stylers for all relevant features, which you'll use to help navigate where to make changes.

|Feature type |Element type |Stylers|
|-------------------------|---------------|---------------|
|Administrative/Neighborhood |Labels/Text/Fill |Color: Tussock #c98d3a|
|Landscape/Man_made          |Geometry/Fill    |Color: Aqua Haze #e9f2f0|
|Landscape/Natural/Landcover |Geometry/Fill    |Color: Pastel Gray #cdd0c2|
|POI|Labels|Visibility:off|
|POI/Attraction| |Visibility: simplified|
|POI/Park|Geometry/Fill|Color: Eton Blue #9ec798|
|Road/Highway|Geometry/Fill|Color: White #ffffff|
|Road/Highway/Controlled_access|Labels/Icon|Visibility: off|
|Water|Geometry|Color: Paradiso #2b6376|
|Water|Labels|Color: White #ffffff|
