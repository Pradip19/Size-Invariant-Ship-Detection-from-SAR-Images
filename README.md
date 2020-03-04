# Size-Invariant-Ship-Detection-from-SAR-Images

	* Processing geo tiff files in python:

			 * Read and write geo tiff files.
		
	* Remove Speckle noise using NDSAR filter.


	* Generate Superpixels using fast-slic.


	* Use K-means to cluster the superpixels.


	* Identify and remove the land-superpixels.


	* Use GSHHG data to remove the landmass overlooked by Superpixel-merging.


	* Train VGG16 faster RCNN model for SHIP DETECTION.


	* Return the count of Ships.


	* Estimate Ship size using Haversine formula.


	* Output a Vector file with:

			* Location(XY - Latitude and Longitude).
			* Ship Count.
			* Ship Size.
		