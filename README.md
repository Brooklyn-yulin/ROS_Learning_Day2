# From Zero to Zero
# Day 2
今天学习到的主要内容是建立两轮机器人的urdf模型，并编写launch文件调用Rviz实现urdf模型的显示，通过向urdf模型增加<joint>与<collision>标签，建立可以参与gazebo仿真的模型。对urdf文件进行gazebo形式的改写，编写从gezebo软件中直接打开urdf的仿真环境模型，编写.world文件用来配置gazebo仿真中的虚拟世界，最终通过launch文件打开仿真模型。
# 概述
建立节点与通信机制的具体流程主要可以分为：编写两轮机器人urdf模型、调用Rviz打开urdf模型、创建从gezebo启动.gazebo文件、创建.world文件、创建gazebo的launch文件四部分内容。
具体内容请见：https://yz9kcdb1bb.feishu.cn/wiki/IbkvwInZQiAtCwkYZj9cOATjnYc
