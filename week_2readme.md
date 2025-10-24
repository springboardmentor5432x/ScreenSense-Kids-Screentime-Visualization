# Indian Kids Screen Time Analysis - Data Cleaning

A comprehensive data cleaning and preprocessing project for analyzing screen time patterns and health impacts among Indian children.

## 📋 Overview

This project focuses on cleaning and preparing the Indian Kids Screen Time dataset for analysis. The notebook handles missing values, standardizes categorical data, and creates meaningful derived features for better insights into children's screen time habits and associated health impacts.

## 📊 Dataset Information

- **Total Records**: 9,712 children
- **Original Columns**: 8
- **Final Columns**: 16 (8 new features created)
- **Age Range**: Children, Pre-teens, and Teenagers

### Original Features
- Age
- Gender (Male/Female)
- Average Daily Screen Time (hours)
- Primary Device (Smartphone, TV, Laptop, Tablet)
- Exceeded Recommended Limit
- Educational to Recreational Ratio
- Health Impacts
- Urban or Rural location

## 🧹 Data Cleaning Process

### Missing Values
- **Health_Impacts**: 3,218 missing values (33.13%) filled with 'None'
- All other columns had no missing values

### Data Standardization
- **Gender**: Already clean (Male: 4,942, Female: 4,770)
- **Primary_Device**: Standardized device names
- **Health_Impacts**: Cleaned and standardized health impact categories

### New Features Created
1. **Age_Group**: Categorized into Children (≤10), Pre-teens (11-14), Teenagers (15+)
2. **Screen_Intensity**: Light, Moderate, Heavy, Extreme based on daily hours
3. **Health_Impacts_Clean**: Standardized health impact categories
4. **Binary Health Indicators**:
   - Has_Poor_Sleep: 4,868 cases (50.1%)
   - Has_Eye_Strain: 2,382 cases (24.5%)
   - Has_Anxiety: 1,605 cases (16.5%)
   - Has_Obesity_Risk: 1,217 cases (12.5%)
5. **Total_Health_Issues**: Count of health issues per child

## 📈 Key Statistics

### Screen Time Distribution
- **Heavy Users**: 4,596 children
- **Moderate Users**: 2,930 children
- **Extreme Users**: 1,354 children
- **Light Users**: 832 children

### Device Preferences
- **Smartphone**: 4,568 children (47%)
- **TV**: 2,487 children (26%)
- **Laptop**: 1,433 children (15%)
- **Tablet**: 1,224 children (13%)

## 🛠️ Requirements

pandas
numpy
matplotlib
seaborn

text

## 🚀 Getting Started

1. **Clone or download** the notebook file
2. **Install required libraries**:
pip install pandas numpy matplotlib seaborn

text
3. **Place your dataset** (`Indian_Kids_Screen_Time.csv`) in the same directory
4. **Run the notebook** in Google Colab or Jupyter

## 📁 Output Files

- **Clean_Screen_Time_Data_.csv**: Fully cleaned dataset ready for analysis

## 🔍 Data Quality

- **Missing Values**: 0 (all handled)
- **Data Consistency**: All categorical variables standardized
- **New Insights**: 8 additional features for comprehensive analysis

## 📝 Usage

The cleaned dataset is perfect for:
- Screen time pattern analysis
- Health impact correlation studies
- Device preference research
- Age group behavioral analysis
- Urban vs Rural comparisons

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements or additional cleaning features.

## 📄 License

This project is open source and available under the MIT License.