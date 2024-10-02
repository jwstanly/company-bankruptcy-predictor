* JW Note: It looks like Github pages also supports hosting markdown we could also work in files like this readme if we didn't wanna do HTML 

# Company Bankruptcy Predictor

A machine learning model for predicting company bankruptcies based on financial data and risk factors

**Teammates:** Max Boggus, Danny Long, Blake Rodgers, John Wright Stanly, Drew Verzino 

## Proposal

### Introduction / Background
Assessing the risk of bankruptcy is crucial for companies, impacting not only their financial stability but also their employees, stakeholders, and investors. Research has shown that ML can be a helpful tool in accurately determining risk, performing up to 35% better than traditional models in one study on North American firms from 1985 to 2013 [1]. Still, there are limiting factors with ML based predictions, like an overlapping feature space between financial variables of bankrupt companies [2]. In our project, we will use accounting data from American public companies listed on the NYSE and NASDAQ from 1999 to 2018. Some features, like EBITDA, Market Value, Total Assets and others will be used to make predictions of which companies went bankrupt during this period. [DATASET LINK](https://www.kaggle.com/datasets/utkarshx27/american-companies-bankruptcy-prediction-dataset)

### Problem Definition
Unexpected corporate bankruptcies can be problematic for stakeholders, as they can lead to substantial financial losses and job insecurity. Despite advancements in predictive modeling, many existing methods lack accuracy and may fail to capture the complexities of what actually causes or indicates risk of bankruptcy. The inability to accurately predict bankruptcy leaves investors vulnerable to unforeseen market volatility and instability. Therefore, there is a pressing need for more effective solutions that leverage traditional and more cutting-edge machine learning techniques to enhance prediction accuracy. By improving bankruptcy prediction models, we can better inform stakeholders and at-risk companies, which contributes to a more resilient financial ecosystem.

### Methods
To address the bankruptcy prediction problem, a variety of machine learning techniques and algorithms will be needed. First, we will consider dimensionality reduction techniques like Principal Component Analysis (PCA) to remove noise and redundancy in our data in hopes of addressing overfitting. Our primary prediction model will most likely be based on logistic regression, support vector machines (SVMs), random forests, or a combination of the three. Logistic regression will help us capture linear relationships and insights to the influence of each feature [1]. SVMs will help us capture subtle differences between bankrupt and non-bankrupt companies due to their effectiveness in higher-dimensional space [3]. Random forests will help us capture non-linear relationships of each feature, highlighting each feature's importance to bankruptcy. This combination of models, along with PCA, will hopefully offer a balanced approach to predicting bankruptcy and understanding the features that contribute to it.


### Potential results and Discussion
We will potentially evaluate the performance of our predictions using a variety of key quantitative metrics. These will include accuracy, precision, recall, F1-score, and ROC-AUC score. Accuracy will provide a measure of overall performance while precision and recall will help us understand the potential tradeoff between false positives and false negatives. This will be important due to the potentially imbalanced nature of bankruptcy data. Additionally, F1-score will be used to evaluate the model’s effectiveness in handling class imbalance. Also, the ROC-AUC score will help us evaluate the model’s ability to discern between bankrupt and non-bankrupt firms over different threshold settings. Our goal is to create a robust model capable of accurately predicting bankruptcy while minimizing false results. Ideally, our model will achieve F1 and ROC-AUC scores of at least 0.8 respectively.

### References
[1] F. Barboza, H. Kimura, and E. Altman, "Machine learning models and bankruptcy prediction," Expert Systems with Applications, vol. 83, pp. 405-417, 2017.
<br>
[2] S. Shetty, M. Musa, and X. Brédart, "Bankruptcy prediction using machine learning techniques," Journal of Risk and Financial Management, vol. 15, no. 1, p. 35, 2022. doi: 10.3390/jrfm15010035.
<br>
[3] N. Wang, "Bankruptcy prediction using machine learning," Journal of Mathematical Finance, vol. 7, pp. 908-918, 2017. doi: 10.4236/jmf.2017.74049.

## Gantt Chart

## Contribution Table

<table>
   <thead>
      <tr>
         <th>Task</th>
         <th>Owner</th>
      </tr>
   </thead>
   <tbody>
    <tr>
         <td>Github Pages Setup</td>
         <td>John Wright Stanly</td>
      </tr>
      <tr>
         <td>Proposal Write Up</td>
         <td>Drew Verzino, Danny Long</td>
      </tr>
      <tr>
         <td>Gantt Chart and Contribution Table</td>
         <td>Name</td>
      </tr>
      <tr>
         <td>Google Slides</td>
         <td>Name</td>
      </tr>
      <tr>
         <td>Final Video</td>
         <td>Name</td>
      </tr>
   </tbody>
</table>

## Presentation
