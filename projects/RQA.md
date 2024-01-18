---
layout: project
type: project
image: "https://media.licdn.com/dms/image/D562DAQEMdRhW3ZH1mg/profile-treasury-image-shrink_800_800/0/1695032972400?e=1706144400&v=beta&t=e1kQRjYOstYrIsDDUCT4dl0zxFJpHobpDQJ6wHpUVVQ"
title: "Ride Quality Assessment"
date: 2023
published: true
labels:
    - Rail Transportation
    - Test Analysis
    - Python
summary: "Ride Quality Assessment Tool to quantify mechanical vibration of train car"
---
<p align="center">
    <img width="700px" class="img-fluid" src="https://media.licdn.com/dms/image/D562DAQEMdRhW3ZH1mg/profile-treasury-image-shrink_800_800/0/1695032972400?e=1706144400&v=beta&t=e1kQRjYOstYrIsDDUCT4dl0zxFJpHobpDQJ6wHpUVVQ">
</p>

The Ride Quality Assessment project was a tool developed during my internship at HART. It was designed to quantify the mechanical vibration experienced within a Skyline train car. 

This project stands out in particular due to the fact that it a real world application of basic circuit analysis concepts. The data that is processed by the script is collected by an accelerometer, consisting of acceleration values plotted by time. The script uses the Fast Fourier Transform algorithm to plot the acceleration values by frequency instead of time, which is needed to compare to international standards for mechanical vibration.

