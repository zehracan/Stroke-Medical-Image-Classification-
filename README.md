# Stroke-Medical-Image-Classification-
Project written with the transfer learning method using efficientnetb2, which makes the classification of healthy and stroke <br>

Data is not public so if you are wondering how the file layout is: <br>
Parent folder is data :
![image](https://user-images.githubusercontent.com/61902608/190482493-b5520356-f4f4-40b4-9d73-c92f606530d5.png) <br>
And data has 2 folder named as val and train <br>
train folder has 3556 png and -to be balanced- half of them healthy, half of them stroke brain CT's. <br>
![image](https://user-images.githubusercontent.com/61902608/190483019-03b861d9-9edb-46b4-8b40-fc969142172f.png) <br>

val folder -which i use for test (Don't be confused by the name :) )- has 890 PNG. It consists of stroke(445) and healthy(445) images, half as well as on the train. <br>
![image](https://user-images.githubusercontent.com/61902608/190483878-78bca4c5-76e2-4724-ad73-ef11dbe73ebb.png)
<br>
The image shape resized to 150X150 because imagenet trained by 150x150x3 images. <br>
