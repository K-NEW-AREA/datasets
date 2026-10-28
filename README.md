# K-NEW AREA · 具身智能数据集

K-NEW AREA 是聚焦具身智能的开源社区，欢迎贡献模型、框架、数据集和相关资料。本仓库集中整理数据集入口、下载方法和使用说明；数据文件保留在原托管平台。

## 数据集目录

| 数据集 | 托管平台 | 下载与说明 |
| --- | --- | --- |
| Catch123 | ModelScope | [数据集主页](https://modelscope.cn/datasets/AlicePotter/Catch123) · [本仓库说明](datasets/Catch123.md) |

## 快速下载 Catch123

```bash
pip install modelscope
modelscope download --dataset AlicePotter/Catch123 --local_dir ./data/Catch123
```

ModelScope 页面显示数据集约 1.59 GB。下载前请预留磁盘空间。更多信息和数据文件以[原始数据集页面](https://modelscope.cn/datasets/AlicePotter/Catch123)为准。

## 仓库与数据的关系

- 本仓库用于维护索引、文档和后续使用代码，不在 GitHub 重复托管大型数据文件。
- 本仓库采用 Apache License 2.0；Catch123 数据集的许可与使用条件请查看 ModelScope 页面。
- 数据集目前由 ModelScope 账号 `AlicePotter` 发布；本仓库提供社区入口，不改变原始发布位置。

## 参与贡献

欢迎通过 [Issues](https://github.com/K-NEW-AREA/datasets/issues) 反馈下载、数据说明或使用问题，也欢迎提交 Pull Request 补充可验证的使用示例。请附上数据集链接、复现步骤、环境信息及预期与实际结果。
