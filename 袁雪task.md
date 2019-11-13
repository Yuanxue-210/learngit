# 第二次考核
>一个正常的Unity工程目录下初步需要哪些基本文件夹？

*答：Assets:Scenes,prefabs,material,scrips*
>两个物体之间若能发生碰撞，需要什么先决条件？

*答：其中一个物体有刚体组件，两个物体都要有碰撞器。*
>触发器函数（Trigger与collider）有几种类型？

*答：Trigger是触发器，Collider是碰撞器。Collider有Box Collider、Sphere Collider、Capsule collider、Wheel Collider、Mesh Collider、Terrain Collider。触发器有三种类型：进入触发器时触发，退出触发器时触发，逗留在触发器时触发。*
>Start()函数和Update()函数的作用？

*答：Start函数是启动函数，Start仅在Update函数第一次被调用前调用。Update是刷新函数，Behaviour启动时，update在每一帧被调用。*
>如何用脚本来控制UI层Text的变化？

*答：在player脚本定义text组件，将text组件拉进player,再给text赋值。*
>如何赋予一个物体速度（或使其动起来）？

*答：用向量来表示物体的运动，通过将向量乘以一个数来改变速度。*
>如何获取到键盘按下事件？

*答：使用input.*