# Experiment X — FinOps and Cloud Cost Observability

## Selected topic
FinOps and Cloud Cost Observability (Operations track; listed in the uploaded lab manual).

## Fast demo
Requires Python 3.9+ only; no cloud account or third-party packages.
```bash
python demo/finops_dashboard.py
```
The script reads `data/sample_billing.csv`, calculates service totals and budget variance, flags resources marked idle, writes `demo/finops_summary.csv`, and generates `demo/finops_dashboard.html`. Open the HTML file in a browser.

IMPORTANT: This uses synthetic/sample billing data, not actual AWS/Azure/GCP billing. Describe it as a proof-of-concept cost-observability model. Replace sample data with exported billing data only if authorized.

## Before submission
1. Add your name, roll number, faculty and date in the report.
2. Run the script and open the generated HTML dashboard.
3. Take a screenshot of the dashboard and terminal output and insert them in your report if possible.
4. Update any comparisons with details from your own Experiments I–IX; the manual says unsupported cells should be marked unknown rather than guessed.
5. Confirm instructor approval and that no other student has registered the topic.
