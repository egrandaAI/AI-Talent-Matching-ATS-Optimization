# AI-Driven Talent Matching & ATS Bias Reduction  
### Rethinking Recruitment Systems through Data, AI and System Design

---

## 🚀 Overview

This project was developed during the **ESSCA Data Hackathon 2026**, addressing a critical and persistent paradox in modern labor markets:

👉 **Why do companies struggle to fill jobs while unemployment remains high?**

Using real data from the **Auvergne-Rhône-Alpes (AURA) region in France**, this project reframes the problem as a **systemic failure in recruitment mechanisms**, rather than a simple labor shortage.

It combines:
- **labour market analytics**
- **AI system design**
- **recruitment process analysis**

to propose a more effective and fair way to match talent with opportunity.

---

## ⚠️ The Problem

Despite a clear availability of workforce, companies continue to struggle filling roles:

- **293,000 unemployed individuals** in AURA  
- **8,000+ industrial jobs unfilled annually**  
- **~61.5% average recruitment difficulty rate** in industrial sectors  

📊 These indicators reveal a structural contradiction:

> 📉 Unemployment is decreasing  
> 📈 Hiring difficulty remains high  

👉 This is **not a labor shortage** — it is a **systemic skills mismatch**

---

## 🔍 Root Cause: A Systemic Filtering Problem

Beyond macro indicators, the analysis identified a critical bottleneck:

> The mismatch is not only in the market — it is embedded in how candidates are evaluated.

### Core issue:
Most recruitment pipelines rely on **Applicant Tracking Systems (ATS)** that apply:

- Boolean keyword matching  
- rigid rule-based filters  
- automated CV parsing  
- binary decision logic  

---

## ⚙️ How ATS Systems Work (Technical Perspective)

Traditional ATS systems operate as **rule-based classification engines**:
IF candidate matches predefined criteria → PASS
ELSE → REJECT


These criteria typically include:

- exact keyword matches  
- minimum years of experience thresholds  
- certification requirements  
- formatting-dependent parsing  

👉 This creates a **binary evaluation system** with no intermediate states.

---

## ❗ Why Binary Filtering Fails in Mismatch Contexts

This approach becomes highly inefficient in regions like AURA.

### 1. Near-match candidates are discarded
Candidates are rejected for reasons such as:
- expired (but renewable) licenses or permits  
- slightly lower experience thresholds  
- missing short-term certifications  

👉 These are **temporary or fixable gaps**, not true disqualifiers.

---

### 2. No concept of trainability
ATS systems do not evaluate:
- how quickly a gap can be closed  
- whether skills are transferable  
- if short training could unlock employability  

---

### 3. No explainability or feedback loop
- Candidates receive no insight into rejection  
- Recruiters cannot assess “almost fit” profiles  
- No pathway for reskilling or re-entry  

---

### 4. Industrial profiles are disproportionately penalized
In sectors like manufacturing and logistics:

- Skills are often **practical, not keyword-heavy**  
- Certifications may **expire periodically**  
- Experience may not be **standardized in CVs**  

👉 Result: **systematic exclusion of viable workers**

---

## 🧠 Research & Data Analysis

The project integrates multiple datasets from public French and regional sources:

- Labour shortage datasets (e.g., BMO 2025)  
- Unemployment trends across AURA  
- Job vacancy and demand indicators  
- Recruitment difficulty rates by sector  

### Analytical approach:
- Trend comparison: unemployment vs hiring difficulty  
- Segmentation of occupations by demand vs difficulty  
- Clustering of structurally hard-to-fill jobs  

📈 Key finding:
- Over **60 job categories** were identified as structurally difficult to fill  

👉 confirming that the issue is **persistent and systemic**, not cyclical.

---

## 💡 Key Insight

> The recruitment system treats **“not perfect” as “not viable”**

This leads to:

- viable candidates filtered out early  
- reduced visibility for recruiters  
- persistent unfilled vacancies  
- continued unemployment  

---

## 💡 Proposed Solution

### 🔹 AURA AI SkillsBridge

A dual-layer AI system designed to transform recruitment from **binary filtering → structured decision-making**

---

### 1. ATS FairMatch Layer

A plug-in layer integrated into existing ATS systems:

- ✅ **Fit Score (0–100)** instead of pass/fail  
- ✅ **Explainability** (why a candidate matches or not)  
- ✅ **Gap Analysis** (what is missing)  
- ✅ **Actionability** (training or license renewal pathways)

👉 Introduces **graded, interpretable evaluation**

---

### 2. Talent Re-Discovery Engine

- Scans regional unemployed talent pools  
- Identifies **near-match candidates**  
- Detects **renewable licenses or short-term gaps**  
- Proactively reconnects candidates with job opportunities  

👉 Ensures viable talent is not lost due to initial filtering

---

### 🔄 System Logic

The system creates a **closed-loop recruitment model**:

1. Identify relevant candidates (even imperfect matches)  
2. Evaluate using contextual scoring instead of rigid rules  
3. Highlight:
   - trainability  
   - short training paths  
   - renewable licenses or permits  
4. Enable better recruiter decision-making  

👉 Transforms recruitment from **filtering → interpreting → enabling**

---

## 🎯 Business Impact

This solution directly addresses the AURA paradox:

- Reduces talent loss caused by rigid ATS filters  
- Improves hiring efficiency in high-demand sectors  
- Makes **hidden viable candidates visible again**  
- Supports workforce activation through:
  - reskilling pathways  
  - license renewals  
  - short-term training opportunities  

👉 Moves recruitment from exclusion to optimization

---

## ⚖️ Ethical Value

- Reduces bias from rigid keyword-based filtering  
- Improves transparency in hiring decisions  
- Enables fairer access to employment opportunities  
- Aligns AI with **decision support**, not blind automation  

---

## 🏆 Hackathon Outcome

🥈 **2nd Place — ESSCA Data Hackathon 2026**

Evaluated on:
- originality  
- feasibility  
- data robustness  
- real-world relevance  

---

## 💻 Repository Contents

- `/index.html` → Interactive consulting-style case study  
- `/assets` → Visuals and design components  
- `/data` → Processed datasets (if included)  
- `/notebooks` → Python analysis (optional)

---

## 👩‍💻 Authors
 
**Estefania Granda Orozco**

**And credit to my teammates!**
Manuela Marques de Toledo Piza
Christian Kadima
Niloofar Vafa

---

👉 Bridging **data, AI, and real-world business impact**
