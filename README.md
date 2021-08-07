# Distributed-Recommedation-System
A recommendation system that can be run on big data on multiple spark cluster architechture
- Worked on building distributed recommendation system.
- Learned basic content and collaborative filtering based techniques 
- Used Alternating least squares matrix factorization implemented in Spark ,for a scalable model capable of handling big data and parallelizable on a cluster

### Dataset
For this project, Amazon Review Dataset (2018) have been utilized. It is an updated version of the Amazon Review Data released in 2014. This dataset includes more and newer reviews along with metadata related to product like color, product type, technical details and product images taken by the users. It also includes the 2014 dataset’s reviews, product metadata and links. The dataset is also divided into smaller subsets for training purposes like K-cores is arranged such that each of the remaining users and items have k reviews each along with Ratings only dataset which includes no metadata or review but only (item, user, rating, timestamp) tuples. The total number of reviews is 233.1 million (34 GB). This dataset contains various categories like - Musical Instruments, Books, Amazon Instant Video, Digital Music etc.


### Results
| Category                   	| RMSE  	|
|----------------------------	|-------	|
| Musical Instruments        	| 0.97  	|
| Amazon Instant Video       	| 0.91  	|
| Digital Music              	| 0.85  	|
| Tools and home improvement 	| 1.017 	|


