# Prioritization Framework

## 🎯 Overview

This document outlines the decision-making methodology used to prioritize features and initiatives in the Krista product roadmap.

## 📊 Primary Framework: RICE Scoring

RICE is a prioritization framework that helps evaluate initiatives objectively across four dimensions:

### Components

**R - Reach**
- **Definition:** How many customers/users will this impact over a given time period (typically per quarter)?
- **Scale:** Percentage of user base (0-100%)
- **Example:** A feature that all users see = 100% reach

**I - Impact**
- **Definition:** How much will this move the needle on our core metrics?
- **Scale:**
  - 3 = Massive impact (game-changer, transforms business)
  - 2 = High impact (significant improvement)
  - 1 = Medium impact (noticeable improvement)
  - 0.5 = Low impact (marginal improvement)
- **Example:** Reducing time-to-automation by 60% = Massive (3)

**C - Confidence**
- **Definition:** How confident are we in our Reach and Impact estimates?
- **Scale:** Percentage (0-100%)
- **Based on:**
  - Customer research and validation
  - Data from similar features
  - Technical feasibility assessment
  - Team expertise in the domain
- **Example:** Feature validated with 20 customers = 90% confidence

**E - Effort**
- **Definition:** How much engineering time is required?
- **Scale:** Engineer-weeks (person-weeks of development time)
- **Includes:**
  - Design
  - Development (front-end + back-end)
  - QA testing
  - Documentation
  - Deployment
- **Example:** Feature requiring 2 engineers for 6 weeks = 12 engineer-weeks

### Formula

```
RICE Score = (Reach × Impact × Confidence) / Effort
```

Higher scores = higher priority

### Example Calculation

**Feature:** Guided Onboarding Flow

- **Reach:** 100% (every new user)
- **Impact:** 3 (massive - reduces time-to-value by 60%)
- **Confidence:** 90% (validated through user research)
- **Effort:** 12 engineer-weeks

**RICE Score:** (100 × 3 × 0.90) / 12 = **22.5**

This is a very high score, indicating top priority.

## 🎨 Secondary Considerations

RICE provides a quantitative baseline, but we also consider qualitative factors:

### Strategic Alignment
- **Question:** Does this support our long-term vision?
- **Examples:**
  - ✅ AI agent orchestration aligns with vision to be "OS for AI automation"
  - ❌ Adding more report types doesn't advance strategic positioning

### Competitive Pressure
- **Question:** Is this a competitive gap or opportunity?
- **Examples:**
  - High Priority: Competitors just launched similar feature
  - Medium Priority: No competitors have this yet (first-mover advantage)
  - Low Priority: Commodity feature everyone has

### Customer Urgency
- **Question:** How urgent is this for customers?
- **Signals:**
  - Deal blockers (lost deals due to missing feature)
  - Churn risk (existing customers threatening to leave)
  - High support volume (top 3 most requested)
  - Net Promoter Score (NPS) impact

### Technical Debt vs. Features
- **Rule:** Reserve 20% of engineering capacity for tech debt
- **Rationale:** Maintain velocity and platform health
- **Examples of tech debt:**
  - Database optimization
  - Test coverage improvements
  - Infrastructure modernization
  - Security patches

### Platform DNA
- **Question:** Is this core to what makes Krista unique?
- **Examples:**
  - Core: Conversational automation, multi-agent orchestration
  - Not Core: Generic project management features

## 🚦 Priority Levels

### P0 - Critical (Must Have)
- **Criteria:**
  - RICE score > 10 OR
  - Deal blocker (lost >$500K ARR due to missing feature) OR
  - Churn risk (>10% of base threatens to leave) OR
  - Security/compliance requirement
- **Commitment:** Ship within committed quarter
- **Resource Allocation:** Protected capacity, cannot be de-prioritized

### P1 - High (Should Have)
- **Criteria:**
  - RICE score 5-10 OR
  - Significant competitive advantage OR
  - Strategic alignment with 12-24 month vision
- **Commitment:** Ship within 6 months if resources allow
- **Resource Allocation:** Flexible, can be moved based on learnings

### P2 - Medium (Nice to Have)
- **Criteria:**
  - RICE score 2-5 OR
  - Incremental improvement, not game-changing
- **Commitment:** Backlog, ship if capacity available
- **Resource Allocation:** Opportunistic

### P3 - Low (Not Now)
- **Criteria:**
  - RICE score < 2 OR
  - Doesn't align with strategy OR
  - High effort, low impact
- **Decision:** Deprioritize, revisit in 12+ months

## 📋 Prioritization Process

### Step 1: Idea Collection (Ongoing)
**Sources:**
- Customer requests (via CS, Support, Sales)
- User research and interviews
- Competitive analysis
- Internal team ideas
- Analytics and usage data

**Tool:** Maintain idea backlog in product management tool (e.g., ProductBoard, Aha!)

### Step 2: Initial Screening (Weekly)
**Questions:**
1. Is this aligned with product strategy?
2. Do we understand the problem deeply?
3. Is this technically feasible?

**Decision:** Proceed to scoring OR reject with explanation

### Step 3: RICE Scoring (Bi-weekly)
**Process:**
1. PM drafts initial RICE scores
2. Validate Reach with customer data
3. Validate Impact with business metrics
4. Validate Effort with engineering leads
5. Validate Confidence with available evidence

**Output:** Scored initiative ready for roadmap consideration

### Step 4: Roadmap Review (Monthly)
**Participants:**
- Product Manager
- Engineering Lead
- Design Lead
- CTO (for strategic initiatives)
- CEO (for quarterly roadmap)

**Agenda:**
1. Review top 10 RICE-scored initiatives
2. Apply qualitative overlays (strategic, competitive, urgent)
3. Consider team capacity and dependencies
4. Sequence initiatives across quarters
5. Identify initiatives to cut or defer

**Output:** Committed roadmap for next 3-6 months

### Step 5: Stakeholder Alignment (Quarterly)
**Stakeholders:**
- Sales (understand what's coming, how to position)
- Marketing (launch planning, messaging)
- Customer Success (training, customer communication)
- Support (knowledge base updates)

**Deliverable:** Roadmap presentation with rationale

## 🎯 Decision-Making Principles

### 1. Customer Value First
**Principle:** Prioritize initiatives that solve customer pain points over internal preferences.

**Example:**
- ✅ Build template library (customers struggling with time-to-automation)
- ❌ Rebuild admin UI to use latest framework (engineers want it, no customer value)

### 2. Validate Before Building
**Principle:** Invest in research and validation to increase Confidence scores.

**Methods:**
- Customer interviews (qualitative)
- Prototype testing (usability)
- Beta programs (quantitative)
- A/B testing (optimization)

### 3. Focus Over Breadth
**Principle:** Do fewer things exceptionally well rather than many things poorly.

**Rule:** Max 3-5 major initiatives per quarter for 4-engineer team.

### 4. Embrace Constraints
**Principle:** Small team = forcing function for ruthless prioritization.

**Strategy:**
- Leverage no-code to enable customer self-service
- Partner ecosystem to extend capabilities
- Community marketplace for long-tail features

### 5. Balance Short and Long Term
**Allocation:**
- 60% - Near-term value (0-6 months)
- 30% - Strategic bets (6-18 months)
- 10% - Exploration and innovation (18-24+ months)

### 6. Sequencing Matters
**Dependencies:**
- Build foundation before advanced features
- Platform capabilities before ecosystem
- Adoption before monetization

**Example Sequence:**
1. First: Onboarding and templates (adoption)
2. Then: Analytics and ROI (retention)
3. Finally: Marketplace and monetization (expansion)

## 🔄 Continuous Refinement

### Retrospectives (Post-Launch)
**Questions:**
1. Did we achieve expected Reach? (usage data)
2. Did we achieve expected Impact? (metric movement)
3. Was Effort estimate accurate? (actual vs. planned)
4. What would we do differently?

**Output:** Calibrate future RICE scoring based on learnings

### Quarterly Roadmap Adjustments
**Triggers for Re-prioritization:**
- Major customer churn or win/loss patterns
- Competitive moves (new features, pricing)
- Technical discoveries (harder/easier than expected)
- Market shifts (new regulations, economic changes)

**Process:**
- Review RICE scores with new data
- Adjust roadmap as needed
- Communicate changes transparently

## 📊 Example: Feature Prioritization Matrix

| Feature | Reach | Impact | Confidence | Effort | RICE | Priority | Quarter |
|---------|-------|--------|------------|--------|------|----------|---------|
| Guided Onboarding | 100% | 3 | 90% | 12 | 22.5 | P0 | Q1 |
| Template Library | 80% | 3 | 85% | 12 | 17.0 | P0 | Q1 |
| Agent Orchestration | 70% | 3 | 80% | 30 | 5.6 | P0 | Q3 |
| Marketplace | 90% | 3 | 75% | 30 | 6.8 | P0 | Q4 |
| Mobile Enhancements | 40% | 2 | 60% | 6 | 8.0 | P1 | Q2 |
| Dark Mode | 30% | 0.5 | 95% | 2 | 7.1 | P2 | Backlog |
| Advanced Filters | 50% | 1 | 70% | 4 | 8.8 | P1 | Q2 |

## ⚖️ Trade-off Examples

### Trade-off 1: Polish vs. New Features
**Scenario:** Should we perfect onboarding (95% → 98% completion) or build new template categories?

**Decision Framework:**
- Marginal improvement (3% onboarding) = Low Impact (0.5)
- New templates = High Impact (2-3)
- **Decision:** Ship new templates; onboarding is "good enough"

### Trade-off 2: Enterprise Features vs. Self-Serve
**Scenario:** Build complex RBAC or improve trial experience?

**Decision Framework:**
- RBAC: Low Reach (20% of customers), High Impact (3) = Deal enabler
- Trial: High Reach (100% of prospects), Medium Impact (1.5) = Volume driver
- **Decision:** Depends on growth strategy
  - If land-and-expand: Prioritize trial
  - If enterprise-focused: Prioritize RBAC

### Trade-off 3: Quick Wins vs. Strategic Bets
**Scenario:** Ship 5 small features or 1 game-changing feature?

**Decision Framework:**
- Quick wins: High Reach, Low-Medium Impact, Low Effort
- Strategic bet: Medium Reach, High Impact, High Effort
- **Balance:** 70% quick wins, 30% strategic bets per quarter

## 🎯 Anti-patterns to Avoid

### ❌ HiPPO Prioritization
**Problem:** "Highest Paid Person's Opinion" overrides data  
**Solution:** Require RICE scoring and customer evidence for all decisions

### ❌ Shiny Object Syndrome
**Problem:** Chasing latest trends without strategic fit  
**Solution:** Every feature must map to strategic objective

### ❌ Feature Factory
**Problem:** Shipping features without measuring impact  
**Solution:** Define success metrics before building; measure after launch

### ❌ Analysis Paralysis
**Problem:** Over-researching, never shipping  
**Solution:** Set "confidence threshold" (70% minimum to proceed)

### ❌ Build It and They Will Come
**Problem:** Assuming usage without validation  
**Solution:** Prototype, test, validate before full build

## 📈 Success Metrics for Prioritization Process

**Good prioritization results in:**
- ✅ 80%+ of shipped features achieve expected impact
- ✅ <10% of initiatives cut mid-development
- ✅ Effort estimates within 20% of actuals
- ✅ Roadmap commitments met 90%+ of the time
- ✅ High team confidence in priorities (survey quarterly)

---

**Bottom Line:**  
RICE provides a data-driven baseline for prioritization, but PM judgment is essential to balance quantitative scores with qualitative strategic considerations. The goal is not to be perfectly scientific, but to make transparent, defensible decisions that maximize customer value within team constraints.
