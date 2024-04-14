---
title: "Raspberry Pi Light Trace System - Embedded OS System
"
excerpt: "Step into the world of our Light Tracker project, where we've attempted to recreate the fascinating behavior of sunflowers. Through a combination of camera input, servo motors, and user-friendly controls, our system aims to follow moving light sources. Join us as we explore the intersection of nature and technology.<br/><img src='/images/portfolio-3.png'>"
collection: portfolio
---

**Project Overview**:  
I led a groundbreaking project centered on developing a Light Tracker system that emulates the natural behavior of sunflowers. This innovative project aimed to seamlessly integrate computer vision, servo motors, and user-friendly controls to create a system capable of accurately tracking moving light sources. The Light Tracker holds immense potential for applications in solar energy optimization, smart agriculture, and interactive art installations.<br/><img src='/images/portfolio-4.png'>

[Click here to watch the video!](https://www.bilibili.com/video/BV1qd4y1v7ze/)

**Design and Implementation**:  
The project encompassed two distinct approaches to light tracking:

1. **Camera-based Tracking**:  
   - Utilized OpenCV library to detect the brightest point in captured images.
   - Employed servo motors to adjust the panel's orientation, keeping the light source centered.

2. **Photoresistor-based Tracking**:  
   - Implemented four photoresistors to detect changes in light luminosity.
   - Calculated the light source's position based on the relative luminosity values.

The system combined mechanical and electronic components with Python programming on a Raspberry Pi to create a sophisticated light-tracking solution. Advanced techniques such as Gaussian filtering, edge detection, and proportional control were employed to enhance tracking accuracy and responsiveness.

**User Interface and Interaction**:  
- Developed an intuitive three-level GUI using piTFT touch control.
- Provided users with options to select the tracking method and display real-time system information.

**Hardware Integration and Optimization**:  
- Successfully integrated PCF8591 ADC-DAC modules and TCA9548A I2C multiplexer for photoresistor-based tracking.
- Optimized servo motor control using PWM signals for smooth and precise panel movement.
- Overcame challenges related to I2C bus communication and component compatibility.

**Project Management and Collaboration**:  
As the project lead, I effectively coordinated tasks, managed timelines, and fostered a collaborative environment within the team. Regular meetings were conducted to discuss progress, address challenges, and ensure alignment with project goals. I actively contributed to hardware assembly, software development, and system integration.

**Skill Enhancement**:  
This project significantly expanded my skill set, strengthening my expertise in computer vision, embedded systems, and hardware-software integration. I gained proficiency in OpenCV, Raspberry Pi programming, servo motor control, and I2C communication protocols. Additionally, the project honed my problem-solving abilities and reinforced the importance of effective project management and teamwork.

**Work Distribution**:  
<br/><img src='/images/portfolio-3.png'>  
Winchester Zhang (sz442): Circuit design, Software development (Photoresistor Mode), System testing

Yuning Xia (yx546): Software Development (Light Mode), Robot Motion System Development, Web Development

Suhan Shi (ss3389): Software Development (Photoresistor Mode), PyGame Interface Design, System Testing





