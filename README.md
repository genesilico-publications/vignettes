# Vignettes – Clinical Cases & Sample Reports

Data repository for the GeneSilico precision oncology LLM benchmark. Contains de-identified clinical case vignettes and sample model-generated reports used in the manuscript.

## Contents

### `cases/`

Structured clinical vignettes in markdown format, each presenting a real-world oncology case with:

- **NEJM and Cases from other sources** (`all_patients_001_1.md` – `all_patients_036_1.md`): 36 cases adapted from *New England Journal of Medicine* case records, covering a range of solid tumours and haematologic malignancies. Each case includes demographics, diagnosis, treatment history, genomic/biomarker data, and precision oncology discussion points.
- **In-house Cases** (`in_house_structured_data_*.md`): Proprietary de-identified cases from the GeneSilico clinical database, formatted identically to the NEJM cases.

### `samples/`

Sample clinical reports for one representative case (*Ananya Rao, breast cancer*), which can be used to test out CancerAI at https://cancerai.genesilico.ai/:

| File | Contents |
|------|----------|
| `lab_report_breast_cancer_case_Ananya_Rao.pdf` | Laboratory results summary |
| `ngs_report_breast_cancer_case_Ananya_Rao.pdf` | Next-generation sequencing report |
| `pathology_report_breast_cancer_case_Ananya_Rao.pdf` | Pathology report |
| `radiology_report_breast_cancer_case_Ananya_Rao.pdf` | Radiology imaging report |

## Benchmark Overview

Cases were evaluated against 22 model/agent configurations spanning:

- **Models**: GPT-4.1, GPT-5.2, Claude Sonnet/Opus 4, Gemini 3 Pro/Flash, O4-mini
- **Agents**: Standalone LLM, Function-calling, ReAct, Graph-SAGe
- **Tools**: Web search (Tavily), 700+ biomedical databases (ToolUniverse), clinical literature (Exa)

**5-metric evaluation framework** (LLM-as-judge, 1–10 scale):
- Overall Correctness
- Patient Centricity
- Safety & Toxicity
- Guideline Concordance
- Clinical Reasoning

## Related

- **Manuscript**: available from authors (rdas@genesilico.ai, dsengupta@genesilico.ai)
