	实体组件系统 (ECS) 是 Unity Data-Oriented Tech Stack(DOTS) 的核心。
	重要思想：面向数据编程
[官方文档](https://docs.unity3d.com/Packages/com.unity.entities@0.17/manual/ecs_core.html) 

#1.构成简介
##1.1 Entity
游戏中的实体、对象。它是带有组件数据的实例。
##1.2 Component
entity上相关的数据，存储的数据。注：这里的数据并不是实体本身。
##1.3 System
处理数据的系统，控制逻辑（从某一个逻辑状态到另一个逻辑状态）