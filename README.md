# 🎮 Video Game Recommendation System

This project develops a **recommendation system for video games** using sales, ratings, and metadata such as platform, genre, and publisher.  
The notebook combines **exploratory data analysis (EDA)**, data preprocessing, and recommendation algorithms to suggest games to players.

---

## ⚙️ Project Workflow

1. **Data Preparation**  
   - Loaded dataset containing sales, ratings, and game metadata.  
   - Fixed data types (e.g., `User_Score`) and handled missing values.  
   - Treated outliers using **Winsorization**.  

2. **Exploratory Data Analysis (EDA)**  
   - Analyzed regional sales trends (NA, EU, JP, Global).  
   - Reviewed platform and genre popularity.  
   - Explored relationships between **critic scores, user scores, and sales**.  

3. **Recommendation System**  
   - Built a **content-based recommendation system** using similarity of features (genre, rating, platform).  
   - Incorporated user and critic scores for ranking recommendations.  
   - Suggested top-N games for players based on preferences.  

---

## 📈 Results and Conclusion

- The system successfully recommends games based on **genre preferences, ratings, and sales trends**.  
- Popular genres such as **Action and Sports** dominated recommendations, while niche genres like RPGs appeared for specific regions.  
- The approach demonstrates how game metadata can support **personalized recommendation engines**.
