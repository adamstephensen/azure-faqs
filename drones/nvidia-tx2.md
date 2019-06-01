## Overviews
- great tx2 overview https://hackaday.com/2017/03/14/hands-on-nvidia-jetson-tx2-fast-processing-for-embedded-devices/
- programming languages for the jetson https://www.jetsonhacks.com/2016/08/18/thoughts-on-programming-languages-and-environments-part-iv-jetson-dev-kits/

## Tips for working with the tx2
- You need to run Linux on bare metal. 
- [Never use ```sudo``` to run jetpack](https://devtalk.nvidia.com/default/topic/1027939/inquire-about-jetpack-3-2/)
- [How to setup Ubuntu remote desktop](https://www.lifewire.com/setup-ubuntu-remote-desktop-4129666) (you can't connect from Windows)
- [Installing OpenCV on a tx2](https://jkjung-avt.github.io/opencv3-on-tx2/)
- [Python code to access OpenCV](https://gist.github.com/jkjung-avt/86b60a7723b97da19f7bfa3cb7d2690e)
- if you get 'return code: 1' see https://devtalk.nvidia.com/default/topic/1027939/inquire-about-jetpack-3-2/

```
mkdir /home/me/jetpack
chmod 7777 /home/me/jetpack
mv <install.run file> /home/me/jetpack
cd /home/me/jetpack
./<install.run file>
```

## Getting started with the tx2

This article is awesome and is the source for many of the links on this page
https://medium.com/@surmenok/getting-started-with-nvidia-jetson-tx2-5952a2d8d7ae

JetPack 3.0 – NVIDIA Jetson TX2 Development Kit
https://www.jetsonhacks.com/2017/03/21/jetpack-3-0-nvidia-jetson-tx2-development-kit/

## Tutorials
- Hello world AI https://github.com/dusty-nv/jetson-inference

- [tensor flow on tx2](https://jkjung-avt.github.io/tf-trt-models/)
- [tensor flow models on tx2](https://jkjung-avt.github.io/tf-trt-models/) **this is the one for me to run on **

## doco
 - [Nvidia - tensorrt with phyton](https://docs.nvidia.com/deeplearning/sdk/tensorrt-developer-guide/index.html#python_topics)
 - [tensor rt containers](https://ngc.nvidia.com/catalog/containers/nvidia:tensorrt)
 - [tensorrt overview](https://devblogs.nvidia.com/speed-up-inference-tensorrt/)

- [Deep Vision tutorial for Tx2 / Nano](https://github.com/dusty-nv/jetson-inference)


## Compiling vs code on tx2 **todo**
https://devtalk.nvidia.com/default/topic/1035752/how-to-install-quot-visual-studio-code-quot-/


## Cog services
-  https://www.microsoft.com/developerblog/2017/05/12/food-classification-custom-vision-service/


## Jetson Nano
- [Basic setup](https://jkjung-avt.github.io/setting-up-nano/)