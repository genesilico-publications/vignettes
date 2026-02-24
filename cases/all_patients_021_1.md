# 021_1 | all_patients

## Case

# Case vignette — Patient 4095 (NEJM case)

- Patient identifier: 4095 (as reported in Tran et al., NEJM "T-Cell Transfer Therapy Targeting Mutant KRAS in Cancer").
- Demographics: 50-year-old woman.
- Relevant history/comorbidities: Not specifically reported in the case report; no major comorbidities or baseline organ dysfunctions were described. Performance status prior to therapy was adequate for trial enrollment (eligible for lymphodepletion and high-dose cell infusion); exact ECOG score not stated.

Clinical presentation and timeline
- Primary diagnosis: Metastatic colorectal adenocarcinoma with pulmonary-only metastases at the time of enrollment.
- Baseline staging/imaging: CT showed seven lung metastases (measured maximum diameters reported for three resected lesions: 0.6 cm, 0.8 cm, 1.0 cm). Three of the ten lung lesions were resected for tissue (VATS) to generate tumor-infiltrating lymphocyte (TIL) cultures and for molecular analysis.
- Pre-treatment molecular work-up: Whole-exome sequencing and transcriptome sequencing of the three resected lung nodules (median sequencing depths reported as 128, 131, and 163 reads for the lesions) to identify expressed somatic mutations.

Pathology, radiology, and response
- Pathology: Resected lesion 2 at 9 months showed extensive necrosis and no viable tumor. Lesion 3 (the progressing lesion) contained viable tumor at time of resection.
- Radiologic course after therapy: All seven pulmonary metastases regressed on first follow-up at 40 days. Six of seven maintained regression at 9 months; lesion 3 initially regressed but progressed by 9 months and was resected. After resection, the patient was clinically disease-free at 4 months follow-up.

Immunotherapy intervention and product details
- Trial: Phase 2 adoptive cell-transfer trial (NCI Surgery Branch; ClinicalTrials.gov NCT01174121) investigating autologous TIL selected for neoepitope reactivity.
- Lymphodepletion regimen: Cyclophosphamide 60 mg/kg IV for 2 days, then fludarabine 25 mg/m2 IV for 5 days (nonmyeloablative lymphodepletion).
- Infusion product: Single infusion of 1.48 × 10^11 TILs. Approximately 75% of the infused cells were CD8+ (≈1.11 × 10^11 cells) reactive to mutant KRAS G12D. Product was polyclonal, composed of at least four distinct KRAS G12D–reactive CD8+ T-cell clonotypes; the three largest clonotypes composed ~49.5%, 19.1%, and 6.9% of the product; the fourth clonotype comprised ~0.04%.
- Post-infusion cytokine support: Up to five doses of interleukin-2 at 720,000 IU/kg were planned; administration was limited because the patient reported fatigue.
- Functional profile of infusion product: The KRAS G12D–reactive CD8+ T cells were multifunctional, producing IFN-γ, TNF, and IL-2, and exhibited degranulation (CD107a), with higher multifunctionality for mutant peptide stimulation versus wild-type KRAS peptide.

Molecular/genomic findings and biomarkers
- Driver mutation: KRAS G12D identified and expressed in tumor(s). Whole-exome and transcriptome sequencing confirmed the presence of KRAS G12D in the progressing lesion (lesion 3) at the time of resection (see article/supplementary data).
- HLA genotype and antigen presentation: Patient expressed HLA-C*08:02 (the presenting allele required for CD8+ recognition of the KRAS G12D epitope used). KRAS G12D–specific TCRs were HLA-C*08:02–restricted.
- Tumor immune escape: Chromosome 6 copy-neutral loss of heterozygosity (LOH) in the progressing lesion resulted in loss of the HLA-C*08:02 haplotype in lesion 3, providing a direct mechanism for immune escape from KRAS G12D–specific CD8+ T cells.
- Sequencing metrics: Median exome sequencing depths for the three resected lesions were reported as 128, 131, and 163 reads. The NEJM main text and public supplementary materials confirm presence/retention of KRAS G12D in lesion 3, but specific variant allele frequencies (VAFs) for KRAS G12D in each lesion were not provided in the NEJM article text; raw sequencing data are available under BioProject PRJNA342632 for further analysis.
- MSI/TMB/PD-L1/FISH: Not reported in the main case report. Microsatellite instability (MSI) status, tumor mutational burden (TMB), and PD-L1 IHC were not described; therefore, they are unknown for this patient based on the published report.

T-cell receptor (TCR) tracking and persistence
- Four distinct KRAS G12D–reactive TCR clonotypes were identified and tracked via deep sequencing of the TCR β-chain across tumor samples, infusion product, and peripheral blood.
- In vivo persistence: The TRBV10-02 clonotype showed the greatest long-term peripheral persistence and remained detectable months after infusion; dynamics of clonotype frequencies in blood and tumor were reported in the manuscript figures and supplementary data (representing substantial engraftment for dominant clones and variable decline for others).

Toxicity and current status
- Toxicity: No unexpected severe toxicities were reported aside from fatigue that limited IL-2 dosing; the patient tolerated lymphodepletion and cell infusion.
- Clinical status in report: Patient remained clinically disease-free 4 months after resection of progressing lesion 3.

Key points and implications
- This case demonstrates that adoptive transfer of CD8+ T cells targeting a recurrent driver mutation (KRAS G12D) can mediate objective regression of multiple metastatic lesions.
- Immune escape occurred via loss of the presenting HLA allele (HLA-C*08:02) through copy-neutral LOH on chromosome 6 in the progressing lesion, highlighting a mechanism of selective pressure and immune evasion relevant to T-cell–based therapies.

Citations
- Tran E, Robbins PF, Lu Y-C, et al. T-Cell Transfer Therapy Targeting Mutant KRAS in Cancer. N Engl J Med. 2017;376(7):e11. (PMCID: PMC5178827) https://pmc.ncbi.nlm.nih.gov/articles/PMC5178827/
- NEJM clinical trial registration and supplementary materials; BioProject PRJNA342632 (sequencing data) as noted in the article.

---

## Q1 (021_1)

Given the reported sequencing depths (median 128, 131, and 163 reads) and the confirmation that KRAS G12D was present in the progressing lesion (lesion 3), how would you assess clonality and cancer cell fraction (CCF) of the KRAS G12D mutation from the available reported data, and what additional sequencing/analytic data would you request to calculate an accurate variant allele frequency (VAF) and CCF for KRAS G12D in each lesion?

### Answer 1

The NEJM report confirms presence of KRAS G12D but does not give locus-specific VAFs. With median exome depths of 128–163, locus-level read counts should be adequate for variant calling, but accurate clonality/CCF estimation requires: (1) per-site read counts for KRAS G12D (variant and total reads), (2) tumor purity estimates for each lesion, (3) local copy-number state at the KRAS locus, and (4) ploidy-aware conversion of VAF to CCF using tools such as ABSOLUTE or Sequenza. Request raw BAM/VCF files or per-site VCF annotations plus copy-number and purity calls (e.g., from BioProject PRJNA342632) to compute VAF and infer clonality precisely.

---

## Q2 (021_2)

Considering that the infused CD8+ T cells were HLA-C*08:02–restricted and that lesion 3 lost HLA-C*08:02 via copy-neutral LOH, what is the most probable immunologic mechanism by which lesion 3 escaped immune control, and what assays would you perform on resected lesion 3 to confirm the mechanism of escape?

### Answer 2

Most probable mechanism is loss of antigen presentation due to allele-specific loss of the presenting HLA (copy-neutral LOH on chromosome 6 removing HLA-C*08:02), preventing KRAS G12D peptide presentation in that HLA context. Confirmatory assays: allele-specific copy-number and LOH analysis (Sequenza/FACETS) comparing tumor and germline, tumor HLA typing versus germline, RNA-seq for HLA-C transcript levels, IHC or flow cytometry for HLA class I expression, and functional coculture assays with KRAS G12D–specific TCR-transduced T cells to demonstrate loss of recognition.

---

## Q3 (021_3)

Based on current guideline-relevant practice for RAS-mutant metastatic colorectal cancer and the specifics of this case (KRAS G12D, pulmonary-only metastases, prior experimental adoptive cell therapy), what systemic standard-of-care therapies should be considered and which commonly used targeted or immunotherapies would be contraindicated or expected to be ineffective because of the KRAS mutation?

### Answer 3

Standard systemic options for RAS-mutant metastatic colorectal cancer include combination cytotoxic regimens such as FOLFOX or FOLFIRI with or without bevacizumab. Anti–EGFR antibodies (cetuximab, panitumumab) are ineffective in tumors with activating KRAS mutations and are therefore not recommended. Immune checkpoint inhibitors are effective primarily for MSI-H/dMMR tumors; MSI status was not reported here, so checkpoint monotherapy would not be expected unless MSI-H. Clinical-trial options (KRAS-targeted agents, TCR/TIL trials) are reasonable at progression.

---

## Q4 (021_4)

If a KRAS G12D–selective small-molecule inhibitor (e.g., MRTX1133) were available and all tumors retained KRAS G12D but one lesion had lost HLA-C*08:02, how would you rationalize sequencing or combining TCR-based therapy with a KRAS G12D inhibitor to minimize clonal escape and maximize durability of response for this patient?

### Answer 4

Combining orthogonal mechanisms is rational: a KRAS G12D inhibitor targets oncogenic signaling independent of antigen presentation and would act on HLA-loss variants, while TCR therapy eliminates HLA-expressing clones. Concurrent or sequential combination could reduce selection pressure for HLA-loss escape; however, potential drug–immune interactions and toxicities must be evaluated in clinical trials. Preclinical and early-phase data support MRTX1133 activity against KRAS G12D tumors and justify trial-based combination strategies.

---

## Q5 (021_5)

For trial matching: Given this patient’s HLA-C*08:02 expression and KRAS G12D mutation, what types of adoptive T-cell–based or TCR-engineered clinical trials would she be eligible for, and what molecular inclusion/exclusion criteria should be confirmed prior to enrollment?

### Answer 5

Eligible trials include TCR-engineered T-cell trials targeting KRAS G12D in the HLA-C*08:02 context, TIL trials enriched for KRAS G12D reactivity, or trials using public TCRs for G12D–C*08:02. Confirmations required: tumor or ctDNA evidence of KRAS G12D, patient HLA-C*08:02 genotype, adequate organ function and performance status, and evidence of target allele expression in lesions (biopsy/IHC or allele-specific assays). Demonstrated LOH or B2M loss in target lesions should be considered an exclusion or stratification variable.

---

## Q6 (021_6)

Suppose at 9 months the progressing lesion acquired a B2M loss-of-function mutation causing loss of surface MHC class I expression; how would that alter the interpretation of immune escape and subsequent therapeutic strategy compared with the observed copy-neutral LOH of HLA-C*08:02?

### Answer 6

B2M loss causes global loss of MHC class I surface expression (pan–MHC I deficiency), leading to broad CD8+ T-cell evasion; HLA LOH is allele-specific and may leave other HLA alleles intact. B2M loss would favor non–MHC I–dependent strategies (NK-cell therapies, innate immune engagers, direct tumor-targeted small molecules), whereas HLA LOH may allow targeting via T cells restricted by retained HLA alleles or via CD4+ strategies. Diagnostic confirmation (B2M sequencing, MHC I IHC) is required to guide therapy.

---

## Q7 (021_7)

Design a translational monitoring plan (blood and tissue assays and timepoints) to detect early evidence of antigen-loss variants or HLA-LOH in a patient undergoing KRAS G12D–directed adoptive cell therapy, including recommended molecular assays and thresholds for action.

### Answer 7

Baseline multi-region tumor biopsy for KRAS VAF, allele-specific HLA typing, copy-number analysis (Sequenza), B2M sequencing, and HLA I IHC. Serial plasma ctDNA (ddPCR/ultra-deep NGS) for KRAS G12D pre-treatment, weekly for first 4–8 weeks, then monthly for 6–12 months; rising KRAS VAF after nadir or discordant imaging should trigger early biopsy. TCRβ deep sequencing in blood at baseline, day 7–14, 28, then monthly to assess clonotype persistence. Biopsy of progressing lesions for WES/RNA-seq and allele-specific HLA analysis to identify LOH or B2M mutations. Action thresholds: rising ctDNA KRAS G12D or radiographic progression triggers biopsy; detection of HLA-C*08:02 loss or B2M inactivation in progressing lesion should prompt change to non–MHC I–dependent strategies or targeted inhibitors.

---

## Q8 (021_8)

If asked to prioritize three rational combination strategies to prevent or overcome HLA-LOH–mediated escape observed in this case, which combinations would you propose and why (include mechanism-level justification and risks)?

### Answer 8

Priority combinations: (1) TCR/TIL therapy + KRAS G12D small-molecule inhibitor (e.g., MRTX1133) — addresses antigen-loss variants by direct oncogene inhibition; risk: combined toxicities and immune modulation. (2) TCR/TIL therapy + CD4+ neoantigen-directed adoptive transfer or vaccine — promotes epitope spreading and helper functions; risk: identification of safe MHC II neoepitopes and off-tumor effects. (3) TCR/TIL therapy + NK-cell–based therapy or NK-engaging bispecifics — exploits missing-self due to HLA loss; risk: cytokine toxicity and limited durability. Clinical trials are required to evaluate safety and efficacy.

---

## Q9 (021_9)

Integrate tumor heterogeneity, clonal architecture, and the immunologic data (TCR clonotype frequencies and HLA allele frequencies) to explain why six lesions regressed while lesion 3 progressed, and propose the most likely sequence of clonal events.

### Answer 9

Most likely sequence: baseline lesions shared clonal KRAS G12D and HLA-C*08:02 expression. Infused polyclonal KRAS G12D–reactive CD8+ T cells eliminated HLA-C*08:02–expressing clones in six lesions, producing regression. In lesion 3, a pre-existing subclone or an acquired copy-neutral LOH event removed HLA-C*08:02, permitting outgrowth of KRAS G12D–positive but HLA-C*08:02–negative cells; TCR clonotypes persisted in blood but were ineffective against antigen-presentation–deficient clones. Tumor allele-frequency analysis showed reduced HLA-C*08:02 representation in the progressing lesion compared with pre-therapy samples.

---

## Q10 (021_10)

From a bioethics and informed-consent perspective for future patients enrolling in HLA-restricted, mutation-specific TCR trials, what key risks and uncertainties exemplified by this case should be explicitly discussed, and what monitoring/contingency planning should be part of consent and trial design?

### Answer 10

Key consent elements: risk of tumor immune escape (HLA LOH or B2M loss) making therapy ineffective; investigational and potentially transient benefits; risks of lymphodepletion and IL-2; potential off-target or on-target off-tumor toxicity; need for serial biopsies and intensive molecular monitoring; and limited guaranteed salvage options. Trial design should include predefined monitoring schedules, predefined biopsy and salvage pathways (targeted agents, NK-based therapies), and psychosocial support. These risks and contingencies should be clearly presented to patients during consent.

---
