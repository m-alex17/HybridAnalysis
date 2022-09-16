# HybridAnalysis
This is an automated test oracle to find energy defects of android applications implemented on top of the soot framework.
This tool combines static and dynamic analysis in order to find energy defects related to CPU, GPS, Sensors, Screen, WiFiLock and WakeLock.
Three main patterns are investigated: 
- Resource Leak
- Screen defects
- Update rate of Sensors

Hybrid analysis is a state-of-the-art method for manifesting problems that can drain the battery of Android OS smartphones. 
A quick litrature review regarding what have been done in the area of Energy defects of android applications:
![EnergyDefectLR](https://user-images.githubusercontent.com/59416975/186904367-0db74f4b-3113-4af9-afba-f08eadba3bcd.png)

## Prerequisites
- Python 3
- [Python UIAutomator](https://github.com/openatx/uiautomator2)
- Java JDK 8+
- [Apktool](https://ibotpeaches.github.io/Apktool/)
- [Android SDK](https://developer.android.com/studio/#downloads)
- An Android device or emulator

## How to use?
Clone the project, Run it.

## Abstract
Energy consumption of mobile applications has a great impact on the satisfaction of users. Many developers do not consider energy-efficient programming practices when coding applications. Therefore, many applications can be improved in terms of energy usage by detecting and removing their energy defects. Most researchers towards this goal focus on static analysis of Android applications. In this paper, we propose a hybrid framework consisting of static and dynamic modules for finding energy defects. Our static module can effectively analyze an Android application considering its life-cycle and look for the energy anti-patterns. The results of static analysis are then transformed into executable GUI-based test cases. In the dynamic module, the generated test cases are run, and their results are evaluated using an automated oracle, which does not need energy measurement. Using our framework, 29 applications have been analyzed and 9 applications are found with energy defects. Our dynamic module could effectively detect the false positives in the results of the static analysis module. Index Terms—Static Analysis, Energy Testing, Android

## Questions
If you have any questions, please contact the author.
