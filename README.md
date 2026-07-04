# 🥗 Nutrition Agent

## Overview

The Nutrition Agent is an AI-powered health and wellness assistant designed to provide personalized nutrition guidance based on an individual's age, dietary preferences, medical history, and location. The agent collects user information and generates customized nutrition recommendations while following responsible AI principles, medical safety guardrails, and ethical guidelines.

The solution leverages **Google Gemini 2.5 Flash** as the Large Language Model (LLM) to deliver intelligent, personalized, and context-aware nutrition guidance.

---

# Features

## User Information Collection

The agent gathers the following information:

* Name
* Age
* Diet Preference

  * Vegetarian
  * Non-Vegetarian
* Medical History

  * Diabetes
  * Hypertension (High Blood Pressure)
  * High Cholesterol
  * Obesity
  * Other relevant health conditions
* Location

  * City
  * State
  * Country

---

## Personalized Nutrition Recommendations

Based on the user's information, the Nutrition Agent provides:

* Personalized daily nutrition recommendations
* Balanced meal suggestions
* Healthy food recommendations
* Foods to limit or avoid
* Hydration guidance
* Lifestyle improvement suggestions
* Preventive wellness recommendations
* Healthy eating habits based on medical conditions

---

## Responsible AI & Safety

The Nutrition Agent follows:

* AI Ethics Guidelines
* Responsible AI Principles
* Medical Safety Guardrails
* Harm Avoidance Principles
* Helpful, Accurate, and Respectful (HAM) communication

A medical disclaimer is always included with every response.

---

# System Prompt Behavior

The agent:

* Greets the user.
* Introduces itself as a Nutrition Agent.
* Asks:

> **"How may I help you today?"**

* Collects the required user details.
* Reviews the provided information.
* Generates a personalized nutrition plan.
* Provides healthy meal recommendations.
* Suggests foods to include and foods to limit.
* Includes hydration and lifestyle recommendations.
* Displays a medical disclaimer.

---

# Example Interaction

## User

Hello!

## Agent

Hello! Welcome to the Nutrition Agent.

I am your AI-powered nutrition assistant, and I'm here to help you make healthier food choices by providing personalized nutrition guidance based on your age, dietary preferences, medical history, and location.

**How may I help you today?**

Please provide the following details:

* Name
* Age
* Diet Preference (Vegetarian/Non-Vegetarian)
* Medical History (Diabetes, High Blood Pressure, High Cholesterol, etc.)
* Location (City, State, Country)

Once I receive your information, I'll generate a personalized nutrition plan tailored to your needs.

---

# Technology Stack

| Component    | Technology                         |
| ------------ | ---------------------------------- |
| AI Model     | Gemini 2.5 Flash                   |
| Domain       | Healthcare / Nutrition             |
| Use Case     | Personalized Nutrition Guidance    |
| Safety Layer | AI Guardrails & Medical Disclaimer |

---

# Workflow

1. User initiates the conversation.
2. Agent greets the user.
3. Agent collects user information.
4. Agent analyzes the provided details.
5. Agent generates a personalized nutrition plan.
6. Agent provides meal and lifestyle recommendations.
7. Agent displays a medical disclaimer.

---

# Cost Estimation (Gemini 2.5 Flash)

## Pricing Assumptions

* **Input Tokens:** $0.30 per 1 Million Tokens
* **Output Tokens:** $2.50 per 1 Million Tokens
* **Exchange Rate:** 1 USD ≈ ₹83 INR

### Sample Usage

| Type      |    Tokens |    Cost (USD) |  Cost (INR) |
| --------- | --------: | ------------: | ----------: |
| Input     |        65 |    $0.0000195 |     ₹0.0016 |
| Output    |     1,365 |    $0.0034125 |     ₹0.2832 |
| **Total** | **1,430** | **$0.003432** | **₹0.2848** |

**Approximate total cost per interaction:** **₹0.28 INR**

---

# AI Guardrails

The Nutrition Agent **will**:

* Provide evidence-based nutrition guidance.
* Recommend balanced and healthy diets.
* Encourage healthy lifestyle habits.
* Suggest hydration and wellness practices.
* Promote preventive healthcare.
* Encourage consultation with healthcare professionals when appropriate.

The Nutrition Agent **will not**:

* Diagnose medical conditions.
* Prescribe medications.
* Recommend unsafe supplements or treatments.
* Suggest extreme diets or starvation plans.
* Replace professional medical advice.
* Promote harmful or misleading health information.

---

# Medical Disclaimer

This application is intended for informational and educational purposes only and does not replace professional medical advice, diagnosis, or treatment. Nutrition recommendations are general in nature and may not be suitable for every individual. Users should always consult a qualified healthcare professional or registered dietitian before making significant dietary changes, especially if they have existing medical conditions, allergies, or are taking medications. In case of a medical emergency, seek immediate medical attention.

---

# Future Enhancements

* BMI-based nutrition recommendations
* Daily calorie requirement estimation
* Macronutrient and micronutrient tracking
* Personalized weekly meal planning
* Regional and seasonal food recommendations
* Weight management plans
* Integration with fitness trackers and wearable devices
* PDF nutrition plan generation
* Multi-language support

---

# License

MIT License

---

# Author

**Nutrition Agent**

Powered by **Google Gemini 2.5 Flash**
