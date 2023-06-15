# Machine-Learning-Application

This repositories is made for machine learning part of SoilIt development.

### Collect Data for Dataset
The data is collected by using Bing Image Downloader library. Each class get 120 picture collected.
<br>Code example of 'Tanah Laterit':</br>
![image](https://github.com/SoilIt/Machine-Learning-Application/assets/72585488/fae0ef96-8de0-4b28-a493-e88b5a939e14)


### Preprocessing Data
To remove undesired data, the data of soil image and plant are processed. Panda processes the Plant dataset, whereas Tensorflow processes the Image dataset.

### Training model
The model is created with mobilenetv2. Then it converted by tensorflow lite for deployment to android.

### TF Lite
It consists of Soil Class labels and the model for deployment.
