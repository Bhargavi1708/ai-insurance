# GigSecure – AI-Powered Income Protection for Gig Workers

## 👥 Team Details
-Team Name: hacksphere

-Members:
 - PRASUNAMBA MUTNURI  
 - SRINADH KANCHARLA  
 - TEJASRI REDDY PADALA
 - BHARGAVI REDDAM

## 🎥 Demo Video
[Watch Here](video-link)

## 📌 Problem Statement

Quick commerce delivery workers associated with platforms like Zepto, Blinkit, and Instamart function in highly time-sensitive and hyperlocal settings. Their income is directly linked to the consistent availability of orders within limited delivery areas.

However, unexpected disruptions such as heavy rainfall, flooding, extreme temperatures, pollution, and zone shutdowns can severely impact or completely stop delivery operations. As a result, workers experience a 20–30% loss in their weekly earnings without any form of financial support.

At present, there is no system in place to compensate gig workers for income loss caused by these uncontrollable external factors.

## 👤 Target Persona

<img width="1202" height="712" alt="Target Persona" src="https://github.com/user-attachments/assets/b22917ca-44f5-47f5-8a73-4541c2acc32c" />

## 💡 Proposed Solution

The platform is an AI-driven income protection system built to safeguard delivery workers from earnings loss caused by external disruptions.

Unlike conventional insurance models:

 - No claim submission required
 - No documentation process
 - No delay in payouts

The platform:

 - Continuously tracks real-time conditions
 - Identifies disruptions automatically
 - Initiates instant payouts

## 🧱 Tech Stack

- Frontend: React.js  
- Backend: Node.js, Express.js  
- Database: MongoDB  
- AI/ML: Python, Flask/FastAPI, scikit-learn  
- APIs: OpenWeather API, AQI API, Traffic API  
- Monitoring: Cron Jobs / Scheduler  
- Payments: Razorpay (Test Mode)  
- Tools: GitHub, Postman, VS Code  

---

## 🏗️ System Architecture  

<img width="1328" height="727" alt="System Architecture" src="https://github.com/user-attachments/assets/77e5bbba-9061-43f8-a64a-1b007f494723" />

---

## 🚀 Key Highlights

- Hyperlocal Intelligence
Identifies disruptions at a micro-zone level (2–3 km), enabling precise detection of localized issues such as waterlogging and traffic congestion.

- Dynamic Income-Based Payouts
Estimates expected earnings and compensates for actual income loss rather than offering fixed payouts.

- Automated Claim Processing
End-to-end automated system that handles detection, validation, and payouts instantly without any manual involvement.

- Intelligent Trust Scoring
Leverages behavioral patterns and activity data to identify and prevent fraudulent claims.

## 🔐 Trust Score-Based Fraud Detection

Each user is assigned a dynamic trust score based on:

- Location consistency  
- Activity patterns  
- Claim history  

This enables intelligent and reliable fraud prevention.

## ⚙️ System Workflow
~~~

User Onboarding
      ↓
AI-Based Risk Profiling & Pricing
      ↓
Weekly Policy Activation
      ↓
Real-Time Monitoring (Weather, AQI, Orders)
      ↓
Disruption Detection (Zone-Level)
      ↓
Automatic Claim Initiation
      ↓
Fraud Verification (Trust Score + GPS)
      ↓
Instant Payout (UPI)
~~~

## 💰 Weekly Pricing Model

~~~
User Data (Location + Activity)
↓
Base Premium (₹20/week)
↓
Risk Adjustments
(Flood +₹5 | Pollution +₹3 | Traffic +₹2)
↓
AI-Based Pricing Engine
(Weather + Historical Trends + Patterns)
↓
Final Premium (₹25–₹35/week)
↓
Coverage Allocation (₹500 – ₹1500/week)
~~~

## ⚡ Parametric Triggers

The system uses predefined measurable conditions to trigger payouts automatically:

| Disruption    | Condition              | Action      |
| ------------- | ---------------------- | ----------- |
| Heavy Rain    | Rainfall > 50 mm       | Auto payout |
| Heatwave      | Temperature > 42°C     | Auto payout |
| Order Drop    | < 40% of normal orders | Auto payout |
| Pollution     | AQI > 300              | Auto payout |
| Zone Shutdown | No activity in zone    | Auto payout |


## 🤖 AI/ML Integration

1. Risk Assessment Model
    
   Predicts the probability of disruptions using location, weather, and historical data

2. Dynamic Pricing Engine
   
   Adjusts weekly premiums based on predicted risk levels

3. Income Prediction Model

   Estimates expected earnings and calculates actual income loss

4. Fraud Detection System

   Identifies anomalies using machine learning to prevent misuse

## 🛡️ Fraud Detection Strategy

- GPS-based location validation
- Activity consistency monitoring
- Duplicate claim prevention
- Trust score evaluation
- ML-based anomaly detection

## 🛡️ Advanced Anti-Spoofing & Security

To handle GPS spoofing and coordinated fraud attempts, the system uses a multi-layered behavioral intelligence approach.

## 🔍 Real vs Fake Detection

- Movement pattern analysis vs static spoofed locations
- Delivery activity verification
- Behavioral consistency tracking

## 📊 Data Signals Used

- GPS trajectory (not just static location)
- Order activity and timestamps
- App usage behavior
- Network anomaly detection
- Zone-level disruption correlation

## 🤖 AI-Based Defense

- Isolation Forest for anomaly detection
- Dynamic trust scoring system
- Fraud pattern recognition

## ⚖️ Risk-Based User Handling

- Auto-approval for high trust users
- Soft verification for medium-risk cases
- Rejection for high-risk activities

## 🧠 Anti-Collusion Detection

- Identifies clustered fake claims
- Detects synchronized behavior patterns
- Monitors sudden spikes within the same zone

Prevents large-scale coordinated fraud attacks such as spoofing rings

## 🧭 Customer Journey
~~~
Awareness
      ↓
Onboarding
      ↓
AI Profiling
      ↓
Plan Selection
      ↓
Activation
      ↓
Monitoring
      ↓
Disruption
      ↓
Automatic Claim
      ↓
Payout
      ↓
Dashboard
~~~

## 🎯 Conclusion

This platform redefines traditional insurance by introducing a proactive, AI-driven income protection system tailored for quick commerce delivery workers.

By combining hyperlocal risk analysis, real-time monitoring, and a fully automated claim process, it ensures immediate financial support during disruptions, improving stability and reliability for gig workers.






















