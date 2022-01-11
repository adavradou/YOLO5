# YOLO5
Customization of the YOLO5 implementation provided by https://github.com/ultralytics/yolov5, in order to train on custom DFU data.

Both training and testing is executed on Google Colab.

The large YOLO model was trained on 150 epochs and gives good prediction of ulcer of diabetic feet: 

![test_example](https://user-images.githubusercontent.com/30274421/148857702-0e9aa663-116f-4ca4-8b57-03c6927da47f.png)

The model achieves a mAP@0.5 of 82%.



## Training on colab
The data structure on colab has the following form:

![image](https://user-images.githubusercontent.com/30274421/148858190-9daa29bc-1b19-4315-8176-8b9be2c4fa7c.png)

- All the codes are kept in folder "Codes".

- The dataset, .yaml and .txt files are uploaded in folder "Input".

- The model will output the results for training and testing in folder "Results".
