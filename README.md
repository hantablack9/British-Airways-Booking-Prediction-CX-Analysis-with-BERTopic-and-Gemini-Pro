# British Airways Booking Prediction, CX Analysis with BERTopic and-Gemini Pro
Task 1: Identify and Analyze Negative Reviews with Sentiment Analysis, Topic Modeling and LLM fine-tuning.

Task 2: Based on previous booking data, customer behviours and route information, build a machine learning model to predict booking completion. 

---
## Task 1: **Identify and Analyze Negative Reviews with Sentiment Analysis, Topic Modeling and LLM fine-tuning.**
British Airways CX Analysis is an assessment of the customer experience provided by British Airways, based on user reviews and independent research, with two main objectives:
- Identify opportunities for enhancing customer satisfaction
- Analyze customer feedback and data and provide recommendations for enhancing the overall CX

### Task 1 Workflow
![image](https://github.com/hantablack9/British-Airways-Booking-Prediction-CX-Analysis-with-BERTopic-and-Gemini-Pro/assets/101001907/464e1633-a858-4ff9-9ef2-3ca379a35e1b)


**Market Trends and Competition**

![image](https://github.com/hantablack9/British-Airways-Booking-Prediction-CX-Analysis-with-BERTopic-and-Gemini-Pro/assets/101001907/2cf98eaf-81db-427e-a85c-086621b2a9b8)

**Sentiment Analysis across travel classes for British Airways**

![image](https://github.com/hantablack9/British-Airways-Booking-Prediction-CX-Analysis-with-BERTopic-and-Gemini-Pro/assets/101001907/0fe9ea74-ab2d-4068-8b52-f23aa5517d7a)

![image](https://github.com/hantablack9/British-Airways-Booking-Prediction-CX-Analysis-with-BERTopic-and-Gemini-Pro/assets/101001907/aa048832-7915-44a9-bf64-bcff3a02e6f5)

**Identify Domain words**
1. Some common tokens (such as ‘flight’, ‘ba’) spuriously increase sentence similarity (cosine)
2. Stop words, domain words and other “non-informative” tokens discarded to improve discriminative power of topic model
3. HDBSCAN clustering performance improves, by clustering around less-frequent, topic-specific tokens

![image](https://github.com/hantablack9/British-Airways-Booking-Prediction-CX-Analysis-with-BERTopic-and-Gemini-Pro/assets/101001907/38de1537-0e11-4d49-a4e5-a1cff4ede958)

**Topics detected with BERTopic 
& Google Gemini Pro Scraping and Analytics Notebooks**

![image](https://github.com/hantablack9/British-Airways-Booking-Prediction-CX-Analysis-with-BERTopic-and-Gemini-Pro/assets/101001907/e94bf011-54fd-4bea-8a29-ea3bfb2b0c4d)

**Visualize Inter-Topic Distance with DataMapPlot**
![image](https://github.com/hantablack9/British-Airways-Booking-Prediction-CX-Analysis-with-BERTopic-and-Gemini-Pro/assets/101001907/22d6c549-520e-42cd-9e06-aa6fd790c221)
