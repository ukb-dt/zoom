# A. Project Orientation & Collaboration Setup

## Meeting Summary

- **Summary notes from our last meeting**  
  - Review them [here](#quick-recap)
- **You'll put your GitHub account to use next month**  
  - Username: `EdwardSsemambo`

## Context & Focus Areas

Notes to [contextualize our work](https://ukb-dt.github.io/ed-01/):

- **Decision support** → **Intelligence** → **Compute** → **Energy** → **Monetary costs**
  - Ecological costs are important
  - But it's the demand we are focusing on for now
  - Your feedback is very welcome

---

## Quick Recap

Ukubona and Edward discussed the setup and importance of using GitHub for their project collaboration, including account creation and access permissions. They explored technical aspects of using Unix commands and GitHub, while also discussing the implications of AI technology on healthcare and energy demand. The conversation ended with a discussion on meeting structures and scheduling, including plans for strategic discussions around grants and PhD applications.

## Next Steps

### Immediate Actions
- [X] **Edward**: Send GitHub username to Ukubona via WhatsApp
- [ ] **Ukubona**: Invite Edward to the GitHub workspace
- [ ] **Ukubona**: Create additional GitHub onboarding instructions
- [ ] **Ukubona**: Guide Edward through the final onboarding steps for GitHub

### Edward's Learning Path
- [ ] **Edward**: Complete the GitHub onboarding process
- [ ] **Edward**: Learn basic Unix commands for working with GitHub and VS Code
- [ ] **Edward**: Practice the workflow of cloning repositories, making changes, and pushing to GitHub
- [ ] **Edward**: Make a contribution to a minor project to demonstrate GitHub workflow
- [ ] **Edward**: Review the Digital Twin application and Energy section

### Administrative
- [X] **Ukubona**: Confirm Edward's GitHub account name

## Detailed Summary

### GitHub Account Setup for Collaboration
Ukubona and Edward discussed the importance of creating a GitHub account for their project collaboration, as all work will be conducted through GitHub to ensure efficient tracking and version control. Edward confirmed he had previously created a GitHub email and username, and Ukubona requested that Edward share his username via WhatsApp to be invited to the relevant workspace. They also touched on the need for Edward to complete his onboarding process and the significance of using GitHub for collaboration, emphasizing its efficiency over traditional file-sharing methods.

- **Username**: `EdwardSsemambo`

### GitHub Basics and Version Control
Ukubona explained to Edward the basics of using Unix commands and GitHub, emphasizing that while GitHub offers free access, there are limitations on storage and features that encourage upgrading to paid plans. Edward confirmed he had created a GitHub account and discussed the importance of using GitHub for version control instead of email sharing. Ukubona advised Edward to explore the platform further and mentioned he would have access to detailed clinical scenarios that inspired their work.

### AI in Healthcare System Access
Ukubona and Edward discussed accessing a healthcare company's system, clarifying the process of navigating through the application to reach the energy section. Ukubona emphasized the importance of having direct access URLs for efficiency and explained the need for backend access for certain tasks. They also discussed the impact of ChatGPT's release on NVIDIA's valuation, highlighting the growing demand for AI and its role in decision-making processes. Ukubona concluded by explaining how AI could help in personalizing risks related to patient care.

### Personalized Risk Assessment in Healthcare
Ukubona discussed the limitations of communicating medical statistics to patients, emphasizing that averages can be misleading and personalized risk assessments are more appropriate. He explained that personalized risk calculations require a digital platform to handle complex variables and simulations, which is necessary for effective decision-making in healthcare and other domains. Ukubona also touched on the relationship between computational power and artificial intelligence, noting that advancements in AI often require significant computational resources and financial investment.

### Energy Demand and Price Trends
Ukubona and Edward discussed the relationship between energy demand, particularly in the context of technology companies like NVIDIA, and the resulting price increases in energy over the past 50 years. They planned to analyze historical energy price trends and explore the implications of increased demand for energy, which they compared to a tree within a larger ecosystem. They also decided on a meeting structure, distinguishing between random, unplanned communications via WhatsApp and regular, ritual meetings held weekly or bi-weekly, with the aim of discussing strategic matters such as grants and PhD applications.

### Meeting Structure and Strategic Planning
Ukubona and Edward discussed the structure and scheduling of meetings, distinguishing between unplanned, ritualized, and strategic meetings, with a focus on digital documentation and operational tracking. They explored the tactical and strategic implications of Edward's OPT status and potential PhD plans, emphasizing flexibility and the importance of aligning timelines with academic deadlines. Edward shared insights into his current status and future plans, while Ukubona highlighted the evolving nature of their collaboration and the potential for grants and strategic shifts. They agreed to review timelines and next steps in their upcoming meeting.

---

*Last updated: Thu Oct 16, 2025*

# B. Ukubona Energy Framework 

## Our Tree Metaphor + Actual Context

| **Tree Layer** | **Our Input** | **Ukubona Context** | **Reconciliation** |
|---|---|---|---|
| **Soil (Fuels)** | Fuels | Oracle, NVIDIA, AMD, Broadcom partnerships; renewable contracts; grid capacity | Energy suppliers compete for clean power. Big AI locks in 30+ GW contracts, leaving less for simulations. |
| **Roots (Access + Untapped)** | Access + Untapped | Renewable supply constraints; household/clinic/city electricity access | Ukubona simulations need sub-$0.01 per prediction to stay accessible as grid costs rise. |
| **Trunk (Supply)** | Utility Companies & Supply | Data center infrastructure (4.5–10+ GW per deal); OpenAI's 30 GW total commitment | Power provisioning is now a deal component. Energy is a cost center competing for limited clean supply. |
| **Branches (dE/dt & Demand)** | dE/dt & Demand; Various Industries | Kidney health simulations (Ukubona), AI training (OpenAI), hospitals, cities | Demand heterogeneity: AI hyperscalers vs. medical research. dE/dt = instantaneous demand spikes during sim runs. |
| **Canopy/Fruit (Output + Cost)** | ∫Power dt + Monetary Cost | Total kWh used per sim (~0.1 kWh/case) + electricity bill impact ($10–20/month per household in affected regions) | Energy consumed over time (integral) directly translates to cost. Efficiency is survival—sub-$0.01/prediction is the target. |
| **Meta Layer (Demands)** | Decision support, Intelligence, Compute, Energy, Monetary costs | Kidney disease predictions → clinical decisions; energy tracking embedded in outputs | Simulations *are* decision support. Intelligence requires compute. Compute requires energy. Energy = cost feedback loop. |

---

## Answering 3 Questions

### 1. **Are we modeling this for a specific context?**

**Yes.** Ukubona builds kidney disease simulations for clinical decision-making (organ donor screening, 20-year risk modeling). The energy angle is *instrumental*: as AI hyperscalers sign multi-billion-dollar power deals (30+ GW by Oct 2025), electricity gets expensive, threatening research accessibility. Our job is to track and optimize energy *within* the simulation pipeline.

**Context tie-in:** OpenAI's 30 GW commitment ≈ 2% of U.S. grid. This drives up costs for households ($10–20/month) and research. Ukubona stays viable by keeping per-prediction cost under $0.01.

---

### 2. **How do the "decision support" and "intelligence" demands feed back into the tree?**

**Feedback loop:**
- **Decision Support** → Clinical teams use our sim outputs (predictions) to decide on donor viability.
- **Intelligence** → Outputs must include risk metrics (age, BP, genetics, aperiodic complexity).
- **Compute** → Higher decision quality = more cases to model = higher CPU/GPU demand.
- **Energy** → More compute = more power draws (dE/dt spikes).
- **Monetary Cost** → Rising grid costs limit how many cases can be modeled affordably.

**Back to roots:** If energy prices spike, Ukubona can't afford to run as many simulations → less intelligence → worse decisions. The tree *starves* from the [bottom](https://ukb-dt.github.io/wl/nairobi/roots.jpg).

> *Roots denied access to fuel by concrete*      
> -- Westlands, Nairobi

<img src="https://ukb-dt.github.io/wl/nairobi/roots.jpg" alt="Roots Nairobi" width="300">

**Our role:** Instrument the simulation to measure kWh per output, identify where energy is wasted, and optimize scheduling for low-cost grid periods.

---

### 3. **Is the framework meant to guide resource allocation or identify bottlenecks?**

**Both, but bottleneck identification comes first:**

**Resource Allocation:**
- Which suppliers (Oracle, NVIDIA, AMD, Broadcom) offer the best energy efficiency per TFLOP?
- When should Ukubona run sims? (e.g., off-peak grid hours, renewable generation peaks)
- Trade-off: more accurate models (higher compute) vs. lower energy cost.

**Bottleneck Identification:**
- **Supply bottleneck:** 30 GW contracts lock up clean power → household costs rise.
- **Energy bottleneck:** Each sim run costs ~$0.001–$0.01. Scale to 10k cases = $10–100/day—unaffordable if grid rates spike.
- **Decision bottleneck:** If sims are too slow or expensive, clinicians can't iterate on "what-if" scenarios.

**Month 1 task:** Build a demo notebook that tracks kWh per sim output and flags when costs exceed acceptable bounds.

---

## Operational Summary for 12-Month Plan

Our framework perfectly maps the Ukubona challenge:

| **Month Range** | **Tree Layer Focus** | **Energy Goal** |
|---|---|---|
| **1–2 (Setup + Data Gen)** | Roots → Trunk | Baseline: measure kWh per case; establish $0.01/prediction budget. |
| **3–5 (Dashboard + Complexity)** | Branches | Track dE/dt (energy demand spikes); identify peak consumption patterns. |
| **6–8 (Stress Tests + Calibration)** | Branches → Canopy | Test edge cases; measure energy cost of added complexity (entropy metrics). |
| **9–11 (Optimization + Docs)** | Trunk → Roots | Scheduling logic; supplier selection; renewable procurement. |
| **12 (Wrap-Up)** | Canopy/Fruit | Final ∫Power dt report; cost insights; handoff. |

---

## Key Insight

This tree isn't just infrastructure—it's a **cost and accessibility model**. Energy flows up (Soil → Roots → Trunk → Branches → Canopy), but *cost* flows down. Optimization means: **keep intelligence high, energy (and cost) low.**
