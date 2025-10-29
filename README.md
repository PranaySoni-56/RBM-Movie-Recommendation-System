🎬 RBM Movie Recommendation System
📄 Description

A collaborative filtering-based movie recommendation system using a Restricted Boltzmann Machine (RBM). It predicts user preferences from historical ratings by learning hidden feature patterns, enabling accurate and personalized movie suggestions.

🚀 Features
Learns latent features from user–movie interactions
Predicts unseen movie ratings with RBM
Uses collaborative filtering for personalization
Evaluates model performance using RMSE

🧠 Model Architecture
Algorithm: Restricted Boltzmann Machine (RBM)
Type: Unsupervised probabilistic neural network
Training: Contrastive Divergence algorithm
Evaluation Metric: Root Mean Square Error (RMSE) ≈ 14.87

📊 Workflow
Data Preprocessing — Convert raw rating data into user–movie matrix
RBM Initialization — Define visible and hidden layers
Training — Update weights and biases using Contrastive Divergence
Prediction — Estimate unseen movie ratings
Evaluation — Compute RMSE for accuracy

🛠️ Technologies Used
Python
NumPy, Pandas
Scikit-learn
Math, Random

📁 Project Structure
RBM_Movie_Recommendation_System/
│
├── RBM_Movie_Recommendation_System.ipynb   # Main Jupyter Notebook


📈 Results
Achieved RMSE ≈ 14.87
Successfully predicts user preferences based on learned latent factors.

💡 Future Improvements
Integrate Autoencoders for hybrid recommendation
Deploy as a Flask or Streamlit web app
Add movie metadata visualization for better insights

👨‍💻 Author
Pranay Soni
Data Science & Machine Learning Enthusiast
