# Singing Voice Conversion

[![Video Label](http://img.youtube.com/vi/2wHfMukP4hk/0.jpg)](https://youtu.be/2wHfMukP4hk?si=XWouEzIgAWzq_HQX&t=37)

## People

* [Yeongjin Kim](https://github.com/kyj950514 "김영진")
* [Heewon Seo](https://github.com/heewonsuhh "서희원")

## Language / IDE

* <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=white"/><img src="https://img.shields.io/badge/Google Colab-F9AB00?style=flat&logo=Google Colab&logoColor=white"/>
* <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=OpenJDK&logoColor=white"/><img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat&logo=Spring Boot&logoColor=white"/><img src="https://img.shields.io/badge/IntelliJ-000000?style=flat&logo=IntelliJ IDEA&logoColor=white"/><img src="https://img.shields.io/badge/Amazon S3-569A31?style=flat&logo=Amazon S3&logoColor=white"/>
* <img src="https://img.shields.io/badge/NGINX-009639?style=flat&logo=NGINX&logoColor=white"/><img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=flat&logo=Amazon EC2&logoColor=white"/>
* <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=MySQL&logoColor=white"/><img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=flat&logo=Amazon RDS&logoColor=white"/>

## Dataset

* 2 hours audio file (15 minutes of speaking & 1 hour 45 minutes of singing)
* Mono channel 16bit 44,100khz
* .wav file
* No backgroun sound (Noise removal)
* Constant voice size
* The tone is constant, but the range is varied
* Voice volume normalize
* Split by 10 seconds (650 audio files)

## Model
  
* OCR (CNN - LSTM - CTC Loss)

<img src="./images/3-1.png" width="70%" height="70%"/>

## Optimizer


## Result

* Train Accuracy : 45.07%
* Val Accuracy : 59.35%
