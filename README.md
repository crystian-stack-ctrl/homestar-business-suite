# Homestar Business Suite (prototype)

A responsive front-end prototype for Homestar Decor Center with login simulation, role-based navigation, inventory, suppliers/purchases, sales invoices, accounting and expenses, HR, payroll preview, reports, user accounts, audit log, and settings.

## Demo accounts
- `admin` / `Admin123!` — Super Admin
- `manager` / `Manager123!` — Manager
- `inventory` / `Stock123!` — Inventory Officer
- `hr` / `Payroll123!` — HR & Payroll
- `accountant` / `Books123!` — Accountant

These are public demo credentials only.

## Publish with GitHub Pages
1. Create a repository such as `homestar-business-suite`.
2. Upload `index.html`, `style.css`, `app.js`, and `README.md` to the repository root.
3. Open repository Settings → Pages.
4. Select Deploy from a branch, branch `main`, folder `/(root)`, then Save.

## Important prototype limitations
This is not production business software. Login and permissions are simulated in client-side JavaScript and can be bypassed. There is no server/database, secure multi-user login, persistent shared data, double-entry accounting engine, cloud backup, statutory payroll calculation, or tested restore process. Do not enter real payroll or confidential business information. Production needs a backend, database, server-side authorization, password hashing, backups, audit controls, and professional validation of Kenyan accounting and payroll rules.


## Sign-in and account creation (demo only)
- Existing demo logins are shown on the sign-in page.
- Use **Create the first owner account** to register the initial Super Admin with a business email, username, and password.
- After the owner account exists, the Super Admin can add staff accounts from **User Accounts**, assigning a role and temporary password (at least 8 characters).
- Staff can sign in with either their username or email.
- This is a static GitHub Pages prototype: accounts and data are stored only in that browser's local storage. Passwords are not securely protected, accounts are not shared across devices, and this is NOT suitable for real confidential or payroll information. A production version needs a server/database and a real authentication provider.
