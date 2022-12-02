# Image classification with Randon Forest in Google Earth Engine 

This is an exercise of classification to land use land cover. See the initial ajust to use the code. All the information is generated in the Google Earth Engine to do the classification 

### Initial settings:

### 1. Upload .zip compressed shp files and set with ROI

### 2. Select the drawing tool and select non-forest and forest samples, , you can define all classes in your area. 

### 3. Edit the Geometries:
  
  a) Rename the geometries (samples)
  
  b) Change the geometries to "FeatureCollection",
  
  c) In the example we In Property write "landcover" and in Value "1" for forest and "0" non-forest pair

### 4. Rename files and folder to export

Exemple in GEE: https://code.earthengine.google.com/9f1b2fe299ac6abc265b0c4e1c790b76?hideCode=true

![image](https://user-images.githubusercontent.com/60663771/205303561-bc0e4a30-3584-4a3f-994b-a1abcc47ab01.png)
