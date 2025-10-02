# ❄️ Arctic25 Dataset

### Comprehensive Pan-Arctic Permafrost & Climate Observations (2005-2021)

[![Data Points](https://img.shields.io/badge/Observations-2.9M+-brightgreen.svg)](https://github.com/sparcus-technologies/Arctic25)
[![Locations](https://img.shields.io/badge/Locations-171K+-orange.svg)](https://github.com/sparcus-technologies/Arctic25)
[![Years](https://img.shields.io/badge/Years-2005--2021-red.svg)](https://github.com/sparcus-technologies/Arctic25)

---

## 🌍 Overview

**Arctic25** is the largest open permafrost-climate dataset for Arctic Russia, containing **2,917,285 observations** across **171,605 unique locations** spanning **17 years** (2005-2021). This dataset enables machine learning research on permafrost dynamics, infrastructure risk assessment, and climate change impacts in one of Earth's most rapidly warming regions.

## 📊 Dataset Statistics

| Metric | Value |
|--------|-------|
| **Total Observations** | 2,917,285 |
| **Unique Locations** | 171,605 |
| **Temporal Coverage** | 2005-2021 (17 years) |
| **Geographic Coverage** | Arctic Russia (59-82°N) |
| **Features** | 38 climate & permafrost variables |

## 🔬 Features

### Core Climate Variables
- 🌡️ **Temperature**: 2m air temperature (mean, trends, lags)
- 🌧️ **Precipitation**: Total corrected precipitation
- ☀️ **Radiation**: Shortwave downward (all-sky & clear-sky)
- 💨 **Wind**: Wind speed at 2m and 10m heights
- 💧 **Humidity**: Relative humidity, specific humidity, dewpoint
- 🌀 **Pressure**: Surface pressure

### Permafrost Indicators
- ❄️ **Permafrost Fraction** (PFR): Primary target variable (0-100%)
- 🌡️ **Thermal Proxies**: Thawing/freezing degree days
- 📈 **Trends**: Location-specific temporal trends
- ⏱️ **Lags**: 1-year and 2-year temporal lags

### Engineered Features
- 🎯 **Threshold Indicators**: Above-freezing, risk temperature zones
- ⚡ **Energy Balance**: Shortwave energy, wind shear proxies
- 📊 **Spatial**: Normalized lat/lon coordinates
- ⏳ **Temporal**: Years since start, change metrics

## 📥 Download & Usage

```bash
# Clone repository
git clone https://github.com/sparcus-technologies/Arctic25.git
```

## 📧 Contact
Author: Boris Kriuk
Email: bkriuk@connect.ust.hk
Research: [Boris Kriuk Labs]
