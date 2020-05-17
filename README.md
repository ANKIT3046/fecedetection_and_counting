# fecedetection_and_counting
Use Tensor flow to create mass face detection from a group picture and count face 

step 1-
unzip images.zip file by
!unzip images.zip
then images folder contain different images you can uplode your own image onwhich you wNT TO TEST
sample
# images 
  -p1.jpg
  -p2.jpg
  -p3.jpg
  -p4.jpg
  -p5.jpg
  -p6.jpg
  -p7.jpg
unzip yad2k.zip file
by !unzip yad2k.zip
# yad2k
   models
    -keras_darknet19.py
    -keras_yolo.py
   utils
    -__init__.py
    -utils.py
!unzip model_data.zip
#model_data
  -coco_classes.txt
  -object_classes.txt
  -yolo.h5
  -yolo_anchors.txt
  
### yolo_utils.py
  contain different functions
    read_classes, read_anchors, generate_colors, scale_boxes, preprocess_image, draw_boxes

### keras_yolo.py 
  contain diferent functions
   yolo_head, yolo_boxes_to_corners, preprocess_true_boxes, yolo_loss, yolo_body


## steps how this project is made
# stpe1-
## impoer different  library
  1.numpy
  2.pandas
  3.matplotlib
  4.scipy
  5.PIL
   6.most importent tensorflow
  7. keras
  8.yolo_utils.py
# step2 
## then we use yolo algorithm to train our model

# step3
## Filtering with a threshold on class scores

# step4
## Non-max suppression

# step5
## Wrapping up the filtering
# step6
## Test YOLO pretrained model on images
# step7
##  Defining classes, anchors and image shape.
# step8
## Loading a pretrained model
# step9
## checking model summery
# step10
##  Convert output of the model to usable bounding box tensors
# step11
## Filtering boxes
# step12
## At last run pridict function to pridict our model


To test the model on your own images:


1. Add your image to this Jupyter Notebook's directory, in the "images" folder
2. Write your image's name in the cell above code
3. Run the code and see the output of the algorithm!

  

