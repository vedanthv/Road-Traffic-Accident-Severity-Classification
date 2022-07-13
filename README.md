# Road Traffic Accident Severity Classification

![road_traffic](https://user-images.githubusercontent.com/44313631/178222800-9d70bd6a-665a-42ae-84a0-45e0ea25e40a.jpg)

## Problem Description

Every year the lives of approximately 1.3 million people are cut short as a result of a road traffic crash. Between 20 and 50 million more people suffer non-fatal injuries, with many incurring a disability as a result of their injury.

Road traffic injuries cause considerable economic losses to individuals, their families, and to nations as a whole. These losses arise from the cost of treatment as well as lost productivity for those killed or disabled by their injuries, and for family members who need to take time off work or school to care for the injured.

This data set is collected from Addis Ababa Sub-city police departments for master's research work. The data set has been prepared from manual records of road traffic accidents of the year 2017-20. 

All the sensitive information has been excluded during data encoding and finally it has 32 features and 12316 instances of the accident. Then it is preprocessed and for identification of major causes of the accident by analyzing it using different machine learning classification algorithms. 

## Quick  Overview of the Project

### Preliminary Data Alalysis

#### Key Observations: 

- There are 32 features in the dataset with 12,136 records. Here is the description of the major features.
- There are two numerical features `no_of_casulities` and `no_of_vehicles_involved`
- `defect_of_vehicle` and `Service_year_of_vehicle` has the highest number of missing values.
- On analyzing the box plots, none of the numerical features happen to have any significant outliers.

This dataset is a very interesting and challenging one because there are over **30 categorical features** with some of the features having more than 20 classes!

`accident_severity` is the target feature and has three classes
- `slight_injury`
- `serious_injury`
- `fatal_injury`
<br>

**Description of Important Features**
- time : time of the accident
- day_of_week : the day in which accident took place
- age_band_of_driver : the age bracket of the driver
- sex_of_driver : gender of the driver involved
- driving_experience : how experienced was the driver
- type of vehicle : what type of vehicle was involved
- owner of vehicle : who owned the vehicle?
- type_of_junction : what was the tpye of junction(Y-junction/T-Junction/U Turn/O-Junction)
- road_surface_type : what was the type of road(asphalt/gravel)

<hr>

### Exploratory Data Visualization and Analysis
<hr>

- Friday has the most number of accidents closely followed by Thursdays
- Most of the drivers are in the range of 18-30 and 31-50 years

### Data Pre Processing and Handling Missing Values
<hr>

### Feature Selection and Handling Imbalanced Dataset
<hr>
