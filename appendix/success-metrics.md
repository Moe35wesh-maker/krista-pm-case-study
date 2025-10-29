# Success Metrics & KPIs

## 🎯 Overview

This document defines how we measure success across the product roadmap. Metrics are organized by type: North Star, Product Health, Business Outcomes, and Feature-Specific.

## ⭐ North Star Metric

**Time-to-First-Automation**

**Definition:** Time elapsed from user signup to their first successfully executed automation

**Why This Metric:**
- Directly correlates with activation and retention
- Proxy for user-perceived value
- Actionable: can be improved through product changes
- Leading indicator of long-term success

**Current State:** 4-8 hours (estimated)  
**Target State:** <2 hours by Month 6

**How to Measure:**
- Track timestamp: signup → first automation created → first successful execution
- Segment by user role, company size, industry
- Monitor weekly cohorts

**Success Criteria:**
- 70% of users achieve first automation within 2 hours
- Median time <90 minutes by Month 6

---

## 📊 Metric Framework

### Pirate Metrics (AARRR)

#### Acquisition
**How users find and sign up for Krista**

| Metric | Current | 6M Target | 12M Target | 24M Target |
|--------|---------|-----------|------------|------------|
| Website Visitors | Baseline | +50% | +150% | +300% |
| Trial Signups | Baseline | +100% | +250% | +500% |
| Conversion Rate (Visit→Signup) | 3% | 5% | 7% | 10% |
| Cost Per Acquisition (CPA) | $500 | $400 | $300 | $250 |

**Tracked By:** Marketing analytics (Google Analytics, HubSpot)

---

#### Activation
**How users experience the "aha moment"**

| Metric | Current | 6M Target | 12M Target | 24M Target |
|--------|---------|-----------|------------|------------|
| Activation Rate | 35% | 70% | 75% | 80% |
| Time-to-First-Automation | 4-8 hrs | <2 hrs | <1 hr | <30 min |
| Onboarding Completion | 40% | 80% | 85% | 90% |
| Template Adoption | 20% | 80% | 85% | 90% |

**Activation Definition:** User creates and successfully executes their first automation

**Tracked By:** Product analytics (Amplitude, Mixpanel, or custom)

---

#### Retention
**How users continue to get value over time**

| Metric | Current | 6M Target | 12M Target | 24M Target |
|--------|---------|-----------|------------|------------|
| Day 7 Retention | 50% | 65% | 70% | 75% |
| Day 30 Retention | 40% | 55% | 60% | 65% |
| Monthly Active Users (MAU) | Baseline | +100% | +200% | +400% |
| MAU/Signups Ratio | 50% | 60% | 65% | 70% |
| Weekly Automation Executions | Baseline | +150% | +300% | +500% |

**Retention Cohorts:** Analyze by signup month, segment by use case

**Tracked By:** Product analytics + CRM

---

#### Revenue
**How we monetize the platform**

| Metric | Current | 6M Target | 12M Target | 24M Target |
|--------|---------|-----------|------------|------------|
| Monthly Recurring Revenue (MRR) | $833K | $1.2M | $2M | $2.5M |
| Annual Recurring Revenue (ARR) | $10M | $14M | $24M | $30M |
| Average Revenue Per Account (ARPA) | $4,000/yr | $4,500/yr | $5,500/yr | $6,000/yr |
| Net Revenue Retention (NRR) | 110% | 120% | 130% | 140% |
| Gross Revenue Retention (GRR) | 90% | 92% | 94% | 95% |

**Revenue Segments:**
- Core platform subscriptions
- Add-on modules (Agent Hub, Analytics, Industry Packs)
- Marketplace revenue (templates, models, extensions)
- Professional services

**Tracked By:** Finance system (Stripe, QuickBooks, or ERP)

---

#### Referral
**How users become advocates**

| Metric | Current | 6M Target | 12M Target | 24M Target |
|--------|---------|-----------|------------|------------|
| Net Promoter Score (NPS) | 35 | 45 | 55 | 65 |
| Referral Sign-ups | 5% | 10% | 15% | 20% |
| Case Studies Published | 3 | 8 | 15 | 25 |
| G2/Capterra Reviews | 20 | 50 | 100 | 200 |
| Average Rating | 4.3/5 | 4.5/5 | 4.7/5 | 4.8/5 |

**Tracked By:** NPS surveys (Delighted, Wootric), review platforms, CRM

---

## 🎯 Product Health Metrics

### Engagement

| Metric | Definition | Current | Target |
|--------|-----------|---------|--------|
| DAU/MAU Ratio | Daily active / Monthly active | 25% | 35% |
| Session Duration | Avg time in product per session | 15 min | 20 min |
| Sessions per User per Week | Frequency of use | 3 | 5 |
| Automations per User | Total active automations | 5 | 12 |
| Integrations per User | Connected apps | 3 | 6 |

### Feature Adoption

| Feature | Launch Date | Current Adoption | Target Adoption (90 days) |
|---------|------------|-----------------|--------------------------|
| Guided Onboarding | M1 | N/A | 80% |
| Template Library | M3 | N/A | 80% |
| Integration Health Dashboard | M2 | N/A | 60% |
| Agent Orchestration Hub | M9 | N/A | 50% |
| Analytics & Process Mining | M9 | N/A | 40% |
| Template Marketplace | M12 | N/A | 60% |

**Adoption Definition:** % of active users who used feature at least once in past 30 days

### Quality Metrics

| Metric | Current | 6M Target | 12M Target |
|--------|---------|-----------|------------|
| Platform Uptime | 99.5% | 99.7% | 99.9% |
| Automation Success Rate | 95% | 97% | 98% |
| Average Execution Time | 30 sec | 20 sec | 15 sec |
| Support Tickets per 100 Users | 15 | 10 | 8 |
| Time to Resolution (Avg) | 24 hrs | 12 hrs | 6 hrs |
| Bug Escape Rate | 5% | 3% | 2% |

---

## 💼 Business Outcome Metrics

### Sales & Marketing

| Metric | Current | 6M Target | 12M Target | 24M Target |
|--------|---------|-----------|------------|------------|
| Sales Qualified Leads (SQLs) | Baseline | +50% | +150% | +300% |
| Win Rate | 30% | 35% | 40% | 45% |
| Average Deal Size | $40K | $45K | $55K | $65K |
| Sales Cycle Length | 60 days | 50 days | 45 days | 40 days |
| Customer Acquisition Cost (CAC) | $15K | $12K | $10K | $8K |
| CAC Payback Period | 18 mo | 15 mo | 12 mo | 10 mo |

### Customer Success

| Metric | Current | 6M Target | 12M Target | 24M Target |
|--------|---------|-----------|------------|------------|
| Customer Health Score | Baseline | 75/100 | 80/100 | 85/100 |
| Time-to-Value | 4 weeks | 1 week | 3 days | 1 day |
| Quarterly Business Reviews Held | 60% | 80% | 90% | 95% |
| Expansion Rate | 15% | 25% | 35% | 45% |
| Churn Rate (Logo) | 8% | 6% | 4% | 3% |
| Churn Rate (Revenue) | 10% | 8% | 6% | 5% |

### Partner & Ecosystem

| Metric | Launch | 12M Target | 24M Target |
|--------|--------|------------|------------|
| Active Technology Partners | 0 | 20 | 50 |
| Active ISV Partners | 0 | 5 | 10 |
| Partner-Sourced Revenue | 0% | 15% | 25% |
| Partner-Built Integrations | 0 | 100 | 500 |
| Marketplace GMV | $0 | $250K | $1M |

---

## 📋 Feature-Specific Success Metrics

### Guided Onboarding (Month 1-2)

**Leading Indicators:**
- % who start onboarding flow: >90%
- % who complete each step: >80%
- Drop-off rate per step: <15%

**Lagging Indicators:**
- Onboarding completion rate: 70% (target)
- Time-to-first-automation: <2 hours
- NPS delta (before/after): +10 points

**How to Measure:**
- Funnel analysis in product analytics
- User surveys at onboarding completion
- Cohort comparison (with vs. without onboarding)

---

### Template Library (Month 3-4)

**Leading Indicators:**
- Templates viewed per user: >10
- Template usage rate: 80%
- Templates deployed successfully: >90%

**Lagging Indicators:**
- Time-to-automation (template vs. scratch): 70% reduction
- Automation creation volume: 3x increase
- Template satisfaction score: >4.5/5

**How to Measure:**
- Template analytics (views, deployments, success rate)
- User feedback surveys
- A/B test (template group vs. control)

---

### AI Agent Orchestration Hub (Month 7-9)

**Leading Indicators:**
- Hub activation rate: 50% of new customers
- Agents per customer: 4+
- Multi-agent workflows created: 2+ per customer

**Lagging Indicators:**
- Agent Hub premium adoption: 50%
- Agent orchestration NPS: 60+
- Time saved vs. unorchestrated agents: 40%

**How to Measure:**
- Feature adoption dashboard
- Customer interviews and case studies
- Cost savings analysis

---

### Template Marketplace (Month 10-12)

**Leading Indicators:**
- Template creators: 100+
- Templates published: 500+
- Templates downloaded: 5,000+

**Lagging Indicators:**
- Marketplace GMV: $250K in 6 months
- % automations from marketplace: 60%
- Creator satisfaction: 80%+ would recommend

**How to Measure:**
- Marketplace analytics (transactions, revenue)
- Creator surveys
- User adoption metrics

---

## 🔍 Metric Instrumentation

### Analytics Stack

**Product Analytics:**
- Tool: Amplitude or Mixpanel
- Events tracked: 100+ key user actions
- Properties: user role, company size, industry
- Funnels: onboarding, activation, feature adoption

**Business Intelligence:**
- Tool: Tableau or Metabase
- Data warehouse: Snowflake or BigQuery
- Dashboards: executive, sales, CS, product

**Qualitative Research:**
- User interviews (10-15 per quarter)
- NPS surveys (quarterly)
- Feature feedback surveys (post-launch)
- Usability testing (monthly)

### Key Events to Track

**User Lifecycle:**
- account_created
- onboarding_started
- onboarding_completed
- first_automation_created
- first_automation_executed
- integration_connected
- template_used
- invited_team_member

**Feature Usage:**
- automation_created
- automation_executed
- integration_added
- template_browsed
- template_deployed
- agent_deployed
- marketplace_purchase
- analytics_viewed

**Business Events:**
- subscription_started
- subscription_upgraded
- subscription_downgraded
- subscription_cancelled
- support_ticket_created
- nps_survey_completed

---

## 📊 Metric Dashboards

### Executive Dashboard (Weekly Review)

**Top-Line Metrics:**
- ARR (current, growth rate, forecast)
- New Customers (this week, this month, this quarter)
- Net Revenue Retention
- Churn Rate (logo and revenue)

**Product Health:**
- MAU (growth rate)
- Activation Rate
- Time-to-First-Automation
- NPS

**Sales & Marketing:**
- Pipeline (current, change from last week)
- Win Rate
- Average Deal Size
- Marketing Qualified Leads

---

### Product Dashboard (Daily Review)

**Engagement:**
- DAU, WAU, MAU
- DAU/MAU ratio
- Active automations (total, per user)
- Session duration

**Activation:**
- New signups (daily)
- Activation rate (7-day rolling)
- Onboarding completion rate
- Time-to-first-automation (median)

**Feature Adoption:**
- Top 10 features by usage
- New feature adoption curves
- Feature engagement by cohort

**Quality:**
- Uptime (current, 7-day, 30-day)
- Automation success rate
- Support tickets (new, open, resolved)
- Page load time (P50, P95)

---

### Sales Dashboard (Real-Time)

**Pipeline:**
- Total pipeline value
- Pipeline by stage
- Forecast vs. target
- Deal velocity

**Performance:**
- Deals closed (this week, this month)
- Win rate (overall, by segment)
- Average deal size
- Sales cycle length

**Leading Indicators:**
- SQLs (new, total)
- Demos scheduled
- Trials started
- Proof-of-concept conversions

---

### Customer Success Dashboard (Weekly)

**Health:**
- Customer health score distribution
- At-risk customers (churn probability >50%)
- Expansion opportunities
- Upcoming renewals

**Engagement:**
- Product usage by account
- Feature adoption by account
- Support tickets by account
- Last touchpoint date

**Outcomes:**
- QBRs completed (this quarter)
- Expansion ARR (this quarter)
- Churn prevented
- NPS by cohort

---

## 🎯 Goal-Setting Process

### OKR Framework (Quarterly)

**Objective:** What we want to achieve (qualitative, inspirational)

**Key Results:** How we measure success (quantitative, time-bound)

**Example - Q1 OKR:**

**Objective:** Dramatically reduce time-to-value and accelerate self-serve adoption

**Key Results:**
1. Increase activation rate from 35% to 70%
2. Reduce time-to-first-automation from 4-8 hours to <2 hours
3. Achieve 80% template usage rate among new users
4. Reduce onboarding-related support tickets by 40%

**Initiatives Supporting This OKR:**
- Guided onboarding flow
- Template library
- Integration health dashboard

---

## 📈 Reporting Cadence

### Daily
- DAU, signups, activation rate (automated Slack/email)
- Critical incidents and outages
- Major customer escalations

### Weekly
- Executive dashboard review (leadership team)
- Product metrics deep dive (PM + engineering)
- Sales pipeline review (sales team)

### Monthly
- All-hands metrics presentation (entire company)
- Board update (CEO + CFO)
- Customer health review (CS team)

### Quarterly
- OKR review and retrospective
- Strategic roadmap adjustment
- Metric targets recalibration

---

## 🔄 Metric Evolution

Metrics should evolve as the product matures:

**Early Stage (Now - Month 6):**
- Focus: Activation and retention
- Key Metrics: Time-to-first-automation, activation rate, D7/D30 retention

**Growth Stage (Month 6-12):**
- Focus: Scaling usage and expansion
- Key Metrics: MAU growth, feature adoption, NRR, ARPA

**Maturity Stage (Month 12-24):**
- Focus: Efficiency and ecosystem
- Key Metrics: CAC payback, LTV/CAC, marketplace GMV, partner-sourced revenue

---

**Bottom Line:**  
Success metrics should be few, measurable, and directly tied to business value. The North Star (time-to-first-automation) keeps the team aligned, while supporting metrics provide a comprehensive health check. Regular reviews ensure we're moving the needle on what matters most.
