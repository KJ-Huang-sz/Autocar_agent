# Autocar_agent
An autocar agent based on multimodal LLM

## 1. 思路
（1）使用自动驾驶仿真软件，主要使用其中的汽车，环境等功能。

（2）感知模块：视觉感知（未来可扩展lidar，radar等等），主要使用LLM的视觉能力。

（3）记忆模块：历史图像和文本信息。

（4）规划模块：使用LLM自身的规划能力。

（5）控制模块：调用API实现控制（方向，油门，刹车等等）。


## 2. 待解决问题
（1）大模型本身的视觉能力（目前gpt4v的视觉能力还可以，可以实现图片导航能力）？

（2）如何获取实时图片？

（3）使用什么仿真软件，是否有供第三方调用的api？
