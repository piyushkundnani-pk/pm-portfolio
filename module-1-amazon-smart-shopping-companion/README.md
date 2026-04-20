# Module 1 — Amazon Smart Shopping Companion
### Guided Retail Experience for Amazon India

**Program:** PM & Agentic AI Certificate | Vishlesan i-Hub, IIT Patna × Masai School  
**Type:** Product Concept | **Domain:** E-Commerce | **Platform:** Amazon India  
**PM:** [Piyush Kundnani](https://linkedin.com/in/piyush-kundnani-67312594)

---

## 📌 Quick Summary

| | |
|---|---|
| **Problem** | Amazon's self-serve model creates decision fatigue for 25–30M guidance-seeking users in India |
| **Solution** | AI-guided Shopping Assistant that replicates in-store concierge experience |
| **North Star Metric** | Guided Shopping Conversion Rate |
| **MVP Scope** | AI Guided Assistant + Contextual Search (rule-based, validated before ML) |
| **Market Opportunity** | ~₹25 Crore Year 1 revenue uplift (250K users × ₹1,000 incremental spend) |
| **Prioritization** | MoSCoW Framework |
| **Roadmap** | Now / Next / Later (0–6 months) |

---

## 1. Why This Problem

My father runs an utensils shop in Ahmedabad. In a digital-first era, his customers still walk in — not because Amazon doesn't carry the products, but because **they don't know what they need**.

A customer came in wanting to eat healthier without giving up taste. She didn't know an Air Fryer existed. My father understood her need, recommended the right product at the right price, and she left confident.

Amazon would have shown her 10,000 results for "healthy cooking."

> **Insight:** A person who knows what to buy searches Amazon.  
> A person who needs a solution to their problem walks into an experience store.  
> **What if Amazon could behave less like a catalog and more like a concierge?**

---

## 2. Product Vision & Mission

**Amazon's Vision:**  
*"To be Earth's most customer-centric company, where customers can find and discover anything they might want to buy online."*

**Problem with current state:**  
The vision says *find and discover* — but discovery for guidance-seeking users is broken. Amazon optimizes for users who already know what they want.

---

## 3. Problem Statement

> *When I shop on Amazon, I want to easily select products suited to my occasion, mood, or budget, but I struggle because Amazon lacks personalized assistance or human-like guidance — leading to confusion, frustration, wasted time, and reduced confidence in my purchase decisions.*

---

## 4. Jobs To Be Done (JTBD)

> *Help me confidently choose and purchase the right product quickly, so I can feel assured that I'm making the best possible decision for my needs, mood, occasion, or budget.*

---

## 5. User Research Plan

### Target Segments

| User Segment | Why Chosen |
|---|---|
| **Elders (50+)** | Less tech-savvy, often need family assistance for online purchases |
| **Rural/Semi-urban Users** | Prefer physical retail for trust, familiarity, and direct product interaction |
| **Confused Online Shoppers** | Know their need broadly but get overwhelmed by options, reviews, and price points |

### Methods Planned
- **User Interviews:** 5–7 users — understand behavior, pain points, emotional friction
- **Surveys:** 20–30 users — quantify decision fatigue frequency across segments

### Sample Interview Questions
1. *"Do you prefer shopping online or visiting a physical retail store, and what influences your choice?"*
2. *"Which best describes your shopping behavior: Planned / Confused / Window shopper?"*

### Sample Survey Question
*"Do you often find that buying products online requires significant planning to figure out what product best suits your need, mood, or occasion?"*
→ Yes, frequently / Sometimes / Rarely / Never

---

## 6. User Personas

| Attribute | Meena Devi | Rakesh Patel | Shruti Jain |
|---|---|---|---|
| **Archetype** | Dependent Shopper | Confused Festival Shopper | Impulsive Urban Buyer |
| **Age** | 61 | 36 | 27 |
| **Location** | Rural Uttar Pradesh | Vadodara, Gujarat | Mumbai, Maharashtra |
| **Tech Comfort** | Low | Medium | High |
| **Occupation** | Homemaker | Small Business Owner | Marketing Professional |
| **Goal** | Buy essentials or family gifts | Shop for occasions like festivals | Discover exciting or mood-based items |
| **Pain Points** | Needs help to place orders; distrusts listings | Compares endlessly; fears wrong choice | Impulse buyer; regrets purchases |
| **Behavioral Insight** | Avoids Amazon unless guided | Wants someone to simplify decisions | Needs personalized, curated discovery |

### 🎯 Primary MVP Persona: Rakesh Patel
Chosen because: sufficient tech comfort to engage with a guided assistant, shops with real purchase intent but lacks confidence, and represents the largest addressable segment among the three.

---

## 7. Customer Journey Map — Rakesh Patel

| Stage | User Action | Emotion | Pain Point |
|---|---|---|---|
| **1. Need Recognition** | Decides to buy Diwali gifts | Excited | — |
| **2. Product Search** | Types "Diwali gifts" on Amazon | Overwhelmed | Too many results; brand confusion |
| **3. Evaluation** | Opens 5–6 tabs to compare | Confused | No expert guidance; no occasion filter |
| **4. Decision Making** | Reads reviews, still unsure | Frustrated | Spends 30+ mins; too many alternatives |
| **5. Purchase** | Picks one product randomly | Hesitant | No confidence; fear of wrong choice |
| **6. Post-Purchase** | Waits for delivery, unsure if it's good | Anxious | No personal assurance like a physical store |

**Biggest drop-off moment:** Stage 3 → 4 (Evaluation to Decision Making)  
**Smart Shopping Companion intervenes here.**

---

## 8. Opportunity Sizing

### Top-Down (TAM → SAM → SOM)

| Level | Description | Size |
|---|---|---|
| **TAM** | All online shoppers in India | ~200 million |
| **SAM** | Regular Amazon India users | ~120 million |
| **SOM** | Guidance-seeking / decision-fatigued users | ~25–30 million (20–25% of SAM) |

### Bottom-Up Validation

| Assumption | Value |
|---|---|
| Year 1 SOM adoption (1%) | ~250,000 users |
| Average incremental spend uplift per user/year | ₹1,000 |
| **Potential Revenue Uplift** | **~₹25 Crores (~$3M USD)** |

> ⚠️ **Confidence Level:** Low-to-medium. This is a directional estimate to validate opportunity size, not a financial projection. The ₹1,000 uplift assumption requires validation against Amazon's actual basket size data.

---

## 9. Prioritization — MoSCoW Framework

| Feature | Priority | Rationale |
|---|---|---|
| AI Guided Shopping Assistant | **Must Have** | Directly addresses core problem: lack of guidance & decision fatigue |
| Contextual Search Results | **Must Have** | Helps users express needs naturally; reduces confusion |
| Mood-Based Category Pages | **Should Have** | Adds emotional engagement but not essential for MVP validation |
| Voice Support (Regional) | **Should Have** | Enhances accessibility for rural/non-English users |
| Gamified Reviews | **Could Have** | Boosts engagement but doesn't solve the primary pain point |
| Deep Personalization / Alexa Integration | **Won't Have** | Requires ML infrastructure; deferred to Later roadmap |

> **Why MoSCoW over RICE:** At the discovery phase, I had no quantitative data to run RICE with validity. MoSCoW was the right tool for aligning on what's essential vs. nice-to-have before any user validation. RICE will be applied in the Next/Later roadmap once MVP engagement data is available.

---

## 10. MVP Definition

**Goal:** Validate that users engage with guided shopping assistance and convert at a higher rate than standard search.

| Feature | Description |
|---|---|
| **Mini Q&A Prompt** | 2–3 questions: "What's the occasion?", "What's your budget?", "Who is it for?" |
| **Curated Recommendations** | 5–10 relevant products based on Q&A responses |
| **Mood-Based Tabs** | "Gifting", "Relaxation", "Festive", "Useful" |
| **Fallback to Standard Search** | Users can skip the assistant anytime |
| **Feedback Prompt** | "Did these suggestions help you?" — collects initial validation signal |

### What's Excluded from MVP (and Why)
- ❌ Voice input → Higher implementation complexity, deferred
- ❌ ML/AI personalization → Needs behavioral data that doesn't exist yet
- ❌ Purchase history integration → Infrastructure dependency, deferred

> **Rule-based recommendation engine for MVP:** Building a full ML model before validating the core hypothesis would be false confidence. Rule-based lets me validate UX and user behavior cheaply. Once conversion data is available, it becomes the training signal for a proper ML model. I'm not avoiding AI — I'm earning the right to build it properly.

---

## 11. AI Component Strategy

| AI Component | Role in Product |
|---|---|
| **NLP** | Parses natural language queries like "gift for 10-year-old nephew under ₹500" |
| **Recommendation Engine** | Curates products based on occasion, mood, budget (rule-based in MVP → ML in Phase 2) |
| **Sentiment Analysis** | Analyzes feedback ("Not helpful" vs. "Loved it!") to improve recommendation quality |
| **Dynamic Mood Curation** | AI auto-generates mood-based categories based on trends and seasons |
| **Voice AI (Future)** | Regional language voice queries for Tier 2/3 markets and elders |

### Agentic AI Vision (Long-Term)
A proactive assistant that learns user intent across sessions and acts on their behalf:
> *"Looks like you're shopping for a festival gift again. Need suggestions under ₹1000?"*

### Responsible AI Considerations
- Show **"Why Recommended"** transparency tags on every suggestion
- Keep recommendations grounded in catalog constraints — no hallucinated products
- Collect explicit feedback to continuously improve outputs
- Don't overstate confidence of AI recommendations

---

## 12. Metrics Hierarchy

| Level | Metric | Definition |
|---|---|---|
| **NSM (North Star)** | Guided Shopping Conversion Rate | % of users completing a purchase after using the assistant |
| **L1** | Assistant Engagement Rate | % of eligible users who start the guided flow |
| **L1** | Recommendation CTR | % of recommendations clicked |
| **L1** | Add-to-Cart Rate from Guided Flow | Purchases initiated from assistant recommendations |
| **L1** | Helpfulness Feedback Rate | % of users rating suggestions as helpful |
| **L2** | Prompt Completion Rate | % of users completing all Q&A steps |
| **L2** | Assistant Exit Rate | % abandoning mid-flow |
| **L2** | Refinement / Retry Rate | % requesting new recommendations |

> **Why Guided Shopping Conversion Rate as NSM (not Revenue per Session):**  
> Revenue is a lagging indicator. Conversion rate is a leading indicator — it tells me in real-time whether users are finding value, which predicts future revenue. Revenue per Session can also be gamed by recommending expensive products regardless of fit — conversion rate tied to user satisfaction is harder to manipulate.

---

## 13. Roadmap — Now / Next / Later

### 🟢 Now (0–1 Month): Validate
- Launch Q&A-based Guided Shopping Assistant MVP
- Add 4–5 mood-based shopping categories
- Collect user feedback post-interaction
- Track: engagement rate, add-to-cart, satisfaction scores

### 🟡 Next (1–3 Months): Expand
- Contextual Search Enhancements ("gift for sister's wedding" → smart filters)
- Regional language prompts (Hindi + 1 regional language)
- A/B test: guided flow vs. standard browsing
- Expand mood categories ("Rainy Day", "Heartbreak Recovery")

### 🔵 Later (3–6 Months): Personalize
- Voice input for non-English speakers
- ML-based personalization using behavior + location + purchase history
- Alexa & mobile homepage integration
- Festive campaign launch (Prime Day, Diwali)

---

## 14. Key Decisions & Tradeoffs

| Decision | Alternatives Considered | Why This Choice |
|---|---|---|
| Rule-based recommendations for MVP | Full ML model | Validate problem-solution fit before investing in ML infrastructure |
| MoSCoW prioritization | RICE, Kano | No quantitative data available at discovery phase; MoSCoW better for scoping |
| Focus on Rakesh Patel as primary persona | Meena Devi (needs voice), Shruti (already navigates Amazon well) | Best fit for MVP: tech-capable, high intent, largest segment |
| Amazon as target product | Flipkart, Meesho | Largest user base, India's most-used e-commerce platform, highest impact |

---

## 15. What I'd Do Differently

> *"I'd invest 2 weeks in contextual user research before writing a single line of PRD — specifically accompanying Tier 2 and Tier 3 city users as they attempt to shop online. My personas were hypothesis-driven. Real research might have revealed that Meena Devi's barrier isn't discovery at all, it's trust in payments and delivery — which would have shifted the product direction entirely."*

**Lesson:** Observation gives you the problem space. User interviews give you the problem truth.

---

## 📎 Full Project Document

📄 [Download Full PDF Report](./artifacts/Piyush_Kundnani_Module1_SmartShoppingCompanion.pdf)

---

*Part of [PM Portfolio](https://github.com/piyushkundnani-pk/pm-portfolio) | [← Back to Master Portfolio](../README.md)*
