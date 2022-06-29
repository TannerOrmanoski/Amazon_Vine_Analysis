# Amazon_Vine_Analysis

## Purpose

The purpose of this analysis is to use the ETL process to extract a dataset of Amazon reviews, transform the data, connect to an AWS RDS instance, and then load the transformed data into pgAdmin. Then Pandas is used to detect if any bias exists toward favorable reviews from Vine members. 

## Results

### Vine vs. Non-Vine

The number of vine users are 94.

![](https://github.com/TannerOrmanoski/Amazon_Vine_Analysis/blob/main/Module16_photos/Screen%20Shot%202022-06-28%20at%207.19.21%20PM.png)

The number of non-vine users are 40,471.

![](https://github.com/TannerOrmanoski/Amazon_Vine_Analysis/blob/main/Module16_photos/Screen%20Shot%202022-06-28%20at%207.19.53%20PM.png)

### 5 Star Reviews Vine vs. Non-Vine

There are 48 five-star reviews from vine members.

![](https://github.com/TannerOrmanoski/Amazon_Vine_Analysis/blob/main/Module16_photos/Screen%20Shot%202022-06-28%20at%207.19.29%20PM.png)

There are 15,663 five-star reviews from non-vine members.

![](https://github.com/TannerOrmanoski/Amazon_Vine_Analysis/blob/main/Module16_photos/Screen%20Shot%202022-06-28%20at%207.20.02%20PM.png)

### Percentage of 5 Star Reviews Vine vs. Non-Vine

About 51% of the reviews are five-star for vine members.

![image](https://user-images.githubusercontent.com/99365550/176326505-a9a0e457-b4b9-42f5-9eb0-8e37f494b4f1.png)

About 38.7% of the reviews are five-star for the non-vine members.

![](https://github.com/TannerOrmanoski/Amazon_Vine_Analysis/blob/main/Module16_photos/Screen%20Shot%202022-06-28%20at%207.20.11%20PM.png)

## Summary

There seems to be some positivity bias for reviews of the vine members. A little over half of the reviews from vine members are five-stars, while only 38.7% of the reviews of non-vine members are five-stars. If we wanted further confirmation of this, we could determine how many of the reviews were one-star for each group. We could also get the mean stars for each of the groups, or use a distribution curve. 

