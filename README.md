# Justin Cox
Machine Learning Engineer | Data Scientist

I build machine learning systems and deploy them as production APIs using Python and AWS.

---

## 🚀 Current Focus

- Machine Learning Engineering  
- Model Deployment  
- Predictive Modeling   

---

## ⭐ Featured Projects

### 🚲 **Citi Bike Availability Prediction Pipeline**

End-to-end machine learning pipeline predicting **low dock availability (≤10% capacity)** at Citi Bike stations using real-time station data, with **scheduled ingestion, weekly retraining, and AWS deployment**.

**Key Features:**

- Time-series feature engineering using grouped station snapshot data  
- Station-level features including capacity, location, and transit proximity  
- Temporal features including hour-of-day and weekday usage patterns  
- Automated weekly retraining workflow using fresh operational data  

**Models:**

- Logistic Regression  
- Random Forest  
- XGBoost  
- Neural Network (TensorFlow, experimental)  

**Deployment:**

- FastAPI REST API  
- Docker container  
- AWS (S3, Lambda, EventBridge, CodeBuild, ECR, App Runner)  

🔗 [**GitHub Repo**](https://github.com/jac6779/citi-bike-prediction)  

🔗 [**Live FastAPI Docs**](https://er8i8uv8hc.us-east-1.awsapprunner.com/docs#/default/predict_predict_post)

---

### 🏠 Brooklyn Home Price Prediction API
End-to-end machine learning system for predicting Brooklyn residential property prices using NYC open housing sales data, deployed as a production-ready API with LLM-powered natural language input.

**Key Features:**
- Geospatial feature engineering (KD-tree nearest subway distance, proximity indicators)
- Log-transformed target + engineered property features for price stability
- Robust preprocessing pipeline with categorical encoding + feature scaling
- Structured input pipeline for both programmatic and natural language queries

**Models:**
- XGBoost (primary production model)
- ElasticNet (regularized baseline for interpretability)
- OLS regression (statistical validation & feature significance)

**Deployment:**
- FastAPI REST API with validated input schema
- LLM integration via OpenAI API for natural language → structured prediction inputs
- Dockerized service deployed on AWS EC2 behind an Application Load Balancer
- Interactive Swagger /docs endpoint for real-time inference

**Highlights:**
- Supports both structured JSON inputs and user-friendly prompt-based predictions
- Designed as a production-style ML service with clear separation of training, preprocessing, and inference pipelines
- Emphasizes interpretable metrics (MAE) aligned with real estate use cases

🔗 [**GitHub Repo**](https://github.com/jac6779/brooklyn-home-sales-llm)  

🔗 [**Live FastAPI Docs**](https://zv8bfybrkn.us-east-1.awsapprunner.com/docs#/) 

---

### 🏙 NYC 311 Service Request Prediction API
Production-style ML system predicting NYC 311 complaint resolution outcomes.

**Key Features:**
- End-to-end ML pipeline (preprocessing + model)
- Real-time inference via REST API
- Interactive Swagger documentation
- Containerized deployment

**Tech Stack:**
- FastAPI  
- Docker  
- scikit-learn Pipeline  
- AWS App Runner  
- Amazon ECR  

🔗 [**GitHub Repo**](https://github.com/jac6779/nyc-311-ml-api)  

🔗 [**Live FastAPI Docs**](https://dyypyhmjdv.us-east-1.awsapprunner.com/docs)  

🔗 [**Polished HTML frontend powered by a FastAPI backend**](https://d3oxki74u11f6.cloudfront.net)  

---

### 📊 Marketing Performance Dashboard

**Overview**  
This project presents an interactive Tableau dashboard designed to analyze marketing performance across campaigns, channels, and audience segments. It enables quick KPI monitoring and supports data-driven decision-making.

**Key Features**  
- KPI tracking (Revenue, Impressions, CTR, Conversions)
- Campaign and channel performance comparison
- Audience segmentation insights
- Time-series trend analysis
- Interactive filtering for exploration

**Tools Used**  
- Tableau Public
- Data Visualization
- Marketing Analytics

🔗 **Live Dashboard**  
https://public.tableau.com/app/profile/justin.cox1489/viz/MarketingCampaignPerformanceOverview/Dashboard  

---

## 🧠 Skills

- Python
- Machine Learning
- FastAPI
- Docker
- AWS (S3, Lambda, EventBridge, Athena, ECR, App Runner, EC2, IAM, SageMaker, ECS)
- SQL
- Scikit-learn
- XGBoost
- TensorFlow

---

## 🔗 Connect

- LinkedIn: https://www.linkedin.com/in/justincox1
