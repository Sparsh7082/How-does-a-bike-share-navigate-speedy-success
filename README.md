Case study: How does a bike-share navigate speedy success?
---
author: **Sparsh Gupta**

date: *2024-05-16*


<p align="center">
  <img src="https://lh3.googleusercontent.com/pw/AP1GczNohHQvj9irPIjBP_4r4LFOnTQaVRk-IXfocWlm69oYKcdh4rQZ1nSLRb9KtGXCNwC4krwae0Xv7dbkOaRQDrcyxOP7xtDZ3qnKqxOT1zzgkp-9a0ZjUhkK00LCLSHIeTrHs8gsq37RBEBVXVmUghgSXaGUaNLpTNv3CpLzRThMrgL224Rb2oHyMdQi2PLsaIO1LkOfeaB-eNzqPtyUU8pgZGd6dy4cJN-u-gdnnwt2H7Oo7vb9vocsf5b_xHd0Da-RbYCLNSNoJPSRhzbBpVL1muF9BML8lACAgYYLqLoGx9-CT5MyYB1yredj_Q3P-JUJp9Eo7IheCxHaeGQZTPuunBzk445AefeVEsMpRiE-q_KCxgdCrSaj_OMungYMWy9kVaL8dIU8IdqfuyHzqDDvuv_rqu0_XBzHOe5XtX0KXCf_SDEdxMHtl-mrdnT3MImbp-4O5YFa6PukUk-OONjlrWImuejKg_0UEq3XfOb10vt6ViAjpsv4PA4fO79DlEs3eEaMNDm0aMKvPXKzxyF7HatS8g5sy00hY5QRZgmZQMGyin_KX0qHOIlwKvx6GZ8HDfK2Bh1SJIK3LkFVWPFV5KTSITPPnqHYhrNrs7Sc3yBDNTy_gml9JYXv75mTfgwtNoSkvArickmtKAQSjDRYbrkR0tyzkUISM3M3Y7FEAHS4pBzGWfDi23rhWXye11nhF4-VNL-9ndW9goxTIoDbKis6i2UPj920K_J9mXR4XHG6W-wjYrCh-PDyeZ3thX6MJV95b7FIbZY-cAzX_AN2sya-xyoKyFvdu8S_j0G2qG5TNmSZTzRnBrJoF9nljy_aC4msPAz98PYJ0gKBkehFrK56BdVWL-7tIeS7wGL-E7zFVKrMNfAhnX05p78biKOjTpFO9lB6UTh2Rhv6FCw2VuHgMLAGSJ0I551KmXCJFajTh0F8uXRkdTtIKw=w387-h387-s-no-gm?authuser=0"/>
</p>

# Table of content
- [Introduction](#introduction)
- [Scenario](#scenario)
- [About the company](#about-the-company)
- [Ask](#ask)
- [Prepare](#prepare)
- [Process](#process)
- [Analyze](#analyze)
- [Share](#share)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)

# Introduction

Welcome to the Cyclistic bike-share analysis case study! In this case study, I work for a fictional company, Cyclistic, along with some key team members. In this case study, I will follow the steps of the data analysis process— **Ask**, **Prepare**, **Process**, **Analyze**, **Share**, and **Act** —to answer the business questions.

# Scenario

I am a junior data analyst working on the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, my team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, my team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must approve my recommendations; hence, they need to be supported by compelling data insights and professional visualizations.

# About the company

In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime.

Until now, Cyclistic’s marketing strategy has relied on building general awareness and appealing to broad consumer segments. One approach that helped make these things possible was the flexibility of its pricing plans: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members.

Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. Although the pricing flexibility helps Cyclistic attract more customers, Moreno believes that maximizing the number of annual members will be key to future growth. Rather than creating a marketing campaign that targets all-new customers, Moreno believes there is a solid opportunity to convert casual riders into members. She noted that casual riders are already aware of the Cyclistic program and have chosen Cyclistic for their mobility needs.

Moreno has set a clear goal: Design marketing strategies aimed at converting casual riders into annual members. In order to do that, however, the team needs to better understand how annual members and casual riders differ, why casual riders would buy a membership, and how digital media could affect their marketing tactics. Moreno and her team are interested in analyzing the Cyclistic historical bike trip data to identify trends.


### Using the steps of the data analysis process to solve this case study.
<p align="center">
  <img src="https://lh3.googleusercontent.com/pw/AP1GczOz05UzQcamB3mwFzOwBUFSCmsL1aBVjgdNlMkUPfr782gGkpDLd_2NG3KZUtY7gZh7MIrfXUdOfsY3aqTW2TlzmP8xL4EQ2VWWs-pY5ISALFx9Pu393IsAL8MqJ1NigOvUegV3JLr6dPseyCkMxGGpbnnfs4NCDJ9-T3eGbJgfhsnw4ZUxRfMBD_O5ZvQP4ihSXS86sOQ_RLUbGRBzSpVo1q44ZKK-FKOxjBsW4uiiAbW3xO6GuP6J9D7-P70Xpe3ny6OY2bS2EsVm53vBoQV1X7SptGFag_4gpjkiFDXikAp06DeFFpMFbxYc-LPdXX9Z22X1BsylwNRRelBUPcA0tfjIGWqT-xmqmuiMrgYJKiU4AYkjhA8S_C96G6ujRl_5AwTi78R84AXub0mBCazFr0YnaC1_N-XJkRj6z6pxpfTT985cKd0Sh5jT6C7XjkQAhSLAEeYM9nQ5IDs3V5iG5xAgA3RqpQLgNOyztqeyV6bLo5cE1K4QdmpcItUXXVBp_G_WY64JOxriADM1TynKnxymZRPVkgBX1QlVuQMDDwGCmL0xstnFnd8RuUeI8Bf2oUL-EVSKG0UZgFJ-yisJjjobRRsQNwMfQTnoZhKt4MbUbID8RvBsLVqZc-RXfZtF8MFoz5vykQcu_3F7sPFNHD9mSOmz2BXol5Je9AeGdgDt1xyvmF4YaHnfYKOHArYCzZJQjZbvN05WTwVgg8-ol9sxVwGY67b8ZqgHinHlysKtzhmIbmK3YXChdAKdx1zQXHc5lmJisZ8k49usY0ftO9HAWW1kmzrwYLOOASfygrLfwCpxPA2OAF05ypv3ajz68IZFT0yHS5TwUAtjR_t9EY6fYyH9hxLnm0ESwAcmITNDlYRbLi6PADL2Ry4Z_1VSUnNclhn8to5eGu7_7OgQop746kQHAN45doDlvrspGTiVx0_MebGqqdegjFU=w1400-h520-s-no-gm?authuser=0"/>
</p>

## Ask

The **three business questions** that need to be answered:

1. How do annual members and casual riders use Cyclistic bikes differently?

2. Why would casual riders buy Cyclistic annual memberships?

3. How can Cyclistic use digital media to influence casual riders to become members?

**My Stakeholders-**

1. Lily Moreno (Director of marketing and my manager)

2. Cyclistic marketing analytics team

3. Cyclistic executive team

**Stakeholders Expectations-** Design marketing strategies aimed at converting casual riders into annual members. In order to do that, however, the team needs to better understand how annual members and casual riders differ, why casual riders would buy a membership, and how digital media could affect their marketing tactics.

## Prepare

**Note:** For this case study, I will use the public dataset which is located [**here**](https://divvy-tripdata.s3.amazonaws.com/index.html). The data has been made available by Motivate International Inc. under this [**license**](https://www.divvybikes.com/data-license-agreement).

### Checking whether the data is good or bad with the help of ROCCC Analysis.

**Reliable** -> The data is accurate, complete & unbiased

**Original** -> The data is discovered through 3^rd^ party source (which is public data)

**Comprehensive** -> The data contains all the critical information which is needed to answer the questions.

**Current** -> In this case study, the current data is used which is from **May, 2023** to **April, 2024**. The source of this data updates the data every month.

**Cited** -> Yes, the data is cited and vetted public data set.

### Installing & Loading necessary packages for preparing this good dataset

```{r installing packages}
install.packages("tidyverse", repos = "http://cran.us.r-project.org")
install.packages("ggplot2", repos = "http://cran.us.r-project.org")
install.packages("tidyr", repos = "http://cran.us.r-project.org")
install.packages("dplyr", repos = "http://cran.us.r-project.org")
install.packages("geosphere", repos = "http://cran.us.r-project.org")

library(tidyverse) #helps to wrangle the data
library(ggplot2) #helps in data visualization
library(tidyr) #helps to clean the data
library(dplyr) #helps to clean the data
library(geosphere) #used to compute distance & related measures for angular loactions
```

### Importing data

```{r importing data}
May_2023 <- read.csv("~/cycle_project/202305-divvy-tripdata.csv")
Jun_2023 <- read.csv("~/cycle_project/202306-divvy-tripdata.csv")
Jul_2023 <- read.csv("~/cycle_project/202307-divvy-tripdata.csv")
Aug_2023 <- read.csv("~/cycle_project/202308-divvy-tripdata.csv")
Sep_2023 <- read.csv("~/cycle_project/202309-divvy-tripdata.csv")
Oct_2023 <- read.csv("~/cycle_project/202310-divvy-tripdata.csv")
Nov_2023 <- read.csv("~/cycle_project/202311-divvy-tripdata.csv")
Dec_2023 <- read.csv("~/cycle_project/202312-divvy-tripdata.csv")
Jan_2024 <- read.csv("~/cycle_project/202401-divvy-tripdata.csv")
Feb_2024 <- read.csv("~/cycle_project/202402-divvy-tripdata.csv")
Mar_2024 <- read.csv("~/cycle_project/202403-divvy-tripdata.csv")
Apr_2024 <- read.csv("~/cycle_project/202404-divvy-tripdata.csv")
```

### Wrangling data

```{r comparing column names of each file}
#comparing column names of each file

colnames(May_2023)
colnames(Jun_2023)
colnames(Jul_2023)
colnames(Aug_2023)
colnames(Sep_2023)
colnames(Oct_2023)
colnames(Nov_2023)
colnames(Dec_2023)
colnames(Jan_2024)
colnames(Feb_2024)
colnames(Mar_2024)
colnames(Apr_2024)
```

### Inspect the dataframes and look for incongruencies

```{r inspecting the individual dataframes}
str(May_2023)
str(Jun_2023)
str(Jul_2023)
str(Aug_2023)
str(Sep_2023)
str(Oct_2023)
str(Nov_2023)
str(Dec_2023)
str(Jan_2024)
str(Feb_2024)
str(Mar_2024)
str(Apr_2024)
```


### Merging data into a data frame

```{r merging data}
all_trips <- rbind(May_2023,Jun_2023,Jul_2023,Aug_2023,Sep_2023,
                        Oct_2023,Nov_2023,Dec_2023,Jan_2024,Feb_2024,
                        Mar_2024,Apr_2024)
```

## Process

Processing the dirty data to clean data. In this stage I choose the Rstudios because the data is too large and spreadsheet is not able to handle this dataset.

### Inspect the data

```{r Inspect the dataset}
head(all_trips) #first 6 rows of the data frame
tail(all_trips) #last 6 rows of the data frame
str(all_trips) #list of columns and data types
colnames(all_trips) #list of column names
nrow(all_trips) #number of rows in a data frame
ncol(all_trips) #number of columns in a data frame
dim(all_trips) #dimensions of the data frame
summary(all_trips) #statistical summary of data
```

### Removing NA values

In statistical summary, I saw that there are 7610 NA values in the column end_lat and end_lng. So, I removed the NA values from the data frame.

```{r Removing the NA values}
all_trips <- drop_na(all_trips)
```

### Transforming the started_at and ended_at column from char to dates

By using str function, I got to know that the started_at and ended_at columns are in character format. So, I converted them to date and time format.

```{r Transforming data from char to dates}
all_trips$started_at <- as.POSIXlt(all_trips$started_at, format = "%Y-%m-%d %H:%M:%S")
all_trips$ended_at <- as.POSIXlt(all_trips$ended_at, format = "%Y-%m-%d %H:%M:%S")
```

### Checking how many different types of users are there in the dataset
```{r types of users in the dataset}
table(all_trips$member_casual)
```

### Checking how many different types of rideables are there in the dataset
```{r rideable type in the dataset}
table(all_trips$rideable_type)
```

### Adding the columns of date, month, day and year in the dataset
```{r adding column of date, month, day and year}
all_trips$date <- as.Date(all_trips$started_at) #The default format is yyyy-mm-dd
all_trips$month <- format(as.Date(all_trips$date), "%m")
all_trips$day <- format(as.Date(all_trips$date), "%d")
all_trips$year <- format(as.Date(all_trips$date), "%Y")
all_trips$day_of_week <- format(as.Date(all_trips$date), "%A")
```

### Adding a "ride_length" calculation to all_trips

```{r Adding a "ride_length" calculation to all_trips}
all_trips$ride_length <- difftime(all_trips$ended_at,all_trips$started_at)
```

### Inspect the structure of the columns

```{r inspect the structure of columns}
str(all_trips)
```

### Convert "ride_length" from difftime to numeric so we can run calculations on the data

```{r Convert "ride_length" from difftime to numeric}
is.difftime(all_trips$ride_length)
all_trips$ride_length <- as.numeric(all_trips$ride_length)
is.numeric(all_trips$ride_length)
```

### Removing "bad" data
The dataframe includes a few hundred entries when bikes were taken out of docks and checked for quality by Divvy or ride_length was **negative**. I will create a new version of the dataframe (v2) since data is being removed.

```{r removing bad data}
all_trips_v2 <- all_trips[!(all_trips$start_station_name == "HQ QR" | all_trips$ride_length<0),]
```

### Checking for duplicate data

```{r checking for duplicate data}
all_trips_v2 %>% 
  group_by(ride_id) %>% 
  filter(n() > 1 & !is.na(ride_id) & ride_id != "") %>% 
  nrow()
```

### Checking for blank cells

Here, I am creating a function for counting the blank cells in the dataset so that I can perform the task again and again.

```{r Checking for blank cells}
count_blank_values <- function(all_trips_v2) {
  blank_ride_id_count <- all_trips_v2 %>% filter(ride_id == "" | is.na(ride_id)) %>% nrow()
  blank_rideable_type_count <- all_trips_v2 %>% filter(rideable_type == "" | 
                                                         is.na(rideable_type)) %>% nrow()
  blank_started_at_count <- all_trips_v2 %>% filter(is.na(started_at)) %>% nrow()
  blank_ended_at_count <- all_trips_v2 %>% filter(is.na(ended_at)) %>% nrow()
  blank_start_station_name_count <- all_trips_v2 %>% filter(start_station_name == "" | 
                                                              is.na(start_station_name)) %>% nrow()
  blank_start_station_id_count <- all_trips_v2 %>% filter(start_station_id == "" | 
                                                            is.na(start_station_id)) %>% nrow()
  blank_end_station_name_count <- all_trips_v2 %>% filter(end_station_name == "" | 
                                                            is.na(end_station_name)) %>% nrow()
  blank_end_station_id_count <- all_trips_v2 %>% filter(end_station_id == "" | 
                                                          is.na(end_station_id)) %>% nrow()
  blank_start_lat_count <- all_trips_v2 %>% filter(start_lat == "" | is.na(start_lat)) %>% nrow()
  blank_start_lng_count <- all_trips_v2 %>% filter(start_lng == "" | is.na(start_lng)) %>% nrow()
  blank_end_lat_count <- all_trips_v2 %>% filter(end_lat == "" | is.na(end_lat)) %>% nrow()
  blank_end_lng_count <- all_trips_v2 %>% filter(end_lng == "" | is.na(end_lng)) %>% nrow()
  blank_member_casual_count <- all_trips_v2 %>% filter(member_casual == "" | 
                                                         is.na(member_casual)) %>% nrow()
  blank_ride_length_count <- all_trips_v2 %>% filter(ride_length == "" | 
                                                       is.na(ride_length)) %>% nrow()
  blank_day_of_week_count <- all_trips_v2 %>% filter(day_of_week == "" | 
                                                       is.na(day_of_week)) %>% nrow()
  
  blank_counts_df <- data.frame(
    Column = c("ride_id", "rideable_type","started_at","ended_at","start_station_name",
               "start_station_id","end_station_name","end_station_id","start_lat",
               "start_lng","end_lat","end_lng","member_casual","ride_length","day_of_week"),
    Blank_Count = c(blank_ride_id_count, blank_rideable_type_count,blank_started_at_count,
                    blank_ended_at_count,blank_start_station_name_count,
                    blank_start_station_id_count,blank_end_station_name_count,
                    blank_end_station_id_count,blank_start_lat_count,blank_start_lng_count,
                    blank_end_lat_count,blank_end_lng_count,blank_member_casual_count,
                    blank_ride_length_count,blank_day_of_week_count)
  )
  
  return(blank_counts_df)
}

count_blank_values(all_trips_v2)
```

Here, I found that there are some blank cells in the column start_station_name, start_station_id, end_station_name and end_station_id.

### Completing the incomplete data
Now with the help of latitudes and longitudes I filled the blank cells of station names and station ids. I will create a new version of the dataframe (v3) since data is being edited and removed.

```{r Completing the incomplete data}
# Creating the unique dataset for start stations
unique_start_stations <- all_trips_v2 %>%
  filter(start_station_name != "" & !is.na(start_station_name) & start_station_id != "" & !
           is.na(start_station_id)) %>%
  select(start_lat, start_lng, start_station_name, start_station_id) %>%
   group_by(start_lat, start_lng) %>%
  summarize(
    start_station_name = first(start_station_name),
    start_station_id = first(start_station_id)
  ) %>%
  ungroup()

# Creating the unique dataset for end stations
unique_end_stations <- all_trips_v2 %>%
  filter(end_station_name != "" & !is.na(end_station_name) & end_station_id != "" & !
           is.na(end_station_id)) %>%
  select(end_lat, end_lng, end_station_name, end_station_id) %>%
   group_by(end_lat, end_lng) %>%
  summarize(
    end_station_name = first(end_station_name),
    end_station_id = first(end_station_id)
  ) %>%
  ungroup()

#Join the unique stations back to the main dataset based on latitude and longitude to fill missing 
#values
all_trips_v3 <- all_trips_v2 %>% 
  left_join(unique_start_stations, by = c("start_lat", "start_lng"), suffix = c("", ".filled")) %>% 
  left_join(unique_end_stations, by = c("end_lat", "end_lng"), suffix = c("", ".filled"))

# Fill missing station names and station id with the filled values
all_trips_v3 <- all_trips_v3 %>%
  mutate(
    start_station_name = ifelse(start_station_name == "" | is.na(start_station_name), 
                                start_station_name.filled, start_station_name),
    start_station_id = ifelse(start_station_id == "" | is.na(start_station_id), 
                              start_station_id.filled, start_station_id),
    end_station_name = ifelse(end_station_name == "" | is.na(end_station_name), 
                              end_station_name.filled, end_station_name),
    end_station_id = ifelse(end_station_id == "" | is.na(end_station_id), 
                            end_station_id.filled, end_station_id)
  ) %>%
  select(-start_station_name.filled, -start_station_id.filled, -end_station_name.filled, 
         -end_station_id.filled)
```

Now, I checked for the blank cells again in the updated dataset.

```{r rechecking for blank cells}
count_blank_values(all_trips_v3)
```

Here, I found that there are still some data whose locations are not retrieved. Which means there are 618309 rides in which the bikes are not picked from the stations and there are 668378 rides in which the bikes are not parked on their respective stations. So, I am dropping this data to clean my dataset.

```{r Removing the NA values for unidentified stations}
all_trips_v3 <- drop_na(all_trips_v3)
```


```{r final rechecking for blank cells}
count_blank_values(all_trips_v3)
```

### Checking whether each station is alloted to unique station id

```{r Checking whether each station is alloted to unique station id}
length(unique(all_trips_v3$start_station_id))
length(unique(all_trips_v3$start_station_name))
length(unique(all_trips_v3$end_station_id))
length(unique(all_trips_v3$end_station_name))
```

In this dataset, each station is identified by a unique Station ID. However, it has been observed that there are instances where multiple Station Names are associated with a single Station ID. This can occur due to several reasons, including historical name changes, different naming conventions across sources, or typographical variations.

To ensure consistency and accuracy in analysis, it is important to recognize that these multiple names refer to the same physical station.

```{r finding 2 or more station names which are allotted to 1 station id}
all_trips_v3 %>%
  group_by(start_station_id,start_station_name) %>% 
  summarise(unique(start_station_name)) %>% 
  filter(length(start_station_id) > 1) %>% 
  arrange(start_station_id,start_station_name)

all_trips_v3 %>%
  group_by(start_station_name,start_station_id) %>% 
  summarise(unique(start_station_id)) %>% 
  filter(length(start_station_name) > 1) %>% 
  arrange(start_station_name,start_station_id)

all_trips_v3 %>%
  group_by(end_station_id,end_station_name) %>% 
  summarise(unique(end_station_name)) %>% 
  filter(length(end_station_id) > 1) %>% 
  arrange(end_station_id,end_station_name)

all_trips_v3 %>%
  group_by(end_station_name,end_station_id) %>% 
  summarise(unique(end_station_id)) %>% 
  filter(length(end_station_name) > 1) %>% 
  arrange(end_station_name,end_station_id)
```

As per the observation there are multiple stations allocated to one station id and there are multiple station ids allocated to one station. So, for this analysis I will only continue with station names not with station ids just to avoid conflicts.

### Creating column to find out distance of each ride

```{r Creating column to find out distance of each ride}
all_trips_v3$ride_distance <- distGeo(matrix(c(all_trips_v3$start_lng, all_trips_v3$start_lat), 
                                             ncol=2), matrix(c(all_trips_v3$end_lng, 
                                                               all_trips_v3$end_lat), ncol=2))
```


Now, my dataset is cleaned.

## Analyze

After cleaning, now its time to analyze the data.

### CONDUCTING DESCRIPTIVE ANALYSIS

```{r Descriptive analysis on ride_length (all figures in seconds)}
#Descriptive analysis on ride_length (all figures in seconds)
summary(all_trips_v3$ride_length)
```

```{r Compare members and casual users}
# Compare members and casual users
aggregate(all_trips_v3$ride_length ~ all_trips_v3$member_casual, FUN = mean)
aggregate(all_trips_v3$ride_length ~ all_trips_v3$member_casual, FUN = median)
aggregate(all_trips_v3$ride_length ~ all_trips_v3$member_casual, FUN = max)
aggregate(all_trips_v3$ride_length ~ all_trips_v3$member_casual, FUN = min)
```

```{r See the average ride time by each month for members vs casual users}
# See the average ride time by each month for members vs casual users
aggregate(all_trips_v3$ride_length ~ all_trips_v3$member_casual + all_trips_v3$month, 
          FUN = mean)
```

```{r analyze ridership data by type and month}
# analyze ridership data by type and month
all_trips_v3 %>% 
  mutate(month = month(started_at, label = TRUE)) %>%  #creates month field using wday()
  group_by(member_casual, month) %>%  #groups by usertype and month
  summarise(number_of_rides = n()							#calculates the number of rides and
                                              #average duration 
            ,average_duration = mean(ride_length)) %>% 		# calculates the average duration
  arrange(member_casual, month)								# sorts
```

```{r See the average ride time by each day for members vs casual users}
# See the average ride time by each day for members vs casual users
aggregate(all_trips_v3$ride_length ~ all_trips_v3$member_casual + all_trips_v3$day_of_week, 
          FUN = mean)
```

```{r fixing the out of order days of the week}
# Notice that the days of the week are out of order. Let's fix that.
all_trips_v3$day_of_week <- ordered(all_trips_v3$day_of_week, levels=c("Sunday", "Monday", 
                                                                       "Tuesday", "Wednesday", 
                                                                       "Thursday", "Friday", 
                                                                       "Saturday"))

```

```{r running the average ride time by each day for members vs casual users}
# Now, let's run the average ride time by each day for members vs casual users
aggregate(all_trips_v3$ride_length ~ all_trips_v3$member_casual + all_trips_v3$day_of_week, 
          FUN = mean)
```

```{r analyze ridership data by type and weekday}
# analyze ridership data by type and weekday
all_trips_v3 %>% 
  mutate(weekday = wday(started_at, label = TRUE)) %>%  #creates weekday field using wday()
  group_by(member_casual, weekday) %>%  #groups by usertype and weekday
  summarise(number_of_rides = n()							#calculates the number of rides and  
                                              #average duration 
            ,average_duration = mean(ride_length)) %>% 		# calculates the average duration
  arrange(member_casual, weekday)								# sorts
```

```{r analyze ridership data by user type and rideable type}
# analyze ridership data by user type and rideable type
all_trips_v3 %>% 
  group_by(member_casual, rideable_type) %>%  #groups by usertype and weekday
  summarise(number_of_rides = n()							#calculates the number of rides and  
                                              #average duration 
            ,average_duration = mean(ride_length)) %>% 		# calculates the average duration
  arrange(member_casual, rideable_type)								# sorts
```

### Checking for number of rides with same start and end station.

```{r Checking for number of rides with same start and end station}
all_trips_v3 %>%
  group_by(member_casual) %>%
  summarise(
    number_of_riders = n(),
    same_station = sum(ride_distance < 1),
    .groups = 'drop'
  ) %>% 
  mutate(percentage = (same_station / number_of_riders) * 100)
```


## Share

```{r Compare number of members and casual users}
# Compare members and casual users
ggplot(all_trips_v3,mapping= aes(x= member_casual, fill = member_casual)) +
  geom_bar() + 
  labs(title="Compare members and casual users") + 
  scale_fill_manual(values = c("blue", "darkorange"))
```

```{r Ride duration of casual and member riders}
# Ride duration of casual and member riders
all_trips_v3 %>% 
  group_by(member_casual) %>% 
  summarise(avg_ride_length = mean(ride_length)) %>% 
ggplot(all_trips_v3,mapping= aes(x= member_casual, y = avg_ride_length, fill = member_casual)) +
  geom_col() + 
  labs(title="Ride duration of casual and member riders")  + 
  scale_fill_manual(values = c("blue", "darkorange"))
```

``` {r visualizing the number of rides by rider type and rideable type}
# Let's visualize the number of rides by rider type and rideable type
all_trips_v3 %>% 
  group_by(member_casual, rideable_type) %>% 
  summarise(number_of_rides = n(),average_duration = mean(ride_length)) %>%
  mutate(percentage = number_of_rides / sum(number_of_rides) * 100) %>% 
  arrange(member_casual, rideable_type)  %>% 
  ggplot(mapping = aes(x = "", y = percentage, fill = rideable_type)) +
  geom_bar(width = 1, stat = "identity") +
  coord_polar(theta = "y")+
  facet_wrap(~member_casual)+
  theme_void() +
  geom_text(aes(label = paste0(round(percentage, 1), "%")),
            position = position_stack(vjust = 0.5)) + 
  scale_fill_manual(values = c("red","skyblue", "darkgreen"))
```

```{r creating a visualization for average duration for rider type and rideable type}
# Let's create a visualization for average duration for rider type and rideable type
all_trips_v3 %>% 
  group_by(member_casual, rideable_type) %>% 
  summarise(number_of_rides = n(),average_duration = mean(ride_length)) %>%
  mutate(percentage = average_duration / sum(average_duration) * 100) %>% 
  arrange(member_casual, rideable_type)  %>% 
  ggplot(mapping = aes(x = "", y = percentage, fill = rideable_type)) +
  geom_bar(width = 1, stat = "identity") +
  coord_polar(theta = "y")+
  facet_wrap(~member_casual)+
  theme_void() +
  geom_text(aes(label = paste0(round(percentage, 1), "%")),
            position = position_stack(vjust = 0.5)) + 
  scale_fill_manual(values = c("red","skyblue", "darkgreen"))
```

``` {r visualizing the number of rides by rider type wrt months}
# Let's visualize the number of rides by rider type wrt months
all_trips_v3 %>% 
  mutate(month = month(started_at, label = TRUE)) %>% 
  group_by(member_casual, month) %>% 
  summarise(number_of_rides = n()
            ,average_duration = mean(ride_length)) %>% 
  arrange(member_casual, month)  %>% 
  ggplot(mapping = aes(x = month, y = number_of_rides, fill = member_casual)) +
  geom_col(position = "dodge")  + 
  scale_fill_manual(values = c("blue", "darkorange"))
```

```{r creating a visualization for average duration wrt months}
# Let's create a visualization for average duration wrt months
all_trips_v3 %>% 
  mutate(month = month(started_at, label = TRUE)) %>% 
  group_by(member_casual, month) %>% 
  summarise(number_of_rides = n()
            ,average_duration = mean(ride_length)) %>% 
  arrange(member_casual, month)  %>% 
  ggplot(mapping = aes(x = month, y = average_duration, fill = member_casual)) +
  geom_col(position = "dodge")  + 
  scale_fill_manual(values = c("blue", "darkorange"))
```

``` {r visualizing the number of rides by rider type wrt days of week}
# Let's visualize the number of rides by rider type wrt days of week
all_trips_v3 %>% 
  mutate(weekday = wday(started_at, label = TRUE)) %>% 
  group_by(member_casual, weekday) %>% 
  summarise(number_of_rides = n()
            ,average_duration = mean(ride_length)) %>% 
  arrange(member_casual, weekday)  %>% 
  ggplot(mapping = aes(x = weekday, y = number_of_rides, fill = member_casual)) +
  geom_col(position = "dodge")  + 
  scale_fill_manual(values = c("blue", "darkorange"))
```

```{r creating a visualization for average duration wrt days of week}
# Let's create a visualization for average duration wrt days of week
all_trips_v3 %>% 
  mutate(weekday = wday(started_at, label = TRUE)) %>% 
  group_by(member_casual, weekday) %>% 
  summarise(number_of_rides = n()
            ,average_duration = mean(ride_length)) %>% 
  arrange(member_casual, weekday)  %>% 
  ggplot(mapping = aes(x = weekday, y = average_duration, fill = member_casual)) +
  geom_col(position = "dodge") + 
  scale_fill_manual(values = c("blue", "darkorange"))
```




```{r visualizing the number of rides by starting stations}
# Let's visualize the number of rides by starting stations
all_trips_v3 %>%
  group_by(member_casual, start_station_name) %>%
  summarise(n = n(), .groups = 'drop') %>%
  arrange(member_casual, desc(n)) %>%
  group_by(member_casual) %>%
  slice_head(n = 10) %>% 
ggplot(mapping = aes(x = reorder(start_station_name, n), y = n, fill = member_casual)) +
  geom_bar(stat = "identity") +
  coord_flip() +
  labs(title = "Number of rides by starting stations",
       x = "Start_Station_Name",
       y = "Number of Rides") +
  facet_grid(member_casual~.,scales = "free_y") +
  theme_minimal() +
  theme(legend.position = "none")  + 
  scale_fill_manual(values = c("blue", "darkorange"))
```

```{r visualizing the number of rides by ending stations}
# Let's visualize the number of rides by ending stations
all_trips_v3 %>%
  group_by(member_casual, end_station_name) %>%
  summarise(n = n(), .groups = 'drop') %>%
  arrange(member_casual, desc(n)) %>%
  group_by(member_casual) %>%
  slice_head(n = 10) %>% 
ggplot(mapping = aes(x = reorder(end_station_name, n), y = n, fill = member_casual)) +
  geom_bar(stat = "identity") +
  coord_flip() +
  labs(title = "Number of rides by ending stations",
       x = "End_Station_Name",
       y = "Number of Rides") +
  facet_grid(member_casual~.,scales = "free_y") +
  theme_minimal() +
  theme(legend.position = "none")  + 
  scale_fill_manual(values = c("blue", "darkorange"))
```

```{r Histogram that shows ride distance count}
#Histogram that shows ride distance count
all_trips_v3 %>% 
  group_by(member_casual) %>% 
  filter(ride_distance < 10000) %>% #removing outliner 
  ggplot(mapping = aes(x=ride_distance, fill=member_casual))+
  geom_histogram()  + 
  scale_fill_manual(values = c("blue", "darkorange"))
```

```{r Bar chart that shows average ride distance wrt the month}
#Bar chart that shows average ride distance wrt the month.
all_trips_v3 %>% 
  group_by(member_casual, month) %>% 
  summarise(average_ride_distance = mean(ride_distance),.groups = 'drop') %>% 
  ggplot(mapping = aes(x=month, y=average_ride_distance, fill=member_casual))+
  geom_bar(position = 'dodge', stat = 'identity')  + 
  scale_fill_manual(values = c("blue", "darkorange"))
```


```{r Bar chart that shows average ride distance wrt the day of week}
#Bar chart that shows average ride distance wrt the day of week.
all_trips_v3 %>% 
  group_by(member_casual, day_of_week) %>% 
  summarise(average_ride_distance = mean(ride_distance),.groups = 'drop') %>% 
  ggplot(mapping = aes(x=day_of_week, y=average_ride_distance, fill=member_casual))+
  geom_bar(position = 'dodge', stat = 'identity')  + 
  scale_fill_manual(values = c("blue", "darkorange"))
```


### Exporting the data for further analysis

```{r selecting the required columns only}
all_trips_v4 <- all_trips_v3 %>% 
  select(rideable_type, started_at, ended_at, start_station_name, end_station_name, 
         start_lat, start_lng, end_lat, end_lng, member_casual, date, month, day, 
         year, day_of_week, ride_length)
```


```{r Exporting the data for further analysis}
write.csv(all_trips_v4, file = "all_trips_final.csv",row.names = FALSE)
```

### Dashboard from tableau ([**link**](https://public.tableau.com/app/profile/sparsh.gupta6875/viz/Casestudy1Howdoesabike-sharenavigatespeedysuccess/Dashboard3#1))

<p align="center">
  <img src="https://lh3.googleusercontent.com/pw/AP1GczOIcELYiVV_cyFprSmH1O6Hp7UXo0oQK1L6QrTxj-J3NqlpOh6vj9s-zVUuwevON5x4huiDn4UwmmKsLtxumKrAVzazh6nUbtV8PqM52MOqj3CaEu4hXRIs248LFZop_fUTh1LDssnMGRwosCpo_AMowRUee_BSR5ep7zzaxk-b_zmL9Tn1IYeVTGJaV4zaiAbNJYiP0wX6_DfAdIGEv0SoC5h7zsnUZj-ixdgumLwoG1HgzpuOtBYheu6Y23bEdSAGcTaGqfzQpqwIyAe1O5g0cqWAyS27_y205AhZWIS8H_MRyTKd2esk1v9jPW9Us1pKK1s-vCe0GMa2fJRwcVSg3r38T3dqiN26KfGXk1eMXvKAZbuQkTL96mOy3L31Kw9ooRQqOMk1yGmlV5X0MOtmnMDk8LLBY7JHYp1VtGT7K_WB34SH1c5G4X8fTCc64_N7R8rDmIIOqvlPu0vPEzIVH0yFeha7dSzsQN_lhlp7Yi6E65dWX7YLlIjpsSHtauxyCjN91amuEwHZyHPKbQcmVNkjoRq1Kn4cB2cwjjmCG9a83NdH_MmSPEahadwnReKiB3nc0BR6Dl42vj-zpe4qthKcCa7PniDVOn9WSxNqHgzXWveaErwUWsfPFXI1I2_6bhoW74phEmee93F3L6qjpENLpLBuCK1_nC0668oEmOfdFaieV2p_jibewFSf2ZEbOmbQe9Ni_I97mMe3VAdmljM9tYBp0gOICKn832QVpAcGqzSHSjJVN4GHgIUVfO1zBop5uVfC3j4IAQmYdULQimf4Sc1XU0OrdwIMoZmwHtt6BTbsOekZCZH85UeHOCc__IPlOJcQELkNANM5ts5hse0qfEIc3auadaDUxG1Q6ScaUmj0QfbSBf0QwNHC-AS7SFjc_ulIj4hIf0zcr0ANk-ldKouLgLKs2HOJ7_FdHyG2yAZaljY3zGKMj5A=w1545-h869-s-no-gm?authuser=0"/>
</p>


### Key Findings
1. **Usage Patterns:**
    - **Annual Members:** Tend to use bikes for regular commuting, often seen in peak hours during weekdays. Trips are typically shorter in duration and distance.
    - **Casual Riders:** Use bikes more for leisure and sporadic trips, often during weekends and holidays. Their trips are generally longer in duration but fewer in frequency.
    
2. **Revenue and Profitability:**
Annual members generate stable, predictable revenue, contributing more consistently to Cyclistic's profitability compared to casual riders.

3. **Popular Stations:**
Many casual riders start and end their rides at Streeter Dr & Grand Ave. Additionally, 7.31% of casual riders and 3.08% of annual members have trips where the start and end stations are the same, indicating circular or leisure rides.

4. **Seasonal Preferences:**
Both casual riders and annual members prefer to ride during the summer months, with the highest usage recorded from June to August.

5. **Bike Preferences:**
Both casual and annual members show a strong preference for classic bikes. However, casual riders who use docked bikes have the longest ride durations compared to other bike types.

6. **Ride Distances:**
Both casual riders and annual members have similar ride distances, indicating that the primary difference in their usage patterns lies in the frequency and duration of rides rather than the distance traveled.

7. **Conversion Potential:**
Casual riders, already familiar with the service, present a significant opportunity for conversion to annual memberships. Their existing engagement with Cyclistic lowers the cost of acquisition for memberships.

8. **Digital Media Influence:**
Digital media campaigns can effectively target casual riders with personalized offers and reminders, potentially increasing conversion rates. Strategies might include retargeting ads, social media promotions, and email marketing.


### Recommendations

1. **Tailored Marketing Campaigns:**
  - Develop marketing campaigns highlighting the cost savings and convenience of annual memberships. Use data insights to show casual riders the potential savings with a membership based on their usage patterns.
  - Focus on popular locations such as Streeter Dr & Grand Ave in promotional materials, emphasizing the convenience of starting and ending rides at these key locations.
  - Highlight the preference for classic bikes among both casual and annual members in marketing materials to emphasize user satisfaction.
  - Emphasize that both casual riders and annual members have similar ride distances, promoting the convenience and efficiency of the service for typical ride lengths.

2. **Incentives and Offers:**
  - Offer limited-time discounts or additional benefits for signing up for an annual membership. Consider providing a free trial period or perks like exclusive access to new bikes or stations.
  - Create special offers for casual riders who frequently start and end their trips at the same station, encouraging them to see the benefits of an annual membership.
  - Design seasonal promotions for the summer months when ridership peaks, highlighting the benefits of an annual membership during the busiest times of the year.
  - Target promotions towards casual riders who prefer docked bikes, offering incentives for long-duration rides to convert them to annual memberships.

3. **Enhanced User Experience:**
  - Enhance the user experience for casual riders by streamlining the membership sign-up process. Implement in-app prompts and simplified sign-up procedures.
  - Introduce features that highlight the advantages of annual membership for users frequently using popular stations.
  - Prepare for increased summer usage by ensuring bike availability and maintaining station infrastructure to handle the higher demand.
  - Ensure a sufficient supply of classic bikes, as they are the preferred choice among users, to maintain high satisfaction and meet demand.

4. **Leveraging Digital Media:**
  - Use targeted digital media campaigns to reach casual riders. Utilize personalized ads on social media, search engines, and email to promote the benefits of annual memberships. Implement retargeting strategies for users who have previously used casual passes.
  - Specifically target ads to users who have high usage at Streeter Dr & Grand Ave, showcasing the convenience and benefits of an annual membership for their regular routes.
  - Plan and execute digital media campaigns leading up to and during the summer months to capture the peak interest and conversion potential during this period.
  - Highlight the benefits of classic bikes in digital media campaigns, appealing to the preferences of both casual and annual members.

5. **Feedback and Engagement:**
  - Engage with casual riders to gather feedback on what could encourage them to consider an annual membership. Use surveys, feedback forms, and social media engagement to collect insights and adapt marketing strategies accordingly.
  - Collect feedback specifically from users who frequently start and end their trips at the same station to understand their motivations and how best to convert them to annual members.
  - Solicit feedback during and after the summer peak season to identify and address any service issues, ensuring continued satisfaction and potential for membership conversion.
  - Gather specific feedback from users who prefer docked bikes, understanding their needs and how to cater to their long-duration ride preferences.
