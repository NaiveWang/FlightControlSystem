# FlightControlSystem
This a Embeded Project
# Introduction
Before I post this project, I've made a Quadricopter, which is controlled by APM2.8 which is a fairly foolproof platform, 
all you have to do is having some integrated compoments and match them with wiring signal cables correctly,then you can "Go Sky".    
So when I've "done" the job, when the motor spun successfully, I didn't feel much excited about it : I've done
nothing about the actual development at all.What's more, I didn't have ability to deal with it that time.   
But now, I think I could handle it-----Developing an embedded system to control a Quadricopter, that's the project's final goal.

Let's wait and see.

+1S.
              -----------Naive Wang,5/3/2017,Tsingtao
# 简介
在开这个项目之前我弄过一个大四轴，用的飞控是APM2.8，稍有常识的人都能看出，这是个傻瓜式的平台:你只需要买堆零件，把线
给他连对喽，就能上天谈笑风生。
所以当我的电机跑起来以后并没有感到一颗赛艇。
但现在，我可是身经百战，见得多了，西....咳咳，我有能力自己写个飞控玩玩。
废话不多讲，天上不会掉馅饼，大家撸起袖子加油干。
另，续一秒。
此致
            不敬礼
            -------------王拿衣，2017年三月五号，青岛
# IDE & MCU's model selected
##IDE : keil uVersion4(ARM version)
##MCU model: STM32,detail(which i'm using):STM32F103C8
# Join the Project/加入此项目
If you're interested in getting on board, please check out these prerequisities  
如有兴趣，注意以下前提要素  
##A.Knowledgement/知识  
###1.Mastered C language/精通C语言  
###2.Already achieved some functions with the assembly language./用汇编写过一些东西  
###3.Basic signal & circuit knowledge./信号、电路知识基础  
###4.Have a basic understanding if Computer Organization./对计算机组成至少有个浅显的了解  
###5.Basic knowledge about model-aircraft/航模的基础知识  
##B.Development Requirements/开发需要  
###1.A material Microcontroller Board for testing./一个微控制器板子用来测试  
###2.Other meterial components*./其它实体的元器件  
###3.A burn-in tool for downloading program from your computer to the chip./烧写工具，用来你的程序从电脑下载到芯片  
##*Fundamental Component Requirements during Development
for testing if your corresponding functional module's running properly.
###A whole set of brushless motor & it's driver(electronic speed regulator、battery pack involved)
###A set of remote controller
###A G-sensor module
###Alternative Components
####A voltage module
####A display module