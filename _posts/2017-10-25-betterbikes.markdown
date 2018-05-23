---
layout: post
title:  "OpenCV Vehicle Recognition Model"
description: "Built a real-time image recognition model in OpenCV using Haar Cascades"
subtitle: "🏆 Winning hackathon project"
date:   2017-10-25 15:39:40
author: "Nick"
avatar: "img/nick.png"
img: betterbikes/car.jpg
---

[Github link](https://github.com/nighthawk469/betterbikelanes-opencv)

### Summary

While attending THacks Hackathon at UofT, our team created a computer vision platform for mobile that automatically detects and reports when cars are parked in the bike lane.

![Picture 1]({{site.baseurl}}/assets/img/betterbikes/team.jpg)

## My Contributions 
- I had the initial idea for the project
- I worked on OpenCV/TensorFlow image recognition in Python
- I worked with the Google Maps API

## Inspiration
Bike lanes are awesome except when they are blocked with a parked car. When a car is blocking the lane it can be very dangerous to try and go around the car. We wanted to create a platform that 1) allowed users to be aware of blocked bike lanes on their route and 2) let users report blocked lanes for other users to see.

## What it does
To use our platform simply mount your phone to your bike's handle bars, and while you are biking, the app will recognize when cars are parked inside the bike lane, using OpenCV. When the lane is obstructed it will be marked on a map for other user's to see and avoid. In addition, the license plate of the car will be sent to local authorities. No manual data entry is needed by the user.