# 🥗 Fitness & Diabetes Care Platform
<img width="1303" height="756" alt="gd" src="https://github.com/user-attachments/assets/5e23ff96-5138-46d0-8a88-294b91bccfb9" />

A full-featured TypeScript application designed to help users track health metrics, manage diabetes risks, calculate personalized nutrition goals, and find healthy local stores within their budget.

---

## 🌟 Key Features

* **👤 User Profile & Preferences:** Customizable user profiles tracking age, height, weight, activity levels, fitness goals, and dietary/budget preferences.
* **📊 BMI & Macro Calculator:** Calculates BMI, ideal weight range, BMR, TDEE, target calories, macronutrient distribution (protein, carbs, fat), and daily water intake needs.
* **🩺 Diabetes Management & Risk Assessment:** Tracks fasting and post-meal glucose readings, assesses diabetes risk levels based on clinical markers, and provides low-GI dietary recommendations.
* **📍 Healthy Store Finder:** Locates local salad bars, juice shops, protein stores, and healthy restaurants filtered by distance, ratings, price levels, and budget-friendly items.
* **🤖 AI Trainer & Clinical Advice:** Generates custom fitness advice, macro recommendations, budget tips, and meal suggestions tailored to user goals.

---

## 📂 Data Model Overview

The application relies on core TypeScript interfaces defined in your types module:

### Core Types & Models

* `UserProfile`: Stores user demographic details, fitness goals, location, and dietary constraints.
* `BMIMetrics`: Captures computed health metrics including BMI, category, BMR/TDEE, and target macros.
* `DiabetesRiskFactors` & `DiabetesReportResponse`: Handles glucose tracking, HbA1c values, clinical risk scoring, and low-GI meal planning.
* `HealthyStore` & `BudgetItem`: Manages healthy vendor listings, GPS coordinates, price tiers, and affordable menu items.
* `TrainerAdviceResponse`: Formats AI or expert recommendations for meals, macros, and budget tips.

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:
* [Node.js](https://nodejs.org/) (v16 or higher)
* [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git](https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git)
   cd YOUR-REPO-NAME
