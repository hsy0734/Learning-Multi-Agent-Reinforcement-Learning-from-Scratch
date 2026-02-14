# 0基础学习多智能体强化学习 - 学习仓库

本仓库专为 0 基础学习者设计，系统性地整理了从 Python 基础到强化学习核心算法的学习路径。通过代码实践与理论结合，助力快速掌握强化学习的核心思想。

## 🚀 学习路径概览

仓库内容按照学习顺序排列，建议从 `0.1` 开始逐步深入。

### 阶段 0：基础准备
这一阶段旨在打好编程基础，掌握必要的库和框架。

- **0.1 Python 速成**
  - [0.1.1-三个小时速成python.ipynb](file:///c:/Users/24584/-0-/0.1.1-三个小时速成python.ipynb): 快速掌握 Python 核心语法。
- **0.2 游戏与环境开发基础**
  - [0.3.1-15min速成pygame sys time介绍.ipynb](file:///c:/Users/24584/-0-/0.3.1-15min速成pygame sys time介绍.ipynb): 学习如何使用 Pygame 构建简单的可视化环境。
  - [0.3.2-gym库介绍.ipynb](file:///c:/Users/24584/-0-/0.3.2-gym库介绍.ipynb): 了解强化学习标准接口 OpenAI Gym/Gymnasium。
- **0.3 深度学习框架**
  - [0.3.3-一个小时速成pytorch神经网络.ipynb](file:///c:/Users/24584/-0-/0.3.3-一个小时速成pytorch神经网络.ipynb): 掌握 PyTorch 基础，为深度强化学习做准备。

### 阶段 1：强化学习入门实战
通过经典控制问题初步体验强化学习的闭环。

- **1.1 经典 Demo**
  - [0.3.4-cartpole.ipynb](file:///c:/Users/24584/-0-/0.3.4-cartpole.ipynb): 跑通第一个强化学习 Demo —— 平衡杆（CartPole）。

### 阶段 2：强化学习理论与算法（核心内容）
本阶段深入研究强化学习的经典算法，位于 `深度学习入门4强化学习` 文件夹中。

- **2.1 基础模型**
  - [1_老虎机算法的实现.ipynb](file:///c:/Users/24584/-0-/深度学习入门4强化学习/1_老虎机算法的实现.ipynb): 学习探索与利用（Exploration vs Exploitation）。
  - [2_马尔可夫决策过程.ipynb](file:///c:/Users/24584/-0-/深度学习入门4强化学习/2_马尔可夫决策过程.ipynb): 理解 MDP 框架。
  - [3贝尔曼方程.ipynb](file:///c:/Users/24584/-0-/深度学习入门4强化学习/3贝尔曼方程.ipynb): 掌握强化学习的核心数学基础。

- **2.2 经典求解方法**
  - [4.1动态规划.ipynb](file:///c:/Users/24584/-0-/深度学习入门4强化学习/4.1动态规划.ipynb): 使用 DP 求解已知模型的环境。
  - [5.0蒙特卡洛方法.md](file:///c:/Users/24584/-0-/深度学习入门4强化学习/5.0蒙特卡洛方法.md): 学习无模型（Model-Free）的采样学习。
  - [5.1重要性采样.md](file:///c:/Users/24584/-0-/深度学习入门4强化学习/5.1重要性采样.md): 解决 Off-policy 学习的关键技术。

- **2.3 时序差分（TD）学习**
  - [6.0TD方法.md](file:///c:/Users/24584/-0-/深度学习入门4强化学习/6.0TD方法.md): 结合 DP 和 MC 优点的核心方法。
  - [6.1sarsa方法.md](file:///c:/Users/24584/-0-/深度学习入门4强化学习/6.1sarsa方法.md): 在线策略（On-policy）学习。
  - [6.2q学习.md](file:///c:/Users/24584/-0-/深度学习入门4强化学习/6.2q学习.md): 离线策略（Off-policy）学习。
  - [6.3分布模型与样本模型.md](file:///c:/Users/24584/-0-/深度学习入门4强化学习/6.3分布模型与样本模型.md): 理解模型类别。

## 🛠️ 环境配置建议

- **Python**: 3.10+
- **核心库**: `gymnasium`, `pygame`, `torch`, `numpy`, `dezero`
- **兼容性提示**: 针对 NumPy 2.0+ 移除了 `np.int` 的问题，建议在代码中使用 `int` 或参考 `test.py` 中的兼容性补丁。

## 🔗 参考资料
- Python 基础：[B站速成视频](https://www.bilibili.com/video/BV1xHn9z8EPX?t=0.6)
- 多智能体概览：[B站概览视频](https://www.bilibili.com/video/BV1tF411b7bg?t=0.8)
- RL 基本思想：[CartPole 实战视频](https://www.bilibili.com/video/BV1Jz421X7KX?t=0.7)

---
*持续更新中，敬请关注后续多智能体进阶算法内容。*
