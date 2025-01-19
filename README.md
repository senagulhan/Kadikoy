# Kadıköy mahalle population based on age, gender analysis and population per year analysis.
![kadıkoy resım](https://github.com/user-attachments/assets/469e0bfa-e156-48bd-ace7-8f9b2c960f87)

In this project, population data of Kadıköy district is analyzed based on age, gender, and annual population trends. The data retrieved from the Kadıköy Open Data Portal provides insights into the demographic structure of the district. The analysis is supported by various visualizations, helping to better understand the population distribution in the area.

Purpose:

The purpose of this project is to analyze the population distribution of Kadıköy based on age and gender, and to examine the annual changes in population, enabling a deeper understanding of the district's demographic composition.

# Datasets
Datasets and images are used from KADIKÖY AÇIK VERİ PORTALI

Some of the data is stored as a dataset on the Kadıköy Open Data Portal, while some are stored as images, so I manually converted the images into a dataset.

0_14 age dataset: https://acikveri.kadikoy.bel.tr/dataset/0-14-yas-cocuk-nufusunun-mahallelere-gore-dagilimi

15_24 age image: https://acikveri.kadikoy.bel.tr/dataset/15-24-yas-nufusunun-mahallelere-gore-dagilimi-haritasi

25_64 age image: https://acikveri.kadikoy.bel.tr/dataset/25-64-yas-arasi-nufusun-mahallelere-gore-dagilimi-haritasi

64_and older age datset: https://acikveri.kadikoy.bel.tr/dataset/65-uzeri-nufusun-mahallelere-gore-dagilimi

Nüfus based on mahalle: https://acikveri.kadikoy.bel.tr/dataset/kadikoy-mahalle-nufuslari-2008-2022

Gender distribution based on mahalle: https://acikveri.kadikoy.bel.tr/dataset/mahalle-nufuslarinin-cinsiyete-gore-dagilimi

# Used Technologies

-Language: Python

-Libraries:

* Pandas

* NumPy

* Matplotlib

* PIL

* IPython

* Sklearn

# Key Findings and Analysis Results

### Total population distribution per age gap

Results:

Population between age 0 to 14 based on Kadıköy:
- 12.4%

Population between age 15 to 24 based on Kadıköy:
- 9.4%

Population between age 25 to 64 based on Kadıköy:
- 64.0%

Population between age 65 and older age based on Kadıköy:
- 14.1%

In the demographic analysis of Kadıköy, it is observed that the majority of the population (64.0%) falls within the 25-64 age range, indicating that this age group plays a dominant role in the district's demographic structure. Additionally, the population of children and young individuals (ages 0-24) collectively accounts for 21.8%, while the elderly population (65 years and older) constitutes 14.1%. These figures highlight that Kadıköy predominantly consists of adults and middle-aged individuals, with younger and older age groups representing smaller portions of the population.

![image](https://github.com/user-attachments/assets/1ad38f2e-06db-4a18-ba1f-923771669710)


### Mahalle population based on age between 25 to 64 (for example)


The pie chart illustrates the distribution of the population aged 25-64 across neighborhoods in Kadıköy, excluding the total value. It is evident that several neighborhoods, including  Zühtüpaşa, Koşuyolu, Hasanpaşa, Fikirtepe, Eğitim, Dumlupınar and Caferağa, share the highest proportion of 7.6%. Conversely, neighborhoods such as Acıbadem, Bostancı, Suadiye, Kozyatağı, Göztepe, and 19 Mayıs, exhibit lower proportions at 2.4%. This data suggests that the population in this age group is more evenly distributed in some neighborhoods, while it is notably smaller in others. Such variations may reflect differences in housing, amenities, or population density across these areas.


![image](https://github.com/user-attachments/assets/3d3feabb-0885-41cf-8279-6fd711b26a7c)


### Mahalle population change based on year between 2008 to 2022

In general, neighborhood populations have shown similar trends. Nearly all neighborhoods exhibited a decline between 2012 and 2015, followed by an increase between 2015 and 2019. These changes could be attributed to economic factors.

![image](https://github.com/user-attachments/assets/3ddba4ee-a80f-4b2f-bdd4-bd31a4c6f2bc)

### Gender distribution based on Mahalle

In Kadıköy, the female population generally exceeds the male population across most neighborhoods. The largest differences in favor of females are observed in neighborhoods such as Göztepe (5,039), Kozyatağı (4,319), and Erenköy (4,394). On the other hand, Fikirtepe is the only neighborhood where the male population (243 more) slightly surpasses the female population. This trend indicates a notable demographic tendency towards a higher female population in the region.

![image](https://github.com/user-attachments/assets/e67b4034-95ee-46eb-b569-7331d4816550)
