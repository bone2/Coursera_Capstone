## The different between HongKong and NewYork, and the smart location choice to open an coffee shop

### Background

New York city and HongKong are both very bustling international metropolis and international finance centers, on the back of two of the world's largest countries - USA and China where the total opposite of the earth. So they must be lots of similarities and dissimilarities. This would be an interesting questions and must many people have interested in.

On the other side, HongKong is famous for its food especially for Chinese traditional food, if someone want to open a western-style restaurant like a coffee shop, where would be a smart choice?

### Data

All those two problems solved based on data, which mainly from [foursquare](https://foursquare.com/). Other part of data may come from Wikipedia pages or other related website.

The data should describe the venue categories in each city neighborhoods. After collected all of those useful data, I will wrangling it firstly. Then use those categories features group the neighborhoods into different clusters by using k-means algorithm. If compare with the majority neighborhoods clusters, we could conclude the characters of the cities, there would be some similarities and some dissimilarities exist at the same.

Chose a right place to run a small business is a very practical problem, everyone who before run a coffee shop must take a deep inspect into the business environment around it, in my report I will show a very different solution from that traditional tactic. My solution still based on the data collected from foursquare, firstly I will group the venues into different type of cluster of some neighborhood, then take this operation to each neighborhoods to get the cluster and top 5 venues of each neighborhood, finally chose those neighborhoods have not any or many coffee shops as considerable neighborhoods where could run a coffee shop.
