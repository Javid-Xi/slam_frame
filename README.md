# Slam-Frame
Simulation of SLAM algorithm and autonomous navigation algorithm.

博客(blog): [Cartographer算法和自主导航算法仿真](https://javid.cn/slam-sim/)

## 1. 安装依赖
```sh
$ rosdep install --from-paths src --ignore-src --rosdistro=kinetic -y
```

## 2. 仿真环境
<img src="https://cdn.jsdelivr.net/gh/Javid-Xi/cdn@1.9.1/img/blog/sim/mylab.jpg" width="80%"/>

## 3. Cartographer算法仿真
### 3.1 建图效果
<img src="https://cdn.jsdelivr.net/gh/Javid-Xi/cdn@1.9.1/img/blog/sim/cartographer.jpg" width="80%"/>

### 3.2 计算图
<img src="https://cdn.jsdelivr.net/gh/Javid-Xi/cdn@1.9.1/img/blog/sim/slam-graph.jpg"/>

## 4. 主动SLAM
<img src="https://cdn.jsdelivr.net/gh/Javid-Xi/cdn@1.9.1/img/blog/sim/rrt2.jpg" width="80%" />  

<img src="https://cdn.jsdelivr.net/gh/Javid-Xi/cdn@1.9.1/img/blog/sim/rrt1.jpg" width="80%" />

## 5. 自主导航算法仿真
### 5.1 导航效果
设定目标点并进行路径规划：
<table>
	<tr>
		<td><img src="https://cdn.jsdelivr.net/gh/Javid-Xi/cdn@1.9.1/img/blog/sim/nav2.jpg"/></td>
		<td><img src="https://cdn.jsdelivr.net/gh/Javid-Xi/cdn@1.9.1/img/blog/sim/nav1.jpg"/></td>
	</tr>
</table>

抵达目标点：
<table>
	<tr>
		<td><img src="https://cdn.jsdelivr.net/gh/Javid-Xi/cdn@1.9.1/img/blog/sim/nav4.jpg"/></td>
		<td><img src="https://cdn.jsdelivr.net/gh/Javid-Xi/cdn@1.9.1/img/blog/sim/nav3.jpg"/></td>
	</tr>
</table>

### 5.2 计算图
<img src="https://cdn.jsdelivr.net/gh/Javid-Xi/cdn@1.9.1/img/blog/sim/nav-graph.jpg"/>

