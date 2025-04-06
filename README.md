# customer_segmentation
University project: segmentation of insurance company customers

This project aimed to segment insurance policyholders to help better assess risk and claim behavior. The dataset included over 413,000 observations with details like driver age, car age, exposure period, and claim amounts. After extensive data cleaning and transformation—including handling missing values, encoding categorical variables, and aggregating duplicate policies—the analysis moved to clustering.

Using principal component analysis (PCA) and the elbow method, the team identified three optimal customer segments via the K-means algorithm. The segments included two no-claim groups (one of older drivers with long coverage periods, and another of younger, newly insured drivers), and one high-risk group with frequent and severe claims.

An alternative clustering method, DBSCAN, was also applied, which successfully identified not only core clusters but also outlier profiles with extremely high claim amounts. This helped in refining risk profiles and revealed valuable insights.
