# Smart Agriculture System
## Artificial Intelligence Assignments & Case Studies
### Course: SECJ 3553 - Artificial Intelligence (UTM)

This repository contains the assignments and design documentations for a **Smart Agriculture System** case study, analyzing how artificial intelligence paradigms can optimize irrigation, resource usage, machinery operations, and crop health in modern farming.

---

## 📂 Repository Structure
```text
└───assignments
        Assignment_1_Knowledge_Representation.pdf   # First-Order Logic & Rule-Based Modeling
        Assignment_2_State_Space_Graph.pdf          # State Space Formulation & Transitions
        Assignment_3_PEAS_Agent_Model.pdf           # PEAS representation & Multi-Agent Architecture
```

---

## 📑 Assignment Breakdown

### 1. Assignment 1: Knowledge Representation
Focuses on representing agricultural logic using Propositional Rules (IF-THEN) and formalizing them using **Predicate Logic / First-Order Logic (FOL)**.
- **Irrigation**: Activation based on soil moisture levels and rain expectation forecasts.
  - *FOL Formula*: `∀x∀y(LowMoisture(x) ∧ ¬RainExpected(y) → ActivateIrrigation(x))`
- **Autonomous Machinery**: Safety checks considering battery levels, terrain stability, and obstacle proximity.
- **Predictive Crop Modeling**: Forecasting yields based on soil status, climate history, and extreme weather risks.
- **Pest/Disease Control**: Sensing leaf spots and temperature/humidity levels to trigger pesticide or fungal treatments.
- **Resource Optimization**: Materials reordering based on wastage rates and stock thresholds.

---

### 2. Assignment 2: State Space Graph Formulation
Models the decision-making transitions of the agricultural system using a **State Space Graph**.
- **Initial State**: `weather_conditions`
- **Actions**: Checking sensors, monitoring wastage, activating/deactivating irrigation, evaluating crop health, and checking machinery metrics.
- **Goal State**: Achieving crop yield prediction (Low, High, or Uncertain).
- **Path Costs**: Represented by specific environmental states (favorable, extreme, unstable, stable, poor, good).

---

### 3. Assignment 3: PEAS Agent Model
Formulates the **PEAS (Performance Measure, Environment, Actuators, Sensors)** framework for each autonomous sub-agent inside the system:
1. **Smart Irrigation Agent**: Regulates water usage dynamically.
2. **Smart Crop Prediction Agent**: Forecasts harvests based on climate patterns.
3. **Smart Pest & Disease Detection Agent**: Minimizes chemical usage via targeted camera-based application.
4. **Electric & Autonomous Machinery Agent**: Governs navigation, collision avoidance, and safety on the field.

---

## 👥 Group Members (Section 02)
- **Iman Abadi Bin Mohd Nizwan** (Matric ID: A23CS0084)
- **Muhammad Afiq Danial Bin Rozaidie** (Matric ID: A23CS0117)
- **Mohamed Alif Fathi Bin Abdul Latif** (Matric ID: A23CS0112)
- **Dheshieghan A/L Saravana Moorthy** (Matric ID: A23CS0072)

**Lecturer**: Dr. Roliana Binti Ibrahim


---

## 💭 Course Reflection
Designing logic rules (FOL), state-space search trees, and PEAS multi-agent architectures here showed me how to model complex agricultural tasks logically. It taught me how to translate environmental constraints into structured machine-readable decisions.
