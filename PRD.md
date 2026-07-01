# KitchenIQ – Product Requirements Document (PRD)

## Project Overview

KitchenIQ is an AI-powered recipe recommendation application that helps students and young adults reduce food waste by suggesting meals using ingredients they already have at home.

The application prioritizes ingredients that are close to their expiry dates while considering dietary preferences, allergies, and available cooking time.

---

## Problem Statement

Many students purchase groceries but forget to use ingredients before they expire, leading to unnecessary food waste and extra spending.

KitchenIQ solves this problem by recommending personalized recipes based only on ingredients the user already owns.

---

## Target Users

- University students
- Young professionals
- Budget-conscious households
- People wanting to reduce food waste

---

## Goals

- Reduce household food waste
- Save users money
- Make meal planning quick and easy
- Encourage healthier eating habits

---

## Core Features

### Ingredient Input

Users can enter:
- Ingredients available
- Expiry dates
- Dietary preferences
- Allergies
- Available cooking time

---

### AI Recipe Generator

The AI will:

- Prioritize ingredients closest to expiry
- Remove recipes containing allergens
- Respect dietary preferences
- Generate three recipe suggestions
- Rank recipes by how many expiring ingredients they use

---

### Recipe Details

Each recipe includes:

- Recipe title
- Ingredients used
- Step-by-step instructions
- Estimated cooking time

---

### Smart Suggestions

If a complete recipe cannot be created, KitchenIQ will:

- Recommend the closest possible recipe
- Suggest one or two extra ingredients that unlock more meal options

---

## User Flow

1. Open KitchenIQ
2. Enter ingredients
3. Enter expiry dates
4. Select allergies and dietary preferences
5. Enter available cooking time
6. Click "Generate Recipes"
7. View three ranked recipes
8. Choose one to cook

---

## Success Criteria

- Recipes only use available ingredients
- Allergies are always respected
- Expiring ingredients receive highest priority
- Recipes are easy to prepare
- Recipe generation takes less than 10 seconds

---

## AI Behaviour

Trigger:
User clicks "Generate Recipes"

Input:
Ingredients, expiry dates, allergies, dietary preferences, cooking time

Output:
Three ranked recipe suggestions with cooking steps and cooking time.

Backend:
OpenAI-powered recipe generation engine.
