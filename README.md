How to install, setup and control the Robotiq 2F-140 Gripper on a Kuka LBR IIWA using EtherCAT
---
- follow gripper manual
- connect the gripper to X65 interface

- Download from Robotiq's website the Universal Controller Configuration. Go to the product [page](https://robotiq.com/products/2f85-140-adaptive-robot-gripper), choose "Download files" --> "Other brands" --> "Software" --> "Universal Controller Configuration" --> "EtherCAT" --> "Download XML" (you can find the file in the XML folder too)

- Open WorksVisual and go to "File --> Close", to close your current project.

- Import the XML configuration file: "File" --> "Import / Export" --> "Import device description file" --> "Browse", and set the file type to "EtherCAT ESI". It should import the "NIC 50-RE/ECS" device.

- Close WorksVisual. Open the Sunrise Workbench Project and add an IOConfiguration.wvs file: "File" --> "New" --> "I/O Configuration".
