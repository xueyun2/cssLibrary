### 背景颜色

| 类名            | 值       | 备注 |
| --------------- | -------- | ---- |
| bg-color-yellow | \#F1CD4C | 黄色 |
| bg-color-orange | \#FF8804 | 橘色 |
| bg-color-gray   | \#999999 | 灰色 |
| bg-color-black  | \#666666 | 黑色 |

### 文字颜色

| 类名              | 值       | 备注 |
| ----------------- | -------- | ---- |
| text-color-yellow | \#F1CD4C | 黄色 |
| text-color-orange | \#FF8804 | 橘色 |
| text-color-gray   | \#999999 | 灰色 |
| text-color-black  | \#666666 | 黑色 |

### 文字大小

| 类名         | 值   |
| ------------ | ---- |
| text-size-12 | 12px |
| text-size-14 | 14px |
| text-size-16 | 16px |
| text-size-18 | 18px |
| text-size-20 | 20px |
| text-size-22 | 22px |
| text-size-24 | 24px |

### 文字对齐

| 类名        | 值      | 备注         |
| ----------- | ------ | ------------ |
| text-center | center | 剧中对齐     |
| text-left   | left   | 左对齐       |
| text-right  | right  | 右对齐       |

### 文字加粗

| 类名      | 值   |
| --------- | ---- |
| text-bold | bold |

### 布局

> `flex`布局-所有的排列都需要带上`flex`类名

| 类名      | 值               | 备注                   |
| --------- | ---------------- | ---------------------- |
| flex      | display: flex;   | 水平排列（默认不换行） |
| flex-wrap | flex-wrap: wrap; | 允许换行               |

#### 水平排列

| 类名            | 值                              | 备注         |
| --------------- | ------------------------------- | ------------ |
| justify-start   | justify-content: flex-start;    | 左排列       |
| justify-end     | justify-content: flex-end;      | 右排列       |
| justify-center  | justify-content: center;        | 剧中排列     |
| justify-between | justify-content: space-between; | 两端排列     |
| justify-around  | justify-content: space-around;  | 周围空间分布 |

#### 垂直排列

| 类名         | 值                       | 备注     |
| ------------ | ------------------------ | -------- |
| align-start  | align-items: flex-start; | 顶部排列 |
| align-end    | align-items: flex-end;   | 底部排列 |
| align-center | align-items: center;     | 剧中排列 |

### 边距

`margin-{边距的方向}-{边距大小} `

**列如：**  margin-right-10 ; //右边距10px

> 目前只有 10px、20px、40px

`lr`-代表左右边距

`bt`-代表上下边距

- `margin`代表全局边距
- `margin-{right,left,top,bottom,lr,bt}-{10,20,40}`大括号填写任意值

| 类名           | 值   |
| -------------- | ---- |
| margin-left-10 | 10px |

#### 填充和边距同理

padding-{边距的方向}-{边距大小}