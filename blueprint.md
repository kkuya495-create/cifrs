# **App Name**: CIFRS: Cloud Intelligent Financial Reporting System

## Core Features:

- Intelligent Configuration Engine: Automatically generates a tailored Chart of Accounts (COA) based on the selected business type (Trading, Service, Manufacturing, Retail, SME, Startup, Custom). The COA dynamically adjusts for inventory, Cost of Goods Sold (COGS), taxes, operational costs, revenue, assets, and liabilities.
- Smart COA Engine: Manages the Chart of Accounts, ensuring each account includes a code, name, category (Asset, Liability, Equity, Revenue, Expense), normal balance (Debit/Credit), and relation to financial reports. Accounts are validated to prevent omissions.
- Automated Double-Entry Accounting: Automatically generates corresponding debit and credit entries across various accounts (e.g., cash, sales, accounts receivable, expenses) upon any singular transaction input, following the fundamental accounting equation. Supports stock adjustments and Rupiah currency. Automatic number formatting with thousand separators.
- Automated Error Detection: Uses AI as a tool to identify errors or abnormalities in user inputs, such as unusual expenses or unbalanced transactions. Provides warnings and flags for review, using defined business rules.
- Real-time Financial Reporting: Automatically generates key financial statements including Balance Sheet, Income Statement, Cash Flow Statement (Direct & Indirect), General Ledger, Trial Balance, Statement of Retained Earnings, and Stock Card. Users can filter reports by period, account, branch, and project. All reports support Rupiah currency
- Interactive Financial Dashboard: Presents real-time, interactive, and dynamic visualizations of key financial metrics, including cash balances, net profit, revenue vs. expenses, cash flow trends, top expenses, and stock level alerts. All data views support Rupiah currency.
- Secure User & Role Management: Implements role-based access control (RBAC) with defined roles such as Super Admin, Owner, Accounting, Finance, Auditor, and Viewer, each with specific permissions. Maintains an audit log of user activities and tracks all changes made within the system.

## Style Guidelines:

- Primary color: Gray (#808080) to convey neutrality and professionalism.
- Secondary color: Amber (#FFBF00) to provide warmth and highlight key elements.
- Background color: White (#FFFFFF) for a clean and modern look.
- Body text and headlines: 'Inter', a sans-serif font known for its modern and neutral appearance, ensures readability and a clean user interface.
- Use minimalist, professional icons relevant to financial data and actions, maintaining a consistent style throughout the application.
- Employ a clean and structured layout with clear visual hierarchy, utilizing white space effectively to prevent clutter and improve user focus.
- Incorporate subtle transitions and animations for user interactions, such as loading data or displaying new information, to enhance the user experience without being distracting.