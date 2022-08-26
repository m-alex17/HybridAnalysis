# HybridAnalysis
This is an automated test oracle to find energy defects of android applications implemented on top of the soot framework.
This tool combines static and dynamic analysis in order to find energy defects related to CPU, GPS, Sensors, Screen, WiFiLock and WakeLock.
Three main patterns are investigated: 
- Resource Leak
- Screen defects
- Update rate of Sensors
A quick litrature review what have been done regarding Energy defects of android application:
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

## Questions
If you have any question, please contact the authors of the paper.
