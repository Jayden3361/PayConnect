# PayConnect

B2B embedded finance and payments integration platform prototype for multi-tenant merchants. It supports Stripe-style card payments, ledger reconciliation, webhook reliability, KYC/AML and rule-based fraud controls, with future scope for UK Open Banking A2A payments and stablecoin-enabled settlement.

## Status

In active development. Stack: Python + FastAPI + PostgreSQL + AWS.

## Security

API keys are stored in environment variables and never committed to GitHub. A `.env.example` file is provided for local setup. Stripe test keys only. Webhook signing secrets are handled separately from API keys and are also loaded from environment variables.