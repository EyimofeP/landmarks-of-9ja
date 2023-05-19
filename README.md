# The Landmarks of 9ja

[Check it Out!](https://eyes-of-landmarks.streamlit.app/Nigeria-Landmarks)
___
The aim of this project is to build an application that can classify eleven (11) popular natural & architectural landmarks that are in Nigeria. These landmarks include

* Bowers Tower, Ibadan, Oyo State

    *   <img src="data/bowers tower/bowerstower0.jpeg" alt="bowers tower" style="height: 300px; width:500px;"/> 

<br />

* Gidan Rumfa, Kano, Kano State

    *   <img src="data/gidan rumfa/gidanrumfa40.jpeg" alt="gidan rumfa" style="height: 300px; width:500px;"/> 

<br />

* Gurara Falls, Gurara, Niger State
    *   <img src="data/Gurara Falls/GuraraFalls19.jpeg" alt="gurara falls" style="height: 300px; width:500px;"/> 


<br />

* Kajuru Castle, Kajuru, Kaduna State

    *   <img src="data/kajuru castle/kajurucastle2.jpeg" alt="kajuru castle" style="height: 300px; width:500px;"/> 

<br />

* National Theatre, Surulere, Lagos State

    *   <img src="data/national theatre lagos/nationaltheatrelagos1.jpeg" alt="national theatre" style="height: 300px; width:500px;"/> 

<br />

* National Ecumenical Center, Abuja, Federal Capital Territory (FCT)

    *   <img src="data/national ecumenical center abuja/nationalecumenicalcenterabuja5.jpeg" alt="national ecumenical center abuja" style="height: 300px; width:500px;"/> 

<br />

* National Mosque, Abuja, FCT

    *   <img src="data/national mosque abuja/nationalmosqueabuja22.jpeg" alt="national mosque abuja" style="height: 300px; width:500px;"/> 

<br />

* Olumo Rock, Abeokuta, Ogun State

    *   <img src="data/olumo rock/olumorock181.jpeg" alt="olumo rock" style="height: 300px; width:500px;"/> 

<br />

* Osun Osogbo Sacred Grove, Osogbo, Osun State

    *   <img src="data/osun osogbo sacred grove/osunosogbosacredgrove4.jpeg" alt="osunosogbosacredgrove rock" style="height: 300px; width:500px;"/> 

<br />


* Tafawa Balewa Square (TBS), Onikan, Lagos State

    *   <img src="data/tafawa balewa square/necombuildinglagos75.jpeg" alt="tbs" style="height: 300px; width:500px;"/> 

<br />

* Zuma Rock, Abuja, FCT

    *   <img src="data/zuma rock/zumarock112.jpeg" alt="zuma rock" style="height: 300px; width:500px;"/> 

___
The data was scraped using the [Google Image Scraper](https://github.com/ohyicong/Google-Image-Scraper) tool to extract all the images from Google

___

* Extracted the data 

* Arranged and label the data

* Performed various Data Preprocessing techniques such as converting images into tensors and feature normalization/scaling

* Convolutional Neural Networks (CNN) using Data Augmentation and Transfer Learning / Pretrained Model to achieved best performance

* **Tuned Inception V3** achieved best performance with **84% training accuracy** and **93.3% test accuracy**

___
## Model Performamce
Accuracy with Confusion Matrix was used to evaluate performance. 

* **Tuned Inception V3 with Data Augmentation**
    * Training Accuracy : 84%
    * Testing Accuracy : 93.3%
    * Confusion Matrix
    ![CF of base](plots/cf.png)
___
## Model Deployment
The final model with the best score was deployed on a web application built with **Streamlit**

![Web application of the model](plots/app.png)
___ 
