关键词>视频>论文
KEY WORDS: Human-Robot Cooperative;
human-robot manipulator cooperative
# 人机协作搬运
## [Dynamic Human-Robot Interaction -Realizations of collaborative motion and peg-in-hole-](https://www.youtube.com/watch?v=xB9-vEiZwKY)  
We developed a dynamic human-robot interactive system consisting of a high-speed vision and a high-speed robot hand. The high-speed vision can measure the position and the orientation of the board to be manipulated by a human and a robot. Then the high-speed robot hand can react based on the board information. This system can correspond to a randomly human motion at high-speed and low-latency. Also, this system can compensate the pitch angle, and follow the yaw and roll angles by the human motion. In addition, we successfully achieved a collaborative peg-in-hole. In this task, the diameters of the peg and the hole are 6.350 mm and 6.325 mm, respectively. Therefore, we can perform the high-accuracy peg-in-hole by using the developed human-robot interactive system.
我们开发了由高速视觉和高速机械手组成的动态人机交互系统。高速视觉可以测量要由人和机器人操纵的板的位置和方向。然后，高速机械手可以根据板信息做出反应。该系统可以对应于高速和低延迟的人类随机运动。而且，该系统可以补偿俯仰角，并通过人类运动来跟踪偏航角和侧倾角。此外，我们成功实现了协作钉入式。在此任务中，栓钉和孔的直径分别为6.350毫米和6.325毫米。因此，通过使用开发的人机交互系统，我们可以执行高精度的钉入孔。

## [Human-Robot Cooperative System using a High-speed Vision System and a Robot Hand](https://www.youtube.com/watch?v=VP072LTMBjo)
Recently, robotics research and development have been done actively, and some robots are introduced in human life environment. This means that cooperation between human and robot is significantly important. And it is very interested in human-robot cooperation in that context. In this research, we aim at a realization of human-robot cooperative task that the board which is grasped by a human subject and a robot hand is controlled to be keep horizontally. By using the high-speed robot hand system, we achieved this task robustly.
近来，机器人技术的研究和开发已经积极开展，并且在人类生活环境中引入了一些机器人。这意味着人与机器人之间的合作非常重要。在这种情况下，它对人机合作非常感兴趣。在这项研究中，我们的目标是实现人与机器人之间的协作任务，即控制被人体和机器人手抓住的板子使其保持水平。通过使用高速机械手系统，我们稳健地完成了这一任务。
[LINK](http://www.k2.t.u-tokyo.ac.jp/fusion/Cooperation/index-e.html)
## []()
## []()
## []()
## []()
# 机械臂抓取飞着的物体：接取物体
KEY WORDS: Robot catching flying object
## [Robot catching flying object](https://www.youtube.com/watch?v=hGu9h0gy76c)  
Learning Algorithms and Systems Laboratory(LASA) of EPFL proposes a Programming by Demonstration (PbD) approach to learn how to catch robustly objects in flight. This requires to solve three complex problems: predicting accurately the trajectory of fast moving object, predicting the feasible catching configuration, and fast planning the robot's arm. Among these issues, we propose new methodologies to predict an object trajectory and to find a feasible catching posture in a probabilistic manner. Our methodology consists of: 1) Offline learning of the dynamical model of a flying object by observing its behavior over a number of throws, 2) Offline learning of end-effector configuration of a robot to grasp an object, 3) Offline learning of reachable-space of the robot, 4) Online determination of good catching postures and 5) fast planning of precise trajectories for the robot's arm to intercept and catch the object on time. We validate the approach in real experiment with robotic arm KUKA-LWR.  
EPFL的学习算法和系统实验室（LASA）提出了一种基于演示的编程（PbD）方法，以学习如何捕捉飞行中的坚固物体。这就需要解决三个复杂的问题：准确预测快速移动物体的轨迹，预测可行的捕捉配置以及快速规划机器人的手臂。在这些问题中，我们提出了新的方法来预测物体的轨迹并以概率方式找到可行的捕捉姿势。我们的方法包括：1）通过观察飞行物体在多个投掷过程中的行为，离线学习飞行物体的动力学模型； 2）离线学习机器人的末端执行器配置，以抓住物体； 3）离线学习可到达的物体机器人的空间； 4）在线确定良好的捕捉姿势； 5）快速规划精确的轨迹，以使机器人的手臂按时拦截和捕捉物体。我们使用机器人手臂KUKA-LWR在实际实验中验证了该方法。
## []()
## []()
## []()

# 多台机械臂协作搬运
## [Robust Cooperative Manipulation: V-REP Simulation and Experimental Results](https://www.youtube.com/watch?v=jJWeI5ZvQPY)
KEY WORDS: 
## [Distributed estimation and manipulation](https://www.youtube.com/watch?v=1q5I6r3iJ4Y)
Video comes together the paper:
 Alessandro Marino, Giuseppe Muscio, and Francesco Pierri. "Distributed cooperative object parameter estimation and manipulation without explicit communication". In  IEEE International Conference on Robotics and Automation, pages 2110–2116.  2017.
Abstract.
We present a two stages fully distributed algorithm for cooperative manipulating an unknown object rigidly grasped by mobile manipulators, in the absence of both a central unit and any explicit information exchange among robots. In the first stage, robots cooperatively estimate the object kinematic and dynamic parameters by properly moving the object or applying specific contact wrenches. In the second stage, the estimated parameters are used in a distributed cooperative algorithm aimed at controlling the object pose while limiting both the squeezing wrenches exerted by the manipulators and the wrench exerted by the environment on the object. Differently from existing solutions, the proposed technique does not require any information exchange among robots and is devised in the 3-dimensional space. Numerical simulations demonstrate feasibility of the approach.我们提出了一种两阶段全分布式算法，用于在没有中央单元和机器人之间没有任何显式信息交换的情况下，协同操纵由移动操纵器牢牢抓住的未知对象。在第一阶段，机器人通过适当移动对象或使用特定的接触扳手来协同估计对象的运动学和动态参数。在第二阶段中，将估计的参数用于分布式协作算法中，该算法旨在控制对象姿势，同时限制操纵器施加的挤压扳手和环境施加于对象的扳手。与现有解决方案不同，所提出的技术不需要在机器人之间进行任何信息交换，并且是在3维空间中设计的。数值模拟证明了该方法的可行性。

# 相关性比较小：
## [Making of Cooperative Manipulation Using a Leader-Follower based approach](https://www.youtube.com/watch?v=3nEyB9YKrj8)
## [Task Transfer via Collaborative Manipulation for Insertion Assembly](https://www.youtube.com/watch?v=cDMX_RrtCpg)

# 底盘轨迹规划

## [Online Trajectory Optimization for Cooperative Mobile Robot Navigation](https://www.youtube.com/watch?v=zaIW76A7ips)
## []()
## []()
## []()
## []()
