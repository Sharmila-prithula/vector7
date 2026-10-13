# VECTOR7: Zero-Trust Claim-Level Credibility Assessment for Conversational AI

## Anonymous Supplementary Material for Review

This repository contains the anonymous supplementary data and detailed audit outputs for the manuscript **"VECTOR7: Zero-Trust Claim-Level Credibility Assessment for Conversational AI."** 

This material is provided to support transparency, independent auditing, and reproducibility during the double-blind peer review process. The main manuscript contains the complete framework definition, algorithms, aggregate results, and core conclusions.

### Repository Contents

*   📄 **`VECTOR7_Anonymous_Supplementary_Material.pdf`**: This is the primary supplementary document containing all detailed appendices referenced in the main paper.

### Overview of Supplementary Appendices (inside the PDF)

Please refer to `VECTOR7_Anonymous_Supplementary_Material.pdf` for the full data tables and matrices, which are organized as follows:

#### Appendix A: Claim Types and Probe Applicability
A detailed matrix (Table A.1) specifying how the seven VECTOR7 probes (V1-V7) map to representative claim types (Factual, Procedural, Technical/System, Reasoning, Safety/Policy, Evidentiary, and Hypothetical/Counterfactual). It outlines which diagnostic dimensions are required (R), optional (O), or typically not applicable for different epistemic obligations.

#### Appendix B: Result of Individual Probes
Contains the raw diagnostic outputs for claims evaluated against Gemini and DeepSeek models.
*   **Table B.1 & B.2**: Reports the Independent Credibility Vector (ICV) prior to consistency conditioning, and the Consistency-Conditioned Credibility Vector (CCV) which highlights outcomes conservatively downgraded due to cross-probe contradiction or commitment drift.

#### Appendix C: Credibility Decision Interpretation Layer
Provides the human-facing operational breakdown of how raw probe scores translate into final credibility decisions (Tables C.1 for Gemini and C.2 for DeepSeek). 
Includes the following detailed metrics for each claim:
*   **CES** (Credibility Evaluation Score)
*   **CCM** (Coverage and Consistency Metric)
*   **CEE** (Cross-probe Epistemic Entropy)
*   **CSR** (Contextual Stability Ratio)
*   **Final Decision** (Credible vs. Inconclusive)
*   **Diagnostic Explanation**: A precise breakdown of the specific epistemic strengths and weaknesses identified during the V7-EDA and V7-CPCC decision flow.

---
*Note: This repository is completely anonymized in accordance with double-blind peer-review guidelines. No author names, institutional affiliations, or identifiable commit histories are included.*
