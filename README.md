# Readme



## Abstract

With the popularization of mobile devices, we are generating massive amounts of data  every day. Traditional storage technologies as well as analytics software can no  longer meet the performance demands. Spark is a cutting-edge technology that  addresses the three challenges of big data: velocity, volume and variety. The  motivation of this analysis is mainly using spark to process and analyze the data from  the 2020 US presidential election ad dataset on Facebook, and visualize it with tools  such as Excel and Tableau. The contribution of this analysis is that I found some  interesting phenomena, such as ads with low impressions are generally more cost effective. But if the expensive ads are impressive, the more often they are placed the  better the cost-effective. Campaign teams prefer to place ads on their campaign  websites rather than mainstream media sites in order to control costs. In addition to  strengthening the camp of your own party, gaining support from swing states is also  quite important for the campaign.



## Dataset description

The dataset to be used in this assessment is a collection of sponsored political posts on Facebook targeted at US users  during 23 months (03/2020-01/2022). This includes the period preceding the latest US Presidential election in  November 2020. A description of the data structure is available starting from:  https://www.facebook.com/ads/library/api/. The dataset covers 23-month worth of data collected from this API. The  format in which the data is provided by Facebook is JSON files. Each file is the result of a request for active ad  campaigns performed every 12 hours during the 23 months period, thus a lot of ad campaigns are duplicated across  files (i.e., if ad campaigns run for more than 12 hours) 
