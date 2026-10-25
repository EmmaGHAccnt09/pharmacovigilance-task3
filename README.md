# Task 3: Advanced Causality Assessment, MedDRA Coding & Signal Detection

**Repository Name:** `pharmacovigilance-task3`  
**Course / Internship:** Pharmacovigilance Virtual Internship (VirtualWorks Lab / Noivrn)  
**Module:** Pharmacovigilance Analytics, Terminology Standardization & Safety Risk Evaluation  

---

## 📌 Task Overview
This task builds upon the Individual Case Safety Report (ICSR) generated in Task 2. It demonstrates the application of standardized medical terminologies (**MedDRA Hierarchy**), dual causality assessment tools (**WHO-UMC & Naranjo Algorithm**), and post-marketing risk management protocols for patient safety.

---

## 1. MedDRA Coding & Terminology Mapping

To ensure international harmonization across global safety databases (e.g., WHO VigiBase, FDA FAERS), the reported adverse event is mapped through the **Medical Dictionary for Regulatory Activities (MedDRA)** hierarchy:

| MedDRA Level | Terminology / Code | Description / Clinical Mapping |
| :--- | :--- | :--- |
| **System Organ Class (SOC)** | Skin and subcutaneous tissue disorders *(10040785)* | Highest level of hierarchy representing anatomical/etiological system affected. |
| **High-Level Group Term (HLGT)** | Epidermal and dermal conditions *(10014982)* | Sub-category grouping related skin conditions. |
| **High-Level Term (HLT)** | Rashes, eruption and exanthems NEC *(10037844)* | Broad classification of dermatological reactions. |
| **Preferred Term (PT)** | Drug eruption *(10013687)* / Angioedema *(10002424)* | Standardized single medical concept used for signal analysis. |
| **Lowest Level Term (LLT)** | Generalized maculopapular skin rash *(10025429)* | Specific reported verbatim term recorded during clinical presentation. |

---

## 2. Comparative Causality Assessment

### A. WHO-UMC Causality Assessment Scale
* **Category Assigned:** **PROBABLE / LIKELY**
* **Clinical Justification:**
  1. **Temporal Relationship:** Event onset occurred on Day 3 following drug initiation, representing a reasonable time sequence.
  2. **Dechallenge:** Positive dechallenge was demonstrated when rash and angioedema abated within 48 hours of drug withdrawal.
  3. **Concomitant Exposure:** Concomitant Paracetamol PRN use is unlikely to account for the acute hypersensitivity rash.
  4. **Rechallenge:** Rechallenge was ethically withheld and not required to establish probability.

---

### B. Naranjo Probability Scale Evaluation

| Question / Parameter | Score Option | Assigned Value | Clinical Rationale |
| :--- | :---: | :---: | :--- |
| 1. Previous conclusive reports on this reaction? | Yes (+1) | **+1** | Well-documented penicillin/amoxicillin beta-lactam hypersensitivity. |
| 2. Did event appear after suspect drug administered? | Yes (+2) | **+2** | Symptoms emerged on Day 3 of therapy. |
| 3. Did reaction improve when drug was stopped? | Yes (+1) | **+1** | Positive dechallenge; clear improvement within 48h of discontinuation. |
| 4. Did reaction reappear upon re-administration? | Unknown (0) | **0** | Rechallenge not performed due to risk of severe anaphylaxis. |
| 5. Are there alternative causes that could cause this? | No (+2) | **+2** | Absence of viral exanthem history or reactive concomitant medications. |
| 6. Did reaction reappear when placebo given? | No (0) | **0** | Placebo testing not applicable in clinical practice. |
| 7. Was drug detected in toxic blood concentrations? | No (0) | **0** | Standard therapeutic dosage administered; drug levels not measured. |
| 8. Was reaction dose-dependent? | Unknown (0) | **0** | Reaction occurred under standard therapeutic dosage (500 mg TID). |
| 9. Previous similar reaction to same/similar drugs? | Unknown (0) | **0** | Patient reported NKDA prior to this event. |
| 10. Was event confirmed by objective evidence? | Yes (+1) | **+1** | Clinical examination confirmed cutaneous maculopapular rash and facial edema. |
| **TOTAL SCORE** | | **+7** | **PROBABLE** *(Range 5–8)* |

---

## 3. Signal Detection & Risk Management Plan (RMP)

### A. Signal Assessment
* **Disproportionality Screening:** Monitored via Reporting Odds Ratio (ROR) and Proportional Reporting Ratio (PRR) in spontaneous reporting registries.
* **Risk Type:** Identified Risk (Hypersensitivity / Beta-lactam allergic reaction).

### B. Risk Mitigation Strategy
1. **Patient Care Management:**
   * Immediate cessation of suspect beta-lactam agent.
   * Documented drug allergy in patient's electronic health record (EHR/EMR).
   * Recommendation for future alternative antibiotic therapy (e.g., Macrolides or Fluoroquinolones, subject to allergy panel).

2. **Regulatory & Industry Action:**
   * Submission of ICSR to national regulatory authority (e.g., Philippine FDA / VigiBase) within mandatory expedited reporting timeline (15 calendar days for serious, periodic for non-serious).
   * Review product labeling and SmPC (Summary of Product Characteristics) for allergy warning updates if novel safety signals emerge.

---

## ✒️ Reporter Verification
* **Evaluator Name:** Emmalyn Chua Mondano-Mariquit  
* **Professional Qualification:** Registered Pharmacist (RPh) / Healthcare Virtual Assistant Intern  
* **Date of Assessment:** October 26, 2026
