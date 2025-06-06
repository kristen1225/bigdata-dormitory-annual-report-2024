# 🏠 大数据宿舍年度数据分析报告 2024

[![GitHub license](https://img.shields.io/github/license/username/repo)](https://github.com/username/repo/blob/main/LICENSE)
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Data Analysis](https://img.shields.io/badge/Data-Analysis-green.svg)](https://pandas.pydata.org/)

## 📊 项目概述

本项目运用大数据技术对学生宿舍的日常生活数据进行全面分析，通过数据挖掘和统计分析方法，生成详细的年度报告，为宿舍管理和学生生活质量改善提供数据支撑。

### 🎯 项目目标

- 🔍 **数据收集**：系统收集宿舍用电、用水、网络使用等多维度数据
- 📈 **趋势分析**：识别学生生活习惯的时间模式和季节性变化
- 💡 **智能建议**：基于数据分析结果提供节能减排和生活优化建议
- 📋 **可视化报告**：生成直观的数据可视化图表和综合性报告

## 🏢 宿舍基本信息

| 项目 | 详细信息 |
|------|----------|
| **宿舍楼栋** | 学生公寓A栋 |
| **宿舍号** | A-3-305 |
| **成员数量** | 4人 |
| **房间面积** | 25平方米 |
| **统计周期** | 2024年1月1日 - 2024年12月31日 |
| **数据源** | 智能电表、水表、路由器日志、学习时长统计APP |

## 📊 核心数据统计

### ⚡ 用电数据分析

#### 月度用电量统计
```
1月: 245 kWh  |  2月: 198 kWh  |  3月: 267 kWh  |  4月: 289 kWh
5月: 312 kWh  |  6月: 356 kWh  |  7月: 423 kWh  |  8月: 445 kWh
9月: 334 kWh  | 10月: 298 kWh  | 11月: 256 kWh  | 12月: 234 kWh
```

**年度总用电量：** 3,657 kWh  
**月均用电量：** 304.75 kWh  
**日均用电量：** 10.02 kWh  

#### 用电模式分析
- **峰值时段**：19:00-23:00（晚间学习和娱乐时间）
- **低谷时段**：02:00-06:00（休息时间）
- **夏季用电特点**：空调使用导致7-8月用电量激增
- **节能效果**：通过智能插座控制，待机功耗降低15%

### 💧 用水数据分析

#### 季度用水量统计
```
Q1 (1-3月): 36.8 吨    Q2 (4-6月): 42.3 吨
Q3 (7-9月): 51.7 吨    Q4 (10-12月): 38.9 吨
```

**年度总用水量：** 169.7 吨  
**月均用水量：** 14.14 吨  
**人均日用水量：** 116 升  

### 🌐 网络使用分析

#### 网络流量统计（TB）
- **学习相关流量**：2.34 TB（在线课程、学术资源下载）
- **娱乐流量**：4.67 TB（视频流媒体、游戏更新）
- **社交通信**：0.89 TB（视频通话、社交媒体）
- **其他应用**：1.23 TB（系统更新、软件下载）

**总流量：** 9.13 TB  
**月均流量：** 760 GB  

### 📚 学习数据统计

#### 学习时长分析
```
成员A: 2,847小时  |  成员B: 2,634小时
成员C: 2,901小时  |  成员D: 2,723小时
```

**宿舍总学习时长：** 11,105小时  
**人均学习时长：** 2,776.25小时  
**日均学习时长：** 7.6小时/人  

#### 学习效率分析
- **高效时段**：09:00-11:00, 14:00-16:00, 19:00-21:00
- **专注度最高的月份**：3月、9月（开学季）
- **学习方式分布**：线上学习65%，线下自习35%

## 📈 数据可视化展示

### 月度用电量趋势图
```
    用电量(kWh)
    500 |
    400 |        ●●
    300 |    ●●●    ●●
    200 |  ●          ●●
    100 |
      0 +--+--+--+--+--+--+--+--+--+--+--+--
        1  2  3  4  5  6  7  8  9 10 11 12 月份
```

### 学习时长vs用电量相关性分析
- **相关系数**：0.73（强正相关）
- **分析结论**：学习时间越长，用电量越高，主要因素为电脑、台灯、空调的使用

## 🔍 深度数据分析

### 生活模式识别

#### 作息时间分析
通过用电和网络使用数据，识别出宿舍成员的作息规律：
```
起床时间: 06:30-07:30
就寝时间: 23:00-24:00
午休时间: 12:30-13:30
学习黄金时间: 09:00-11:00, 14:00-17:00, 19:00-22:00
```

#### 季节性行为模式
- **春季（3-5月）**：学习时长增加，用电量稳定上升
- **夏季（6-8月）**：空调使用频繁，用电量达到峰值
- **秋季（9-11月）**：学习强度最高，网络使用量增加
- **冬季（12-2月）**：取暖需求增加，用水量相对较高

### 成本效益分析

#### 年度费用统计
```
电费: 1,828.5元 (0.5元/kWh)
水费: 509.1元 (3.0元/吨)
网费: 1,200元 (100元/月)
总计: 3,537.6元
人均: 884.4元
```

#### 节能减排成果
- **LED灯具改造**：节电15%，年省电费274.3元
- **智能插座使用**：减少待机功耗12%，年省电费219.4元
- **用水习惯优化**：节水8%，年省水费40.7元

## 💡 智能化改进建议

### 短期改进措施（1-3个月）
1. **安装智能温控系统**：根据作息时间自动调节空调温度
2. **优化网络使用**：在学习时段限制娱乐流量，提高学习效率
3. **建立用水提醒机制**：通过APP推送每日用水量，培养节水意识

### 中期改进计划（3-6个月）
1. **引入物联网传感器**：实时监控室内环境参数
2. **建立预测模型**：基于历史数据预测未来用电用水需求
3. **开发宿舍管理小程序**：集成各类数据监控和生活服务功能

### 长期发展目标（6-12个月）
1. **构建智慧宿舍生态系统**：整合所有智能设备和系统
2. **建立宿舍间数据共享平台**：促进最佳实践的推广
3. **开展大数据研究项目**：将宿舍数据用于学术研究和政策制定

## 🛠️ 技术实现方案

### 数据采集技术栈
```python
# 数据采集框架
import pandas as pd
import numpy as np
from datetime import datetime, timedelta
import sqlite3
import requests
from bs4 import BeautifulSoup

# 传感器数据读取
class DormitoryDataCollector:
    def __init__(self, db_path="dormitory_data.db"):
        self.db_path = db_path
        self.setup_database()
    
    def collect_electricity_data(self):
        """采集用电数据"""
        # 从智能电表API获取数据
        pass
    
    def collect_water_data(self):
        """采集用水数据"""
        # 从智能水表获取数据
        pass
    
    def collect_network_data(self):
        """采集网络使用数据"""
        # 从路由器日志分析网络流量
        pass
```

### 数据分析算法
```python
# 时间序列分析
from sklearn.preprocessing import StandardScaler
from sklearn.cluster import KMeans
import matplotlib.pyplot as plt
import seaborn as sns

def analyze_usage_patterns(data):
    """分析使用模式"""
    # 聚类分析识别使用模式
    scaler = StandardScaler()
    scaled_data = scaler.fit_transform(data)
    
    kmeans = KMeans(n_clusters=4, random_state=42)
    clusters = kmeans.fit_predict(scaled_data)
    
    return clusters

def predict_future_usage(historical_data):
    """预测未来使用量"""
    # 使用ARIMA模型进行时间序列预测
    pass
```

## 📚 项目文档结构

```
📁 docs/
├── 📄 API文档.md
├── 📄 数据字典.md
├── 📄 安装部署指南.md
├── 📄 用户使用手册.md
└── 📄 开发者指南.md

📁 analysis/
├── 🐍 data_preprocessing.py
├── 🐍 statistical_analysis.py
├── 🐍 machine_learning_models.py
└── 🐍 visualization_generator.py
```

## 🤝 贡献指南

欢迎对本项目进行贡献！请遵循以下步骤：

1. **Fork** 本仓库到您的GitHub账户
2. **创建特性分支** (`git checkout -b feature/AmazingFeature`)
3. **提交更改** (`git commit -m 'Add some AmazingFeature'`)
4. **推送到分支** (`git push origin feature/AmazingFeature`)
5. **开启Pull Request**

### 代码规范
- 遵循PEP 8 Python代码规范
- 添加必要的注释和文档字符串
- 确保所有测试通过
- 更新相关文档

## 📜 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 👥 项目团队

| 姓名 | 角色 | 联系方式 |
|------|------|----------|
| 张三 | 项目负责人 | zhangsan@example.edu.cn |
| 李四 | 数据分析师 | lisi@example.edu.cn |
| 王五 | 前端开发 | wangwu@example.edu.cn |
| 赵六 | 后端开发 | zhaoliu@example.edu.cn |

## 🙏 致谢

感谢以下项目和组织的支持：
- XX大学大数据学院提供的实验环境
- 宿舍管理中心提供的数据支持
- 开源社区提供的技术框架和工具

---
