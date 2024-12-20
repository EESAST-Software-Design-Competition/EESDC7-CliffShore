![cliffshore2](D:\LocalFiles\4Spring\1软设\game\cliffshore2.png)

## 简介

CliffShore是一款以战斗、跑酷为主要玩法的2D类银河恶魔城游戏。玩家将在游戏中操控小红帽（？的角色，在充满怪物和谜团的异世界（？中冒险，并在深入地穴的同时逐渐发现世界的真相

## 说明

------

游戏引擎：Gamemaker（版本号2023.11.1.129）

构建步骤：使用游戏引擎IDE的Release构建

平台：Windows10+ & Android

成品：直接点击名为CliffShore的exe文件即可安装

## 设计说明书

------

#### 作品名称：

CliffShore

#### 创意来源：

两位作者有各自的游戏品味，dou-bh21喜欢动作类冒险游戏，享受不断磨练游戏操作带来的成就感，尤其喜欢《Hollow Knight》《Celeste》等动作游戏；cyd21则享受《乌鸦先生的独白》《Rusty Lake》等游戏独特的叙事风格带来的游戏体验。经过一个寒假又n周的奋战，一款结合了2D动作跑酷玩法和隐秘叙事展开的游戏CliffShore出炉了。CliffShore，堂堂出场！

- 《空洞骑士》

《空洞骑士》（Hollow Knight）是独立团队 Team Cherry 开发的一款 2D 类银河恶魔城动作冒险游戏。玩家需要扮演故事的主人公——小骑士，以多种多样的行动与战斗技巧，在许多连通的区域间旅行，探索广阔的圣巢世界。

- 《蔚蓝》

《Celeste》 是Maddy Makes Games Inc. 于 2018 年发布的一款二维平台游戏。玩家需要控制 Madeline，踏上攀登神秘的 Celeste 山的旅程，并在整个旅程中逐渐了解和接纳自己的内心。

#### 设计目的：

计划设计一款包含解谜，战斗，跑酷等元素的2D类银河恶魔城游戏。

已经实现：

- 基础的人物动作（移动跳跃，冲刺攀墙，劈砍射箭等）
- 部分敌人ai（包括四种小怪和Boss）
- 能力解锁机制（玩家通过与npc对话/完成任务，获取对应的能力）
- 存档机制
- 文本对话系统（显示文本对话框）
- 剧情设计（包含简单剧情和隐藏剧情）
- 关卡设计（设计了较为丰富的关卡流程，估计初次游玩时间不少于15分钟）

使用技术：

- 人物的动作和动画切换逻辑，使用有限状态机FSM实现
- 敌人ai使用有限状态机FSM实现
- 流程化设计，针对包括玩家和敌人在内的对象，采用接收输入→处理数据→绘制图像统一流程编写，代码工整，可拓展性高
- 存档机制通过对ini文件进行读取和写入实现
- 文本对话系统，依托Github上开源的Gamemaker插件Scribble和Chatterbox实现，前者用于文本特效，后者用于文本流管理
- 关卡设计，借鉴《空洞骑士》和《蔚蓝》

## 使用说明书

------

基本的操作如下：

- Press A/D to move left/right 
- Press S to crouch 
- Press K/Space to jump or double jump 
- Press J to attack 
- Press I to shoot arrows
- Press L to dash
- Press W to save game
- 在火堆旁，按下W键可以恢复血量
- 弓箭需要通过攻击怪物来积累