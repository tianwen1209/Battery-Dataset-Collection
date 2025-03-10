# Battery Dataset Collection

[![GitHub stars](https://img.shields.io/github/stars/tianwen1209/battery-dataset-collection)](https://github.com/tianwen1209/battery-dataset-collection/stargazers)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://makeapullrequest.com)

English | [中文](./README.md)

This repository contains a collection of publicly available battery datasets, aiming to facilitate battery research and the application of machine learning in the battery field. We have curated battery testing, performance, and aging data from research institutions worldwide to provide researchers and engineers with convenient data access.

## 🌟 Features

- 🔍 Curated collection of public battery datasets
- 📂 Standardized dataset descriptions
- 📘 Detailed usage guides
- 🔄 Continuously updated resources

## 📊 Open-Source Battery Datasets

| Institution | Dataset Link | Battery Type | Experimental Conditions | Measured Data |
|------------|-------------|--------------|--------------------------|---------------|
| **NASA** | [Link](link) | - | - | - |
| **CALCE Battery Research Group** | [Link](CALCE) | - | - | - |
| **Sandia National Lab** | [Link](battery dataset) | LFP, NCA, NMC (18650) | 15-35℃, Various C-Rates | Voltage, Current, Temperature, Energy |
| **Oxford Battery Intelligence Lab** | [Link](link) | Lithium-ion pouch cells | 40℃, Artemis driving cycle | Voltage, Temperature, Discharge Capacity |
| **Nature Communications Open Data** | [Link](link) | - | - | - |
| **Hawaiian Natural Energy Institute** | [Link](link) | - | - | - |
| **Automotive Lithium-ion Battery Dataset** | [Link](link) | - | - | - |
| **MIT-Stanford-Toyota Research Center** | [Link](link) | LFP/graphite (124 & 233 cells) | Fast charging degradation study | Voltage, Current, Capacity, Temperature |
| **RWTH Aachen University** | [Link](link) | Samsung 18650 NCA/carbon+Si | 25℃, Drive cycle aging | Voltage, Power, Temperature, SOC Tests |
| **Battery Archive** | [Link](link) | - | - | - |
| **Beijing Institute of Technology** | [Link](link) | - | - | - |
| **Cambridge University (Nature Communications Dataset)** | [Link](link) | - | - | - |
| **Xi'an Jiaotong University** | [XJTU Battery Dataset](wang-fujin.github.io/) | NMC/graphite (27 Ah pouch cells) | 40℃, CC-CV charge/discharge | Voltage, Temperature, Capacity, Energy |
| **Tongji University** | [Zenodo Dataset](https://zenodo.org/record/6379165) | - | - | - |
| **EV Large-Scale Li-ion Battery Dataset** | [Link](ivstskl.changan.com.cn/?p=2697) | - | - | - |
| **Toyota Research Institute** | [Experimental Data Platform](data.matr.io/1/) | LFP/graphite (124 & 233 cells) | Fast charge degradation study | Voltage, Current, Capacity, Temperature |
| **EVERLASTING Project** | [4TU.ResearchData](4tu.nl) | 18650, 3.5 Ah | 0-45℃, Various C-Rates | Voltage, Current, Capacity |
| **KIT (Karlsruhe Institute of Technology)** | [KIT Dataset](kit.edu) | NMC (40Ah) | Room Temperature | Voltage, Temperature, Current |
| **UCL (University College London)** | [Dataset](https://dx.doi.org/10.5522/04/12159462.v1) | NCA INR18650 MJ1 (3.5 Ah) | 24℃, 400 Cycles | Voltage, Temperature, Capacity |

## 📊 In-House Experimental Battery Datasets

| Experiment Name | Battery Type | Experimental Conditions | Measured Data |
|----------------|-------------|--------------------------|---------------|
| **Prof. Xu Lab Experiment** | [Battery Type](link) | [Experimental Conditions] | [Measured Data](link) |
| **Prof. Yan Lab Experiment** | [Battery Type](link) | [Experimental Conditions] | [Measured Data](link) |

## 🚀 Usage

1. Clone the repository:
```bash
git clone https://github.com/tianwen1209/battery-dataset-collection.git
cd battery-dataset-collection
```

2. Browse dataset information:
- Visit [Project Website](https://tianwen1209.github.io/battery-dataset-collection)
- Check detailed documentation in the `datasets` directory

## 📂 Repository Structure
```
battery-dataset-collection/
├── README.md              # Chinese README
├── README_EN.md          # English README
├── LICENSE               # MIT License
├── datasets/             # Dataset description files
│   ├── nasa/            # NASA dataset files
│   └── oxford/          # Oxford dataset files
└── docs/                # Detailed documentation
    ├── contribution.md  # Contribution guidelines
    └── dataset_spec.md  # Dataset specifications
```

## 🤝 How to Contribute

We welcome all forms of contributions, including but not limited to:
- Adding new datasets
- Improving documentation
- Reporting issues
- Providing usage examples
- Sharing dataset analysis experiences

Refer to [Contribution Guidelines](docs/contribution.md) for more details.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌟 Acknowledgments

Thanks to all researchers and institutions who contributed to this project. Special thanks to:
- NASA Ames Research Center
- Oxford University
- All dataset contributors

## 📮 Contact

- Submit Issues: [GitHub Issues](https://github.com/tianwen1209/battery-dataset-collection/issues)
- Email: zhutianwen129@sina.com

## 🔗 Related Links

- [Project Website](https://tianwen1209.github.io/battery-dataset-collection)
- [Dataset Usage Examples](./examples)
- [FAQ](./docs/FAQ.md)
