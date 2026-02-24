# 022_1 | all_patients

## Case

# Case vignette: HER2-amplified, trastuzumab-resistant metastatic colorectal cancer (based on NEJM_case_022)

Patient demographics and background

- Age/sex: 48-year-old patient (sex not explicitly stated in source). The patient was previously healthy with no family history of colorectal cancer or inherited cancer syndrome.
- Relevant comorbidities: History of deep venous thrombosis (reason to avoid bevacizumab). No other major comorbidities documented.
- Baseline functional and organ-status data: Baseline cardiac evaluation (echocardiogram) was performed prior to HER2-directed therapy and was sufficient to permit trastuzumab administration. No explicit ECOG performance-status score or baseline creatinine/liver-function panel values were provided in the report.

Clinical presentation and timeline

- Presentation: 1 week of right flank pain and bloody stools; hemoglobin on presentation 7.1 g/dL.
- Staging at presentation: Contrast-enhanced CT showed sigmoid colon thickening and multiple hepatic and pulmonary nodules. Biopsy of a liver lesion confirmed metastatic colorectal adenocarcinoma.
- Initial management timeline and response:
  - First-line: Capecitabine + oxaliplatin (every 3 weeks). Best response: stable disease at 3 months; progression at 6 months with a new adrenal metastasis.
  - Second-line: Capecitabine + irinotecan → progression.
  - Third-line: Capecitabine + irinotecan + cetuximab → progression after ~3 months.
  - Fourth-line: Regorafenib — brief (1 month) and poorly tolerated.
  - Fifth-line: Trastuzumab monotherapy (three 21-day infusions) — radiographic progression.
  - Sixth-line: Ado-trastuzumab emtansine (T-DM1) q21 days — durable objective radiographic response for 15 months without discernible toxicity; target hepatic lesion decreased from 4.8 cm → 5.3 cm (after trastuzumab) → 3.5 cm (3 months T-DM1) → 3.0 cm (6 months T-DM1) → 2.2 cm (12 months) → nadir 2.1 cm; two additional metastases achieved complete response. The patient later progressed and died in hospice care.

Pathology and biomarker results

- Histology: Adenocarcinoma consistent with colorectal primary (liver metastasis core needle biopsy).
- Mismatch repair / MSI status: Immunohistochemical expression of MLH1, MSH2, MSH6, PMS2 was intact (MMR-proficient, MSS).
- RAS/BRAF: Tumor was documented KRAS wild-type; NRAS/BRAF status not reported in the source.
- HER2 status by molecular methods:
  - NGS reported an ERBB2 (HER2) amplification (unexpected, actionable finding).
  - Orthogonal ddPCR validation showed approximately 28–30 HER2 copies per genome in tumor DNA vs ~2 copies in peripheral blood (estimated ~14-fold amplification over diploid).
  - No formal IHC 3+ or FISH ratio values were supplied in the text; ddPCR copy-number quantification is the primary HER2 metric reported.
- Other somatic variants (validated on NGS): APC R232* (truncating) and TP53 splice-site 97_1G>A. Variant allele fractions (VAF) and read depths for these SNVs were not reported in the source.

Radiology

- Baseline and on-therapy CT: multiple hepatic and pulmonary metastases and an adrenal metastasis at progression. Serial target hepatic lesion diameters are reported above.
- Radiographic changes on T-DM1: sustained lesion shrinkage and hypodense central changes consistent with treatment-induced necrosis.

Prior treatments, toxicities and tolerability

- Prior cytotoxic regimens: capecitabine + oxaliplatin; capecitabine + irinotecan ± cetuximab.
- Anti-angiogenic therapy: Bevacizumab omitted due to rectal bleeding and prior DVT.
- Regorafenib: poorly tolerated, discontinued.
- Trastuzumab monotherapy: three cycles — progression.
- Ado-trastuzumab emtansine (T-DM1): administered every 21 days for 15 months with objective response and no discernible toxicity reported.

Molecular interpretation and clinical impression

- High-level ERBB2 amplification (~28–30 copies by ddPCR) in KRAS wild-type, MSS mCRC indicates HER2 as a clonal oncogenic driver and a rational therapeutic target; ADC therapy (T-DM1 in this case) produced a durable response despite trastuzumab monotherapy failure, consistent with ADC payload delivery overcoming resistance to antibody blockade alone.

Limitations in source data

- Patient sex not specified. ECOG performance-status and detailed organ-function labs (LFTs, creatinine) not provided. VAF and read-depth for APC/TP53 not reported. HER2 IHC/FISH categorical scores not provided — ddPCR copy number is the principal HER2 metric.

Source: Haslem DS et al., "Precision Oncology Strategy in Trastuzumab-Resistant HER2–Positive Colon Cancer: Case Report of Durable Response to Ado-Trastuzumab Emtansine" (JCO Precision Oncology, 2017); internal filename NEJM_case_022.


---

## Q1 (022_1)

Given this patient’s tumor harbors a high-level ERBB2 amplification (~28–30 copies by ddPCR), is KRAS wild-type and MSS, which HER2-directed regimens are supported by current phase II data and guideline recommendations for refractory metastatic colorectal cancer and which would be preferred in 2024–2025 for an otherwise fit patient?

### Answer 1

Phase II data and guideline consensus support several HER2-directed approaches in HER2-amplified, RAS/BRAF wild-type mCRC: dual HER2 blockade (trastuzumab + lapatinib; HERACLES) and trastuzumab + pertuzumab (MyPathway) have demonstrated activity, and HER2-directed antibody–drug conjugates (trastuzumab deruxtecan, T-DXd) have shown high response rates in DESTINY-CRC studies. By 2024–2025, T-DXd (trastuzumab deruxtecan) is considered a preferred option for many patients with prior lines of therapy given robust response data and regulatory expansions; dual-antibody or antibody+TKI combinations remain reasonable alternatives depending on prior exposures, toxicity profile, and trial availability. Selection should incorporate prior trastuzumab exposure, organ function, and patient comorbidities.

---

## Q2 (022_2)

How should a ddPCR result of ~28–30 HER2 copies per genome be interpreted clinically relative to IHC/FISH thresholds used in colorectal HER2 trials, and is orthogonal confirmation required prior to HER2-directed therapy?

### Answer 2

Approximately 28–30 HER2 copies per genome by ddPCR indicates high-level amplification consistent with an oncogenic driver and is clinically actionable. CRC HER2 trials and scoring systems typically use IHC 3+ and/or high-level FISH amplification as eligibility; a ddPCR copy-number in this range corresponds to high-level amplification well above common trial thresholds. Orthogonal confirmation (IHC or FISH) is often recommended when feasible for diagnostic certainty and trial entry, but in the setting of unequivocal high-level amplification by a validated assay, multidisciplinary molecular tumor board consensus may be sufficient to proceed with HER2-directed therapy.

---

## Q3 (022_3)

Why might an antibody–drug conjugate (ADC) such as T-DM1 or trastuzumab deruxtecan produce clinical responses after progression on trastuzumab monotherapy, and what tumor molecular feature(s) in this patient increase the likelihood of ADC benefit?

### Answer 3

ADCs deliver a cytotoxic payload directly to HER2-expressing tumor cells via receptor-mediated internalization, producing cell death independent of pure HER2 signaling blockade; this can overcome resistance mechanisms to antibody therapy (e.g., downstream pathway activation, partial receptor blockade). High-level HER2 amplification and increased receptor density (as seen here ~28–30 copies) enhance ADC binding and internalization, increasing payload delivery and the likelihood of response despite prior trastuzumab failure.

---

## Q4 (022_4)

If trastuzumab deruxtecan (T-DXd) is being considered in 2024 for this patient, what baseline evaluations and on-treatment monitoring are required because of ADC-specific toxicities, and how does substantial hepatic metastatic disease affect eligibility or monitoring?

### Answer 4

Baseline evaluation should include thorough pulmonary assessment and symptom review for ILD/pneumonitis risk, baseline LVEF/cardiac evaluation, comprehensive hepatic panel (AST/ALT, bilirubin), and performance status assessment. On-treatment, closely monitor for ILD/pneumonitis (regular clinical assessment and low threshold for chest CT if symptoms), serial liver function tests, and hematologic parameters. Significant hepatic metastases do not preclude T-DXd but marked hepatic impairment or abnormal bilirubin/transaminases may necessitate dose adjustments or exclusion per trial/label. Close monitoring is required for hepatotoxicity and dose modifications per product label/trial criteria.

---

## Q5 (022_5)

Given that the tumor is MSS (MMR-proficient) and KRAS wild-type, would single-agent immune checkpoint blockade be recommended at this time and under what circumstances could immunotherapy be considered later?

### Answer 5

Single-agent PD-1/PD-L1 immune checkpoint inhibitors are not recommended for MSS mCRC outside of a trial because response rates are very low. Immunotherapy could be considered if the tumor later demonstrates MSI-high conversion, very high TMB, or if enrolled in trials combining immunotherapy with other modalities intended to sensitize MSS tumors (e.g., targeted therapy + checkpoint inhibitor), but routine use is not guideline-supported for MSS disease.

---

## Q6 (022_6)

At progression after 15 months on T-DM1, what molecular re-evaluation strategy (sample types and assays) should be pursued to guide subsequent management, and which emergent findings would most likely change therapy?

### Answer 6

Obtain a re-biopsy of an accessible progressing lesion for comprehensive tissue NGS (DNA and RNA), HER2 IHC/FISH, and possibly single-cell or spatial assays as available; concurrently perform plasma ctDNA (cfDNA) NGS to capture heterogeneity and rapidly detect emergent mutations. Findings that would alter management include emergence of RAS/NRAS or BRAF V600E mutations (predict resistance to continued HER2 targeting and change eligibility for certain targeted options), loss of HER2 amplification (reduces likelihood of further HER2-directed benefit), or ERBB2 mutations amenable to alternate inhibitors — these would directly inform therapy selection or trial matching.

---

## Q7 (022_7)

Which clinical-trial classes or specific investigational agents available in 2024 would be reasonable matches for this patient after progression on T-DM1, and what case features support trial eligibility?

### Answer 7

Reasonable trial matches include next-generation HER2 ADCs or bispecific HER2-targeted antibodies, combinations of HER2-targeted agents (antibody + TKI), pan-HER2 tumor-agnostic trials (DESTINY-PanTumor programs), and combination strategies pairing HER2 blockade with inhibitors addressing emergent downstream alterations (e.g., PI3K/MEK pathways) if such alterations are detected. Supporting eligibility features: documented high-level HER2 amplification, prior lines consistent with refractory-disease enrollment, KRAS wild-type status (if required), and prior demonstrated tolerability of HER2-targeted therapy (15 months on T-DM1 implying adequate organ reserve).

---

## Q8 (022_8)

How should the patient’s history of deep venous thrombosis and rectal bleeding influence future systemic therapy selection, supportive-care planning, and trial eligibility?

### Answer 8

History of DVT and active/previous bleeding that previously contraindicated bevacizumab should continue to be considered when evaluating anti-angiogenic therapies due to bleeding and thrombotic risk. These comorbidities do not contraindicate HER2-directed ADCs but necessitate assessment of current anticoagulation, bleeding risk, and trial-specific exclusion criteria. Supportive care should include individualized thrombosis prophylaxis and management of anemia, and documentation of bleeding history must be communicated for trial screening and drug-safety planning.

---

## Q9 (022_9)

If a progression biopsy or ctDNA demonstrates emergent KRAS mutation at VAF 8% with adequate read depth, and concurrent loss of HER2 amplification, how should therapy be modified and why are VAF and read-depth reporting important?

### Answer 9

An emergent KRAS mutation signals acquired resistance to HER2-directed therapy and predicts lack of benefit from EGFR-targeted and HER2-targeted strategies; loss of HER2 amplification further argues against continuing HER2-directed therapy. Management should pivot to therapies appropriate for RAS-mutant mCRC or clinical trials targeting RAS-driven disease. Reporting VAF and read depth is crucial to interpret clonality and assay confidence: a VAF of 8% suggests a subclonal but biologically relevant population when read depth supports the call, distinguishing true emergent resistance from sequencing artifact and influencing urgency of therapeutic change.

---

## Q10 (022_10)

What cardiac monitoring schedule and management strategy is indicated for patients receiving HER2-directed therapies such as trastuzumab or T-DM1, and how should asymptomatic LVEF declines be balanced against ongoing oncologic benefit in this patient?

### Answer 10

Baseline LVEF assessment (echocardiogram or MUGA) is required prior to initiating HER2-targeted therapy. Serial monitoring (commonly every 3 months during therapy, or per institutional/trial protocol) is recommended. Asymptomatic LVEF declines (e.g., absolute LVEF <50% or a ≥10% drop from baseline) generally prompt treatment interruption, cardiology evaluation, and initiation of guideline-directed heart-failure therapies as indicated; HER2 therapy may be resumed if LVEF recovers to acceptable levels. Decisions should weigh the magnitude and durability of oncologic benefit (this patient derived prolonged benefit from T-DM1) and involve cardio-oncology consultation for shared decision-making.

---
