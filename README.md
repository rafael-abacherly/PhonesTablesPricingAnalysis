# Phones and Tables Pricing Analysis

[Kaggle](https://www.kaggle.com/datasets/ahsan81/used-handheld-device-data)

### Context
The used and refurbished device market has grown considerably over the past decade as it provide cost-effective alternatives to both consumers and businesses that are looking to save money when purchasing one. Maximizing the longevity of devices through second-hand trade also reduces their environmental impact and helps in recycling and reducing waste. Here is a sample dataset of normalized used and new pricing data of refurbished / used devices.

### Objective
The objective is to do Exploratory Data Analytics and apply Linear Regression to create a model which can help in pricing of such devices.

### Metadata
- **device_brand:** Name of manufacturing brand
- **os:** OS on which the device runs
- **screen_size:** Size of the screen in cm
- **4g:** Whether 4G is available or not
- **5g:** Whether 5G is available or not
- **front_camera_mp:** Resolution of the rear camera in megapixels
- **back_camera_mp:** Resolution of the front camera in megapixels
- **internal_memory:** Amount of internal memory (ROM) in GB
- **ram:** Amount of RAM in GB
- **battery:** Energy capacity of the device battery in mAh
- **weight:** Weight of the device in grams
- **release_year:** Year when the device model was released
- **days_used:** Number of days the used/refurbished device has been used
- **normalized_new_price:** Normalized price of a new device of the same model
- **normalized_used_price (TARGET):** Normalized price of the used/refurbished device

### Analysis

1) **Device Brand Distribution**<br>
    1.1. OS Analysis for *"Others"* Devices Brand
2) **OS Distribution**
3) **4G Distribution**<br>
    3.1. Release Year for Devices Without 4G
4) **5G Distribution**
5) **Cellular Network Technology vs. Pricing**
6) **Pearson's Correlation Coefficient Analysis**

### Linear Regression

1) **Test 01**: Using All Variables
2) **Test 02**: Removing Some Variables
3) **Test 03**: Using Only the Release Price Variable