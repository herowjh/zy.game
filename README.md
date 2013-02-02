﻿zyGame(html5游戏开发引擎)
============================

声明：非经书面许可，不得使用本引擎开发商业化产品。

适合游戏类型：
	基于html5-canvas的2d/2.5d贴图游戏
	
引擎设计目标：
	为游戏开发者提供，一种面向控件编写游戏的框架，提供丰富的控件类及通用方法。

文件结构说明：
根目录
  |--game.htm  (游戏html面页)
  |--css  (放存css样式文件)
  |--img  (放存图片文件)
  |--aud  (放存声音文件)
  |--vid  (放存视频文件)
  |--js  (放存javascript脚本文件)
    |--game.js (具体游戏编写代码放于此文件)
	|--core (游戏引擎目录，禁止擅自修改此目录下文件内容)
	  |--引擎核心文件
	  |--cls (引擎基础类目录)
	  |--pls (引擎插件类目录)
	
	