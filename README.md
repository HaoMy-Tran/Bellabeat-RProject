# Bellabeat project: How can a wellness company play it smart?

(The result file was saved in PDF and HTML file, please download the one which is more convenient to read) <br />
This project is completed under the umbrella of Google Data Analytics Professtional Certificate. 
As a newbie in data analysis field, it took me a certain amount of time to get familiar with the data analysis process and the use programming languages (which is R in this project). By trials and errors, at some senses, this project was finally completed. However, this is not comprehensive and it needs to be developed.

In this case study, I will perform data analysis for Bellabeat, a high-tech manufacturer of health-focused products for women. I will analyze smart device data to gain insight into how consumers are using their smart devices. My analysis will help guide future marketing strategies for Bellabeat's team. 
## Key findings
After analyzing the Fitbit dataset, I have discovered the general insights towards the use of smart device of Fitbit's customers:<br />
* We  expect that people who use the smart devices partially have concerned about their health. And they have, through inspecting their own health ratios. However, from the data analysis, haft of them, on average in a month, had not had enough time for activities per day. When it comes to sleeping, the significant portion of the valid users (whose information recorded is greater than 14 days) sleep for at least 7 hours a day on average, which means there is a small number of customers did not sleep enough.
* The customers prefer running/walking as a way to travel than using by bikes, cars, or other vehicles.

From these key findings, I suggest some act-calling which are: <br /> 
* The high relation between Total Steps and Total Distance can help the marketing know more about the users of smart devices. This finding leads to a new opportunity of a customer segment. They should focus on the customer that usually travel by foot or other ones who often run or jog. <br /> 
* Also, the people who are supposed to be live in a healthy way actually have some problems with the total time for physical activities and sleeping. The team backing for Bellabeat app should pay their effort on solving these problems for the future users.<br />
* Finally, more research should be taken further to explore more knowledge of this data and the answer the questions around the high degree of relation between levels of minute and distance, between total time asleep and total time in bed. 

## Limitations

Due to as narrow focuses a case study has limited representatives and generalization is impossible. <br />
Due to narrow study the discrimination & bias can occurs.<br />
The number of valid observations (people who commit long enough for a meaningful conclusion) is not enough, which can lead skewed results.

## Installation
``` 
install.packages('tidyverse')
install.packages('reshape2')
```
### Usage
```
library(reshape2)
library(tidyverse)
library(lubridate)
```

## Liscence
This Kaggle data set contains personal fitness tracker from thirty fitbit users. Thirty eligible Fitbit users consented to the submission of personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. It includesinformation about daily activity, steps, and heart rate that can be used to explore users’ habits. Please find further information at [here](https://www.kaggle.com/datasets/arashnic/fitbit)
