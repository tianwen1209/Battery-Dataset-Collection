# 电池数据集收集 (Battery Dataset Collection)

[![GitHub stars](https://img.shields.io/github/stars/tianwen1209/battery-dataset-collection)](https://github.com/tianwen1209/battery-dataset-collection/stargazers)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://makeapullrequest.com)

[English](./README_EN.md) | 中文

这个仓库收集了公开可用的电池数据集，旨在促进电池研究和机器学习在电池领域的应用。我们整理了来自世界各地研究机构的电池测试、性能和老化数据，为研究人员和工程师提供便利的数据访问。

## 🌟 特点

- 精选的公开电池数据集集合
- 标准化的数据集描述格式
- 详细的数据集使用指南
- 持续更新的数据集资源

## 📊 数据集列表

### 1. NASA 随机电池数据集
- **来源**: NASA Ames Research Center
- **描述**: 包含四种商用锂离子电池在不同操作条件下的充放电测试数据
- **大小**: 2.5GB
- **数据类型**: 时间序列数据
- **包含内容**:
  - 电压
  - 电流
  - 温度
  - 充放电周期
- **链接**: [数据集下载](https://link-to-dataset)
- **引用**: [相关论文](paper-link)

### 2. Oxford 电池降解数据集
- **来源**: Oxford University
- **描述**: 记录锂离子电池在快速老化测试条件下的性能变化数据
- **大小**: 1.8GB
- **数据类型**: 循环测试数据
- **包含内容**:
  - 容量衰减曲线
  - 阻抗谱数据
  - 温度分布
- **链接**: [数据集下载](https://link-to-dataset)
- **引用**: [相关论文](paper-link)

## 🚀 使用方法

1. 克隆仓库：
```bash
git clone https://github.com/tianwen1209/battery-dataset-collection.git
cd battery-dataset-collection
```

2. 浏览数据集信息：
- 访问 [项目网站](https://tianwen1209.github.io/battery-dataset-collection)
- 查看 `datasets` 目录下的详细说明文件

## 📂 仓库结构

```
battery-dataset-collection/
├── README.md              # 项目说明
├── README_EN.md          # English Version
├── LICENSE               # MIT 许可证
├── datasets/             # 数据集描述文件
│   ├── nasa/            # NASA 数据集相关文件
│   └── oxford/          # Oxford 数据集相关文件
└── docs/                # 详细文档
    ├── contribution.md  # 贡献指南
    └── dataset_spec.md  # 数据集规范说明
```

## 🤝 如何贡献

我们欢迎各种形式的贡献，包括但不限于：

1. 添加新的数据集
2. 改进文档
3. 报告问题
4. 提供使用示例
5. 分享数据集分析经验

请参考 [贡献指南](docs/contribution.md) 了解详细信息。

## 📜 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详细信息

## 🌟 致谢

感谢所有为这个项目做出贡献的研究者和机构。特别感谢：

- NASA Ames Research Center
- Oxford University
- 所有数据集贡献者

## 📮 联系方式

- 提交 Issue: [GitHub Issues](https://github.com/tianwen1209/battery-dataset-collection/issues)
- 邮箱: zhutianwen129@sina.com

## 🔗 相关链接

- [项目网站](https://tianwen1209.github.io/battery-dataset-collection)
- [数据集使用示例](./examples)
- [常见问题解答](./docs/FAQ.md)

---

## 📅 更新日志

| 日期 | 版本 | 更新内容 |
|------|------|----------|
| 2025-01-15 | v1.0.0 | - 项目初始化 <br> - 添加 NASA 和 Oxford 数据集 |
| 2025-01-15 | v1.0.1 | - 完善项目文档 <br> - 添加中英文支持 |
| 2025-01-16 | v1.0.2 | - 添加数据集规范文档 <br> - 添加贡献指南 |

我们会持续更新和维护这个项目，定期添加新的数据集和改进文档。您可以：
- Watch 这个仓库来获取更新通知
- Star 这个仓库来支持我们
- Fork 这个仓库来参与贡献

如果这个项目对您有帮助，请给我们一个 star ⭐️
