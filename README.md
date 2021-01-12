# Covid_Face_Mask_Detection_using_yolov4
 This is a face mask detection using object detector i.e yolov4 for mask detection in a simple way.
In general for custom training the yolov4 there are lots of changes needed to be done for many file, for starters it will be cumbersome.
But here I will show you a smile way to train your object detector (for simplicity I have trained it on Mask Detection).
Lets get started
1. Download the dataset from <a>https://www.kaggle.com/andrewmvd/face-mask-detection<a> 
2. Upload the dataset in the Roboflow account 
3. Generate the dataset in the "YOLO Darknet " format which consists of the bounding box co-ordination in the text file format.  Copy the link and use it in the notebook.
4.Open the Mask_Detection_Yolov4-Training.ipynb in collab and run the cell after pasting the darknet url.
5. Training will take a couple of hours.
6. Afte the training is done. Great job.
You can check for a few preditions using the test images. See for yourself
