## Reproducible Hydrologic Analysis with USGS Data

This repository provides a comprehensive, two-part tutorial for processing and analyzing **USGS daily streamflow data** using Python. Designed for students, researchers, teachers/lecturers, hydrologists and data scientists, these workflows transition from individual site diagnostics to large-scale regional assessments.

## Interactive Tutorials
Open these directly in your browser. All libraries are pre-installed via the `usgs-env` engine. No setup required.

| Tutorial | Launch (Fast-Start) |
| :--- | :--- |
| **Part 1: Site-Level Analysis** | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cwslab/usgs-env/main?urlpath=git-pull?repo=https://github.com/cwslab/usgs_data%26branch=main%26targetpath=usgs_data%26urlpath=lab/tree/usgs_data/usgs_data_part1.ipynb) |
| **Part 2: Regional Scaling** | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cwslab/usgs-env/main?urlpath=git-pull?repo=https://github.com/cwslab/usgs_data%26branch=main%26targetpath=usgs_data%26urlpath=lab/tree/usgs_data/usgs_data_part2.ipynb) |

## Module Summaries

### Part 1: Single-Station Diagnostics
Learn the fundamentals of the USGS data ecosystem. This module covers:
* **Station Identification:** Criteria for selecting high-quality reference stations.
* **Data Acquisition:** Automated retrieval of multi-decadal discharge records.
* **Geospatial Context:** Delineating contributing watersheds.
* **Hydrologic Analytics:** Performing baseflow separation and calculating the **Baseflow Index (BFI)**.

### Part 2: Regional Scale Workflows
Scale your analysis from one station to hundreds. This module focuses on:
* **Data Screening:** Applying consistent quality filters across large datasets.
* **High-Throughput Retrieval:** Strategies for batched data API calls.
* **Comparative Diagnostics:** Visualizing and summarizing hydrologic behavior across different physiographic regions.

### Speed Tip for Users
> **Note:** These tutorials involve large datasets. To ensure the fastest performance in Colab, the notebooks are optimized to fetch data directly from the USGS via high-speed cloud backbones. If you are running these locally, ensure you have a stable high-speed internet connection for the initial data pull.
