# Report_EmerCall
Contains related documents about project EmerCall, such as report and Android installation files.

- REPORT_EMERCALL.pdf: official report of project EmerCall, submitted at 2018 Da Nang Mobile App Development Contest.
- tran_Certificate.pdf: official certificate awarded to this project from 2018 Da Nang Mobile App Development Contest.
- emercall.apk: Android installation file of EmerCall - main application for normal users, which will be distributed widely on application store platforms.
- emercallambulance.apk: Android installation file of EmerCall Ambulance - application for ambulance drivers and staff.
- emercallmonitoring.apk: Android installation file of EmerCall Monitoring - application for hospital staff who direct movements of ambulances.


# About

EmerCall is a non-profit, Android-based project, developed to provide a fast, accurate communicative assistance system which can support the transportation process of victims in
emergency cases across Vietnam - my home country. Comprised of 3 Android applications, this system can allow civilians and hospitals to real-time acquire and update location
information of each other, as well as victim’s status, in order to help the ambulances to approach their designated victims faster, while preparing for his/her current status. The
project is still under development, thus I sincerely hope to receive comments and suggestions from everyone.

# Project infrastructure

The EmerCall system consists of 3 apps:

## 1. [EmerCall](https://github.com/TranHuuNhatHuy/EmerCall)
This app is dedicated to standard users - ordinary civilians. When an emergency case occurs, the app enters its emergency mode, allowing users to determine the victim's status, symptoms, and then call the ambulance. While waiting for the ambulance to arrive, the user can access a database of possible first-aid methods, as well as looking for the ambulance's current location.

## 2. [AmbulanceEmerCall](https://github.com/TranHuuNhatHuy/AmbulanceEmerCall)
This app is dedicated to drivers and retrieval team. When an emergency case occurs and a user using EmerCall app sends an emergency signal to the system, an ambulance is selected and assigned for the rescue mission. While approaching the victim and user, the app can show current victim/user's location, and the victim's status/symptoms, which are entered by EmerCall user.

## 3. [MonitoringEmerCall](https://github.com/TranHuuNhatHuy/MonitoringEmerCall)
This app is dedicated to people in charge of coordinating ambulances and retrieval teams. When an emergency case occurs and a user using EmerCall app sends an emergency signal to the system, MonitoringEmerCall users can select/assign an available ambulance to the rescue mission. This app also supports information management of EmerCall users and AmbulanceEmerCall ambulances in the system.

<img src="https://user-images.githubusercontent.com/29034232/166429400-c50d9b59-c04e-4d1e-90e4-6c92aa4f34dc.png" width=75% height=75%>
