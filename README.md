# WindmillDetectorModel

The acquired information originates from OpenStreetMap. To ensure relevance and efficiency, a specific filter was utilised to keep only important data from OSM. The file for generating data instituted an automated procedure to crop Regions of Interest (ROI) from extensive satellite images, employing 256*256 image coordinates. I incorporated an additional command to account for the coordinate system, thus ensuring each cropping was matched with the accurate coordinate system for its respective area. It should be emphasized that the OSM data tagging system requires enhancement for a more comprehensive description of its features. Consequently, further documentation of Oil Rigs and other floating objects is necessary.
<br/>
Data before Augmentation
![PieChartBefore](https://github.com/td121/WindmillDetectorModel/assets/94444639/7759260e-2e72-451a-95fe-1233ba335d60)
<br/>
Data after Augmentation
![PieChart](https://github.com/td121/WindmillDetectorModel/assets/94444639/39c9c225-721d-4aaf-9125-b8227cf64086)
<br/>
Validation confusion matrix
![Val Result Confusion Matrix](https://github.com/td121/WindmillDetectorModel/assets/94444639/b22584c0-17a3-437e-b114-249c69c2066c)
<br/>
Testing confusion matrix
![Test Result Confusion Matrix](https://github.com/td121/WindmillDetectorModel/assets/94444639/faa2b75b-30b0-4d3b-859e-80a5052ae2e5)
<br/>
Log
![Result_TrainingLoss](https://github.com/td121/WindmillDetectorModel/assets/94444639/681b7ddd-52d9-44ac-87dd-5899ec426c2f)
<br/>
Example of model prediction - 1
![Result 1](https://github.com/td121/WindmillDetectorModel/assets/94444639/8eb908c7-c46b-4429-95fe-057c4f1b2048)
<br/>
Example of model prediction - 2
![Random Check Final](https://github.com/td121/WindmillDetectorModel/assets/94444639/e2393316-0295-4f17-b27c-31c2c81c223e)
<br/>


