# Music Genre Identification

## Author : Surendran R

## Data set :  https://www.dropbox.com/s/4jw31k5mlzcmgis/genres.tar.gz?dl=0

## Objective : Given audio files for songs , we have to  identify which genre they fall in .

## Programming Language : Python 

## Model Architecture : Pre trained Model 
                        1.resnet34
                        2.vgg19
                        3.resnet152

## About Data Set:

The data  set consist of audio files for songs of following genre

'country', 'disco', 'hiphop', 'jazz', 'metal', 'pop', 'reggae', 'rock'


# Steps:


## Step 1: **Downloading the data set**


1.   Unziping the data set (tar file)
2.   converting the audio into array by librosa



### **Note** :
**ERROR_RATE** --> Using an input table, returns a table that calculates the rate of incorrect classifications and displays them as FLOAT values

## Step 2 : **Data pre-processing**

1.   Creating a function to convert the audio into spectogram of specific class or genre
2.  visualizing the data



## Step 3 : **Evaluvating the data using different pre trained model** 

1.   resnet34
2.   vgg19
3.   resnet152







## 1. resnet34



## **Error_rate :** 0.312500 (resnet34)

## 2.VGG19

## **Error_rate :** 0.287500 (vgg19)

## 3.resnet152

## **Error_rate :** 0.262500 (resnet152)






# Music-Genre-Identification___Surendran_R
