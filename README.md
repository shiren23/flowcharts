# Flowcharts - 批改留痕流程图与界面原型

商量智能批阅小程序 — 批改留痕相关功能的流程图与界面原型图。

## 在线预览

### 卡纸中断续打 [P0]

| 文件 | 说明 | 链接 |
|------|------|------|
| 卡纸中断续打流程图 | 卡纸检测、处理、续打完整流程 | [查看](https://shiren23.github.io/flowcharts/) |
| 卡纸中断续打界面设计 | 卡纸场景下的界面原型 | [查看](https://shiren23.github.io/flowcharts/kazhi-ui.html) |

### 试卷乱序二次匹配 [P1]

| 文件 | 说明 | 链接 |
|------|------|------|
| 试卷乱序二次匹配流程图 | 乱序重扫、智能匹配、手动补匹配流程 | [查看](https://shiren23.github.io/flowcharts/luansu-liucheng.html) |
| 试卷乱序二次匹配界面设计 | 乱序场景下的界面原型 | [查看](https://shiren23.github.io/flowcharts/luansu-ui.html) |

### 留痕打印优化

| 文件 | 说明 | 链接 |
|------|------|------|
| 留痕打印新界面 | 留痕打印页面优化原型 | [查看](https://shiren23.github.io/flowcharts/liuhen-dayin.html) |
| 留痕优化流程图 | 留痕打印优化流程 | [查看](https://shiren23.github.io/flowcharts/liuhen-liucheng.html) |
| 留痕打印弹窗原型 | 佳能/汉图打印机弹窗界面设计 | [查看](https://shiren23.github.io/flowcharts/printer-modals.html) |

### DeepSeek TUI 教程

| 文件 | 说明 | 链接 |
|------|------|------|
| DeepSeek TUI Mac 教程 | 面向 Mac 新手的下载与使用教程 | [查看](https://shiren23.github.io/flowcharts/deepseek-tui-tutorial.html) |

## UI 设计规范

详见 [文生图prompt.md](文生图prompt.md)，包含中英文 Prompt 及完整风格要素定义。

| 要素 | 描述 |
|------|------|
| 布局 | 白色卡片式分组，圆角12px，卡片间距12-16px |
| 背景色 | 纯白 `#FFFFFF` |
| 主色 | 紫色 `#7B61FF` |
| 正确状态 | 绿色 `#52C41A` |
| 错误状态 | 红色 `#FF4D4F` |
| 设计风格 | 扁平化，极简，轻量阴影，无装饰性元素 |
| 设备比例 | 9:20 竖屏（iPhone比例） |

## 项目结构

```
├── index.html                  # 卡纸中断续打流程图（首页）
├── kazhi-ui.html               # 卡纸中断续打界面原型
├── luansu-liucheng.html        # 试卷乱序二次匹配流程图
├── luansu-ui.html              # 试卷乱序二次匹配界面原型
├── liuhen-dayin.html           # 留痕打印新界面原型
├── liuhen-liucheng.html        # 留痕优化流程图
├── printer-modals.html         # 留痕打印弹窗界面原型
├── 文生图prompt.md              # UI 设计文生图 Prompt
├── deepseek-tui-tutorial.html  # DeepSeek TUI Mac 使用教程
└── .github/workflows/
    └── static.yml              # GitHub Pages 部署工作流
```
