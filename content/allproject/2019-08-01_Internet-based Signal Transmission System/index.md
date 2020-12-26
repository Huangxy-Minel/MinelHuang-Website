---
title: Internet-based Signal Transmission System
summary: Advisor - Professor Zhongxiao Yang
type: project

tags: 
- Network Science
- Embedded Systems
- STM32

authors:
- Minel Huang
- Peng Xu
- Jiajie Cai

date: "2019-08-01T00:00:00Z"
lastmod: "2019-08-01T00:00:00Z"

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
url_code: "https://github.com/Huangxy-Minel/Internet-based-Signal-Transmission-System"
url_pdf: ""
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

​		Minel Huang, Peng Xu, Jiajie Cai

## **Internet-based Signal Transmission System**

The project requirement is that collect signals at the same time and transmit the results to another terminal across the network via TCP. Therefore, we needed to design three terminals, which are responsible for collecting signals and output signal. The system structure is as follows:



![](./01.png)

In order to synchronously collect signal in high-speed, we introduced PTP protocol based on DP83640. In addition, we introduced LwIP protocol to STM32H7 so that terminals can communicate with each other by TCP/IP connection. The final device is as follows and we participated in the National Electronic Design Competition.

![](./02.jpeg)

**Link**:

​		STM32 codes: https://github.com/Huangxy-Minel/Internet-based-Signal-Transmission-System