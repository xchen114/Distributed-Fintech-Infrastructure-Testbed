# ConsensusPBFT

Thanks for your visit!

This is an Android project for a demo of the practical Byzantine fault tolerance algorithm. To run the demo, you'd better to install the Android Studio first. Then inport the "PBFTDemo" project directly. 

If you would like to run the demo on the emulator, you need to create the virtual machine in Android Studio by "Tools" - "AVD Manager". Then, you should redirect the ports. Modify the "port_arr" and "port_send_arr" in "SystemInfo" class CommDemoMainNode.java file, which contains the listening port and the port redircting to the listening port. After that, please set port redir according to the https://developer.android.com/studio/run/emulator-networking?hl=zh-cn. 
