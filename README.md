# SAS_text_mining
# Traffic Accident Severity Prediction & Text Analytics (SAS)

This repository contains an academic project by **Vrushali Ankit Patil** for the module *Data Mining and Text Analytics with Application in SAS*.  The project explores **UK road traffic accident data** and **tweets about accidents in Surrey**, applying **data mining, predictive modeling, and text analytics** using SAS Viya.

## 📖 Project Overview
The project is divided into four main tasks:

1. **Data Exploration & Cleaning**  
   - Handling missing values and outliers.  
   - Filtering error terms and imputing missing data.  
   - Balancing dataset for accident severity.  

2. **Predictive Modeling**  
   - Models used: Neural Network, Decision Tree, Logistic Regression.  
   - Evaluation with Lift curves, ROC curves, and Fit statistics.  
   - Neural Network emerged as the *champion model*.  

3. **Text Analytics of Tweets**  
   - Tweets related to accidents on **M25 & M23 motorways**.  
   - Term maps, word frequency analysis, and sentiment analysis.  
   - Findings: Negative sentiment dominates; “collision” and “M25” appear most frequently.  

4. **Decision-Maker’s Summary & Recommendations**  
   - Accident severity influenced by:  
     - Junction details  
     - Light conditions  
     - Day of week  
     - Number of vehicles  
     - Speed limit  
   - Recommendations for road safety campaigns, stricter speed enforcement, and targeted awareness on Thursdays/Fridays.

## 📊 Key Insights
- Most accidents are **slight severity**, often on **Thursdays**.  
- Accidents occur frequently in **daylight** and **fine weather conditions**.  
- Neural Network achieved the best performance (KS = **0.5630**).  
- Negative sentiment dominates Twitter discussions, especially around **M25** traffic and collisions.  
- Strong correlation between **traffic density** and **accident probability**.

## 🖼️ Visualizations
The following figures are included from the analysis
1. **Accident Severity Distribution**
<img width="429" height="157" alt="image" src="https://github.com/user-attachments/assets/b72797c5-ea09-4834-b4de-86af3c27afcc" />

2. **Correlation Matrix of Key Variables**
<img width="418" height="185" alt="image" src="https://github.com/user-attachments/assets/94adfaa8-e8f5-4465-be56-ec916559a7cc" />

3. **Missing Values Analysis**
<img width="452" height="180" alt="image" src="https://github.com/user-attachments/assets/b77c0d03-c577-4a31-be00-bba5c71fe17f" />

4. **Predictive Model Pipeline**
<img width="224" height="190" alt="image" src="https://github.com/user-attachments/assets/662dc59b-6dde-459a-a8f3-5bc0484ee63c" />

5. **Model Performance Comparison (ROC/Lift curves)**
<img width="458" height="176" alt="image" src="https://github.com/user-attachments/assets/d66afd42-f0e8-4efe-9933-aac67bb86737" />

<img width="482" height="233" alt="image" src="https://github.com/user-attachments/assets/25cc10a9-4b13-4177-b728-e3234f303bf8" />

<img width="431" height="232" alt="image" src="https://github.com/user-attachments/assets/00f9a1f9-cfc4-46d1-b656-4220a00c0bce" />

<img width="412" height="200" alt="image" src="https://github.com/user-attachments/assets/f8c3357d-fdad-4aee-bf3e-50ca55871d99" />

<img width="496" height="371" alt="image" src="https://github.com/user-attachments/assets/735581c9-2573-4a7c-83fb-ed4e87d94116" />

<img width="493" height="174" alt="image" src="https://github.com/user-attachments/assets/25e439af-6f9d-4dda-a2d6-cb5da7e5fb82" />

6. **Neural Network Architecture**
<img width="503" height="278" alt="image" src="https://github.com/user-attachments/assets/caa687c7-0ba3-45cc-9b56-024a11239945" />

7. **Decision Tree Diagram**
<img width="241" height="202" alt="image" src="https://github.com/user-attachments/assets/762301a2-b771-4ea9-b6dc-cef666ef5b85" />

8.  **Sentiment Distribution**
<img width="451" height="188" alt="image" src="https://github.com/user-attachments/assets/6d28a940-1c0d-4b32-a447-2c1867cdce71" />

# ✅ Conclusion

This project demonstrates the power of data mining and text analytics in SAS for understanding and predicting road traffic accident severity. Through structured data exploration, cleaning, and predictive modeling, it was shown that junction details, light conditions, number of vehicles, speed limits, and day of the week play a critical role in influencing accident outcomes. Among the models tested, the Neural Network consistently outperformed Decision Trees and Logistic Regression, making it the most reliable predictor of accident severity.
The text analytics of Surrey traffic-related tweets provided complementary insights. By extracting frequent terms, analyzing sentiment, and mapping concepts, it became clear that negative sentiment dominates online discussions, particularly around M25 collisions and heavy traffic conditions. This highlights the public’s perception of risk and reinforces the importance of traffic safety interventions.
Overall, the findings emphasize the need for targeted safety measures—including stricter monitoring at junctions, heightened awareness campaigns on high-risk days (like Thursdays and Fridays), and proactive communication with drivers during heavy traffic conditions. Combining structured accident data with unstructured social media insights offers a comprehensive view of road safety risks, providing valuable guidance for policymakers, law enforcement, and transportation authorities.















