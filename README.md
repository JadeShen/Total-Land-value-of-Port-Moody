# Total-Land-value-of-Port-Moody
## Team member 
Yutao Shen, Zhengyang Sun and Linwan Xu

## Background Info
In just five years, the land value of a small town has shrunk 20 times. Therefore, our team assumes that a wealthy businessman wants to buy all the land of Port Moody.
Then we predicts total land value of Port Moody. 

## Source Explanation

Target population: lands in Port Moody, Observation unit: lands within a zip code area, Sampling frame: list of all zip codes in Port Moody, 
Sampling unit: zip codes are on the sampling frame, Sampled population: lands within the zip code area from the sampling frame. 

We find the map of Port Moody and divide it into 12 different area according to the street trend. we find zone 12 is a whole oil factory. So we decide exclude it. We found there are 705 postal code in Port Moody, then divided into each zones. 

datacollection.xlsx using random selection software, five of eleven zones are randomly selected. The data includes 25% selecting of the zip code in each zone, and find all the land values contained in each zip code according to the BC assessment website and Google map. 

ID: zone, N: Total zone number, M: total number of zip code in each zone, n: selected zone number, y: land value

## Method: Two-stage Cluster Sampling

A two-stage cluster sample is obtained by first selecting a sample of cluster, and selecting a sample of elements from each sampled cluster.

## Conclusion: 

![alt text](https://github.com/JadeShen/Total-Land-value-of-Port-Moody/blob/main/result.png)

The above picture is estimate for 11 zones, then add the total value for zone 12 (oil facotry $ 121279000). Total land value in 12 zones is 11237399692, and the CI changes to (9535200455, 12939598928). 


