<img src="https://www.deeprobotics.cn/public/static/robot/images/logo_.png" alt="Deep Robotics" width="300">

[![bilibili](https://img.shields.io/badge/bilibili-f87598?style=flat&logo=bilibili&logoColor=white&labelColor=f87598&color=f87598)](https://space.bilibili.com/22477177)
[![linkedin](https://img.shields.io/badge/Linkedin-1465bd?style=flat&logoColor=white&labelColor=1465bd&color=1465bd)](https://cn.linkedin.com/company/deep-robotics)
[![YouTube](https://img.shields.io/badge/YouTube-%23ff1a47?style=flat&logo=Youtube&labelColor=%23ff1a47)](https://www.youtube.com/@deeprobotics8601)
[![X](https://img.shields.io/badge/Twitter-black?style=flat&logo=X&labelColor=black)](https://x.com/DeepRobotics_CN)

[English](./README.md)

云深处科技是一家专注于人形机器人、四足机器人及核心零部件的研发、生产、销售和服务的国家级高新技术企业。
公司始终坚持自主创新，先进控制算法、智能环境感知、人工智能算法等核心技术处于国际前沿。
	
### Projects

<table style="width: 100%; table-layout: fixed; border-collapse: collapse;">
  <tr>
    <th> 名称 </th>
    <th> 介绍 </th>
  </tr>

  <tr>
    <td align="center"><a href="https://github.com/DeepRoboticsLab/URDF_model"> URDF_model </a></td>
    <td> 机器人的URDF模型.
    </td>
  </tr>

  <tr>
    <td align="center"><a href="https://github.com/DeepRoboticsLab/Lite3_MotionSDK"> Lite3_MotionSDK </a></td>
    <td> 绝影<b><i>Lite3</b></i>运动控制算法SDK。
    <br> 可获取每个关节的数据，并下发数据，控制机器人运动，提供关节端的控制参数接口。
    <br> 支持 <a href="https://github.com/DeepRoboticsLab/Lite3_MotionSDK">C++</a> 和 <a href="https://github.com/DeepRoboticsLab/Lite3_MotionSDK/tree/add_python">Python</a> 开发。
    </td>
  </tr>

  <tr>
    <td align="center"><a href="https://github.com/DeepRoboticsLab/Lite3_ROS"> Lite3_ROS </a></td>
    <td> ROS与UDP消息的功能转换。
    <br> 通过UDP协议实现绝影Lite3的运动主机与感知主机之间、感知主机与手柄App之间的数据传输。
    <br> <a href="https://github.com/DeepRoboticsLab/Lite3_ROS"> ROS-Ubuntu20 </a>,<a href="https://github.com/DeepRoboticsLab/Lite3_ROS/tree/ubuntu18"> ROS-Ubuntu18 </a>,<a href="https://github.com/DeepRoboticsLab/Lite3_ROS/tree/ros2-foxy"> ROS2-foxy-Ubuntu20 </a>
    </td>
  </tr>

  <tr>
    <td align="center"><a href="https://github.com/DeepRoboticsLab/Lite3_rl_training"> Lite3_rl_training </a></td>
    <td> 一种基于学习的四足机器人运动控制器。 
    <br> 包含在云深处科技绝影<b><i>Lite3</b></i>上进行强化学习训练和硬件部署所需的所有组件。
    </td>
  </tr>
  
  <tr>
    <td align="center"><a href="https://github.com/DeepRoboticsLab/Lite3_rl_deploy"> Lite3_rl_deploy </a></td>
    <td> 包含了RL训练出的策略。
    <br> 包含了在仿真环境中或<b><i>Lite3</b></i>实机上实现策略部署和验证的方法。
    </td>
  </tr>
  
  <tr>
    <td align="center"><a href="https://github.com/DeepRoboticsLab/x30_motion_sdk"> x30_motion_sdk </a></td>
    <td> 绝影<b><i>X30</b></i>运动控制算法的SDK。 
    <br> 提供了关节端的控制参数接口。
    <br> 支持 C++ 和 Python 编译。
    </td>
  </tr>
  
  <tr>
    <td align="center"><a href="https://github.com/DeepRoboticsLab/gamepad"> gamepad </a></td>
    <td> 基于UDP通讯在远程主机上监听手柄端的物理按键触发事件。
    <br> 实时获取手柄端物理按键的触发信息。
    </td>
  </tr>

  <tr>
    <td align="center"><a href="https://github.com/DeepRoboticsLab/Deep_Motor_SDK"> Deep_Motor_SDK </a></td>
    <td> SDK提供了与<b><i>J60</b></i>关节的can通讯、关节使能、关节控制等功能。 
    <br> 提供了 <b><i>单关节控制</b></i>, <b><i>多关节控制</b></i>的例程, 和<b><i>关节调试工具软件</b></i>。
    </td>
  </tr>

  <tr>
    <td rowspan="2" align="center"><a href="https://github.com/DeepRoboticsLab/Lite3_Model_Control"> Lite3_Model_Control </a></td>
    <td><a href="https://github.com/DeepRoboticsLab/Lite3_Model_Control/tree/main/basic_level_sim"> basic_level_sim </a>
    <br> 基于绝影 <a href="https://github.com/DeepRoboticsLab/Lite3_MotionSDK">Lite3 MotionSDK</a> 和 <a href="https://gazebosim.org/">Gazebo</a> 仿真平台实现的基础仿真项目，实现了绝影Lite3的起立动作。</td>
  </tr>
    <td><a href="https://github.com/DeepRoboticsLab/Lite3_Model_Control/tree/main/high_level_sim"> high_level_sim </a>
    <br> 基于昇腾开源项目 <a href="https://gitee.com/HUAWEI-ASCEND/quadruped-robot/tree/master/model-control">model-control/quadruped-robot</a> 进行移植和优化的进阶仿真项目，在<a href="https://gazebosim.org/">Gazebo</a>仿真平台中实现了绝影Lite3的起立和移动，支持使用键盘或手柄控制机器狗运动，支持部署到实机。</td>

</table>
