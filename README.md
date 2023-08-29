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

* Voice: [Yeongjin Kim](https://github.com/kyj950514 "김영진")
* 2 hours audio file (15 minutes of speaking & 1 hour 45 minutes of singing)
* Mono channel 16bit 44,100khz
* .wav file
* No backgroun sound (Noise removal)
* Constant voice size
* The tone is constant, but the range is varied
* Voice volume normalize
* Split by 10 seconds (650 audio files)

## Model

* DDSP-SVC
  * New open source singing voice conversion project dedicated to the development of free AI voice changer software that can be popularized on personal computers.
  * Its training and synthesis have much lower requirements for computer hardware
  * The training time can be shortened by orders of magnitude, which is close to the training speed of RVC.
  * When performing real-time voice changing, the hardware resource consumption of this project is significantly lower than that of SO-VITS-SVC，but probably slightly higher than the latest version of RVC.

ㅤㅤㅤ<img src="./images/2.png" width="70%" height="70%"/>

</br>

* RVC
  * Reduce tone leakage by replacing the source feature to training-set feature using top1 retrieval.
  * Easy and fast training, even on relatively poor graphics cards.
  * Training with a small amount of data also obtains relatively good results (>=10min low noise speech recommended)
  * Supporting model fusion to change timbres (using ckpt processing tab->ckpt merge)
  * Easy-to-use Webui interface.
  * Use the UVR5 model to quickly separate vocals and instruments.

ㅤㅤㅤ<img src="./images/4.jpg" width="70%" height="70%"/>

## DDSP-SVC

<img src="./images/1.png" width="40%" height="40%"/>

## RVC

<img src="./images/3.jfif" width="40%" height="40%"/>
