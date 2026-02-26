# AI Personalization Research: Cosmetics & XAI for Nutrition

> RU: В этом репозитории — мои исследования про (1) AI-персонализацию в уходе/косметике и (2) объяснимые рекомендации еды/питания (XAI).

## Contents
  - **Artificial Intelligence in Personalized Skincare and Cosmetics: A Systematic Literature Review** (Apr 05, 2025)
  - **Explainable AI for Nutrition: A Research Proposal on Enhancing Trust and Health Outcomes in Food Recommendation Systems** (Apr 30, 2025)

---

## Project 1 — AI in Personalized Skincare & Cosmetics (Systematic Literature Review)

### Research question
How do AI techniques (deep learning, computer vision, augmented reality) enhance personalized skincare and cosmetic product recommendations?

### Method (high level)
- PRISMA-based screening workflow.
- Primary database: IEEE Xplore (2020–2025).
- Boolean query built around AI + cosmetics/skincare + application/technique keywords.
- Final included set: 10 studies after filtering and full-text screening.

### What the review covers
- CNN-based skin type / condition classification
- AR / virtual try-on and interactive makeup trials
- GAN-based makeup transfer
- Ingredient-level, content-based skincare recommendations
- Shade matching approaches and clustering-based personalization

### Key challenges highlighted
- Dataset bias & limited demographic diversity
- Privacy concerns (facial images / skin data)
- Sensitivity to lighting and image quality
- Lack of long-term validation and standardized evaluation metrics

---

## Project 2 — Explainable AI for Nutrition (Research Proposal)

### Research question
What are the effects of integrating nutritional expertise and user-centered explainability into hybrid food recommender systems on dietary compliance and user satisfaction compared to non-explainable systems?

### Core idea
- Extend an existing grocery recommendation engine with a **symbolic, rule-based XAI layer**.
- Add a concise one-line rationale per item (e.g., “high fibre → supports digestion”).
- Use rule-based post-filtering to better reflect explicit dietary constraints.

### Evaluation plan (proposal)
- 200 synthetic user profiles based on USDA dietary data (diverse nutrition goals).
- Two conditions: baseline (no explanations) vs XAI-enhanced (rules + rationales).
- 60 participants rate outputs for trust, usability (SUS), and perceived health relevance.
- Compute nutrient-density scores; paired t-tests for significance.

### Expected outcomes (hypotheses)
Higher trust, improved usability, and better nutritional quality in the XAI condition.

---

## Author
Sabina Yamilova
