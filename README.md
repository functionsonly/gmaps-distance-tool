	gmapsDistanceTool.js for Google Maps -- Basic library for calculating distance(s) 
		between clicked points (IE11 javascript compatible)

	Required dependencies:
		Google Maps v3+
		jQuery v3+ (older versions have not been tested)
		Bootstrap v4+ (older versions have not been tested)

	Install:
		1.  Load gmapsDistanceTool.js after the required dependencies are loaded
		2.  Create a div inside the Google Map container, eg:
			<div id="map"><div id="distanceTool"></div></div>
		3.  Initiate distance tool after Google Maps object is available, 
		    in this case 'map' is the Google Map object, ie:
			var map = new google.maps.Map(document.getElementById('map'), {});
			var distanceTool = new gmapsDistanceTool(map, 'distanceTool'); 

	HTML Element class/id's used by this library:
		ID's:
			gdtDistanceDiv
			gdtLineDistance
			gdtUnitLabel
		class:
			gdtDistanceUnits
			gdtLineDisplay
		Check to make sure class/id's do not conflict

	Use:
		Right-click on map to set initial point.
		Right-click on point to delete a previously set point.
		
	Updated:
		2019-Feb-21 -- v0.1 -- Epoch
		2019-Mar-03 -- v0.1.1 -- Updated for Boostrap 4 only 
