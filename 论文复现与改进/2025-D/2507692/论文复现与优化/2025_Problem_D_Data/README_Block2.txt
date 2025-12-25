MCM/ICM 2025 Problem D - Block 2: BPR Engine & Beckmann Objective
----------------------------------------------------------------------
本模块实现了交通流分配的核心反馈机制：
1. update_travel_time: 基于流量 V 计算非线性延时 T。
2. calculate_beckmann_objective: 计算用于收敛判断的全局目标函数。
这些函数利用 NumPy 向量化技术，专门针对 8.9 万条边的大规模路网进行了性能优化。
