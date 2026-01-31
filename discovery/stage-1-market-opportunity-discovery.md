# Stage 1 – Market & Opportunity Discovery (Generic)

Stage: Discovery  
Version: v1.0  
Last updated: 2026-01-30  
Primary use case: Deep market research and opportunity identification
Scope: Vertical SaaS / SMB Software

---


# **🔍 MASTER PRODUCT RESEARCH & OPPORTUNITY DISCOVERY PROMPT (Generic)**

(Stage 1 — Vertical SaaS / SMB Software)

---

## **PRIMARY TARGET PRODUCT (REFERENCE, NOT BOUNDARY)**

## PROJECT BRIEF (Fill these in)

- Target Product Name: {{TARGET_PRODUCT_NAME}}
- Target Product Category: {{TARGET_PRODUCT_CATEGORY}}
- Geography: {{GEOGRAPHY}} (e.g., U.S., EU, global)
- Primary Personas: {{PRIMARY_PERSONAS}}  (comma-separated: owner, manager, frontline staff)
- Key Workflows In Scope: {{WORKFLOWS_IN_SCOPE}} (e.g., booking, payments, payroll, inventory)

---

The primary product is a reference point, not a constraint.
Do not assume it defines the category, user expectations, or solution space.

## **ROLE & OBJECTIVE**

You are an **independent product research and competitive intelligence agent**.

Your objective is to identify **unmet consumer pains, feature gaps, workflow friction, and product opportunities** in the target product category listed above.

The end goal is to enable the design of a **superior competing product** by deeply understanding:

- Why users are frustrated
- What existing products fail to solve
- Which features users love, tolerate, or resent
- Where competitors overbuild or underdeliver

You must prioritize **real user experience over marketing claims**.

YOU MUST:

- Analyze this product deeply to understand positioning, strengths, and failures
- Identify **direct competitors**, **adjacent competitors**, and **substitute tools**
- Treat the category broadly (not just “like-for-like” competitors)

YOU ARE EXPLICITLY REQUIRED TO ANALYZE:

- Vertical-native platforms
- Horizontal/general-purpose substitutes
- Legacy tools users migrate from or pair alongside the primary product

**PROVIDED SOURCES (SEEDS ONLY — NOT LIMITS)**

---

If any seed sources are listed below, you are given these initial sources **for orientation and calibration only**:

- N/A

### **🚫 CRITICAL CONSTRAINT**

These sources **MUST NOT** limit your research.

Treat provided sources strictly as:

- Starting points
- Vocabulary and framing references
- Hypothesis generators

You are **REQUIRED** to independently discover many additional sources beyond those listed.

---

## **INDEPENDENT DISCOVERY REQUIREMENTS (MANDATORY)**

You must independently discover:

- **At least 25 additional sources** not provided by the user
- **At least 5 different source types**, such as:
    - Reddit (multiple threads/subreddits)
    - YouTube reviews & walkthroughs
    - G2 / Capterra / Trustpilot
    - Forums, Discords, Facebook groups
    - App store reviews
    - Blog posts written by real shop owners
- **At least 3 independent platforms**

If fewer than 25 sources are found, **continue searching until diminishing returns are clear**.

---

## **RESEARCH DEPTH & EXPLORATION RULES**

Optimize for:

- Depth
- Completeness
- Signal over speed

Do **NOT** stop after a single search pass.

You must:

- Perform multiple search passes
- Vary keywords, phrasing, and intent
- Search both product-based and problem-based queries

### **Required Query Types**

- "{{TARGET_PRODUCT_NAME}} problems / issues / frustrations"
- "why I stopped using {{TARGET_PRODUCT_NAME}}"
- "{{TARGET_PRODUCT_NAME}} alternatives"
- "best {{TARGET_PRODUCT_CATEGORY}} software"
- "{{TARGET_PRODUCT_CATEGORY}} onboarding problems"
- "{{TARGET_PRODUCT_CATEGORY}} support complaints"
- "{{TARGET_PRODUCT_CATEGORY}} pricing fees complaints"
- "switching from {{TARGET_PRODUCT_NAME}} to"
- "{{TARGET_PRODUCT_NAME}} refund cancellation contract"
- "{{TARGET_PRODUCT_NAME}} data export import"

---

## **TWO-PHASE RESEARCH PROCESS (MANDATORY)**

### **🔹 Phase 1: Collection & Extraction**

- No summarizing
- No conclusions
- No recommendations
- No roadmap or solution generation

Only extract and tag:

- User complaints
- Praises
- Workarounds
- Feature requests
- UX friction
- Pricing frustration
- Integration issues

**Do not generate any product ideas or solutions until Phase 2 is complete.**

---

### **🔹 Phase 2: Synthesis & Pattern Detection**

Only after saturation is reached:

- Identify recurring patterns
- Eliminate one-off complaints
- Validate insights across sources

---

## **PAIN ANALYSIS FRAMEWORK (REQUIRED)**

For **every insight**, explicitly label:

### **Pain Type**

- Functional (missing/broken features)
- UX / Workflow friction
- Emotional (stress, distrust, embarrassment, anger)
- Economic (pricing, add-ons, ROI mismatch)
- Integration (payments, POS, payroll, marketing tools)

### **Persona Affected**

Use one or more of the personas defined in {{PRIMARY_PERSONAS}}.

### **Workflow Stage**

- Setup / onboarding
- Daily operations
- Booking & scheduling
- Payments & payroll
- Client management
- Reporting & growth

### **Evidence Requirements**

- Include **direct quotes**
- Include **links and context**
- Limit to **2–4 representative quotes per pain theme**
- Each pain theme must be supported by **at least 3 independent sources**, unless clearly impossible

---

## **COMPETITIVE FEATURE & MARKET ANALYSIS**

Identify **at least 10 competitor or substitute products**, including:

- **≥ 3 category-native platforms** (built primarily for this use case/industry)
- **≥ 3 horizontal substitutes** (general tools users adapt)
- **≥ 2 legacy/incumbent tools** (older players people still use)

For **each competitor discovered**, analyze:

- Core features (table stakes)
- Differentiators
- Hidden features users love
- Features users complain about
- Features users say “should be standard”
- Features users switch platforms for
- Overbuilt features users ignore

---

## **SCORING & WEIGHTING SYSTEM (MANDATORY)**

Each pain point and opportunity must be scored using the following model:

### **📊 Pain Severity Score (1–5)**

1 = Minor annoyance

5 = Actively drives churn or avoidance

### **📈 Frequency Score (1–5)**

Based on repetition across sources

### **💰 Business Impact Score (1–5)**

Impact on revenue, retention, expansion

### **🛠 Solution Gap Score (1–5)**

How poorly existing products solve it

### **🔥 Opportunity Score (Weighted)**

Opportunity Score =

(Pain Severity × 0.35) +

(Frequency × 0.30) +

(Business Impact × 0.20) +

(Solution Gap × 0.15)

Rank all insights by **Opportunity Score**.

---

## **PRODUCT DESIGN & IDEATION**

*(HYPOTHESES ONLY — AFTER PHASE 2)*

For **high-scoring pains only**:

- Explain why existing products fail
- Identify structural or incentive constraints
- Propose **at least 2 alternative solution approaches**
- Describe the **ideal user experience**
- Note adoption or complexity tradeoffs

These are **hypotheses**, not final solutions.

---

## **FINAL OUTPUT STRUCTURE (STRICT)**

Your final output MUST include:

1. **Market Overview** (1 page max)
    - Market maturity
    - Common software stacks users actually use
    - Key competitive dynamics
2. **Competitor Landscape**
    - [TARGET_PRODUCT_NAME]
    - Other discovered competitors
    - Substitute tools
3. **Top User Pains (Ranked)**
    - Scoring table
    - Evidence & quotes
4. **Pain → Feature Gap Mapping Table**
5. **Feature Sentiment Matrix**
    - Loved
    - Tolerated
    - Hated
    - Ignored
6. **Underserved Segments**
    - Who is not well served today and why
7. **Draft Feature Roadmap**
    - MVP must-haves
    - Differentiators
    - Power-user features
    - Long-term bets
8. **Opportunity Briefs (Top 5)**
    
    Each brief must include:
    
    - Problem statement
    - Who it affects
    - Why competitors fail
    - Proposed solution (hypothesis)
    - Expected business impact
    - Risks & tradeoffs
9. **Contrarian or Non-Obvious Insights**
10. **Research Process Summary (Audit)**
- Number of provided sources used
- Number of independently discovered sources
- Platforms that produced the strongest signal

---

## **FINAL INSTRUCTIONS**

- Prioritize **user truth over brand claims**
- Prefer **raw language over polished copy**
- Clearly separate **observation vs hypothesis**
- Optimize for **founder-level product decision-making**

---

## **✅ SUCCESS CRITERIA**

This research should make it obvious:

- What product to build
- Who it’s for
- Why it will win
- Which features matter most
- Which competitors are vulnerable
