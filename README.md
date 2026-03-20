# SwiggyShield — AI-Powered Parametric Income Insurance for Swiggy Delivery Partners

Guidewire DEVTrails 2026 | Phase 1 — Ideation & Foundation  
Persona: Swiggy Food Delivery Partners

---

## Table of Contents

1. The Problem  
2. Our Solution  
3. Persona & Scenarios  
4. Application Workflow  
5. Weekly Premium Model  
6. Parametric Triggers  
7. Platform Choice  
8. AI/ML Integration Plan  
9. Tech Stack  
10. Development Plan  
11. Adversarial Defense & Anti-Spoofing Strategy  
12. What's Next  

---

## The Problem

Swiggy delivery partners are a critical part of India’s food delivery ecosystem and earn income based on completed deliveries. However, they face frequent income disruptions due to:

- Heavy rainfall and floods  
- Extreme heat conditions  
- Air pollution  
- Curfews and local restrictions  

Even losing 1–2 working days can result in a loss of ₹1000–₹2000, with no compensation or safety net.

---

## Our Solution

SwiggyShield is an AI-powered parametric insurance platform designed specifically for Swiggy delivery partners.

It provides:

- Automated detection of external disruptions  
- Zero-touch claim processing (no manual filing required)  
- Instant payouts via UPI  
- Weekly subscription model aligned with earnings  
- AI-driven fraud detection and risk-based pricing  

Coverage is strictly limited to income loss and excludes health, accident, or vehicle-related claims.

---

## Persona & Scenarios

### Target Persona

| Attribute | Details |
|----------|--------|
| Worker Type | Swiggy Delivery Partner |
| Earnings | ₹500–₹1200 per day |
| Work Pattern | Shift-based |
| Dependency | Fully dependent on active working hours |

---

### Scenario 1 — Heavy Rainfall

A delivery partner is unable to work due to flooded roads and reduced orders.

System Response:
- Rainfall threshold detected via weather API  
- Trigger activated  
- ₹500 payout credited automatically  

---

### Scenario 2 — Heatwave

Extreme temperature (above 45°C) forces workers to stop operations.

System Response:
- Heat threshold detected  
- Partial payout issued based on lost working hours  

---

### Scenario 3 — Curfew

Government imposes local restrictions and stops delivery services.

System Response:
- Curfew detected via official sources  
- 80% of average daily income credited  

---

## Application Workflow

REGISTER → RISK SCORING → POLICY SELECTION → MONITORING → TRIGGER → FRAUD VALIDATION → PAYOUT

### Flow Description

1. User Registration  
   - Basic onboarding with optional KYC  
   - Selection of operating zone  

2. Risk Profiling  
   - AI model calculates risk score based on location and history  

3. Policy Activation  
   - User selects weekly plan  
   - Payment via UPI  

4. Monitoring  
   - System checks disruption triggers at regular intervals  

5. Claim Trigger  
   - Trigger activates automatically  

6. Fraud Validation  
   - Multi-signal verification performed  

7. Payout  
   - Amount credited instantly  

---

## Weekly Premium Model

### Plans

| Plan | Premium | Coverage |
|------|--------|----------|
| Basic | ₹29/week | ₹500 |
| Standard | ₹59/week | ₹1000 |
| Premium | ₹99/week | ₹2000 |

---

### Premium Formula

Final Premium = Base × Risk Factor × Seasonal Factor × Claim History Factor

---

### Payout Logic

| Condition | Payout |
|----------|--------|
| Full disruption | 100% |
| Partial disruption | 60% |
| Minor disruption | 30% |

---

## Parametric Triggers

| Trigger | Condition |
|--------|----------|
| Rainfall | > 50mm |
| Heatwave | > 45°C |
| Air Quality | AQI > 300 |
| Flood | Official alert |
| Curfew | Government notification |

Triggers are evaluated at the area (pincode) level, not individual GPS.

---

## Platform Choice

Progressive Web App (PWA)

Reasons:
- No installation required  
- Works on low-end devices  
- Easily accessible via browser  
- Faster updates without app store dependency  

---

## AI/ML Integration Plan

### Risk Scoring Model
- Predicts risk level based on location and environmental history  

### Dynamic Pricing Model
- Adjusts premium weekly based on risk  

### Fraud Detection Model
- Uses anomaly detection techniques to detect suspicious claims  

---

## Tech Stack

| Layer | Technology |
|------|------------|
| Frontend | React |
| Backend | Spring Boot / FastAPI |
| AI/ML | Python (scikit-learn) |
| Database | PostgreSQL |
| APIs | Weather API, AQI API |
| Payments | Razorpay |

---

## Development Plan

### Phase 1
- Problem definition  
- Pricing model  
- Trigger identification  
- Anti-fraud architecture  
- Documentation  

### Phase 2
- Backend API development  
- Frontend UI  
- API integrations  

### Phase 3
- Fraud detection models  
- Dashboard  
- Full system demo  

---

## Adversarial Defense & Anti-Spoofing Strategy

### Problem

Delivery partners may use GPS spoofing tools to fake their location in high-risk zones and trigger false payouts.

---

### Solution Approach

A multi-signal validation system is used instead of relying only on GPS.

---

### Differentiating Genuine vs Fraud Users

Genuine Worker:
- Active before disruption  
- Natural drop in activity  
- Consistent device behavior  

Fraudulent User:
- No prior activity  
- Sudden location change  
- Static device behavior  

---

### Data Signals Used

| Signal | Fraud Indicator |
|-------|----------------|
| GPS | Unrealistic movement |
| Network | Connected to home WiFi |
| Device Motion | No movement |
| Activity Logs | No delivery activity |
| Cluster Behavior | Sudden mass claims |

---

### Trust Score Model

Trust Score = Behavior + Device Signals + Network + Historical Patterns

---

### Fraud Ring Detection

- Multiple users from same IP or device  
- Sudden spike in claims  
- Identical location patterns  

---

### User Experience Handling

| Category | Action |
|---------|--------|
| Trusted | Instant payout |
| Suspected | Delayed verification |
| Fraudulent | Manual review |

---

### Fairness Measures

- No immediate rejection of claims  
- Grace period for network issues  
- Option for appeal and re-evaluation  

---

### Defense Layers

1. Signal Layer  
2. Behavior Analysis  
3. AI Risk Engine  
4. Network Analysis  
5. Decision Layer  

---

## What's Next

- Integration with real APIs  
- Advanced machine learning models  
- Predictive analytics dashboard  
- Scalable deployment  

---

## Conclusion

SwiggyShield provides a reliable income protection system for delivery partners by combining parametric insurance with AI-driven automation and fraud detection, ensuring fairness and financial stability.

Team: DevStorm
Guidewire DEVTrails 2026 🚀


