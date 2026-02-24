# AI-Powered Healthy Snack Planner

Final project for the Building AI course

## Summary
An AI-powered tool that suggests sugar-free, non-flour-based healthy snacks based on your schedule, energy needs, and available ingredients. Helps professionals with tight schedules maintain focus and energy without unhealthy choices.

## Background
* Many working professionals skip proper meals or grab sugary snacks due to time pressure.
* Poor nutrition leads to energy crashes, reduced concentration, and long-term health issues.
* I personally struggle with this: after English classes until 21:30, I need a smart, healthy snack — but often default to suboptimal choices.
* This project solves a real, daily problem using simple AI logic — no coding required.

## How is it used?
The user inputs:
- Current time and next meal gap (e.g., "21:30, next meal in 4 hours")
- Available ingredients at home (e.g., "walnuts, boiled eggs, cottage cheese")
- Dietary restrictions ("no sugar, no flour")

The AI (rule-based classifier) recommends 1–2 optimal snacks from a pre-defined knowledge base, prioritizing:
- Omega-3 sources (like walnuts)
- Protein + healthy fats
- Low glycemic impact

Used via a simple web form or mobile note — no app needed.

## Data sources and AI methods
* **Data**: Personal food diary, nutritional guidelines (WHO, Harvard Healthy Eating Plate), omega-3 content tables.
* **AI method**: Rule-based system + Naive Bayes classifier (as learned in Elements of AI).
  - Features: time_of_day, ingredient_availability, dietary_restrictions
  - Output: snack recommendation with confidence score
* No training data needed — rules are handcrafted by nutrition logic.

## Challenges
* Does not replace a dietitian.
* Assumes user has basic ingredients.
* Not personalized to medical conditions (e.g., diabetes).
* Ethical note: must avoid promoting restrictive eating.

## What next?
* Add voice input for hands-free use after work.
* Integrate with grocery delivery APIs.
* Expand to full "AI Meal Companion" for busy professionals.
* Skills needed: basic Python (optional), nutrition knowledge, UX design.

## Acknowledgments
* Inspired by "Elements of AI" course (University of Helsinki & Reaktor)
* Nutritional data from USDA FoodData Central
* Concept aligns with WHO guidelines on healthy snacking
