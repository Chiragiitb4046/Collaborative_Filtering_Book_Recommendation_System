📚 Book Recommendation System

Recommendation systems are one of the most widely used applications of Machine Learning. They personalize user experiences by tailoring content, boosting engagement, and driving revenue for businesses.

🔹 Types of Recommendation Systems
1. Content-Based Filtering

Recommendations are based on a user’s past likes/dislikes and item features (e.g., author, publisher, genre).

Items are considered “similar” if their features match items the user has enjoyed before.

2. Collaborative Filtering

Recommendations rely only on user-item interactions (ratings), without using item attributes (author, genre) or user attributes (age, gender, location).

Two main approaches:

(a) Memory-Based

Uses the full user-item rating matrix to compute similarity.

User-based CF: Finds users with similar rating patterns. If User A is similar to User B, items liked by B are recommended to A.

Item-based CF: Finds items that are rated similarly by users. If a user liked Item X, they are likely to like Item Y (similar to X).

(b) Model-Based

Builds a predictive model from user-item interactions (e.g., matrix factorization, clustering, or neural networks).

More scalable and efficient for large datasets.

🔹 Project Objective

This project implements a Collaborative Filtering-based Book Recommendation System using both:

Memory-Based Approach (User- and Item-based Nearest Neighbors)

Model-Based Approach (for scalability and speed)

🔹 Dataset

Book-Crossing Dataset by Cai-Nicolas Ziegler (link
)

Users: 278,858 records

Books: 271,379 records

Ratings: 1,149,780 records

🔹 Tech Stack

Python (Pandas, NumPy, Scikit-learn)

Streamlit (for interactive UI)

Joblib (for model saving/loading)

🔹 Features

✅ User-based Collaborative Filtering (using cosine similarity & nearest neighbors)
✅ Item-based Collaborative Filtering
✅ Model-based filtering for efficiency
✅ Interactive Streamlit app for real-time recommendations
