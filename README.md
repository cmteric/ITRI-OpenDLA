## ITRI-OpenDLA 
OpenDLA implementation for FPGA and SoC, revised based on [NVDLA](http://nvdla.org/index.html)

To have more multi-media rich information, please refer to our [public info](https://sites.google.com/view/itri-icl-dla/)

![](FPGA_System.png)

### Contents
- **FPGA_RTL\_nvsmall64** contains the source RTL codes that are revised for FPGA.
- **Prebuilt** contains prebuilt DNN models (Resnet & YOLO) for demo.
- **nvsmall64_zcu104** contains the Vivado project for Xilinx MPSOC ZCU104 board.
- **nvsmall64_zcu102** contains the Vivado project for Xilinx MPSOC ZCU102 board.


### About ITRI-ICL 
- **ITRI** (Industrial Technology Research Institute), founded since 1973, is Taiwan’s largest research institutions.

- **ICL** (Information and Communication Laboratories), one of the major Lab in ITRI, wherein research covers information, networking, cloud, fintech, communication, and IC technologies.

### About DLA
- **DLA** (Deep Learning Accelerator), is the flexible DNN processing engine opened by NVDIA, and now has been revised with several features, including the support of MobileNet Series, weight decompression of convolution / fully-connected operations, and various customize options for users.

### About Future Release
Soon, We will provide prebuilt kits (SD card images) for Xilinx MPSOC ZCU104 and ZCU102. These are the fastest evaluation ways to enjoy edge DNN inference. We will provide a classification (ResNet50) and a object detection (Tiny YOLO v1) application, automatically execute version. All you needs are one of the FPGA board, a usb webcam, a mouse, and a SD or MicroSD for bootup. 

Later than the above demo, we plan to collaborate our partner, [Skymizer ONNC](https://github.com/onnc), to share some results of famous DNN models. Please stay tuned for the update.

### Our Purpose
The OpenDLA here is a basic one, 64-MAC version, which is originally named nv_small in NVDIA's open source. Here we provide the synthesizable codes and project files for popular Xilinx MPSOC FPGA Series. We hope this may contribute an easy entrance for DNN edge implementation whether in academic or industrial. Also, this can be a fast way to evaluate our services. 
