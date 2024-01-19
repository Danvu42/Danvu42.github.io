---
layout: project
type: project
image: "../img/RQA/RQAThumbnail.png"
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

The Ride Quality Assessment project was a tool developed during my internship at the Honolulu Authority for Rapid Transportation. It was designed to quantify the mechanical vibration experienced within a Skyline train car. This project actually started before the opening of the Skyline in June 2023.

This project stands out in particular due to the fact that it a real world application of basic circuit analysis concepts. The data that is processed by the script is collected by an accelerometer, consisting of acceleration values plotted by time. The script uses the Fast Fourier Transform algorithm to plot the acceleration values by frequency instead of time, which is needed to compare to international standards for mechanical vibration.

This project was completed by two interns in the Core Systems department of HART, one of them being myself. However, each intern was asked to create their own versions of the ride quality analysis tool. Even though both interns were asked to create the script separately, much collaboration was done for the methods employed. Both of us were able to experiment with our own methods and share with each other our findings. The code was originally written in Matlab, but after the first analysis was done, I recreated the script in Python in order to continue working on extensions to the tool, such as GUI functionality and automatic pre-processing.

Not only did I get to practice my Python and Matlab numerical analysis skills using this project, I was also exposed to plenty of rail insight and expertise from the mentors of this project. I gained a lot of insight into the relationship between oversight agencies (HART) and their contractors (Hitachi Rail), and how important good software can be in determining actions taken by important project managers. This project was a great way to learn about real-world engineering problems, and I personally believe that I was able to make at least a small impact on this well known public project.



