# World Development Indicators Dashboard

[![PowerBI](https://img.shields.io/badge/PowerBI-F2C811?style=flat&logo=Power%20BI&logoColor=white)](https://powerbi.microsoft.com/)

An interactive business intelligence dashboard that analyzes sustainable development indicators across multiple countries with a focus on UN Sustainable Development Goals (SDGs).

## 📋 Overview

The World Development Indicators Dashboard provides comprehensive visualizations and analytics for monitoring progress towards Sustainable Development Goals. This tool enables policymakers, researchers, and development organizations to compare indicators across countries, identify trends, and make data-driven decisions.

> **Note:** This dashboard is designed to provide evidence-based insights for sustainable development planning and policy implementation.

## ✨ Features

### 🌍 Multi-dimensional SDG Analysis
Explore data across the first 5 SDGs:
- **SDG1:** Good Health and Well-being
- **SDG2:** Sustainable Agriculture and Food Security  
- **SDG3:** Affordable and Clean Energy
- **SDG4:** Clean Water and Sanitation
- **SDG5:** Taking Urgent Action to Combat Climate Change

### 🔍 Country Comparison
Compare development indicators between countries

### 📊 Interactive Visualizations
- Human Development Index (HDI) tracking
- Mortality and poverty rate analysis
- Agricultural production metrics
- Renewable energy consumption patterns
- Health expenditure breakdowns
- Water and sanitation access statistics
- Climate change and emissions data

### ⚙️ Advanced Functionality
- **Filtering Capabilities:** Select specific countries for detailed analysis
- **Multi-format Data Representation:** Bar charts, pie charts, maps, and statistical indicators
- **Cross-visual Filtering:** Filter other visualizations by clicking on specific data points

## 🛠️ Technical Stack

| Component | Technology | Purpose |
|-----------|------------|---------|
| **Frontend** | Power BI Dashboard | Interactive data visualization and user interface |
| **Data Processing** | Talend | Extract, Transform, Load (ETL) operations |
| **Database** | SQL Server/PostgreSQL | Structured data storage and management |
| **Analytics** | Data Mining Algorithms | Pattern recognition and predictive analytics |
| **Version Control** | Git | Source code and configuration management |

## 📚 Data Sources

This dashboard integrates data from multiple authoritative sources:

| Source | Description | Update Frequency |
|--------|-------------|------------------|
| World Bank Development Indicators | Comprehensive development data | Quarterly |
| UN Sustainable Development Goal Tracker | Official SDG metrics | Annually |
| WHO Health Statistics | Global health metrics | Bi-annually |
| FAO Agricultural Data | Agricultural production and land use | Annually |
| National Statistical Offices | Country-specific indicators | Varies by country |

> **Data Freshness:** Last data refresh - May 1, 2025

## 📈 Key Metrics

The dashboard tracks numerous critical development indicators:

### Human Development
- **HDI Rate:** Human Development Index (scale 0-1)
- **Poverty Index:** Population below poverty line (%)

### Health & Well-being (SDG1)
- **Mortality Rate:** Deaths per 1,000 population
- **Health Expenditures:** Per capita in USD
- **Health Workers:** Per 10,000 population
- **R&D Expenditures:** % of GDP

### Agriculture & Food Security (SDG2)
- **Agricultural Production:** In thousands of metric tons
- **Pesticides Use:** Kg per hectare
- **Agricultural Land:** Hectares per capita
- **Agricultural Employment:** % of total employment

### Energy Access (SDG3)
- **Renewable Energy Consumption:** % of total final energy consumption  
- **Renewable Electricity Output:** % of total electricity output
- **Net Energy Imports:** % of energy use
- **Clean Fuels Access:** % of population

### Water & Sanitation (SDG4)
- **Freshwater Withdrawals:** Billion cubic meters annually
- **Basic Drinking Water Access:** % of population
- **Safely Managed Sanitation:** % of population

### Climate Action (SDG5)
- **PM2.5 Air Pollution:** Mean annual exposure (μg/m³)
- **Greenhouse Emissions:** CO₂ equivalent thousand metric tons
- **Disaster Risk Reduction:** Progress score (1-5 scale)

## 🚀 Installation & Setup

### Prerequisites
- Power BI Desktop (latest version recommended)
- Database access credentials (if connecting to live data)
- Minimum 8GB RAM recommended for optimal performance

### For Power BI Desktop Users
```bash
# Clone the repository
git clone https://github.com/yourusername/world-development-indicators.git

# Navigate to the project directory
cd world-development-indicators
```

1. Open the `.pbix` file with Power BI Desktop
2. Navigate to "Transform Data" > "Data source settings" to update credentials
3. Click "Refresh" to update all data sources

### For Power BI Service (Cloud) Users
1. Access the published dashboard via the shared link: [Dashboard Link](https://app.powerbi.com/dashboard-link)
2. Ensure you have appropriate permissions (Viewer role minimum)
3. Use filtering capabilities to customize your view
4. Set up automatic refresh schedules if needed

## 📖 Usage Guide

### Basic Navigation
1. **Country Selection**: Use the dropdown menu to select specific countries
   ```
   Location: Top-left of each dashboard page
   ```

2. **SDG Navigation**: Use tabs to switch between SDG focus areas
   ```
   Location: Top navigation bar
   ```

3. **Data Exploration**: Click on visual elements to filter other visuals on the page
   ```
   Tip: Notice how selection in one chart affects other visualizations
   ```

4. **Detailed Analysis**: Hover over charts for tooltips with additional statistics
   ```
   Tip: Right-click on visuals for additional options
   ```

### Advanced Features
- **Exporting Data**: Right-click on any visual and select "Export data"
- **Full Screen Mode**: Click the "Focus mode" icon on any visual
- **Creating Bookmarks**: Use the Bookmarks pane to save specific views

### Sample Queries

| Question | How to Answer |
|----------|---------------|
| "Compare HDI between Niger and Switzerland" | Select both countries and view the HDI rate chart |
| "Which country has the highest renewable energy consumption?" | Navigate to SDG3 tab and check the renewable energy chart |
| "What's the agricultural production breakdown?" | Go to SDG2 tab and review the production by product chart |

## 📬 Contact

Zeineb Eya Rahmani

[![Email](https://img.shields.io/badge/Email-zeineb.eya.rahmani%40outlook.com-blue?style=flat-square&logo=microsoft-outlook)](mailto:zeineb.eya.rahmani@outlook.com)
[![GitHub](https://img.shields.io/badge/GitHub-zeineb--eya-181717?style=flat-square&logo=github)](https://github.com/zeineb-eya/)

---

<div align="center">
  <sub>Created with ❤️ by Zeineb Eya Rahmani</sub>
</div>
