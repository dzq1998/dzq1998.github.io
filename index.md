# 张个人主页

## 部分成果展示
（由于所做项目不方便完全公开，所以只展示了部分demo效果）

<table rules="none" align="center">
	<tr>
          <td> AR演示原视频  </td>
          <td> AR演示添加虚拟对象(图中蓝车)	首先构建离线点云地图，利用离线地图重定位之后进行指定位置的三维注册，添加虚拟对象 </td>
        </tr>
	<tr>
		<td>
			<center>
				<img src="gif/gif_mark/AR_blue_car_org_mark.gif" height="200" />
			</center>
		</td>
		<td>
			<center>
				<img src="gif/gif_mark/AR_blue_car2_mark.gif" height="200" />
			</center>
		</td>
	</tr>
	<tr>
          <td> AR演示原视频  </td>
          <td> AR演示添加虚拟对象(图中坦克和虚拟士兵)首先构建物体地图，在指定物体(汽车)位置进行三维注册，展示虚拟对象 </td>
        </tr>
	<tr>
		<td>
			<center>
				<img src="gif/gif_mark/AR_soldier_org_mark.gif" height="200" />
			</center>
		</td>
		<td>
			<center>
				<img src="gif/gif_mark/AR_soldier2_mark.gif" height="200" />
			</center>
		</td>
	</tr>
	<tr>
          <td> AR辅助维系虚拟动画展示，在指定位置添加虚拟动画(发动机)，利用交互信息来辅助检查和维修  </td>
          <td> </td>
        </tr>
	<tr>
		<td>
			<center>
				<img src="gif/gif_mark/AR_engine2_mark.gif" height="200" />
			</center>
		</td>
		<td>
		</td>
	</tr><tr>
          <td> kitti数据集上实例分割  </td>
          <td> kitti数据集上进行物体建模和语义重定位，图中蓝色关键帧和黄色关键帧来自两个机器人采集的数据，利用语义和几何结合的重定位技术实现地图拼接 </td>
        </tr>
	<tr>
		<td>
			<center>
				<img src="gif/gif_mark/AR_kitii_mark.gif" height="180" />
			</center>
		</td>
		<td>
			<center>
				<img src="gif/gif_mark/AR_kitii_semantic_map3_mark.gif" height="200" />
			</center>
		</td>
	</tr>
</table>


### 论文《Object-Plane Co-Represented and Graph Propagation-Based Semantic Descriptor for Relocalization》 
论文摘要：   
Relocalization is a critical component of robotics applications, it poses challenges due to changes in lighting conditions, weather, and viewing point. Image feature-based approaches are appearance-sensitive, high-level semantic landmark-based methods are ambiguous, and topological map matching-based methods are not robust enough among available solutions. We propose a highly robust and highly expressive semantic descriptor for graph matching. Specifically, we begin by introducing an object-plane co-represented topological graph and a graph propagation algorithm to formulate descriptors for high-level landmarks; we then solve graph matching using the sKM algorithm. Finally, we develop a relocalization system that combines semantic objects and geometric planes for pose optimization and conducts experimental validation on various datasets. Experimental results demonstrate that the suggested method remains effective even when the viewpoint changes by more than 80˚ on the 2D-3D-S dataset, and the mean orientation error is less than 5˚ on the sceneNN dataset.   
[论文链接](https://ieeexplore.ieee.org/document/9829918)
  

* 在大视差下使用语义拓扑图进行重定位的一个示例：   
<img src="img/paper_Introduction.png" width="350"/>   

* 系统框架：   
<img src="img/paper_system.png" height="250" />   

* 大视差下的实验效果对比：   
<img src="img/there_scenes.png" height="400" />
<!-- ![论文结果展示](https://gitee.com/naughtysnail/NaughtySnail.github.io/blob/master/img/there_scenes.png) -->




## 个人信息 
生日：1998.9   
籍贯：四川宜宾	  
电话/微信：15942016683  
邮箱：1447918519@qq.com	

## 教育背景 
2020.9-2023.7	          东北大学	           控制科学与工程（硕士推免，前10%）	         硕士    
2016.9-2020.7	        沈阳建筑大学	         自动化（GPA：4.16  排名：1/86）	            本科    


## 项目&实习
2022/05-2022/08（OPPO实习）   
项目名称：融合定位与3D环境重建（雷达点云、SLAM、C++/python）       
项目介绍：利用雷达、IMU和相机等多类传感器实现定位与建图.单目和鱼眼相机内参标定，相机和雷达的外参标定；构建激光点云的全局描述子，利用点云的全局描述子实现点云场景重识别、回环检测和地图更新检测。   

2021/02-2022/05          
项目名称：基于增强现实的船载电子装备辅助维修（视觉、Unity3D、C++/C#）    
项目介绍：基于RGBD相机构建AR辅助维修系统，建立多层次地图。实现基于ORB-SLAM2的深度相机定位算法，构建点云地图与八叉树地图；利用solov2进行语义分割和数据关联建立语义地图；利用点、面和物体路标实现桌面级的鲁棒重定位算法；基于真实语义物体建模的虚拟物体注册，实现多用户AR系统的虚实融合和交互同步。   

2020/09-2021/05	  	       
项目名称：基于自组织云的多机器人协同建模（视觉、SLAM、C++）	       
项目介绍：基于双目视觉的多机器人协同建图与定位，多地图拼接与融合。基于CCM-SLAM算法的地图定位与拼接；使用词袋和关键帧来实现地图重定位；使用语义拓扑图实现大视差下的地图重定位。    


  
  
## 科研成果
1. 作为第一作者，发表在RAL+IROS论文《Object-Plane Co-Represented and Graph Propagation-Based Semantic Descriptor for Relocalization》      
2. 作为非第一作者，发表在3DV论文 《Object SLAM-Based Active Mapping and Robotic Grasping》            
3. 作为非第一作者，发表在IROS论文《CFP-SLAM: A Real-time Visual SLAM Based on Coarse-to-Fine Probability in Dynamic Environments》 

## 个人荣誉

  <table border="0">
      <tr>
          <td> 全国大学生数学竞赛  		省一等奖  </td>
          <td> 互联网+创新创业大赛			国家铜奖  </td>
      </tr>
        <tr>
          <td> 美国数学建模竞赛       	H奖  </td>
          <td> 辽宁省计算机博弈			    象棋组季军  </td>
      </tr>
      <tr>
          <td> 新媒体设计竞赛			    省一等奖  </td>
          <td> 辽宁省机器人大赛			    省三等奖  </td>
      </tr>
      <tr>
          <td> 高校数学密码挑战赛		    省一等奖  </td>
          <td> 计算机设计竞赛			        省三等奖  </td>
      </tr>
      <tr>
          <td> 研究生阶段	一等奖学金、优秀研究生  </td>
          <td> 本科生阶段	一等奖学金、励志奖学金、专业标兵  </td>
      </tr>
  </table>
  

## 专业技能
* 算法	语义图匹配  图优化  视觉SLAM     
* 编程	C/C++  Python  Java  OpenCV  Eigen  PCL  g2o     
* 技术	Android开发  Linux操作系统  ROS  Unity3D    
* 语言	CET-4   CET-6    


