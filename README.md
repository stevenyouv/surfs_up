# surfs_up

##Overview
The purpose of this analysis was to determine whether a surf and ice cream shop business is sustainable year round in Oahu.  In order to determine this, temperature data was retrieved for the months of June and December.  This was completed by using Python, Pandas functions and methods, and SQLAlchemy to take the measurements from the hawaii.sqlite database to retrieve all temperate data for the months of June and December to convert into a list, create a dataframe, and then generate teh summary statistics for both months.  


##Results

As you can see by the tables below, the temperature data in both months are very similar with small variances.  Some of the temperature differences between the two months are:
- June has a slightly higher average temperature at nearly 75 degrees versus the 71 degrees in December
- The highest temperature in June was 83 degrees where December's highest temperature was 77 degrees
- The lowest temperatrue in June was also higher at 64 degrees and December's was at 56 degrees.

![June_Temps](https://user-images.githubusercontent.com/78937719/117561442-8c2a6300-b05c-11eb-84dd-dd9c98831f45.png) ![Dec_Temps](https://user-images.githubusercontent.com/78937719/117561446-96e4f800-b05c-11eb-8dac-11153bcded34.png)



##Summary
If only looking at temperature data for the months of June and December to determine if the surf and ice crea shop can be sustainable in Oahu yearround, it can be concluded that the temperature stays warm enough year round to support this.  

Other factors that can be subject to analysis include precipitation year round.  Below are the measurements of June and December pulled from the same hawaii.sqlite database.  The average rainfall in the two months doesn't differ too much and if only looking at these two months,  it can be determined that precipitation levels won't vary enough from month to month to affect the sustainablilty of opening a surf and ice cream shop year rounnd. 

![June_prcp](https://user-images.githubusercontent.com/78937719/117561449-9a787f00-b05c-11eb-8328-ebb9406833b5.png)![Dec_prcp](https://user-images.githubusercontent.com/78937719/117561453-9c424280-b05c-11eb-8ab9-0ad08ce045cc.png)
 
