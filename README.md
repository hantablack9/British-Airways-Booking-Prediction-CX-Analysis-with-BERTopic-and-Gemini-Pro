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

**Resolving CX challenges: Recommendations**

![image](https://github.com/hantablack9/British-Airways-Booking-Prediction-CX-Analysis-with-BERTopic-and-Gemini-Pro/assets/101001907/e6850559-1a77-4f43-8005-4ce48a449edb)

**Recommendations for BA Engineering and Analytics**
![image](https://github.com/hantablack9/British-Airways-Booking-Prediction-CX-Analysis-with-BERTopic-and-Gemini-Pro/assets/101001907/0e697371-768c-4dda-b4e2-5d6eb5c3a9f3)

# Sources
1. British Airways - statistics & facts https://www.statista.com/topics/5372/british-airways/#topicOverview
2. British Airways Plc: Competitors https://www.globaldata.com/company-profile/british-airways-plc/competitors/
3. How Much Airline Revenue Comes From Business Travelers? https://www.investopedia.com/ask/answers/041315/how-much-revenue-airline-industry-comes-business-travelers-compared-leisure-travelers.asp
4. British Airways Competitors https://www.comparably.com/companies/british-airways/competitors
5. British Airways plans to make up to 12,000 staff redundant. BA boss says more than one in four jobs could go as coronavirus causes global collapse in air travel https://www.theguardian.com/business/2020/apr/28/british-airways-plans-to-make-up-to-12000-staff-redundant
6. British Airways Plc's worldwide revenue from FY 2010 to FY 2022 (in million GBP) https://www.statista.com/statistics/264296/british-airways-worldwide-revenues-since-2006/?kw=&crmtag=adwords&gclid=CjwKCAiAiP2tBhBXEiwACslfnrguU6XsRAXQ25JuO3AEwckyFTHvHdCD9DcUI-8Pr2XRFdLSbYCdXRoCJaEQAvD_BwE
7. Airport Operational Performance and Its Impact on Airline Cost https://www.researchgate.net/publication/300299980_Airport_Operational_Performance_and_Its_Impact_on_Airline_Cost
8. Individual Annual Financial Report 2022, IAG https://www.iairgroup.com/investors-and-shareholders/financial-reporting/annual-reports/
9. Andrijana Bogdanovska Djurovic "Transformational Change or Not?: The Case of British Airways (2008-2010)" https://papers.ssrn.com/sol3/papers.cfm?abstract_id=1947296
10. Alderighi et al. "A case study of pricing strategies in European airline markets: The London – Amsterdam route" https://www.sciencedirect.com/science/article/abs/pii/S0969699711000226
11. Gov, S.A. and Dergisi, Y.B. (2020) "Strategic Alliances in airline business: Comparison of Skyteam, Oneworld, Star Alliance groups," [Preprint]. Available at: https://doi.org/10.35408/comuybd.629382.
12. Graham, A. (2020) "U.K. regional airports" Air Transport and Regional Development Case Studies , pp. 64-85. Available at: https://doi.org/10.4324/9781003092063-5.
13. Havlovic, S.J. (2020) "European works councils in the airline industry," Strategic Innovative Marketing and Tourism , pp. 1-6. Available at: https://doi.org/10.1007/978-3-030-36126-6_1
14. Light, L. (2020) British Airways needs to revitalize its Brand , Forbes . Forbes Magazine. Available at: https://www.forbes.com/sites/larrylight/2020/08/14/british-airways-needs-to-revitalize-its-brand/?sh=6eaeef0d747e

