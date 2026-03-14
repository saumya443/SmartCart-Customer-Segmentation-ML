🚀 SmartCart: Customer Segmentation using Agglomerative Clustering
📌 Project Overview
SmartCart ek multi-national e-commerce platform hai jo generic marketing strategies ki wajah se apne high-value customers ko retain nahi kar pa raha tha. Is project mein maine Unsupervised Machine Learning ka use karke customers ko 4 distinct groups mein segment kiya hai taaki marketing ko personalize kiya ja sake.

📝 Problem Statement
Generic marketing approach ki wajah se SmartCart ko niche di gayi problems ho rahi thin:

High-value customers ko retain karne ke opportunities miss ho rahi thin.

Churn-prone (platform chhodne wale) users ka pata nahi chal raha tha.

Marketing budget sahi jagah spend nahi ho raha tha.

🛠️ Tech Stack Used
Language: Python

Environment: Jupyter Lab

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Algorithms: Agglomerative Clustering (Primary), KNN (for Comparison)

📊 Dataset Details
Records: 2240

Features: 22 (Income, Recency, Spending on Wine/Fruits/Meat, Web Visits, etc.)

📉 Key Steps Performed
EDA & Visualization: Correlation heatmap, Pair plots aur distribution plots se data patterns samjhe.

Preprocessing: Null values fix kiye, outliers remove kiye aur StandardScaler se data normalize kiya.

Feature Engineering: Total Spending aur Age jaise naye columns banaye.

Clustering: Agglomerative Clustering ka use kiya. Dendrogram ke basis par 4 optimal clusters select kiye.

💡 Results & Business Insights
Maine customers ko 4 groups mein baanta:

Cluster 0 (Elite): High spending aur loyal customers.

Cluster 1 (At-Risk): Jo pehle active the par ab nahi aa rahe.

Cluster 2 (Deal Seekers): Jo sirf discounts ka wait karte hain.

Cluster 3 (New/Low Engagement): Naye users jinhe engagement ki zaroorat hai.
