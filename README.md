# nova-mvp--NovaLedger-
Nova Ledger is a simple, smart finance tool for small businesses. Track income &amp; expenses in real time, automate bookkeeping, and generate clear reports, no accounting skills needed. Save time, reduce errors, and take control of your business finances effortlessly.
Act like a senior product engineer and MVP mentor.
Your goal is to help a beginner build a simple web-based financial tracking app for small business owners, focusing strictly on core MVP functionality.
Task: Provide a detailed step-by-step plan to build the MVP, covering technical implementation, database schema, UI considerations, and testing, without adding unnecessary features.
Requirements:
1) Transaction Tracking: Users can add, edit, and delete income and expense transactions. Each entry must include amount, date, category, and description. Display real-time balance on a dashboard.
2) Auto Categorization: Automatically assign categories (sales, transport, inventory, utilities) to transactions using description keywords, with option for manual correction.
3) Financial Reports: Generate simple reports showing total income, total expenses, and profit/loss for selectable periods. Include optional CSV/PDF export.
4) Simple UI: Design clean, beginner-friendly, mobile-responsive interfaces with cards or tables, avoiding complex charts or financial jargon.
5) No Advanced Features: Exclude analytics, AI predictions, multi-currency support, or other advanced functionality.
Context:
///
You are guiding a beginner using Lovable.dev to create the app. Lovable provides frontend, backend, database, and authentication scaffolding automatically. The database should integrate with Supabase and include:
- Users: id, name, email, password
- Transactions: id, user_id, type (income/expense), category, amount, date, description
- Categories: name, type (income/expense)
Focus on accurate MVP implementation, modular code for future features, and secure authentication.
///
Constraints:
- Format: Step-by-step instructions with bullets and sub-bullets where needed.
- Style: Clear, concise, actionable, and beginner-friendly.
- Scope: Include only the defined core features; forbid extra features or styling.
- Reasoning: Explicitly justify each step, provide examples where helpful.
- Self-check: Confirm database tables, category logic, dashboard calculation, mobile responsiveness, and authentication setup at each stage.
- Testing: Include manual verification steps for transaction accuracy, auto-categorization, report correctness, and UI usability.
- Deployment: Ensure live database, hosting through Lovable, and basic security practices.
- Avoid: Overcomplication, cluttered UI, hardcoded data, skipping testing, overthinking backend, ignoring mobile optimization, and insecure data storage.
