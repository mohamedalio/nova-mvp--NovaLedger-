# nova-mvp--NovaLedger-
Nova Ledger is a simple, smart finance tool for small businesses. Track income &amp; expenses in real time, automate bookkeeping, and generate clear reports, no accounting skills needed. Save time, reduce errors, and take control of your business finances effortlessly.
Act like a senior software engineer and QA specialist.

Your goal is to identify, diagnose, and provide step-by-step instructions to fix bugs in a beginner-built financial tracking MVP web app. Focus on correctness, reliability, and usability, without adding new features.

Task: Review the existing MVP implementation (transactions, auto-categorization, financial reports, UI) and create a detailed plan to detect, reproduce, and fix any bugs or inconsistencies.

Requirements:
1) Transaction Bugs: Verify that adding, editing, and deleting transactions correctly updates the database and the dashboard balance.
2) Auto Categorization Bugs: Ensure automatic categories are assigned accurately and manual corrections are properly saved.
3) Financial Report Bugs: Confirm that total income, total expenses, and profit/loss calculations are correct across all periods.
4) UI Bugs: Detect visual or functional issues such as broken layouts, unresponsive forms, or misaligned tables.
5) Cross-Device Testing: Ensure functionality and UI are correct on desktop and mobile.
6) Security & Data Integrity: Verify authentication works, user data is secure, and no transactions are hardcoded or missing.

Context:
///
You are debugging the MVP built using Lovable.dev and Supabase. The app includes transaction tracking, auto-categorization, financial reports, and a clean beginner-friendly UI. Assume all previous prompts (V1 and V2) were implemented as intended.
///

Constraints:
- Format: Step-by-step instructions with clear reproduction steps for each bug.
- Style: Analytical, precise, beginner-friendly.
- Scope: Only bug fixes; do not add new features.
- Self-check: Confirm each bug is fixed by reproducing the issue, verifying correct database updates, and validating UI behavior.
- Testing: Include explicit steps for desktop and mobile verification.
- Avoid: Speculative fixes; ensure every recommendation is based on actual behavior or predictable patterns.
