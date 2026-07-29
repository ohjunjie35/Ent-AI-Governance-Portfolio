# AI Governance & Controls Portfolio · Jun Jie Oh

Self-directed work samples built on synthetic data. They apply an assurance and
controls lens to AI and to financial data, showing how I scope, test, and govern,
not how a data scientist builds. Frameworks referenced: NIST AI RMF and ISO/IEC 42001.

## AI Governance (start here)

**1. AI Governance Portfolio Case Study** (read first)
The main writeup: an enterprise AI governance readiness case for a synthetic public
cloud/software company. Covers use-case inventory and risk tiering, a governance model,
policies and standards, an AI impact assessment, a control matrix, findings, and a
staged roadmap.

**2. TalentMatch AI Testing**
The model-testing exercise behind the case study: an independent test of a
candidate-ranking model over 6,000 synthetic records, with a test plan, model card,
SQL data-validation checks, subgroup fairness and drift results, a HOLD disposition,
and a hashed, owner-mapped evidence trail.

## Separate Project: Data & Controls Analytics

**3. Continuous Control Monitoring (Journal-Entry Risk Analytics)**
A standalone project, independent of the AI governance work above. A full-population
Python and SQL pipeline that tests every journal entry against seven fraud and override
rules, surfaces the exceptions, and presents them in an interactive dashboard.

## Note
All data is synthetic. These are learning and demonstration exercises, not real bias
audits, legal opinions, or validations of production systems.
