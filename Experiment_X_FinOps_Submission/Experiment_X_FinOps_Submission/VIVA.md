# FinOps Viva Questions and Answers

1. **What is FinOps?** A collaborative operating practice that helps teams understand and optimize cloud cost while balancing business value.
2. **What problem does your project solve?** It makes spending and budget variance visible and flags records for review instead of relying only on manual inspection.
3. **What are the project inputs and outputs?** Input is a CSV of resource costs, budgets, utilization and idle labels. Outputs are a terminal report, summary CSV and HTML dashboard.
4. **Is this connected to AWS/Azure/GCP?** No. It uses synthetic sample data as a local proof of concept. A production system would ingest authorized billing exports or APIs.
5. **What is budget variance?** Total cost minus total budget. A positive result means spending is above budget; a negative result means below budget for the sample period.
6. **Does an idle flag mean delete the resource?** No. It is a candidate for human review. Ownership, criticality, seasonality and recovery needs must be checked.
7. **What are the limitations?** Synthetic data, static rules, missing allocation context, possible false positives, no forecasting and no provider integration.
8. **How is this different from ordinary monitoring?** Traditional monitoring often focuses on availability and performance; cost observability adds spend, budgets and allocation as operational signals.
9. **Would you use it in production?** Not as-is. I would connect validated billing data, add access controls and ownership tags, test alerts, and require human approval for changes.
10. **What measurement did you take?** The sample run processes eight records and computes $445.25 cost against a $455.00 illustrative budget. These are dataset-derived values, not actual cloud spending.
11. **What can improve it?** Scheduled ingestion, time-series trends, anomaly detection, service/team tags, alert delivery and integration with provider billing tools.
12. **How does it relate to Experiment X?** It researches an approved emerging operational practice, builds a working demonstration, compares it with manual review and states limitations.
