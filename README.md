# 图灵计划-系统功能点梳理

目前图灵计划的开发主要分为以下几个部分：多目标选择共识算法, TURIING虚拟机设计,P2P系统网络,系统账户管理,构建工具,公共基础类,事件处理类,
系统日志处理,	交易数据,区块数据 和 数据库设计。

项目的详细研发计划会陆续更新。

		
## 1.	多目标选择共识算法
1.	算法外部API的开发
2.	算法异常数据流程定义
3.	算法的一次跳票机制
4.	算法的外围投票机制
5.	算法快照的生成，处理与销毁
6.	算法的初始化工具包
7.	算法的内存初始化
8.	算法的激励机制设计
9.	分叉机制设计
10.	算法区块信息的维护
11.	算法引擎接口的设计
12.	算法的验证机制
13.	算法进入授权机制
14.	挖矿代理设计
15.	算法对交易数据的处理
16.	算法对未确认/已确认数据的处理
17.	算法的自动启停机制
18.	矿机Basecoin地址变更机制
## 2.	TURIING虚拟机设计
19.	虚拟机编译器设计
20.	任务分解代码设计
21.	任务分解代码部署
22.	虚拟数据与区块数据的同步
23.	任务完成判断机制
24.	虚拟机的Session处理
25.	虚拟机代码的校验
26.	虚拟机交易数据的处理
27.	虚拟机账户信息处理
28.	交互式的代码处理环境
29.	高级交易和脚本处理
30.	任务协议格式确认
## 3.	P2P系统网络
31.	节点启动
32.	节点建立
33.	网络邻居节点发现
34.	网络普通握手协议
35.	网络握手加密协议
36.	网络编码数据流
37.	网络状态存储
38.	基于UDP的交易蔓延机制
39.	网络适配器
40.	网络的NTP同步数据服务
41.	网络错误数据处理
42.	网络事件跟踪机制
43.	网络http信道建立
44.	网络消息的解码处理
45.	网络安全相关维护机制
46.	网络连接客户端开发
47.	网络节点信息暴露接口
48.	网络节点心跳维护机制
49.	RPC接口开发
50.	下载网络快照
51.	邻居节点的展现
52.	网络信息的订阅处理
53.	网络广播接口
54.	手动添加网络节点
55.	Kademlia协议(模型)设计与实现
56.	Kademlia协议自动刷新机制
57.	网络消息的封装与处理
58.	网络中buffer机制设计
## 4.	系统账户管理
59.	系统账户生成
60.	系统账户权限控制
61.	多重账户维护
62.	任务执行燃料
63.	系统管理的账户管理
64.	账户的密码相关操作（签名，验签）
65.	账户事件处理流
66.	账户的地址映射与编解码
67.	账户的异常处理
68.	账户调用接口
69.	账户的锁定与解锁
## 5.	构建工具
70.	Windows平台下Go 的系统构建工具开发
71.	Linux下Go 的系统构建工具开发
72.	Docker的系统构建工具
6.	公共基础类
73.	16进制工具转换包
74.	常用数学类的工具包封装
75.	压缩工具包
76.	签名工具包
77.	Hash摘要工具包
78.	系统的编码工具包
## 7.	事件处理类
79.	事件的订阅
80.	事件的封装类
81.	事件过滤器
## 8.	系统日志处理
82.	日志结构设计
83.	日志过滤器设计
84.	总日志处理器
## 9.	交易数据
85.	交易数据格式
86.	交易数据流开发
87.	交易验证器
88.	交易池设计
89.	交易的排序机制
90.	交易缓存数据转移
91.	交易的命令行设计
92.	交易的数据同步
93.	交易的自动采集机制
94.	交易的广播机制
95.	交易的拉取功能（从邻居拉去）
96.	交易的推送功能
97.	交易的过滤器
98.	交易下载序列
99.	交易的统计信息处理
100.	交易的事件处理
101.	交易节点的自动感知
102.	交易的数据组织结构(Merkle tree)
103.	交易的转账功能
104.	交易节点数据的监控
105.	交易时间锁
## 10.	区块数据
106.	区块的数据格式设计
107.	区块验证器
108.	区块的入链分叉机制设计
109.	区块对外接口
110.	区块的事件处理
111.	区块的自动同步
112.	未确认区块的广播
113.	已确认区块的广播
114.	区块的延迟获取（头部）
115.	区块的下载
116.	区块的转储功能
117.	最新区块的导出功能
## 11.	数据库设计
118.	数据编码格式的设计
119.	数据库接口设计
120.	数据库读写锁的设计
121.	数据库日志跟踪机制
122.	初始化数据库
123.	数据库的增删改查
124.	数据段chunker数据存储设计
125.	缓存型存储机制设计

