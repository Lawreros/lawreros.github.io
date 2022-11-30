---
title: "Polar Strap Heart Rate App"
excerpt: "iPhone app created for use with the H10 Polar Strap. Connects with the strap using Bluetooth Low Energy and stores transmitted R-R interval and ECG data locally <br/><img src='/images/custom/pshr_app.png' width='150' height='300'>"
collection: projects
date: 2022-03-01
---

## H10 Polar Strap:
The [H10 Polar strap](https://www.polar.com/us-en/sensors/h10-heart-rate-sensor) is a heart rate monitor worn on the chest and capable of recording [ECG](https://www.nhs.uk/conditions/electrocardiogram/#:~:text=An%20electrocardiogram%20(ECG)%20is%20a,heart%20each%20time%20it%20beats.) signals through the electrodes in the strap. From the collected ECG signal the Polar strap calculates beats per minute (BPM) and [R-R intervals](https://help.elitehrv.com/article/67-what-are-r-r-intervals). This data can be periodically sent to a connected listening device through the use of Bluetooth Low Energy [(BLE)](https://www.makeuseof.com/what-is-ble-bluetooth-low-energy/), provided that the Polar strap is withing ~30 feet of the device (varies based on local signal noise and listening device).

## App Functionality:
The app was designed with simplicity in mind, as the main users of the app are teachers who will be distracted during its operation. The purpose of the app is to easily connect to a nearby H10 Polar strap and append all recieved packets of data to local text files. The user is able to select whether or not to record ECG data along with the R-R interval and beats per minute BPM that is automatically recorded and transmitted by the Polar strap. After being connected, the app will vibrate and play a warning sound if it has become disconnected from the Polar strap for any reason (alarms stop when it reconnects).

## How to Use:
The repository for the Swift files can be found [here](https://github.com/Lawreros/PSHR_iOS). Using [Xcode](https://developer.apple.com/xcode/), the provided project can be compiled and run on a local iPhone running an iOS of 13 or more recent. You can also contact me for a link to the app on [Testflight](https://developer.apple.com/testflight/), which allows for easy installation on any applicable iPhone connected to the internet.