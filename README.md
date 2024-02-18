# CryptoClustering

Module 19 Challenge for Vanderbilt Data Analytics January 2024

There are 3 files and 1 folder located in this repository, as follows:

This README file is in the main directory with Crypto_Clustering.ipynb, and crypto_market_data.csv is located in the Resources folder.

Special Recognition: Ahmad Mousa is as passionate and caring as he is knowledgeable, and Joshua Steier never hesitates to help walk us through challenges, but this time around it was my peer Karson Kosek (responding to a question from another student Joshua Gibson) who came through holoviz.org/tutorial/Composing_Plots.html for the final 2 steps in the project: visualizing the composite charts.

I always do participate in office hours and study groups while working on projects with collaborators including but not necessarily limited to the following peers: Ilknur Sekmen, Justin Ibeh, Karson Kosek, Kiara Shannon, Luisa Dinwiddie, Margo Berry, Morgan Escue, Morgan Foge, Nathan Johnson, William Brewer, Andrew Clifft, Angela Reed, and Josh Gibson, and I did spend my time in stackoverflow.com, w3schools.com, geeksforgeeks.com, github.com, and bing's new copilot whom I currently consider > google ai; however, the bootcamp has added a new Xpert Learning Assistant, and my life is now complete. Thank you for this resource!

The Google Drive location for this file is as follows: https://drive.google.com/drive/folders/1es-QWsJGLCvWhpHf6ZUAf2AG_-txWG2_?usp=sharing


Analysis: The [official instructions for this particular challenge](https://bootcampspot.instructure.com/courses/4263/assignments/61114?module_item_id=1063503) explicitly do not require the analysis be located within the actual README file and only include the same reminder that has been included in every challenge for this course: "It is your responsibility to include a note in the README section of your repo specifying code source and its location within your repo."  The creators of the official challenge already included the analysis for this challenge within the actual notebook itself. On the list of things we learn in life nd am regularly reminded in this course, whether the client is paying the bill or handing out grades, their satisfaction is really what matters.

1. Question: What is the best value for k? **Answer: k = 4**  
2. Question: What is the total explained variance of the three principal components? **Answer: sum(pca.explained_variance_ratio_) = 0.8886218549859445, suggesting that pertneer 89% of the total variance is explained with just 3 components.**  
3. Question: What is the best value for k when using the PCA data? **Answer: 4**  
4. Question: Does it differ from the best k value found using the original data? **Answer: No**  
5. Question: After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means? **Answer: The clusters appear both tighter and more distinct from one another when using the PCA data.**
