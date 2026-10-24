# learn · 科研学习记录

记录 PGC 仿真、光电传感、高速光通信与编程实践，把学习过程整理成可追溯、可复现、可继续的材料。

## 目录

| 目录 | 用途 |
| --- | --- |
| [pgc-simulation/](pgc-simulation/README.md) | LabVIEW PGC 仿真、解调流程与对照实验 |
| [photoelectric-sensing/](photoelectric-sensing/README.md) | 光电传感原理、器件与测量记录 |
| [high-speed-optical-communication/](high-speed-optical-communication/README.md) | 高速光通信模型、链路与性能分析 |
| [programming-tools/](programming-tools/README.md) | LabVIEW、MATLAB、Python 和其他工具实践 |
| [literature-notes/](literature-notes/README.md) | 文献阅读、公式理解与复现线索 |
| [templates/](templates/) | 可复现记录、实验参数、文献笔记模板 |

## 开始一条记录

1. 在对应主题下创建 `YYYY-MM-DD-short-topic/`，同一天的不同实验使用不同名称。
2. 复制[可复现记录模板](templates/reproducible-record.md)为该目录的 `README.md`；有实验或仿真时，再复制[实验参数模板](templates/experiment-parameters.md)为 `parameters.md`。
3. 写明目的、环境、输入、操作步骤和判断标准，再保存实际结果；未运行的内容标注“待运行”，不预填结论。
4. 将源文件、参数和记录一起提交。文献阅读直接使用[文献笔记模板](templates/literature-note.md)。

一个实验最初只需 `README.md`、`parameters.md` 和必要源文件。数据、图片和分析脚本按实际需要添加。

## 维护约定

- 文件使用有含义的名称；每次提交围绕一个学习问题或实验变化。
- 数值写明单位和来源；假设、实测结果与推断分开记录。
- 保留失败尝试和卡住的问题；修正结论时补充原因。
- 大文件保存在外部时，记录稳定位置、文件名、获取方法和 SHA-256；仓库中保留可公开的小样本。
- 公开前移除密钥、个人信息和未获授权的材料；文献以链接与自己的笔记为主。

后续如何添加脚本、依赖和自动检查，见[扩展与维护说明](docs/maintenance.md)。当前仅提供目录和模板，尚无已运行的科研实验。
