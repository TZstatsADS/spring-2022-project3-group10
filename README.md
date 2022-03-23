# Project: Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Spring 2022

+ Team Group 10
+ Team members
	+ Liu, Ke (kl3344)
	+ Tang, Shiqi (st3349)
	+ Xu, Rong (rx2180)
	+ Zha, Yvonne (lz2806)
	+ Zheng, Haozhong (hz2694)

+ Project summary: In this project, we created model1 and model2 in two methods to develop an image classification algorithm using images from CIFAR10 and improves the accuracy comparing to the baseline logistic regression model. In our main method, we built model1...
The model was trained and tested on laptop device with GPU [Nvidia Geforce GTX 1660Ti](https://www.nvidia.com/en-us/geforce/graphics-cards/gtx-1660-ti/) and Windows operating system
	
**Contribution statement**: ([default](doc/a_note_on_contributions.md)) All team members contributed equally in all stages of this project. 
+ All team members participated in group discussion and brainstorming session. Ke Liu, Shiqi Tang, Yvonne Zha and Haozhong Zheng mainly focus on constructing and tuning CNN models and Yvonne's model was selected to be the main(optional) model1. Rong Xu developed VGG model which was chosen to be the optional(main) model1 due to its performance.
	+  Ke writed the project summary and integrated files to upload on github...
	+  Shiqi made the slides of our presentation...
	+  Yvonne is responsible of building and training model1, improving it by label correction and ... Also she is the presenter of our team.
	+  Rong finished literature review ...
	+  Haozhong used gpu to run the code to improve efficiency...
+ All team members approve our work presented in this GitHub repository including this contributions statement. 

**Instruction on using GPU Device**:
+ Run the code on device with Nvidia Cuda supported GPU device, the list of devices can be found at [CUDA GPUS](https://developer.nvidia.com/cuda-gpus)
+ Install latest version of [Microsoft Visual Studio](https://visualstudio.microsoft.com/zh-hans/)
+ Install [Nvidia Cuda Toolkit](https://developer.nvidia.com/cuda-toolkit-archive) version 11.5
+ Install [Nvidia cuDNN](https://developer.nvidia.com/cudnn) version 8.3.2
+ Install tensorflow

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
