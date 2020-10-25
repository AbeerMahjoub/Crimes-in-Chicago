# Chicago Crimes 
## by Moahmed Desouky

## Introduction
In this project I will **Explore**, **analyze** and **visualize** the dataset to find some relationships and answers about crimes in Chicago.

This project has **two notebooks** that needed to perform the compelete data analysis process. 

In the **first notebook**, we will start with **Data Wrangling** techniques, e.g. `Gather`, `Assess` and `Clean` the dataset. 

While, in the **second notebook**, we will use Python visualization libraries to systematically `explore` a selected dataset, starting from plots of single variables and building up to plots of multiple variables, then `communicate` the interesting properties, trends, and relationships that we discovered through aesthetic and polished visuals.

## Dataset
Crime analysis has become one of the most important topics in the field of data science, since the availability of crime data sets, in addition to the need of analyzing the reasons of those crime activities and the prediction of future crimes, according to the past criminal records. A lot of online crime datasets are available nowadays, like the `city of Atlanta Crime 2009-2017` dataset, `city of Baltimore Crime 2011-2016 dataset` and many other datasets that can be found [here](https://data.world/datasets/crime).

But in this project we are going to work on the [**Crimes in Chicago Dataset**](https://www.kaggle.com/currie32/crimes-in-chicago).

After data wrangling proccess, I have splitted the data into **5 datasites** for easy access, and they are `crimes`, `locations`, `dates`, `coordinates` and `top_danger_locs` datasets.

## Notes
- In order to run the project, first download the [**Chicago Crime Dataset**](https://www.kaggle.com/currie32/crimes-in-chicago), then put it in `Data` folder.
- The notebooks order as follow:
    1. **01_Wrangling.ipynb**
    2. **02_Analyzing.ipynb**
    3. **03_Slideshow.ipynb**

## Summary of Findings
1. I found that `Theft`, `Battery` and `Criminal Damage` are the top crimes in **Chicago**.
2. **Theft crimes** are active in `streets` and `parking garages`, **Narcotic crimes** are active in `sidewalks` and `alleys`, while **Battery crimes** are active in `schools`, `public buildings`, `residences` and `apartments`.
3. `Battery crimes` are the most common crimes related to **Domestic Violence**.
4. We found a `decrease` in **police performance** from `2014` to `2016` despite a `decrease` in the **total number of crimes** in those years.
5. `July` and `August` (summer months) are the **most** common months for crime while `February` and `March` are the **least**. On the other hand, `Saturday` and `Sunday` (weekends) are the **least** common days for crimes.
6. Crimes are **centred** in Chicago in the `east` while it's **moderate** in the `south` and **less** in the `north`. There are at least `1,000` crime for each location with only 1 or 2 locations that exceeding `10,000` crimes.


## Key Insights for Presentation
- 2001 data has a few records compared to the rest years, in addition `January`, `February` and `March` data is missing too. So in order to build a valid time **series analysis** we need to drop this year.
- 2017 has only 30 records in `January`, so, without much words let's drop it too.

## Resources
The resources I have used in this project:
- [Crime Datasets](https://data.world/datasets/crime)
- [Chicago Crime Dataset](https://www.kaggle.com/currie32/crimes-in-chicago)
