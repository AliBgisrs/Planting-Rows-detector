# Planting-Rows-detector
If you need to extract a specific line from all plants located in a particular row, this tool would be helpful.

![image](https://github.com/AliBgisrs/Planting-Rows-detector/assets/109620013/0da43adc-14f5-4b0d-8fae-2403081fce95)


Sometimes, it's necessary to identify planting rows for specific crops, such as corn or sugar beet. In this tool, various spatial concepts are employed to detect the center point of each polygon and connect them, creating planting rows for all crops with similar row patterns. If you are an ARCGIS user with a similar goal, this tool could be helpful. To use this tool, simply download and unzip it, add it to your ArcGIS environment, and then assign a polygon layer extracted from the NDVI image of your field, along with an output directory to save the result layer. Finally, run the tool. If the planting rows follow a vertical pattern, use the VerticalRowDetection tool; otherwise, use the HorizontalRowDetecti
