# Decisions

- Region locked to ap-southeast-2 (Sydney): an organization policy denies other regions. All resources live there.
- IAM users cannot get console passwords (organization policy). Using the existing assumed role AccountFullAccessRole through the console and CloudShell.
- AWS Free plan: $100 credits, ends 2027-05-12. Do not upgrade without budget alerts set first.
- Data bucket: olist-saad-7824 (ap-southeast-2).
- Local dev: Windows, VS Code, PowerShell, Python venv. Raw data stays out of Git.