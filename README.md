# HUST简约PPT 主题模板
鉴于日常做ppt的需求各异，场景不同，往往很难找到合适的模板，基本都需要再定制化。网上流传的一些hust相关ppt（我找到的）很不好使，设计粗糙、图片夸张、附加各种奇怪的动画和音效，借用来时需要频繁修改字体格式等。还有一些质量比较高一些的ppt，动辄几十块一个，或是需要发pyq挂时长&集赞来获取（特指公众号：华*情报站）。而且这些ppt难以适配新的应用场景，故而仿照
[THU-Theme-PPT](https://github.com/atomiechen/THU-PPT-Theme)，制作了一些简约主题的“基座ppt”，你可以将其作为母版来使用。 

## 📂 structure

本仓库包含 HUST 简约主题模板、相关设计素材以及实验性变体，总共有两个branch：main和otherPPTs。otherPPTs主要存放搜集到的ppt模板，
以下是main的目录结构：

```text
Project_Root
├── 1Compus_pictures/           # 🖼️ 校园素材库
│   ├── 视觉中国/                 # 高质量版权图片参考
│   └── hust校园风光/             # 华科大标志性建筑与风景图
│
├── 1HUST-Theme-PPT/            # 🎨 核心简约模板（日常展示推荐）
│   ├── v1扁平                    # 无边框沉浸式设计
│   ├── v1顶边                    # 顶部带修饰色块，适合学术汇报
│   ├── v1留边                    # 杂志风格，四周留白
│   └── [4-3] / [16-9]          # 对应投影比例
│
├── 2Varians-PPT/               # 🧩 其他变体
│   └── ...                     # 包含特殊进度条、实验性配色等版本
│
├── 3logo/                      # hust常用logo
│
├── log.md                      # 📝 修改日志
│
└── LICENSE                     # 📄 开源许可证
```

## View

比例4-3:扁平、顶边、留边和变体。
<div align="center">
  <a href="./0figures/demo4-3.png">
    <img src="./0figures/demo4-3.png" width="100%" alt="4:3 Panorama">
  </a>
</div>

比例16—9:v1扁平、v1顶边、v1留边、v2扁平、v3顶边白底、v3留边白底
<div align="center">
  <a href="./0figures/demo16-9.png">
    <img src="./0figures/demo16-9.png" width="100%" alt="16:9 Panorama">
  </a>
</div>

### 🔍 Description
为了方便查找，PPT 文件名遵循以下命名规范：

> **格式：** `v[版本号][设计风格][比例].pptx`

- **设计风格**：
  - `扁平`：全屏背景，无边框，视野开阔。
  - `顶边`：顶部带有 HUST 主题色条，适合放置标题。
  - `留边`：四周留白，类似打印文档或杂志排版，更显精致。
- **比例**：
  - `16-9`：适合大多数宽屏显示器和笔记本。
  - `4-3`：适合老式投影仪或学术会议标准。

**示例**：如果你需要一个宽屏的、带有顶部标题栏的模板，请选择 `v1顶边16-9.pptx`。


## How to do  

根据提供的ppt模板，可以直接在其上进行修改使用，也可以进入模板视图进行定制化修改，比如更换ppt背景、logo等。

---
具体使用方法： 
<details>
<summary><strong>👇 点击查看：如何将模板应用到现有 PPT</strong></summary>

<br>

1. **确认尺寸**：确保当前 PPT 比例 (4:3 或 16:9) 与模板匹配。
2. **进入设计**：点击菜单栏 **「设计 (Design)」** 选项卡。
3. **浏览主题**：点击主题栏右下角的箭头 (▼) → 选择 **「浏览主题... (Browse for Themes)」**。
4. **应用文件**：找到并选中 `.potx` 模板文件，点击 **「应用」** 即可。

</details>


## 🔗 Others  

在这个 PPT 模板仓库中，我们为您整理了一些关键的资源链接，帮助您更好地使用和设计 PPT。以下是与 PPT 相关的有用资源：

1. **[HUST Visual Identity](https://vi.hust.edu.cn/index.htm)**
   <details>
   <summary><strong>作为华中科技大学的官方视觉标识...</strong></summary>
   作为华中科技大学的官方视觉标识，提供了规范的颜色、字体和布局参考。点击此链接可以查看学校的官方视觉标识及其应用规范，从而帮助您设计更符合学校形象的 PPT。
   </details>

2. **[阿里巴巴矢量图标库](https://www.iconfont.cn/?spm=a313x.search_index.i3.d4d0a486a.38133a81heCvs1)**
   <details>
   <summary><strong>阿里巴巴矢量图标库是一个广泛使...</strong></summary>
   阿里巴巴矢量图标库是一个广泛使用的图标资源平台，您可以从中选择各种矢量图标来增强您的幻灯片设计。通过此链接，您可以访问图标库，选择您所需的图标，提升您的 PPT 设计效果。
   </details>



## License
[HUST-Theme-PPT](https://github.com/LSTM-zhul/HUST-PPT) © 2025 by [LSTM-zhul](https://github.com/LSTM-zhul) under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).[![CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
