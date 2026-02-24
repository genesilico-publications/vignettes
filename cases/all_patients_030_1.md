# 030_1 | all_patients

## Case

# Case vignette: KIF5B-EGFR fusion positive NSCLC — concise, clinician-oriented summary

Patient demographics and relevant history
- Age/sex: 50-year-old male
- Smoking history: former smoker
- Comorbidities: none reported in the source document
- Baseline performance status: not quantitatively reported; progressive decline by the time of last hospitalization (required hospitalization for dyspnea and progressive weakness)

Initial presentation and staging
- January 2018: Screening chest CT identified an irregular ~2 cm spiculated mass in the left upper lobe.
- Surgical management: left upper lobectomy performed in January 2018.
- Pathology: invasive gland-forming adenocarcinoma with intraductal tumor thrombus.
- Pathologic stage: pT1cN0M0, stage IA3 (per report).
- IHC on primary tumor: CK19(+), TTF-1(+), EGFR (reported as positive on IHC), Ki-67 ~10%; ALK(–), GATA3(–), TG(–), P53(–).

Adjuvant therapy and early course
- Adjuvant chemotherapy: pemetrexed 500 mg/m2 + cisplatin 75 mg/m2 q21 days ×4 cycles (January–April 2018).

Recurrence and metastatic course
- Interval to recurrence: 13 months after surgery (February 2019): metastatic disease in left supraclavicular lymph node and a lytic lesion of the left first rib.
- Biopsy of supraclavicular node: mixed histology with components of adenocarcinoma and squamous cell carcinoma (SCC) at that time.
- The patient received repeat systemic chemotherapy with pemetrexed + cisplatin beginning February 2019 but had disease progression after 2 cycles.

Molecular/genomic findings
- Tumor NGS (performed on postoperative tumor tissue and later on plasma and on repeat biopsies): identified a novel KIF5B-EGFR fusion. Specific fusion structure reported:
  - Fusion breakpoint: KIF5B intron 15 fused to EGFR exon 18 (reported as KIF5B exon 1–15 fused to EGFR exon 18–28) with preservation of EGFR tyrosine kinase domain (EGFR exons 18–28 retained).
  - IGV showed high read support at the fusion junction, interpreted as a clonal driver event in the resected tumor.
- At intracranial progression after afatinib, plasma cell-free DNA NGS detected EGFR T790M at low abundance (reported variant allele frequency [VAF] 0.17%). The source document does not report read depth for the T790M call.
- On repeat pulmonary biopsy after progression on osimertinib, histology showed pure SCC with retained KIF5B-EGFR fusion on NGS. No quantitative read depth or comprehensive copy-number/TMB/MSI data are reported in the case report.

Biomarker data
- PD-L1 by IHC on the recurrent pulmonary SCC: 10% tumor proportion score.
- Ki-67 on recurrent pulmonary lesion: ~20%.
- IHC on recurrent lesion: CK(+), P40(+), P60(+), Napsin A(–), TTF-1(–), ALK(–).

Imaging findings and response kinetics
- Baseline CT: ~2 cm spiculated left upper lobe mass with lytic rib lesion.
- Response to afatinib (40 mg orally daily): marked reduction in primary lobe mass and nodal disease after 2 months; RECIST-classified partial response (>50% reduction in diameter reported). Progression-free survival on afatinib: 11 months.
- Pattern of progression: intracranial progression (multiple enhancing brain metastases, >5 lesions each 0.5–1.2 cm) after 11 months on afatinib.
- After whole-brain radiotherapy and initiation of osimertinib for plasma-detected T790M, the patient developed obstructive pneumonia and tumor progression after 4 months of osimertinib.

Prior systemic therapies, doses, and toxicities
- Pemetrexed 500 mg/m2 + cisplatin 75 mg/m2 × multiple cycles in two separate periods (adjuvant, and again at recurrence) — progression on second-line chemotherapy after 2 cycles.
- Afatinib 40 mg daily (second-line targeted therapy) — partial response and 11 months PFS; no specific afatinib toxicities are detailed in the report.
- Osimertinib administered after detection of plasma T790M (dose not explicitly reported; standard is 80 mg daily) — 4 months clinical course complicated by obstructive pneumonia; progression documented.

Current status and organ function
- After progression on osimertinib and obstructive pneumonia, the patient’s condition deteriorated, systemic anti-tumor therapy was discontinued, and care transitioned to best supportive care. The patient remained alive at the time of final follow-up reported (4 months after stopping therapy).

Pathology-level evolution
- Documented histologic evolution from adenocarcinoma at initial resection to mixed ADC/SCC in nodal metastasis and then to pure SCC on later pulmonary biopsy after TKI exposure, with retention of the KIF5B-EGFR fusion across histologic changes.

Interpretive summary for clinicians
- The KIF5B-EGFR fusion preserves the EGFR tyrosine kinase domain and appends an N-terminal dimerization/coiled-coil domain (KIF5B), creating a plausible ligand-independent, constitutively active receptor via fusion-mediated dimerization. Such architecture predicts sensitivity to EGFR-targeted TKIs in multiple published series and preclinical models for other EGFR fusions.
- Second-generation irreversible EGFR TKI afatinib produced a clinically meaningful partial response and an 11-month PFS in this patient; T790M emerged at low allele frequency in plasma at progression, with limited subsequent benefit from osimertinib.

Source (primary document parsed): OncoTargets and Therapy case report provided (NEJM_case_030 PDF provided to the tasking agent).

---

## Q1 (030_1)

Based on the described fusion breakpoint (KIF5B exon 1–15 fused to EGFR exon 18–28 with preservation of the EGFR kinase domain), would a second‑generation irreversible EGFR TKI such as afatinib be mechanistically expected to be active against this fusion, and what clinical evidence supports using afatinib in this setting?

Answer (ground truth): Yes. The fusion retains the EGFR tyrosine kinase domain (EGFR exons 18–28) fused to an N‑terminal dimerization/coiled‑coil region from KIF5B, which is predicted to produce ligand‑independent receptor dimerization and constitutive kinase activation — a mechanism by which EGFR fusions are oncogenic and sensitive to EGFR TKIs. Clinical evidence supporting afatinib for uncommon/atypical EGFR alterations includes pooled clinical experience showing activity of afatinib against a range of uncommon EGFR mutations (Yang et al., J Thorac Oncol 2020) and multiple case reports/series documenting responses of EGFR fusion–positive NSCLC to EGFR TKIs, including afatinib. The present case itself documents a RECIST partial response and 11 months PFS on afatinib.

References:
- Case report (this patient): https://www.tandfonline.com/doi/full/10.2147/OTT.S263994
- Mechanistic & preclinical/clinical series on EGFR fusions: https://aacrjournals.org/cancerdiscovery/article/6/6/601/65119 (Konduri et al., Cancer Discov. 2016)
- Afatinib in uncommon EGFR mutations (pooled database): https://www.jto.org/article/S1556-0864(20)30014-9/fulltext (Yang JCH et al., J Thorac Oncol. 2020)

### Answer 1



---

## Q2 (030_2)

The patient’s plasma cell‑free DNA NGS detected EGFR T790M at a VAF of 0.17% at the time of intracranial progression. Given that quantitative result, should the clinician consider osimertinib a guideline‑concordant next systemic therapy and how does low VAF affect expected benefit?

Answer (ground truth): Detection of EGFR T790M after progression on a first‑ or second‑generation EGFR TKI is guideline‑concordant evidence to use osimertinib (AURA3 demonstrated superior PFS vs platinum–pemetrexed in T790M‑positive disease). However, low plasma VAF (0.17%) predicts a lower likelihood of durable benefit; multiple studies show that low mutant allele fraction in plasma correlates with shorter PFS on EGFR TKIs. Therefore osimertinib is a reasonable choice if the T790M call is analytically reliable, but clinicians should (a) consider tissue confirmation if feasible (especially to confirm clonality and histology), (b) counsel that low VAF often yields shorter PFS, and (c) monitor closely for limited benefit.

References:
- Osimertinib in T790M-positive NSCLC (AURA3): https://www.nejm.org/doi/full/10.1056/NEJMoa1612674 (Mok et al., NEJM 2017)
- Plasma EGFR mutation abundance and clinical outcome: https://pubmed.ncbi.nlm.nih.gov/33987333/ (Wang X et al., Ann Transl Med. 2021)
- Case report discussion noting low VAF T790M and limited osimertinib benefit: https://www.tandfonline.com/doi/full/10.2147/OTT.S263994

### Answer 2



---

## Q3 (030_3)

The patient developed intracranial progression with >5 lesions (0.5–1.2 cm). Was the multidisciplinary choice of whole‑brain radiotherapy (WBRT) appropriate in this clinical context, and what role could SRS or systemic CNS‑penetrant EGFR inhibitors have played?

Answer (ground truth): For multiple (>4–5) small brain metastases, WBRT is an accepted local‑control option and was reasonable in this patient. Stereotactic radiosurgery (SRS) is typically preferred for limited numbers of metastases (commonly ≤4) and to spare neurocognitive toxicity. Osimertinib has superior CNS penetration and intracranial activity compared with first‑generation TKIs (FLAURA and other data), and for patients with CNS progression on earlier TKIs, switching to a CNS‑penetrant EGFR TKI (osimertinib, if T790M positive or in first‑line use) can control intracranial disease; if multiple symptomatic lesions are present and immediate cytoreduction is needed, WBRT plus systemic therapy is a defensible approach. In this case the team delivered WBRT then started osimertinib for a plasma T790M — a commonly used sequence.

References:
- FLAURA and CNS benefit of osimertinib: https://pubmed.ncbi.nlm.nih.gov/31838405/ (Osimertinib vs erlotinib/gefitinib)
- AURA3 and CNS subgroup data: https://www.nejm.org/doi/full/10.1056/NEJMoa1612674 (Mok et al., NEJM 2017)

### Answer 3



---

## Q4 (030_4)

At progression after osimertinib the rebiopsy showed pure squamous cell carcinoma (SCC) histology with retention of the KIF5B‑EGFR fusion. How should the histologic transformation alter systemic treatment selection in this patient, specifically in regard to continuing targeted EGFR therapy versus switching to histology‑directed chemotherapy or other approaches?

Answer (ground truth): Histologic transformation can be a mechanism of TKI resistance. When transformation to small‑cell histology occurs, standard management is platinum‑etoposide chemotherapy. For squamous transformation with retention of the actionable driver (here, the KIF5B‑EGFR fusion), continuing to target the driver remains biologically rational because the fusion may still be oncogenic in the transformed component; however, clinical outcomes vary and SCC phenotype may respond less well to EGFR TKIs. Given the patient’s clinical deterioration and documented progression on osimertinib, treatment decisions should be individualized: if tissue shows retained EGFR driver and patient is fit, a trial of targeted therapy or driver‑directed approaches may be reasonable; however, given limited benefit from osimertinib in this case and symptomatic pulmonary decline (obstructive pneumonia), switching to systemic cytotoxic therapy tailored to squamous histology (e.g., platinum doublet appropriate for squamous NSCLC) or enrollment in trials may be considered. Repeat comprehensive genomic profiling (including RB1, TP53, MET amplification) should guide therapy because certain co‑alterations predict transformation pathways and therapeutic vulnerabilities.

References:
- Paired genomic analyses of SCC transformed from EGFR‑mutant ADC: https://www.sciencedirect.com/science/article/pii/S0959804921000885 (Park et al., Lung Cancer 2019)
- Case discussion and retained fusion: https://www.tandfonline.com/doi/full/10.2147/OTT.S263994

### Answer 4



---

## Q5 (030_5)

Would first‑line osimertinib (instead of initial resection/adjuvant chemo then afatinib later) likely have altered this patient’s clinical course with respect to intracranial progression and overall PFS based on contemporary evidence?

Answer (ground truth): Contemporary randomized data (FLAURA) demonstrate that first‑line osimertinib yields superior PFS and better CNS control compared with first‑generation EGFR TKIs; extrapolating to EGFR‑fusion disease (which was not represented in FLAURA) suggests that a CNS‑penetrant TKI like osimertinib might delay intracranial progression. However, the patient’s initial presentation was early‑stage resectable disease (pT1cN0M0) treated with surgery±adjuvant chemo — indications for adjuvant osimertinib (ADAURA) are separate from FLAURA first‑line metastatic data. In summary, if the patient had presented with de novo metastatic disease, first‑line osimertinib likely would have offered superior intracranial control; for this resected early‑stage case, adjuvant targeted therapy was not the standard of care at the time, and evidence for adjuvant use of osimertinib in EGFR‑fusion cases is lacking.

References:
- FLAURA (first‑line osimertinib): https://pubmed.ncbi.nlm.nih.gov/31838405/
- ADAURA (adjuvant osimertinib context): https://www.nejm.org/doi/10.1056/NEJMoa2027071 (context for adjuvant use in classical EGFR exon 19/21-mutant disease)

### Answer 5



---

## Q6 (030_6)

The recurrent pulmonary biopsy showed PD‑L1 tumor proportion score (TPS) = 10%. In a patient with an EGFR driver alteration (fusion) and prior EGFR‑TKI exposure, is single‑agent PD‑1/PD‑L1 blockade an evidence‑based option, and under what circumstances might immunotherapy be considered?

Answer (ground truth): Single‑agent PD‑1/PD‑L1 inhibitors have shown limited efficacy in EGFR‑mutant NSCLC and are generally not recommended as monotherapy in driver‑positive disease after TKI failure. The IMpower150 regimen (atezolizumab + bevacizumab + carboplatin + paclitaxel) demonstrated benefit in a subgroup that included patients with EGFR mutations after TKI exposure and is an evidence‑supported option in select patients with prior TKI failure and adequate performance status. Thus, given PD‑L1 10% and EGFR driver status, single‑agent ICI is low‑likelihood to succeed; combined chemo‑bevacizumab‑IO approaches (e.g., IMpower150) may be considered in fit patients after discussion of risks. In this specific patient, poor performance status and active pneumonia would preclude ICI at the time of deterioration.

References:
- IMpower150 subgroup analyses and EGFR patients: https://pubmed.ncbi.nlm.nih.gov/30922878/ (IMpower150 key subgroup analyses)
- General ICI activity discussion in EGFR-mutant tumors: https://www.jto.org/article/S1556-0864(21)03217-2/fulltext

### Answer 6



---

## Q7 (030_7)

What additional genomic/biomarker assessments should have been pursued (or should be pursued if clinically feasible) on the repeat tumor biopsy to define resistance mechanisms and actionable targets after progression on osimertinib?

Answer (ground truth): Comprehensive tissue NGS (large panel) including copy‑number analysis and fusion detection; targeted assessments should explicitly include EGFR resistance mutations (C797S), MET amplification, HER2 amplification, PIK3CA mutations, BRAF, RET, ALK, and assessment of RB1/TP53 for lineage plasticity/small‑cell transformation risk. Tumor mutational burden (TMB) and mismatch repair/MSI status may be informative for immunotherapy considerations. Importantly, quantify allele frequencies and report read depths to interpret clonality (the case lacked read depth for plasma T790M). Tissue confirmation is preferred for copy‑number events and histology‑specific programs.

References:
- Broad landscape of resistance mechanisms & NGS utility: https://www.nature.com/articles/nm.4333 (Zehir et al., Nat Med. 2017)
- Mechanisms of transformation and resistance literature: https://www.sciencedirect.com/science/article/pii/S0959804921000885 (Park et al., Lung Cancer 2019)

### Answer 7



---

## Q8 (030_8)

Given that the KIF5B partner contains a coiled‑coil dimerization domain, explain the predicted biochemical behavior of the chimeric protein and which classes of targeted agents (small molecule TKIs, monoclonal antibodies, or combination strategies) are most rational to test clinically.

Answer (ground truth): The KIF5B coiled‑coil motif mediates dimerization; fused to the intact EGFR kinase domain this likely causes constitutive, ligand‑independent dimerization and activation of EGFR kinase signaling. Small‑molecule EGFR TKIs that inhibit the ATP‑binding pocket (first/second/third generation) are mechanistically rational — demonstrated by clinical responses to erlotinib/afatinib in EGFR fusions. Monoclonal antibodies against EGFR (e.g., cetuximab) have activity in preclinical models of some EGFR fusions and could be considered in combinations (TKI + anti‑EGFR mAb) for selected fusions, but clinical evidence is limited. Irreversible pan‑ERBB inhibitors (afatinib) or newer agents that inhibit mutant EGFR or downstream pathways (MEK/PI3K inhibitors) could also be rational combination strategies in trials.

References:
- Preclinical and case evidence for EGFR fusions and TKI sensitivity: https://aacrjournals.org/cancerdiscovery/article/6/6/601/65119 (Konduri et al., Cancer Discov. 2016)
- Case reports showing response to TKIs/afatinib in EGFR fusions: https://www.tandfonline.com/doi/full/10.2147/OTT.S263994

### Answer 8



---

## Q9 (030_9)

Which clinical trials or drug classes should be prioritized for trial matching after progression on osimertinib in a patient with retained KIF5B‑EGFR fusion and SCC transformation who is now medically fit for investigational therapy?

Answer (ground truth): Prioritized trials/drug classes would include (a) trials of agents targeting EGFR fusions (next‑generation EGFR inhibitors, pan‑ERBB inhibitors, or combinations of EGFR TKI + EGFR antibody), (b) MET or HER2 targeting trials if amplification is found on repeat NGS, (c) antibody–drug conjugates or novel ERBB family approaches, and (d) trials specifically enrolling patients with oncogenic fusions (basket trials). For patients with SCC phenotype, trials that do not exclude squamous histology and that accept EGFR‑driven tumors are appropriate. ClinicalTrials.gov searches and molecular tumor boards should be used for real‑time matching.

References/starting points:
- EGFR fusion literature and rationale: https://aacrjournals.org/cancerdiscovery/article/6/6/601/65119
- Examples of KIF5B‑EGFR case series and registry: https://pubmed.ncbi.nlm.nih.gov/32903808/ (Xu & Shao, OncoTargets Ther. 2020)

### Answer 9



---

## Q10 (030_10)

List and justify three evidence‑based management steps (ranked) you would recommend next for this patient at the point immediately after progression on osimertinib with obstructive pneumonia and deteriorating performance status.

Answer (ground truth): Ranked steps:
1. Stabilize acute medical issues and treat the obstructive pneumonia aggressively (antibiotics, bronchoscopy if indicated, supportive care) because active infection must be controlled before further anti‑cancer therapy; immediate management takes precedence over investigational systemic therapy.
2. Reassess performance status after resolution or partial improvement of infection; if patient becomes fit (ECOG 0–2), obtain comprehensive tissue NGS (if not recently done) and repeat imaging to determine disease distribution and clarify resistance mechanisms (MET amplification, C797S, RB1/TP53, etc.) to guide therapy selection or trial enrollment.
3. If infection persists or the patient remains poor‑performance (ECOG ≥3), prioritize best supportive care; if the patient recovers and actionable resistance mechanisms are identified (eg T790M confirmed at meaningful abundance in tissue or MET amp present), choose targeted therapy (osimertinib if confirmed T790M at adequate clonality, MET inhibitor if MET amp) or consider IMpower150 regimen for EGFR‑mutant patients after TKI failure if appropriate and fit.

References:
- Guidance on management of poor performance and infection before systemic therapy: general oncology practice, and IMpower150 in EGFR subgroup: https://pubmed.ncbi.nlm.nih.gov/30922878/
- Importance of tissue confirmation and broad NGS: https://www.nature.com/articles/nm.4333 (Zehir et al., Nat Med. 2017)

---

DOCUMENTATION: the above answers reference the primary case report and the peer‑reviewed literature cited below. Use local institutional multidisciplinary tumor board and current NCCN/ESMO guidance to individualize decisions.

Key literature links (relevant to multiple answers):
- Case report (this patient): https://www.tandfonline.com/doi/full/10.2147/OTT.S263994
- Konduri/Gallant/Chae et al. on EGFR fusions: https://aacrjournals.org/cancerdiscovery/article/6/6/601/65119
- AURA3 (osimertinib vs platinum–pemetrexed for T790M): https://www.nejm.org/doi/full/10.1056/NEJMoa1612674
- FLAURA (first‑line osimertinib CNS efficacy): https://pubmed.ncbi.nlm.nih.gov/31838405/
- Afatinib in uncommon EGFR mutations (pooled data): https://www.jto.org/article/S1556-0864(20)30014-9/fulltext
- IMpower150 subgroup analyses (EGFR): https://pubmed.ncbi.nlm.nih.gov/30922878/
- Plasma EGFR mutation abundance and response: https://pubmed.ncbi.nlm.nih.gov/33987333/
- Paired genomic analyses of histologic transformation: https://www.sciencedirect.com/science/article/pii/S0959804921000885

### Answer 10



---
