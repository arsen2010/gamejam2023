1. 背景图移动组件：
  - prefab，包含一个背景图
  - 一个组件可以控制背景图的向上移动速度；比如每次update 1个像素
2. 吸引力组件：挂载后，可以每次把目标节点往吸引方向移动多少距离
   - 目标：Node
   - 吸引力方向
   - 吸引力大小
3. 操控主角：点击按钮时让node往移动方向移动部分距离
  - prefab,包含一个按钮
  - 目标：Node
  - 移动方向 
  - 移动速度

4. 收集、障碍系统
  - 收集物放置
    - 数量
    - 速度
  - 障碍物放置
    - 数量
    - 速度

5. 边界检测
  - 目标：Node
  - 设置边界 ，当Node的位置超过某个边界时，游戏结束

6. 主角prefab
  - prefab,包含主角

7. 游戏管理逻辑：负责管理游戏状态
  - 游戏开始按钮 prefab
  - 下一关 按钮
  - 失败逻辑

8. 武器发射
