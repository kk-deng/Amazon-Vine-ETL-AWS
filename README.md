# Big Data Challenge

# An ETL Project with AWS RDS and Big Data Analysis in Google Colab with PySpark

*Analyze whether reviews from Amazon's Vine program are trustworthy*

<img src="https://thewanderingclouddotblog.files.wordpress.com/2020/07/amazonvine.png" width=600>

Many of Amazon's shoppers depend on product reviews to make a purchase. Amazon makes these datasets publicly available. However, they are quite large and can exceed the capacity of local machines to handle. One dataset alone contains over 1.5 million rows; with over 40 datasets, this can be quite taxing on the average local computer. 

The first goal for this assignment will be to perform the ETL process completely in the cloud (Google Colab) and upload a DataFrame to an RDS instance. The second goal will be to use PySpark or SQL to perform a statistical analysis of selected data.

## Files Index

Following files are attached:

1. <a href="https://github.com/kk-deng/Big-Data-Challenge/blob/main/level-1/Big_Data_Level_1.ipynb">Big_Data_Level_1.ipynb</a>: Level 1 ETL with **Luggage Reivews**

2. <a href="https://github.com/kk-deng/Big-Data-Challenge/blob/main/level-1/Big_Data_Level_1_2.ipynb">Big_Data_Level_1_2.ipynb</a>: Level 1 ETL with **Gift Card Reivews**

3. <a href="https://github.com/kk-deng/Big-Data-Challenge/blob/main/level-2/Big_Data_Level_2.ipynb">Big_Data_Level_2.ipynb</a>: Big Data Analysis on Vine Reviews


# Conclusion

* We can see that the percentage of **5-star reviews** in Vine is very close to non-Vine reviews *(51% to 50.5%)*.

* Although the number of Vine reviews is pretty low, so far it can still represent the product. However, the **average rating from Vine customers is 4.38** with **std deviation of 0.78**, and this is much higher than the **3.77 (std deviation: 1.51) from non-Vine customers**. It is obvious that **non-Vine reviews are more diverse than Vine reviews** which got motivated to give higher ratings.

* I believe the Vine customers tend to give higher ratings and pretty focusing on the higher ratings too. So reviews from Vine customers **are not that trustworthy** for me.
