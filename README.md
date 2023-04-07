# CS396 Advanced Computer Graphics Seminar: VR/AR Systems

![cover_image](https://github.com/JipengSun/2023_NU_Summer_VR/blob/main/vr_ar_cover_2.png?raw=true)

Course Coordinator: 

[Prof. Jack Tumblin, Northwestern University](https://www.mccormick.northwestern.edu/research-faculty/directory/profiles/tumblin-jack.html)

Course Instructor: 

[Jipeng Sun, Northwestern University](https://jipengsun.github.io/)

Course Assistant: 

[Ashwin Baluja, Northwestern University](https://www.linkedin.com/in/ashwinbaluja/)

## Introduction
[Course website](https://jipengsun.github.io/2023_NU_Summer_VR/)

[Course Summary Notes from Ashwin Baluja](https://docs.google.com/document/d/1KwzQh9GtexCEEMtMlNWnygPWvxoisXmhsLYb3fq0bsw/edit)

## Syllabus

### Week 1: Introduction to VR/AR Systems
**Key questions to ask** 

1. What really makes a VR VR? 

2. What is the computational process of transforming a 3D scene to what displayed to your eyes?

Introduction to VR/AR systems and basic graphics pipelines.

### Week 2: Design VR Systems from Scratch
**Key questions to ask** 

1. What is the minimum viable product (MVP) for a VR? 

2. How could we turn a passion/dream into a workable engineering plan? 

3. What are the tradeoffs for different design plans?

VR design plans brain storming. There is no 'correct' answers for engineering. The problem we are facing is: 'Driven by your passion/goal, given limited resources, knowing what is your metrics to evaluate success, how to make your best possible plan and act on it.' Come up with a step-by-step hardware prototyping iteration plan. Start sourcing the hardware components based on your design.

[Brainstorm Recording Notes from Ashwin Baluja](https://docs.google.com/document/d/1095E-3hxstYPrixhDUMt8MTo0VFCKXdvQ9nbPGZaKUU/edit)

### Week 3: Graphics Rendering Pipeline on Emebedded Systems
**Key questions to ask** 

1. Given a designed MVP, which is a near eye monitor, how to draw/render scenes on that screen?

2. What is the logic of the graphics rendering pipeline?

3. How to use WebGL to implement the rendering pipeline?

### Week 4: Human Binocular Vision System
**Key questions to ask** 

1. Will the current implemented binocular rendering effect work? Why it won't give us 3D effect?

2. What are the biological anatomy and functions of human binocular eyes? 

3. How should we change our graphics rendering logics to fit for human perception?

4. What are the depth cues for human? How does the relative importance of them change based on the distance?

5. Why will we feel dizzy wearing VR/AR glasses? What is the vergence & accommodation problem?

### Week 5: Near-Eye Display Optics
**Key questions to ask** 

1. To make it real, how to make a 2-cm far displayed image be perceived as 1.5-meter away from the users?

2. What are the poplur optical components of current near eye display? How do they work? What are the trade-offs?

3. Will the rendered images look distorted after adding lens between the display and eyes? If so, how should we correct them?

4. How could we solve the dizziness problem caused by vergence & accommodation conflict?

## Sourcing

### Microprocessor

+ [Raspberry Pi Zero 2W](https://www.raspberrypi.com/products/raspberry-pi-zero-2-w/)

+ [Teensy 4.1](https://www.pjrc.com/store/teensy41.html)

### OS Hardware (Mini Computer)

+ [Raspberry Pi 3 B](https://www.amazon.com/s?k=Raspberry+Pi)

+ [Libre Le Patato](https://libre.computer/products/aml-s905x-cc/)

### Display

Mono-Display
+ [7 inch LCD (STARTEK IPS Module)](https://www.alibaba.com/product-detail/5-5-5-5-6-5_1600512906287.html?spm=a2700.details.0.0.6aa27b35LK90YX)

+ [6 inch LCD (Eurotech Ltd.)](https://www.alibaba.com/product-detail/OEM-ODM-6-Inch-Tft-PCAP_1600162048967.html?s=p)

+ [6 inch LCD (Elida Ltd.)](https://www.alibaba.com/product-detail/High-resolution-7-inch-LCD-display_62446541480.html)

Binocluar-Displays
+ [4 inch Square LCD](https://www.alibaba.com/product-detail/4-0inch-Square-tft-lcd-display_62075695201.html?spm=a2700.7724857.0.0.16502b63kK0wwP)

### Inertial Measurement Unit (IMU w/ or w/o Fusion)
+ [HiLetgo MPU-6050](https://www.amazon.com/Pack-Google-Cardboard-Bi-convex-Biconvex/dp/B01FWVWUEU/ref=sr_1_6?keywords=Virtual+Reality+Lenses&qid=1675283182&sr=8-6)

+ [Adafruit 9-DOF IMU Fusion Breakout - BNO085](https://www.adafruit.com/product/4754)

### Lens
+ [Google Cardboard Biconvex Lens](https://www.amazon.com/Pack-Google-Cardboard-Bi-convex-Biconvex/dp/B01FWVWUEU/ref=sr_1_6?keywords=Virtual+Reality+Lenses&qid=1675283182&sr=8-6)

### Closure with Handle
+ [ATLASONIX](https://www.amazon.com/Headset-Compatible-iPhone-Android-Phones/dp/B07WRYK1BD/ref=sr_1_6?crid=L0HVNTUMBKD0&keywords=viewmaster+deluxe+vr+viewer&qid=1677732551&sprefix=viewmaster+delu%2Caps%2C203&sr=8-6)

### Camera (Optional)
+ [Raspberry Pi Camera Module](https://www.sparkfun.com/products/21331)

### Optical Encoder for Enhanced Pose Estimation (Optional)
+ [MIKROE Opto Encoder 3 Click](https://www.sparkfun.com/products/19634)

### Audio Player(Optional)
+ [MIKROE Audio AMP](https://www.mikroe.com/audioamp-11-click)

### WIFI Module(Optional)
+ [MIKROE WIFI-7 Click](https://www.mikroe.com/wifi-7-click)

## Resources
### VR Hardware Courses from Other Universities:

[Stanford University EE267](http://stanford.edu/class/ee267/syllabus.html)

[University of Washington CSE409V](https://courses.cs.washington.edu/courses/cse490v/20wi/#projects)
