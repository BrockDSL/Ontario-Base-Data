# Ontario Basic Mapping Data
Ontario Base Maps are a popular paper collection of maps that provide large scale coverage of the province (1:10,000 - 1:20,000). The Ontario Basic Mapping Data represents the various geospatial layers that make up these topographic maps. Although the referenced web app and data is somewhat dated (1980s), it will prove useful for historical context or basic mapping at a large scale.  

### Access the Data
1. Go to [http://www.geographynetwork.ca/website/obm/viewer.htm](http://www.geographynetwork.ca/website/obm/viewer.htm)
2. To zoom to your area of interest click the binoculars to search for an upper tier municipality, such as "Niagara". 
3. Click Find String.  
4. From the results displayed at the bottom of the window, click the tiny blue link to the left of the result. The map will zoom to the extent of the upper tier municipality. See screenshot below.

   ![interface](OBM1.jpg) 
   
6. Zoom in even more by clicking the plus magnifying glass and drawing a box on the map. As you zoom in, various layers will become visible. See the layer listing to the right of the map view.

    ![zoom](OBM2.jpg)
    
8. To turn a layer off, uncheck the visibility box and scroll down in the listing to see the REFRESH button.


### Downloading Data

1. Once you have the zoom and layers set, click the FME icon to trigger the download wizard. See the circled FME button below.

    ![FME](OBM3.jpg)
    
2. You will be prompted to sign in or register for a free account.
3. Enter your email and click Proceed to Download.
4. The interface uses FME translation software to clip and ship the geospatial data. Check the box to agree to the license terms and conditions.
5. Make other selections as appropriate including download format, coordinates, layers, etc.

    ![download window](OBM4.jpg)  
    
5. Click Download Data. You will be prompted with a window thanking you for your download request.
6. Go to your email and check for a message from the Geography Network.
7. Click the link provided to download a zip file containing all of your data.

NOTE: You may need to right-click the link and select *Save File As* to download the file.
NOTE 2: You may also be prompted with a warning about security. Select *keep* from the options to download the file.

   ![mail](OBM5.jpg)
    
8. View your DOWNLOADS directory.
9. Right-click the zip file and select *Extract All*.
10. Define a directory for the unzipped files and click *Extract*.

    ![zipped file](OBM6.jpg)

The layers are now ready to be added to your GIS project. Be sure to run the software (ArcGIS Pro, QGIS) before adding the shapefiles.

---
  
 
This tutorial is brought to you by the [Brock University Map, Data & GIS Library](https://brocku.ca/library/mdgl/)  E-mail us at [maplib@brocku.ca](mailto:maplib@brocku.ca)
  
You can also find us on:  
[Facebook](https://www.facebook.com/Brock-University-Map-Data-GIS-Library-107927255178257)  
[Twitter](https://twitter.com/BrockU_MDGL)  
[Instagram](https://www.instagram.com/brockmdgl/)   
 


<!--- Please use reference style images so that it is easier to update pictures later --->

![MDGLlogo](MapDataGIS_sm.png)
