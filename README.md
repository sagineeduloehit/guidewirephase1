# 🛡 GigGuard — AI-Powered Parametric Income Insurance for E-Commerce Delivery Partners

> Guidewire DEVTrails 2026 | Phase 1 — Ideation & Foundation  
> Persona: E-Commerce Delivery Partners (Amazon / Flipkart)

---

## 📌 Table of Contents

1. [The Problem](#the-problem)
2. [Our Solution](#our-solution)
3. [Persona & Scenarios](#persona--scenarios)
4. [Application Workflow](#application-workflow)
5. [Weekly Premium Model](#weekly-premium-model)
6. [Parametric Triggers](#parametric-triggers)
7. [Platform Choice](#platform-choice-web-vs-mobile)
8. [AI/ML Integration Plan](#aiml-integration-plan)
9. [Tech Stack](#tech-stack)
10. [Development Plan](#development-plan)
11. [Adversarial Defense & Anti-Spoofing Strategy](#adversarial-defense--anti-spoofing-strategy)
12. [What's Next](#whats-next)

---

## 🧩 The Problem

India's e-commerce delivery ecosystem — powered by Amazon Flex, Flipkart Ekart, and similar platforms — relies on millions of gig workers earning per delivery.

These workers face a **critical financial vulnerability**:

- External disruptions (weather, curfew, pollution)  
- No employer protection  
- No income fallback  

Even **2–3 lost days = 30–40% income loss**, with **zero compensation**.

👉 GigGuard solves this.

---

## 💡 Our Solution

GigGuard is an **AI-powered parametric income insurance platform** designed for gig delivery workers.

### Key Capabilities

- ✅ Automated coverage for income loss  
- ✅ Zero-touch claims (no manual filing)  
- ✅ Weekly subscription model  
- ✅ AI-driven dynamic pricing  
- ✅ Multi-layer fraud detection  
- ✅ Instant payouts (UPI-enabled)  

> ⚠️ Scope: Covers **income loss only** — not health, vehicle, or accident claims.

---

## 👤 Persona & Scenarios

### 🎯 Target Persona

| Attribute | Details |
|----------|--------|
| Worker Type | Amazon Flex / Flipkart Ekart |
| Earnings | ₹4,200 – ₹7,000/week |
| Work Pattern | 6–10 hrs/day |
| Risk | Lost work hours due to disruptions |

---

### 🌧 Scenario 1 — Extreme Rainfall

- 120mm rainfall → deliveries halted  
- Worker loses ₹800/day  

✅ GigGuard:
- Detects IMD alert  
- Auto triggers payout  
- ₹680 credited within 2 hours  

---

### 🚫 Scenario 2 — Curfew

- Section 144 imposed  
- Worker cannot operate  

✅ GigGuard:
- Detects government alert  
- Pays 80% of daily income  

---

### 🔥 Scenario 3 — Heatwave

- Temperature ≥ 47°C  
- Shift cancelled  

✅ GigGuard:
- Detects heat threshold  
- Pays proportional loss  

---

## 🔄 Application Workflow

### Flow Steps

1. **Onboarding**
   - Aadhaar + PAN (KYC)
   - Select zone

2. **Risk Profiling**
   - AI assigns risk score

3. **Policy Activation**
   - Weekly premium via UPI

4. **Monitoring**
   - APIs check disruptions every 15 mins

5. **Claim**
   - Auto-trigger (no user action)

6. **Payout**
   - Instant UPI transfer

---

## 💰 Weekly Premium Model

### Why Weekly?
- Workers earn weekly  
- Matches real cash flow  

---

### 📊 Plans

| Plan | Premium | Coverage |
|------|--------|----------|
| Basic | ₹49 | ₹700 |
| Standard | ₹79 | ₹1400 |
| Full | ₹109 | ₹2800 |

---

### 🧮 Formula

---

### 💸 Payout Logic

| Severity | Payout |
|----------|--------|
| Full | 100% |
| Partial | 60% |
| Minor | 30% |

---

## ⚡ Parametric Triggers

| Trigger | Source | Condition |
|--------|--------|----------|
| Rainfall | IMD | ≥ 64.5mm |
| Heatwave | IMD | ≥ 45°C |
| AQI | CPCB | ≥ 401 |
| Flood | Municipal | Alert |
| Curfew | Govt/News | Verified |

👉 Trigger based on **pincode cluster (NOT GPS)**

---

## 🌐 Platform Choice (PWA)

### Why PWA?

- No install required  
- Works on low-end phones  
- Share via WhatsApp  
- Faster deployment  

---

## 🤖 AI/ML Integration Plan

### 1. Risk Scoring
- Model: XGBoost  
- Output: Risk Score (0–100)

---

### 2. Fraud Detection
- Model: Isolation Forest  
- Detects anomalies using multi-signal data  

---

### 3. Forecasting
- Model: Prophet  
- Predicts future claims  

---

## 🧰 Tech Stack

| Layer | Tech |
|------|-----|
| Frontend | React + Tailwind |
| Backend | FastAPI |
| DB | PostgreSQL |
| ML | scikit-learn, XGBoost |
| APIs | Weather, AQI |
| Payments | Razorpay |

---

## 🚀 Development Plan

### Phase 1 ✅
- Problem research  
- Pricing model  
- Triggers  
- README  
- Anti-fraud strategy  

---

### Phase 2
- Backend APIs  
- ML model  
- UI dashboard  

---

### Phase 3
- Fraud detection system  
- Predictive analytics  
- Full demo  

---

# 🛡 Adversarial Defense & Anti-Spoofing Strategy

## 🚨 Problem

500+ workers spoof GPS → fake claims → drain system.

👉 Solution: **Multi-Signal Trust Engine**

---

## 🎯 1. Real vs Fake Detection

### Real Worker
- Active before disruption  
- Stops working naturally  
- Sensor + network consistent  

### Fraud Worker
- No activity  
- Fake GPS jumps  
- Home WiFi + no movement  

---

## 📡 2. Multi-Signal Data

| Signal | Fraud Indicator |
|-------|----------------|
| GPS | Perfect/static |
| Network | Home WiFi |
| Motion | No movement |
| Activity | No delivery logs |
| Cluster | Sudden spike |

---

## 🧠 Trust Score

---

## 🔗 Fraud Ring Detection

- Same IP  
- Same device  
- Same time claims  
- Cluster spike  

👉 Uses **graph + anomaly detection**

---

## ⚖️ 3. Fair UX

| Level | Action |
|------|--------|
| Green | Instant payout |
| Yellow | Delayed check |
| Red | Manual review |

---

### 🟡 Grace Handling
- Network failure allowed  
- Delayed claim allowed  

---

### 🔁 Appeal System
- User can re-submit  
- Manual review available  

---

## 🧱 Final Defense

1. Signal Layer  
2. Behavior Layer  
3. AI Layer  
4. Network Layer  
5. Decision Layer  

---

## 🔥 Key Strength

- Not GPS dependent  
- Detects fraud rings  
- Protects genuine workers  

---

## 🔮 What's Next

- Real API integration  
- Advanced fraud ML  
- Dashboard analytics  
- Nationwide scaling  

---

## 📎 Conclusion

GigGuard builds a **financial safety net** for gig workers using:
- AI  
- Parametric insurance  
- Real-time automation  

---

**Team: DevStorm
Guidewire DEVTrails 2026 🚀
