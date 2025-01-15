# Dataset Specification

English | [中文](./dataset_spec.md)

This document specifies the standards and requirements for submitting datasets to this project. Following these specifications ensures consistency and usability of the datasets.

## Table of Contents

- [Basic Requirements](#basic-requirements)
- [File Organization](#file-organization)
- [Data Format](#data-format)
- [Metadata Specification](#metadata-specification)
- [Documentation Requirements](#documentation-requirements)
- [Data Quality Standards](#data-quality-standards)
- [License Requirements](#license-requirements)

## Basic Requirements

Each dataset must:

1. Have a clear open-source license
2. Provide complete citation information
3. Include detailed data description
4. Provide basic usage examples
5. Explain data collection methods and experimental conditions

## File Organization

Dataset folder structure should follow:

```
datasets/
└── dataset_name/
    ├── README.md           # Dataset documentation
    ├── metadata.json       # Metadata file
    ├── data/               # Data files directory
    │   ├── raw/           # Raw data
    │   └── processed/     # Processed data (if any)
    ├── examples/           # Usage examples
    └── docs/              # Supplementary documentation
```

## Data Format

### Supported File Formats

- CSV (preferred format)
- HDF5
- MAT
- Excel (xlsx)
- JSON

### CSV File Requirements

1. Use UTF-8 encoding
2. Use comma as delimiter
3. Include header row
4. Date-time format: ISO 8601
5. Mark missing values as "NA"

Example:
```csv
timestamp,voltage,current,temperature,cycle_number
2024-01-15T10:30:00Z,3.7,1.2,25.3,1
2024-01-15T10:30:01Z,3.69,1.2,25.4,1
```

### Numerical Data Requirements

1. Use period as decimal separator
2. Use "e" for scientific notation
3. Specify unit system (SI units preferred)

## Metadata Specification

metadata.json must include:

```json
{
  "name": "Dataset Name",
  "version": "Version Number",
  "description": "Brief Description",
  "source": {
    "institution": "Institution Name",
    "authors": ["Author1", "Author2"],
    "publication": "Related Paper Citation",
    "url": "Original Data Link"
  },
  "license": "License Type",
  "data_specs": {
    "format": "File Format",
    "size": "Data Size",
    "dimensions": {
      "samples": "Number of Samples",
      "features": "Number of Features"
    }
  },
  "experimental_conditions": {
    "temperature_range": "Temperature Range",
    "current_range": "Current Range",
    "other_parameters": "Values"
  }
}
```

## Documentation Requirements

README.md must include:

1. Dataset overview
2. Data collection method
3. Data structure explanation
4. Feature description
5. Usage examples
6. Citation format
7. License information

## Data Quality Standards

Datasets must:

1. Remove or mark outliers
2. Document data cleaning process
3. Provide data quality metrics
4. Explain missing value handling
5. Provide data validation methods

## License Requirements

Supported license types:

1. CC BY 4.0
2. CC BY-SA 4.0
3. MIT
4. Apache 2.0
5. BSD

License must be clearly stated in:

1. metadata.json
2. README.md
3. Data file headers (if format supports)

## Submission Checklist

Before submitting a dataset, confirm:

- [ ] Complete folder structure
- [ ] Standardized README.md
- [ ] Valid metadata.json
- [ ] Data files meeting format requirements
- [ ] Basic usage examples
- [ ] License information
- [ ] Citation information

## Revision History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | 2025-01-15 | Initial version |

## Contact

For questions, please contact:

1. Submit an Issue
2. Email: your.email@example.com

---

This specification will be updated based on community feedback.
