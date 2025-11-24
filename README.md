# Japan Influenza Surveillance Dashboard

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![R](https://img.shields.io/badge/R-4.3.0+-blue.svg)
![Data](https://img.shields.io/badge/Data-MHLW_Japan-green.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)

A comprehensive real-time monitoring and analysis system for influenza outbreaks in Japan, based on official data from the Ministry of Health, Labour and Welfare (MHLW).

## 📊 Overview

This project provides automated analysis and visualization of Japan's influenza surveillance data, tracking epidemic patterns, school outbreaks, hospitalizations, and regional spread across all 47 prefectures.

### Key Features

- **Real-time Surveillance**: Weekly updates from MHLW official reports
- **Geospatial Analysis**: Interactive maps showing regional outbreak intensity
- **Epidemic Tracking**: Temporal trends and growth patterns
- **School Outbreak Monitoring**: Educational institution closures and student impact
- **Hospitalization Analytics**: Severe case tracking by age groups
- **Automated Reporting**: PDF data extraction and processing

## 🚀 Quick Start

### Installation

```r
# Install required packages
install.packages(c(
  "tidyverse", "lubridate", "sf", "rnaturalearth", 
  "ggrepel", "scales", "knitr"
))

# Clone repository
git clone https://github.com/your-username/japan-flu-surveillance.git
cd japan-flu-surveillance
