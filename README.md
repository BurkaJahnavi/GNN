❖	PREDICTION OF CORN YIELD WITH ATTRIBUTE-MISSING DATA VIA GNNS

📌 Overview

This project leverages Graph Neural Networks (GNNs) to predict corn yield from datasets with attribute-missing data. By capturing complex relationships between environmental factors and crop varieties, the model provides accurate yield forecasts even with incomplete information.

Problem Statement:

Agricultural datasets often contain missing or incomplete attributes such as:

-Soil moisture

-Humidity

-Sunlight hours

-Crop variety

-Pesticide usage

After imputing missing data (e.g., using GANs), accurate yield prediction becomes a challenge due to the complex interdependencies among features. GNNs are used here to model these relationships effectively.

Methodology:

Built a GNN model using PyTorch Geometric (or other GNN frameworks) in Google Colab.

Constructed graphs where nodes represent data samples and edges encode similarity or spatial relationships.

Trained the model on imputed datasets and evaluated prediction performance using standard regression metrics.

Technologies Used:

-Google Colab

-Python

-PyTorch / PyTorch Geometric

-Pandas, NumPy

-Matplotlib / Seaborn

Results:

Achieved improved yield prediction accuracy compared to traditional regression methods.

Demonstrated robustness in handling attribute-missing data scenarios.

Visualized predicted vs actual yields to validate model performance.

How to Run:

1)Open the project notebook in Google Colab

2)Install required libraries (e.g., torch, torch_geometric)

3)Upload your dataset or use the provided one

Run the notebook sequentially to preprocess data, build graphs, train the model, and evaluate predictions

 Entire pipeline runs in the cloud using Google Colab.

Future Work:

-Integrate real-time environmental data and sensor readings.

-Generalize the GNN model for other crops and multi-location datasets.

-Combine with GAN-imputed data for enhanced prediction accuracy.

 Colab Notebook
 
https://colab.research.google.com/drive/19YcmahKuCjVKXrG-DhIkoUioHOoM6G7m?usp=sharing

🧑‍💻 Author

Burka Jahnavi

📧 burkajahnavi@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/jahnavi-burka-699082293?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app

