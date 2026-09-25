 # Ubuntu and ROS Jazzy

 - Boot new Ubuntu image **(24.04)** to lab computer

- ROS installation: ROS2 **Jazzy** on Ubuntu Linux

- Real-time **kernel 7.2.0** installed with **rt5** patched

# UR_driver

- Jazzy Branch, commit
4104ee9433c57aeaf9a5c75e3adefa451c8b7062

- Network congiguration issue solved - robot connected

- Launch driver

# Azure_Kinect_ROS2_Driver

Driver link at  [text](https://github.com/microsoft/Azure-Kinect-Sensor-SDK/blob/develop/docs/usage.md#Installation)

Requires kinect sdk version **1.4** installation which need configuring microsoft package repo for 18.04 since kinect line was disconnected
Requires **libk4a1.4 libk4a-dev and k4a-tools**

libk4a has further dependency on libsoundio version>=1.0.1 which can be gotten at [text](https://ftp.debian.org/debian/pool/main/libs/libsoundio/)

- libsoundio1_1.1.0-1_amd64.deb
