# CS396 Advanced Computer Graphics Seminar: VR/AR Systems

![cover_image](https://github.com/JipengSun/2023_NU_Summer_VR/blob/main/vr_ar_cover_2.png?raw=true)

## Lecture Info

Tue/Thur 3:30PM - 5:00PM CST

June 20th - Aug 27th, 2023

M345, Tech Building, Northwestern University

## Teaching Team

Course Instructor: 

[Jipeng Sun, Northwestern University](https://jipengsun.github.io/)

Course Assistant: 

[Ashwin Baluja, Northwestern University](https://www.linkedin.com/in/ashwinbaluja/)

[Yiran Zhang, Northwestern University](https://zhangpp0802.github.io/)

[Jiahui Li, Northwestern University](https://www.linkedin.com/in/jiahui-iris-li/)

Course Coordinator: 

[Prof. Jack Tumblin, Northwestern University](https://www.mccormick.northwestern.edu/research-faculty/directory/profiles/tumblin-jack.html)

## Introduction

Welcome to CS396 VR/AR Systems! 

Reflecting how much time you spend looking at screens in a day, there is no doubt the physical world and digital world are connecting more and more deeply with each other for better increasing the social productivity and satisifying humans‘ nature needs for curiosity, respect, autonomy, and purpose. Virtual Reality (VR) and Augmentented Reality (AR), by merging the digital world and physical world in a more convenient and profound way, is the next digital world medium for unlocking the greater power of human beings' productivity in the physical world.  

In this course, students will learn how to build a standalone VR hardware & software prototype from scratch in 10 weeks and explore the possibility to extend it to a LLM assisted VR / edge AI AR system. By learning from building, we can better understand the principles, craftsmanship and subtleties behind creating a real world VR/AR product.

[CAESAR Course Website](https://www.mccormick.northwestern.edu/computer-science/academics/courses/descriptions/396-23.html)

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


VR design plans brainstorming. There are no ‘correct’ answers for engineering. The problem we are facing is: ‘Driven by your passion/goal, given limited resources, knowing what your metrics to evaluate success, how to make your best possible plan and act on it.’ Come up with a step-by-step hardware prototyping iteration plan. Start sourcing the hardware components based on your design.


[Brainstorm Recording Notes from Ashwin Baluja](https://docs.google.com/document/d/1095E-3hxstYPrixhDUMt8MTo0VFCKXdvQ9nbPGZaKUU/edit)

### Week 3: Graphics Rendering Pipeline on Emebedded Systems
**Key questions to ask** 

1. Given a designed MVP, which is a near eye monitor, how to draw/render scenes on that screen?

2. What is the logic of the graphics rendering pipeline?

3. How to use WebGL to implement the rendering pipeline?

### Week 4: Human Binocular Vision System
**Key questions to ask** 

1. Will the current implemented binocular rendering effect work? Why won't it give us a 3D effect?

2. What are the biological anatomy and functions of human binocular eyes?

3. How should we change our graphics rendering logic to fit human perception?

4. What are the depth cues for humans? How does the relative importance of them change based on the distance?



### Week 5: Near-Eye Display Optics
**Key questions to ask** 

1. To make it real, how to make a 2-cm far displayed image be perceived as 1.5-meter away from the users?

2. What are the popular optical components of the current near eye display? How do they work? What are the trade-offs?

3. Will the rendered images look distorted after adding a lens between the display and eyes? If so, how should we correct them?

4. Why will we feel dizzy wearing VR/AR glasses? What is the vergence & accommodation problem?


### Week 6: Orientation/Position Tracking Hardware
**Key questions to ask** 

1. How to match the perspective of the rendered scene with the actual head pose of the users?

2. How do humans design ‘inertial measurement unit’ (IMU) to measure the pose? What are the physical principles behind it?

3. How to turn the IMU reading value to control rotation?


### Week 7: Build VR/AR Without Dizziness
**Key questions to ask** 

1. What are the sources of VR/AR dizziness?

2. What is the vergence accommodation conflict? Why is it a problem?

3. How could we solve/alleviate the dizziness problem caused by vergence & accommodation conflict?

4. How to analyze the latency of the current system?

5. What are the graphics and hardware approaches to cut down the latency?



### Week 8: Controller Pose Estimation for Interaction
**Key questions to ask** 

1. What are the human machine interfaces for VR/AR systems? How could we interact with VR/AR systems?

2. How does hand gesture recognition work? What is the general computer vision development pipeline?

3. How to add a camera into the current system?




### Week 9: Additional VR Features: Audio, Eye Tracking, Cloud AI Interfaces, and Rendering Engines
**Key questions to ask** 

1. Vision itself alone is not reality, what other sensory input could we control?

2. Why is eye tracking important for VR/AR systems? How do humans do eye tracking now?

3. How to leverage advanced graphics engine software to accelerate VR/AR creation?

4. How to export and migrate the graphics engine project into our DIY system?

5. How to leverage cloud AI interface to empower your system?



### Week 10: State of Art VR/AR Research (Guest Lectures) and Demo Day
**Key questions to ask** 

1. What are the current state of art VR/AR research projects?

2. What could I do next to start a VR/AR academia/industry job? How to step further?

3. Share and demo your project with people you care and love!



![prototype_image](https://github.com/JipengSun/2023_NU_Summer_VR/blob/main/prototype.png?raw=true)

## Sourcing

### SoC (System on Chip, Mini Computer)

+ [Libre Le Patato](https://libre.computer/products/aml-s905x-cc/)

+ [Nvidia Jetson Nano](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems/jetson-nano/)

### Display

+ [TopFoison 5.5 inch with mini-hdmi board](https://www.alibaba.com/product-detail/Free-Sample-1920-1080-4-5_1600490151764.html?spm=a2747.manage.0.0.5a3e71d24dyiGb)

### Inertial Measurement Unit (IMU w/ or w/o Fusion)

+ [Adafruit 9-DOF IMU Fusion Breakout - BNO085](https://www.adafruit.com/product/4754)

### Camera
+ [ESP32 CAM](https://www.amazon.com/HiLetgo-ESP32-CAM-Development-Bluetooth-Raspberry/dp/B07RXPHYNM)


### Enclosure with Handle

+ [VRG Pro](https://www.amazon.com/NEWSTYP-Wide-Angle-Smartphone-Eyeglasses-Bluetooth/dp/B0BF511LMZ?th=1)



## Archieved Sourcing List (Abandoned)

### Microprocessor

+ [Raspberry Pi Zero 2W](https://www.raspberrypi.com/products/raspberry-pi-zero-2-w/)

+ [Teensy 4.1](https://www.pjrc.com/store/teensy41.html)

### SoC (System on Chip, Mini Computer)

+ [Raspberry Pi 3 B](https://www.amazon.com/s?k=Raspberry+Pi)

### Mono-Display
+ [7 inch LCD (STARTEK IPS Module)](https://www.alibaba.com/product-detail/5-5-5-5-6-5_1600512906287.html?spm=a2700.details.0.0.6aa27b35LK90YX)

+ [6 inch LCD (Eurotech Ltd.)](https://www.alibaba.com/product-detail/OEM-ODM-6-Inch-Tft-PCAP_1600162048967.html?s=p)

+ [6 inch LCD (Elida Ltd.)](https://www.alibaba.com/product-detail/High-resolution-7-inch-LCD-display_62446541480.html)

### Binocluar-Displays
+ [4 inch Square LCD](https://www.alibaba.com/product-detail/4-0inch-Square-tft-lcd-display_62075695201.html?spm=a2700.7724857.0.0.16502b63kK0wwP)

### Lens
+ [Google Cardboard Biconvex Lens](https://www.amazon.com/Pack-Google-Cardboard-Bi-convex-Biconvex/dp/B01FWVWUEU/ref=sr_1_6?keywords=Virtual+Reality+Lenses&qid=1675283182&sr=8-6)

### Inertial Measurement Unit (IMU w/ or w/o Fusion)
+ [HiLetgo MPU-6050](https://www.amazon.com/Pack-Google-Cardboard-Bi-convex-Biconvex/dp/B01FWVWUEU/ref=sr_1_6?keywords=Virtual+Reality+Lenses&qid=1675283182&sr=8-6)

### Enclosure with Handle
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
