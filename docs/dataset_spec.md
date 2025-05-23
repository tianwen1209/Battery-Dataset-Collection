# 数据集规范说明

[English](./dataset_spec_EN.md) | 中文

本文档规定了向本项目提交数据集时应遵循的规范和标准。遵循这些规范可以确保数据集的一致性和可用性。

## 目录

- [基本要求](#基本要求)
- [文件组织](#文件组织)
- [数据格式](#数据格式)
- [元数据规范](#元数据规范)
- [文档要求](#文档要求)
- [数据质量标准](#数据质量标准)
- [许可证要求](#许可证要求)

## 基本要求

每个数据集必须：

1. 具有明确的开源许可证
2. 提供完整的引用信息
3. 包含详细的数据说明
4. 提供基本的使用示例
5. 说明数据收集方法和实验条件

## 文件组织

数据集文件夹结构应遵循：

```
datasets/
└── dataset_name/
    ├── README.md           # 数据集说明文档
    ├── metadata.json       # 元数据文件
    ├── data/               # 数据文件目录
    │   ├── raw/           # 原始数据
    │   └── processed/     # 处理后的数据（如果有）
    ├── examples/           # 使用示例
    └── docs/              # 补充文档
```

## 数据格式

### 支持的文件格式

- CSV (首选格式)
- HDF5
- MAT
- Excel (xlsx)
- JSON

### CSV 文件要求

1. 使用 UTF-8 编码
2. 使用逗号作为分隔符
3. 包含标题行
4. 日期时间格式：ISO 8601
5. 缺失值使用 "NA" 标记

示例：
```csv
timestamp,voltage,current,temperature,cycle_number
2024-01-15T10:30:00Z,3.7,1.2,25.3,1
2024-01-15T10:30:01Z,3.69,1.2,25.4,1
```

### 数值数据要求

1. 使用点号作为小数分隔符
2. 科学计数法使用 "e" 表示
3. 指定单位系统（优先使用 SI 单位）

## 元数据规范

metadata.json 必须包含：

```json
{
  "name": "数据集名称",
  "version": "版本号",
  "description": "简短描述",
  "source": {
    "institution": "机构名称",
    "authors": ["作者1", "作者2"],
    "publication": "相关论文引用",
    "url": "原始数据链接"
  },
  "license": "许可证类型",
  "data_specs": {
    "format": "文件格式",
    "size": "数据大小",
    "dimensions": {
      "samples": "样本数量",
      "features": "特征数量"
    }
  },
  "experimental_conditions": {
    "temperature_range": "温度范围",
    "current_range": "电流范围",
    "其他相关参数": "值"
  }
}
```

## 文档要求

README.md 必须包含：

1. 数据集概述
2. 数据收集方法
3. 数据结构说明
4. 特征说明
5. 使用示例
6. 引用格式
7. 许可证信息

## 数据质量标准

数据集必须：

1. 移除异常值或标注异常值
2. 说明数据清洗过程
3. 提供数据质量指标
4. 说明缺失值处理方法
5. 提供数据验证方法

## 许可证要求

支持的许可证类型：

1. CC BY 4.0
2. CC BY-SA 4.0
3. MIT
4. Apache 2.0
5. BSD

必须在以下位置明确标注许可证：

1. metadata.json
2. README.md
3. 数据文件头部（如果格式支持）

## 提交检查清单

提交数据集前请确认：

- [ ] 完整的文件夹结构
- [ ] 规范的 README.md
- [ ] 有效的 metadata.json
- [ ] 符合格式要求的数据文件
- [ ] 基本使用示例
- [ ] 许可证信息
- [ ] 引用信息

## 修订历史

| 版本 | 日期 | 修改说明 |
|------|------|----------|
| 1.0  | 2025-01-15 | 初始版本 |

## 联系方式

如有疑问，请通过以下方式联系：

1. 提交 Issue
2. 发送邮件至: your.email@example.com

---

本规范将根据社区反馈持续更新。
