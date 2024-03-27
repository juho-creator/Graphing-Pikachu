[![English](https://img.shields.io/badge/lang-English-blue.svg)](https://github.com/juho-creator/Interactive-Pikachu-Pokeball-Graph/blob/main/README.md)
[![한국어](https://img.shields.io/badge/lang-한국어-red.svg)](https://github.com/juho-creator/Interactive-Pikachu-Pokeball-Graph/blob/main/README.KR.md)

# 互动皮卡丘图
* 这是一个皮卡丘和精灵球漂浮在水上的互动图表。
* 总共使用了 30 个方程式，包括 10 种不同类型的函数。
<br />
<br />


# 图表演示
![Pikachu_-_Chrome_2023-05-28_16-11-35_AdobeExpress (1)](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/df81b209-0bf5-4404-8255-aa2323151de5)
<br />
<br />
<br />
<br />
<br />

# 如何使用互动图表
1. 单击 [Pikachu Graph](https://www.desmos.com/calculator/v8mpye0wof) 来访问互动图表。
2. 单击每个文件夹中的播放按钮来控制每个组件。
3. 欲了解有关动画控制的更多详细信息，请参阅 [控制设置](https://github.com/juho-creator/Interactive-Pikachu-Pokeball-Graph/blob/main/README.md#control-settings)

<br />
<br />
<br />
<br />


# 控制设置
* 您可以调整皮卡丘、精灵球和水的设置。 <br />
* 每个组件的控制设置位于以下文件夹中：**`Pikachu_Control, Pokeball_Control, Water_Control`**
<br />


### Pikachu_Control :
* **P <sub> Horizontal</sub>** : 皮卡丘的水平位置
* **P <sub> Vertical </sub>** : 皮卡丘的垂直位置
<br />
<br />


### Pokeball_Control: 
* **B	<sub>Horizontal</sub>** : 精灵球水平位置
* **B <sub>Vertical</sub>** : 精灵球的垂直位置
<br />
<br />


### Water_Control :
* **W <sub> Flow</sub>** : 启用水的动画<br />
* **W <sub>Amp </sub>** : 波浪振幅<br />
* **W	<sub> freq</sub>** : 波浪频率 <br />
* **W <sub>Level </sub>** : 水位<br />

<br />
<br />
<br />
<br />

# 创作过程

## 皮卡丘设计

创建皮卡丘涉及大量的时间投入，使用多个方程式来精确地追踪每个部分。

**步骤1：** 将皮卡丘的基本图像导入 Desmos。<br /><br />

**步骤2：** 开发了一个抛物线方程，其中包含可变常数 A、B 和 C，用于控制凹度、X 和 Y 位置。 <br />
该方程用于追踪皮卡丘的特定部分：
$Y = A((X - B)^2) + C$
<br /><br />

**步骤3：** 将图表与图像对齐后，使用域和范围调整去除不必要的部分。 <br />
![Step 3](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/88e56472-a879-4144-8cb2-e50f300d62f0)
<br /><br />

**步骤4：** 如果抛物线方程未覆盖某些部分，则应用其他方程 <br />
(例如：圆、椭圆、对数、指数、立方、平方根)。<br />
![Step 4](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/848dce22-e0b1-4037-8e9f-9bb35d6382d9)
<br /><br />

**步骤5：** 重复步骤1到步骤4，完成皮卡丘图像。 <br /><br />

**步骤6：** 为了使皮卡丘互动，将滑块变量并入每个部分方程式，使其能够控制皮卡丘的水平和垂直对齐。 <br />
![Step 6](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/f740967f-7dd2-4423-91c6-f995e49a12b5)

通过这个综合的过程，通过方程式的组合和仔细的调整，精心制作了互动皮卡丘。

<br />
<br />
<br />
<br />

## 精灵球设计

制作精灵球涉及一个简单的过程，使用一个水平渐近线和两个圆。

**步骤1：** 圆的方程模板被建立为：$(X-A)^2 + (Y-B)^2 = C^2$。 <br /><br />

**步骤2：** 调整两个圆的大小。 <br />
![Step 2](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/beb67fe5-adab-4f77-96ee-f9a7a85dfbb5)
<br /><br />

**步骤3：** 生成两个不同的水平渐近线，每个具有特定的定义域，以形成精灵球的中心线。 <br />
![Step 3](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/762c90a4-571c-4e8f-b0fa-2b941eb5b2a0)
<br /><br />

**步骤4：** 将两个滑块变量并入每个方程中，以便轻松控制精灵球的水平和垂直位置。<br />
![Step 4](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/cbe51756-feb1-4c6c-8cad-c2208d755d21)
<br /><br />

这个流程简化了流程，创建了互动式精灵球，利用方程式设计和动态调整。

<br />
<br />
<br />
<br />

## 水设计

水方程的创建是一个相对简单的过程，使用带有不等式的正弦方程。 <br />
然而，挑战在于为正弦波开发各种互动功能。
<br /><br />


**步骤1：** 将正弦函数与不等式结合起来，生成填充在图表下方的彩色波状形式的效果，模拟水的外观。<br />
![Step 1](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/cc93cff3-219d-404b-b094-5d4abb404dfa)
<br /><br />

**步骤2：** 为了能够控制水波，引入了四个滑块变量。<br />
![Step 2](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/b03b495f-4305-4717-ab9a-d8a5ae29f076)
<br /><br />
这种方法导致了水效果的创建，利用带有互动组件的正弦方程，实现了动态的视觉体验。

<br />
<br />
<br />
<br />


# 图表组件

对于每个组件，图表功能都组织在以下文件夹中：

### 1. 皮卡丘
皮卡丘由以下功能组成：
* 圆形（9）
* 抛物线（9）
* 椭圆（2）
* 对数（2）
* 指数（1）
* 立方体（1）
* 平方根（1）
<br /><br />

### 2. 精灵球
精灵球包含以下功能：
* 圆形（2）
* 水平渐近线（2）
<br /><br />


### 3. 水
水由正弦函数组成。
<br /><br />

总共使用了 30 个方程式，包括 10 种不同类型的函数，用于创建这些图形组件。
