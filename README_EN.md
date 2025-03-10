# Battery Dataset Collection

[![GitHub stars](https://img.shields.io/github/stars/tianwen1209/battery-dataset-collection)](https://github.com/tianwen1209/battery-dataset-collection/stargazers)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://makeapullrequest.com)

English | [中文](./README.md)

This repository contains a collection of publicly available battery datasets, aiming to facilitate battery research and the application of machine learning in the battery field. We have curated battery testing, performance, and aging data from research institutions worldwide to provide researchers and engineers with convenient data access.

## 🌟 Features

- Curated collection of public battery datasets
- Standardized dataset descriptions
- Detailed usage guides
- Continuously updated resources

## 📊 Dataset List

| Institution | Dataset Link | Battery Type | Experimental Conditions | Measured Data |
|------------|-------------|--------------|--------------------------|---------------|
| **NASA** | [Link](link) | - | - | - |
| **CALCE Battery Research Group** | [Link](CALCE) | - | - | - |
| **Sandia National Lab** | [Link](link)  | LFP, NCA, NMC (18650) | 15-35℃, Various C-Rates | Voltage, Current, Temperature, Energy |
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
| **UC Berkeley** | [Dryad Data](datadryad.org) | Sanyo 18650 LCO/graphite (2.6 Ah) | Fast charging protocols | Voltage, Current, Capacity |
| **Poznan University of Technology** | [Link](link)  | NMC 18650 (2.6 Ah) | Various temperatures & discharge depths | Voltage, Current, SOH data |
| **University of Oviedo** | [Link](link)  | LFP pouch cells | 23℃, C/25 cycles | Voltage, Current, Temperature |
| **University of Wisconsin-Madison** | [Link](link)  | Panasonic 18650PF (2.9 Ah) | 25℃ to -20℃, Driving cycles | Voltage, Current, EIS Tests |
| **McMaster University** | [Link](link) | LG Chem INR18650HG2 (3 Ah) | 40℃ to -20℃, Mixed driving cycles | Voltage, Current, Capacity |
| **USTC (University of Science and Technology of China)** | [ScienceDirect Dataset](ScienceDirect) | LFP Battery Pack (10 Ah) | Room Temperature, DST & UDDS | Voltage, Current |

## 📊 In-House Experimental Battery Datasets

| Experiment Name | Battery Type | Experimental Conditions | Measured Data |
|----------------|-------------|--------------------------|---------------|
| **[Porf. Xu Lab Experiment]** | [Battery Type] | [Experimental Conditions] | [Measured Data] |
| **[Porf. Yan Lab Experiment]** | [Battery Type] | [Experimental Conditions] | [Measured Data] |


### Notes
- Some datasets require proper citation when used in research.
- The experimental conditions and measured data vary between datasets.

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

1. Adding new datasets
2. Improving documentation
3. Reporting issues
4. Providing usage examples
5. Sharing dataset analysis experiences

Please refer to [Contribution Guidelines](docs/contribution.md) for detailed information.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

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

---

## 📅 Update Log

| Date | Version | Updates |
|------|---------|---------|
| 2025-01-15 | v1.0.0 | - Project initialization <br> - Added NASA and Oxford datasets |
| 2025-01-15 | v1.0.1 | - Improved project documentation <br> - Added English and Chinese support |
| 2025-01-16 | v1.0.2 | - Added dataset specification <br> - Added contribution guidelines |

We will continuously update and maintain this project, regularly adding new datasets and improving documentation. You can:
- Watch this repository to receive update notifications
- Star this repository to support us
- Fork this repository to contribute

If this project helps you, please give us a star ⭐️
