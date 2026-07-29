# AI Governance & Controls Portfolio · Jun Jie Oh

Work samples that sit behind my résumé. I am a dual-qualified U.S. CPA and Singapore CA
with 8+ years in technology assurance and SOX/ICFR, now moving into AI governance.
These are self-directed, synthetic-data exercises that show how I scope, test, and govern
with an assurance and controls lens (the governance role, not the model-building role),
aligned to NIST AI RMF and ISO/IEC 42001.

## AI Governance (start here)

**1. AI Governance Portfolio Case Study** (read first)
The full writeup of the "Enterprise AI Governance Readiness" project on my résumé: an
end-to-end readiness case for a synthetic $18B public cloud/software company. Covers a
use-case inventory and risk tiering, a NIST AI RMF and ISO/IEC 42001-aligned governance
model, policies and standards, an AI impact assessment, a control matrix with test and
evidence procedures, executive findings, and a 30/90/180/365-day roadmap.

**2. TalentMatch AI Testing**
The model-testing exercise referenced in that project, with the full evidence pack. I
designed the test plan, model card, and SQL data-validation checks to independently
evaluate a candidate-ranking model over 6,000 synthetic records; found weak predictive
utility (ROC AUC 0.62) and material subgroup disparity (impact ratio 0.53, TPR gap 0.24),
compared a job-related challenger that improved fairness (0.84, 0.09), and issued a HOLD
disposition with a hash-verified, owner-mapped evidence trail (referencing EEOC guidance
and NYC Local Law 144).

## Separate Project: Data & Controls Analytics

**3. Continuous Control Monitoring (Journal-Entry Risk Analytics)**
The continuous-controls-monitoring project on my résumé, independent of the AI governance
work above. A reproducible full-population Python and SQL pipeline over 604 synthetic
general-ledger entries that tests 594 records against seven fraud and override rules,
surfaces 81 exceptions (8 highest-risk), and presents them in an interactive dashboard.

## Note
All data is synthetic. These are learning and demonstration exercises, not real bias
audits, legal opinions, or validations of production systems.
