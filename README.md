# Vision_data_EDA
supports Yolo format data, Gets insights from data


#installation

```
# !pip install pdf2image
# !apt-get install poppler-utils
# !pip install Pygments
# !pip install data-gradients==0.1.4

```

# To run

#### Inside data folder upload the data, here is a sample data link, just move the data to this folder
download data
```
https://drive.google.com/drive/folders/1dPNgUWj7CjFFdCODlLq-ac_4JeXjDIp7?usp=sharing
```

#### data format yolov5,yolov8 
```
train- images & labels
val- images & labels
data.yaml
```


```
!python3 run_EDA.py
```


# output
you will get output in the logs folder which contains pfd

```
Object Detection Features output
1. Distribution of Bounding Box Area
2. Intersection of Bounding Boxes
3. Distribution of Bounding Box per image
4. Distribution of Bounding Box Width and Height
5. Class Frequency
6. Bounding Boxes Density
7. Distribution of Class Frequency per Image
8. Visualization of Samples

```

<img width="352" alt="image" src="https://github.com/akashAD98/Vision_data_EDA/assets/62583018/f47a0cde-be2e-45c0-a0b7-68de8b5fa6e7">




reference
```
https://github.com/Deci-AI/data-gradients.git
https://github.com/ultralytics/ultralytics.git
```
