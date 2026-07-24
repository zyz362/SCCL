# SCCL：基于平滑约束对比学习的定日镜校准方法

用于定日镜跟踪误差校准的数据集与方法，基于平滑约束和对比学习。

## 概述

本仓库提供从德国 Jülich 太阳能塔（PSA）收集的定日镜跟踪误差数据集。该数据支持太阳能聚光器校准、跟踪误差预测及基于机器学习的故障诊断研究。

## 数据集

文件 `data/priint_with_ba42.csv` 包含来自 **5 个定日镜**（AB26、AB52、AD53、AN47、BA42）的 **955 条记录**，时间跨度为 **2022 年 1 月**至 **2024 年 6 月**。

### 数据字段

| 字段 | 描述 |
|------|------|
| `heliostat_id` | 定日镜唯一标识符 |
| `timestamp` | ISO 8601 格式测量时间戳 |
| `sample_id` | 唯一样本标识符 |
| `sun_elevation` | 太阳高度角（度） |
| `sun_azimuth` | 太阳方位角（度） |
| `axis_1_motor_position` | 轴 1 电机位置 |
| `axis_2_motor_position` | 轴 2 电机位置 |
| `target_name` | 目标位置：`solar_tower_juelich_lower` 或 `solar_tower_juelich_upper` |
| `heliostat_lat/lon/alt` | 定日镜地理坐标 |
| `focal_spot_lat/lon/alt` | 焦点地理坐标 |
| `target_center_lat/lon/alt` | 目标中心地理坐标 |
| `tracking_error_lat/lon/alt` | 各方向跟踪误差 |

## 应用方向

- 定日镜跟踪误差分析与校准
- 平滑约束回归建模
- 太阳能聚光器系统的对比学习
- 预测性维护与故障检测
- 跟踪性能的时间序列分析

## 引用

如使用本数据集，请引用：

```bibtex
[发表后补充引用信息]
```

## 许可证

请参阅仓库中的许可证信息。
