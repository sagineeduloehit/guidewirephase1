# 🛡 SwiggyShield — AI-Powered Parametric Income Insurance for Swiggy Delivery Partners

> Guidewire DEVTrails 2026 | Phase 1 — Ideation & Foundation  
> Persona: Swiggy Food Delivery Partners

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

Swiggy delivery partners are the backbone of India’s food delivery ecosystem, earning on a per-order basis.

However, they face **unpredictable income loss** due to:
- Heavy rainfall / floods  
- Extreme heat  
- Air pollution  
- Curfews or local restrictions  

👉 Even **1–2 lost days = ₹1000–₹2000 loss**, with **no compensation**.

---

## 💡 Our Solution

**SwiggyShield** is an AI-powered parametric insurance platform that:

- Detects real-world disruptions automatically  
- Triggers payouts instantly (no claims needed)  
- Uses weekly subscription pricing  
- Applies AI-driven fraud detection  
- Ensures fair payouts for genuine workers  

> ⚠️ Coverage: Only **income loss**, not health or vehicle damages.

---

## 👤 Persona & Scenarios

### 🎯 Target Persona

| Attribute | Details |
|----------|--------|
| Worker | Swiggy Delivery Partner |
| Earnings | ₹500–₹1200/day |
| Work Pattern | Daily shift-based |
| Dependency | Fully on active delivery hours |

---

### 🌧 Scenario 1 — Heavy Rain

- Orders drop drastically  
- Roads flooded  

✅ SwiggyShield:
- Detects rainfall > threshold  
- Auto payout triggered  
- ₹500 credited instantly  

---

### 🔥 Scenario 2 — Heatwave

- Temperature > 45°C  
- Workers stop mid-day  

✅ SwiggyShield:
- Detects heat alert  
- Pays partial shift loss  

---

### 🚫 Scenario 3 — Curfew

- Zone shutdown  
- No deliveries allowed  

✅ SwiggyShield:
- Detects curfew  
- Pays 80% income  

---
### Flow

1. User registers (KYC optional mock)  
2. AI calculates risk score  
3. Weekly plan selected  
4. System monitors disruptions  
5. Trigger fires automatically  
6. Fraud check runs  
7. Payout via UPI  

---

## 💰 Weekly Premium Model

### 📊 Plans

| Plan | Premium | Coverage |
|------|--------|----------|
| Basic | ₹29 | ₹500 |
| Standard | ₹59 | ₹1000 |
| Premium | ₹99 | ₹2000 |

---

### 🧮 Formula

---

### 💸 Payout Logic

| Condition | Payout |
|----------|--------|
| Full disruption | 100% |
| Partial | 60% |
| Minor | 30% |

---

## ⚡ Parametric Triggers

| Trigger | Condition |
|--------|----------|
| Rain | > 50mm |
| Heat | > 45°C |
| AQI | > 300 |
| Flood | Alert issued |
| Curfew | Govt order |

👉 Trigger based on **area (pincode), NOT user GPS**

---

## 🌐 Platform Choice (PWA)

- Works on all phones  
- No app install  
- Easy sharing via WhatsApp  
- Faster updates  

---

## 🤖 AI/ML Integration

### 1. Risk Model
- Predicts zone risk  

### 2. Dynamic Pricing
- Adjusts premium weekly  

### 3. Fraud Detection
- Detect spoofing & anomalies  

---

## 🧰 Tech Stack

| Layer | Tech |
|------|-----|
| Frontend | React |
| Backend | Spring Boot / FastAPI |
| ML | Python |
| DB | PostgreSQL |
| APIs | Weather, AQI |
| Payments | Razorpay |

---

## 🚀 Development Plan

### Phase 1
- Idea + README  
- Pricing model  
- Trigger logic  
- Anti-fraud design  

### Phase 2
- Backend + UI  
- API integration  

### Phase 3
- Fraud ML  
- Dashboard  
- Demo  

---

# 🛡 Adversarial Defense & Anti-Spoofing Strategy

## 🚨 Problem

Workers fake GPS to claim payouts → system loss.

---

## 🎯 Solution: Multi-Signal Trust Engine

### Real Worker
- Active before disruption  
- Stops naturally  
- Consistent behavior  

### Fraud Worker
- No activity  
- Fake location  
- Static device  

---

## 📡 Detection Signals

| Signal | Fraud Pattern |
|-------|-------------|
| GPS | Unreal movement |
| Network | Home WiFi |
| Motion | No movement |
| Activity | No deliveries |
| Cluster | Mass claims |

---

## 🧠 Trust Score

---

## 🔗 Fraud Ring Detection

- Same IP / device  
- Same time claims  
- Location clustering  

---

## ⚖️ Fair UX

| Level | Action |
|------|--------|
| Green | Instant payout |
| Yellow | Delay |
| Red | Review |

---

### 🔁 Worker Protection
- No instant rejection  
- Grace for network issues  
- Appeal option  

---

## 🧱 Defense Layers

1. Signal Layer  
2. Behavior Layer  
3. AI Layer  
4. Network Layer  
5. Decision Layer  

---

## 🔮 What's Next

- Real API integration  
- Advanced fraud models  
- Live dashboards  

---

## 📎 Conclusion

SwiggyShield provides:
- Income protection  
- AI-based automation  
- Fraud-resistant system  

👉 Making gig work safer and more reliable.

---

Team: DevStorm
Guidewire DEVTrails 2026 🚀

## 🔄 Application Workflow
