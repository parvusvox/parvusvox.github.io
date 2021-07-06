---
title: "Fir Tree Stats"
date: 2021-07-06T22:56:14+09:00
draft: false
categories: [projects]
tags: [Python, Computer Vision, YOLOV3, WebSockets, DLIB, RNN, C++]
---

### Developer

A computer vision system & web frontend that utilizes fast object detection algorithms on single-board computers and time series forecasting to predict & display wait times at the school grill

## Motivation
The Fir Tree is a school grill and is oftentimes very crowded and lines regularly reach the exit doors. To alleviate long lines and pressure from workers, I created Fir Tree Stats, a live-updating dashboard that tells you exactly how many people are waiting in the line currently, how long it will take for you to get your food, and how many people were inside the restaurant.

## Solution
Fir Tree Stats utilizes an object detection algorithm and time series forecasting to determine the number of people and projected wait time. Most importantly, the system operated entirely off of a single Raspberry Pi 3 communicating with a webserver without any human intervention.

Unfortunately, the system never reached full operation due to COVID-19 and subsequent closures but implementation was completed.

