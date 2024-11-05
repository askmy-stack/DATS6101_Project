L.A. Crime Scene Investigation: Data-Driven Detectives

# Research Topic: - 
The city of Los Angeles faces ongoing challenges in understanding and addressing the complexity of crime across its diverse neighborhoods. With thousands of recorded incidents varying by crime type, victim demographics, location, and modus operandi, law enforcement and city officials require deeper insights into the patterns and factors driving crime in specific areas.

The dataset includes detailed information on reported crimes such as crime codes, descriptions, victim age, sex, and descent, as well as crime locations, types of weapons used, and case statuses. However, identifying meaningful trends and correlations—such as how crime types vary by location, how victim demographics relate to specific crimes, and how different weapons are used in different crimes—remains a critical challenge.
Focus on Crime Analysis in Los Angeles from 2020 to present using a dataset containing detailed information on crime incidents.

# SMART Question: - 
1) How have theft, robbery, and homicide rates in Los Angeles changed from 2020 to the present, and which of these categories shows the highest overall density of crime during this time?
2) How does the type or frequency of crimes in Los Angeles vary by victim descent, and are there significant geographic patterns (based on latitude and longitude) associated with specific victim groups?
3) How do crime rates fluctuate during the holiday season, particularly in November and December, and what types of crimes predominantly occur during these months? Additionally, how have these patterns evolved over the years?
4) How have the top three most common crimes from 2020 to the present been distributed across the top five areas where they are most frequently committed in Los Angeles, and are these trends increasing or decreasing in each area from 2020 to 2024?
5) Which crimes in Los Angeles exhibited the highest weapon usage, and which ethnicities and genders showed the most significant weapon involvement over the last five years?

# Understanding the Dataset: Key Details and Insights

This dataset, obtained from the official data.gov website, details crime incidents in the City of Los Angeles from January 1, 2020, to October 31, 2024. It is a real-time dataset that receives updates every two weeks and consists of 28 columns and 986,501 rows. Key Components of the dataset include: 
   1.	Geographic Areas: The LAPD is divided into 21 community police stations, referred to as Geographic Areas, each            with a unique identifier and name based on local landmarks.
   2.	Crime Information/ Codes: Each incident includes multiple crime codes (up to four), indicating the type of crime              committed and additional crimes committed.
   3.	Crime Descriptions: Corresponding descriptions for each crime code are provided for clarity.
   4.	Incident Details:
        Dates: The dataset records both the occurrence date and the reporting date of each crime.
        Case Number: Each incident is assigned a unique Division of Records Number (DR_NO).
        Location Data: Each incident includes the approximate location (latitude and longitude), cross streets, and a           rounded address for anonymity.
   5.	Victim Information:
        Age: Numeric representation of the victim's age.
        Descent: Coded descriptions of the victim's descent.
        Sex: Information indicating the victim's gender.
   6.	Weapon Information: Details on the weapon used in the crime, including a description and corresponding code.
   7.	Status: Each incident is classified with a status code to indicate the case's current standing.

# Limitations of the dataset

The data is originally transcribed from paper crime reports, which may introduce some inaccuracies. Additionally, address fields are rounded to the nearest hundred block to maintain privacy. There are also a significant number of null values, especially in columns related to weapon names and descriptions, which will need to be addressed. Furthermore, including the reporting mechanisms in the dataset for each crime incident could facilitate more detailed analyses regarding geographical variations and resource allocation in those areas.

The group members in the project are: -
1. Kamineni Abhinaysai
2. Lasya Ragvendra
3. Neeraj Magadum
4. Aakash Hariharan
5. Amogh Ramagiri
