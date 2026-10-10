# Case Study: Optimising Conversion Funnels via Contextual UX Filters on Myntra
## An Unsolicited Product & Interface Architecture Blueprint

### 1. Strategic Context & Problem Statement
In high-velocity consumer e-commerce platforms like Myntra, a major bottleneck during the final checkout stage is user **color anxiety**. When a user arrives at an apparel page, hidden friction loops arise regarding how a specific clothing shade will complement their individual skin tone. 

**The Problem:** Users experience deep fear that the color won't look good on them after purchasing. This anxiety triggers a massive cart abandonment loop right at the payment page. 
* Left unresolved, this frustration lowers the app's active session duration and damages overall sales revenue. 
* All these dropped clicks are captured inside the **Mixpanel Lexicon** event logs, showing a clear transaction leakage right at the final gateway step. 
* Additionally, it triggers a massive volume of costly product return logistics and creates long-term customer self-doubt.

---

### 2. User Behavior & Spatial Layout Constraints
To resolve this without introducing interface clutter, a strict spatial layout contract was designed based on human interaction biology:
 **Keyword-Triggered Visibility:** To preserve core screen real estate, the contextual skin-tone filter circles remain completely hidden by default. They load dynamically *only* when a user types a relevant search keyword (e.g., "dresses") into the search layout.
 **Ergonomic Action Placement:** Rather than hiding this capability inside a complex "Advanced Settings" dropdown menu at the top-right of the display viewport—where a one-handed user traveling on a bumpy local bus cannot reach it—the horizontal carousel row is anchored strictly within the lower 30% **Natural Thumb Sweep Zone**. This ensures friction-free execution in 0.1 seconds.

---

### 3. Systemic Safety Loop (Dismissal Anchoring)
If a user selects a skin-tone filter circle but later wants to change their mind and see all normal clothes again, the absence of an immediate exit route forces a hard exit from the application. 
* To prevent the application from behaving like it is **"livingly dead"** in the market through sudden drop-offs, an explicit on-screen **Dismissal Component** (`[X]` cross button) is introduced directly next to the carousel row.
* This serves as a low-weight reset trigger, providing a clean exit latch to reset the view state instantly, preserving active session metrics and protecting negative word-of-mouth drops.

---

### 4. Projected Business Metrics & Success Outcomes
When deployed into production sprint cycles, success is systematically measured across three primary validation registers:
1.  **Funnel Conversion Velocity:** An immediate increase in successful payment events as user hesitation drops.
2.  **Logistical Cost Reduction:** A massive, permanent reduction in product return rates and delivery tracking overheads.
3.  **Customer LTV Retention:** Enhanced brand loyalty, systemic trust, and organic word-of-mouth loops as user confidence increases.

---
**Author:** Bhavana Kalyan K  
*2026 Computer Science Engineering Graduate (CGPA: 8.5/10 | SJCIT)*  


