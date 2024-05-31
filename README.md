# CryptoClustering
### Duane Anglin

![clustering](https://github.com/Enaud29/CryptoClustering/assets/161158238/ebf075f9-7554-4472-887a-043121e4c6ba)

## Summary

For this assignment I prepared the data by using StandartScaler from scikit-learn. I used the Elbow method to determind the best value for k which was 4. Then I initialize the K-means model to determined best k value. I fit the model using the original scaled DataFrame. Then create a scatterplot with “price_change_percentage_24h” on the x-axis and “price_change_percentage_7d” on the y-axis. I used Principal Component Analysis to scale the DataFrame and reduce features to 3 components. I used the elbow method again to find the best value for k using the PCA data. I then used K-means model to determind the best k value from PCA data and predict and group cryptocurrencies into clusters. My final step was to create a DataFrame that showed the weights of each feature from the original DataFrame for each principal component and then identify the strongest positive or negative influence on each component.


_Elbow Plot_
![Screenshot 2024-05-31 at 4 15 43 PM](https://github.com/Enaud29/CryptoClustering/assets/161158238/cc143613-374d-4785-9e20-70c088736246)

_Rainbow Scatter Plot_
![Screenshot 2024-05-31 at 4 16 30 PM](https://github.com/Enaud29/CryptoClustering/assets/161158238/bbc4d848-c86b-49c1-bb27-581057e14f70)

_PCA1 & PCA2 Scatter Plot_
![Screenshot 2024-05-31 at 4 17 56 PM](https://github.com/Enaud29/CryptoClustering/assets/161158238/0d23b78e-ad2e-47f5-8744-a4eedf550341)


#### References
Chat GPT, Kalvin Anlgin, Solutions examples from class.
