---
title: Wearable Intelligent Guide Device
summary: Advisor - Professor Zhuming Chen & Professor Yubai Li
type: project

tags: 
- Wearable Device
- Embedded Systems
- STM32

authors:
- Minel Huang
- Zobin Huang
- Zhe Xu
- Wenjing Lu
- Yuwei Wang
- Nan Chen
- Hang Lu
- Peng Xu
- Jiajie Cai

date: "2019-10-01T00:00:00Z"
lastmod: "2019-10-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by MinelHuang
  focal_point: Smart

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: "files/Wearable Intelligent Guide Device.pdf"
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

**Team members**:

​		Minel Huang, Zobin Huang, Zhe Xu, Wenjing Lu, Yuwei Wang, Nan Chen, Hang Lu, Peng Xu, Jiajie Cai

## **Wearable Intelligent Guide Device**

In this project we designed a wearable guide device for blind people. The device could help them avoid obstacles through voice interaction. In addition, it has image recognition and positioning functions, which helps blind people stay safe in complex environments. The third generation of guide device is as shown above and the second generation of guide device is as follows:

![](./01.png)

## **Key Technology**

The system structure is as follows:

![](./02.jpg)

We designed a Thermal Imaging Vision & Ultrasonic Obstacle Avoidance System which recognized obstacle types through neural network algorithms and measured distance to obstacles via the ultrasound system with an accuracy of 1 cm.

Besides, we designed GPS & Inertial Navigation & Vision Navigation System which navigated by calling a navigation app software interface and achieved accurate velocity measurement via EKF algorithm and Kalman filter. Indoor navigation system error was ±50 cm without visual calibration and ±15 cm with visual calibration.

Finally we applied for a Patent: A Wearable Intelligent Blind Guide Device (Current status: publication of invention patent application), Patent number: CN201910639192.3, and participated in the "Internet +" Innovation Competition.

**Link**:

​		Project codes: https://github.com/Huangxy-Minel/Wearable-Intelligent-Guide-Device