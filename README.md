# University Classification - Private VS Public K-Means

## Description
This code is designed to classify US colleges into two categories: Private and Public, based on the dataset from the 1995 issue of US News and World Report. The dataset contains various metrics related to 777 colleges, including institution type, application figures, student demographics, costs, faculty qualifications, and other institutional statistics.

The primary method used for this classification is K-Means Clustering, an unsupervised learning technique. The algorithm classifies data without having prior knowledge of the labels. Although the dataset provides labels (Private or Public), they are used only for evaluating the performance of the algorithm and not during the clustering process.

It's essential to note that while K-Means is typically used when data labels are unavailable, in this scenario, the labels are leveraged to gauge the algorithm's performance. However, this is unconventional for K-Means, and the resulting classification report and confusion matrix may not be representative of a real-world application of the algorithm.

## Code
The code begins by importing necessary libraries for data analysis, modeling, and plotting. It then reads the dataset, performs exploratory data analysis (EDA), and creates the KMeans model. The data is then scaled, and the model is evaluated using the provided labels.

This project serves as an experiment to understand the capabilities and limitations of the K-Means Clustering algorithm in classifying universities based on their characteristics.

[Code](Private_vs_Public_Universities.ipynb)

## License

This script is open-source and licensed under the MIT License. For more details, check the [LICENSE](LICENSE) file.
