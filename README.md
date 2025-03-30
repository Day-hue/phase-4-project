# 🎵 Neural Beats Music Recommender System

## 📖 Overview
Neural Beats is an AI-driven music recommender system that personalizes song recommendations based on user preferences and listening habits. Using deep learning techniques and collaborative filtering, Neural Beats enhances the music discovery experience for users.

---

## 🎯 Objectives
- Provide personalized music recommendations based on user preferences.
- Implement deep learning models for music genre classification and recommendation.
- Enhance user engagement by suggesting trending and similar songs.
- Improve recommendation accuracy using real-time user feedback.

---

## 🚀 Features
- **Personalized Recommendations**: Suggests songs based on past listening history.
- **Genre Classification**: Categorizes songs into different music genres using AI.
- **Trending Music Insights**: Displays popular and trending songs.
- **Collaborative Filtering**: Suggests songs based on similar artists.

---

## 🧠 Technologies Used
- **Programming Language**: Python
- **Machine Learning Framework**: TensorFlow 
- **Data Processing**: Pandas, NumPy

---

## 📊 Dataset
The dataset used for training the model consists of song metadata, user listening history, and audio features extracted from platforms like Spotify and Last.fm. Features include:
- **Song ID**
- **Artist**
- **Genre**
- **Tempo, Loudness, Danceability**
- **User ratings and play counts**

## Visualizations
### 1️⃣ Top 10 Most Popular Genres
![Top 10 Most Popular Genres](<Screenshot from 2025-03-31 00-01-11.png>)
**Key Insights**
- The dominance of pop genre in major mode suggests a widespread appeal for upbeat ​
- Genres like blues and jazz maintain a balanced mood representation while indie and electronic have a minor-mode popularity.

### 2️⃣ [Top 10 most popular Artists]
![Top 10 most popular Artists](<Screenshot from 2025-03-30 23-59-16.png>)
**Key Insights**
- All artists demonstrate very high popularity with scores nearly reaching 100, indicating widespread acclaim.​
- Sam Smith/Kim Petras lead the chart with the highest bar, showing their global recognition.

### 3️⃣ [Popularity of the Top 10 genres by mode]
![Popularity of the Top 10 genres by mode](<Screenshot from 2025-03-30 23-57-31.png>)
- Mainstream genres like K-pop dominate popularity charts. Unique genres like Indian and Emo retain niche yet loyal audiences.

---

## Conclusions
### 1. Top 10 Artists by Popularity  
Based on our analysis of **Spotify API data**, the **top 10 most popular artists** were:  

| **Rank** | **Artist(s)** | **Popularity Score** |
|---------|--------------|---------------------|
| 1️⃣ | Sam Smith; Kim Petras | 100.0 |
| 2️⃣ | Bizarrap; Quevedo | 99.0 |
| 3️⃣ | Manuel Turizo | 98.0 |
| 4️⃣ | Bad Bunny; Chencho Corleone | 97.0 |
| 5️⃣ | Bad Bunny; Bomba Estéreo | 95.0 |
| 6️⃣ | Joji | 94.0 |
| 7️⃣ | Beyoncé | 93.0 |
| 8️⃣ | Harry Styles | 92.0 |
| 9️⃣ | Rema; Selena Gomez | 92.0 |
| 🔟 | Luar La L | 91.0 |

- **Bad Bunny** appears **twice** in the top 5, showing his strong presence in popular music.  
- **Collaborations** between artists (e.g., **Sam Smith & Kim Petras, Bizarrap & Quevedo**) have **higher popularity scores**, indicating the influence of **featured artists**.  
- **A mix of genres** is represented, with pop, reggaeton, and hip-hop leading the charts.  
- **International influence** is evident, with artists from **Latin America, the U.S., and global pop scenes**.  

### 2. General Findings from the Data  

#### ✅ Popularity & Artist Influence  
- Our analysis revealed that **collaborations between artists** tend to have higher popularity scores (e.g., *Sam Smith & Kim Petras* and *Bizarrap & Quevedo*).  
- Certain artists like **Bad Bunny** appear multiple times, indicating **strong dominance in the industry**.  

#### ✅ Genre Diversity & Music Trends  
- The dataset includes a **wide variety of genres**, showing that recommendations should consider more than just popularity.  
- Some **less mainstream artists** still achieved high popularity, proving that emerging artists can attract large audiences.  

#### ✅ Audio Features & Music Similarity  
- Audio features like **danceability, energy, and tempo** showed strong correlations with genre and popularity.  
- Songs within **similar audio feature clusters** are likely to be perceived as related, justifying the use of **Autoencoders** to extract meaningful latent features.  

### 3. Interpretation of our model Results  
- The **Autoencoder effectively captured latent artist similarities**, transforming high-dimensional features into compact embeddings.  
- With an **MSE of 0.0748**, the model demonstrated **strong reconstruction ability**, preserving essential artist relationships.  
- The model allows for **efficient and scalable artist recommendations**, suitable for integration into streaming services.  

---

## Recommendations
**Improving Music Discovery**  
   - The model successfully groups artists with **similar audio characteristics**, promoting discovery beyond mainstream artists.  
   - Users will be introduced to **new artists aligned with their listening preferences**, increasing engagement.  

**Scalability & Efficiency**  
   - The low-dimensional embeddings from the **Autoencoder** make the system **faster and more scalable** than traditional similarity-based models.  
   - This approach is suitable for **large-scale music databases** and can be integrated into streaming platforms via an API.  

**Enhancing Recommendations with Additional Data**  
   - While the model captures **audio-based similarities**, incorporating **user listening behavior** could refine recommendations further.  
   - Future improvements could integrate **real-time user preferences** and **social listening patterns**.  

## Next Steps  
🎵 **Deploy & Monitor:** Implement the recommendation system and track user feedback.  
🎵 **Optimize Model Performance:** Experiment with different latent space dimensions to refine recommendations.  
🎵 **Enhance User Personalization:** Combine **content-based filtering** with **user interaction data** to improve artist discovery.  

---

## 🔧 Installation & Setup
1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/Neural_Beats.git
   cd Neural_Beats
   ```
---

## 📌 Usage
1. **Input your favorite artists**
2. **Receive music and artists recommendations tailored to your taste.**
3. **Provide feedback on recommendations to improve future suggestions.**

---

## 📊 Model Training
- **Preprocessing** of song metadata and audio features.
- **Training** collaborative filtering and deep learning models.
- **Evaluating models** using MSE.

---

## 🛠️ Future Enhancements
- **Real-time streaming recommendations**
- **Integration with multiple music platforms**
- **Support for multiple languages and regions**
- **Voice-based music search and recommendations**

---

## 🤝 Contributions
Contributions are welcome! Feel free to fork this repository, make improvements, and submit a pull request.

---

## 📬 Contact
For any questions or feedback, feel free to reach out at our WhatsApp group [Group 4](https://chat.whatsapp.com/Ch73ixjS72aGvwcNBXXqXb).

