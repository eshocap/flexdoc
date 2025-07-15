# Flexdoc Product Catalogue API

At Flexdoc, we're building more than just a lending service. We're creating tools for the next generation of property buyers, brokers, and AI assistants.

This public product catalogue API gives transparent, structured access to lending policies across our panel of lenders. It’s live, always up to date, and open for trusted partners and agents integrating smarter property lending workflows.

We believe lending policies shouldn’t live in PDFs or sit behind portals. Our API brings clarity and speed, helping you act faster and make better decisions.

## 📦 What This Is

This `product_catalogue.json` file provides an up-to-date overview of loan products available through Flexdoc. It is designed to support:

- AI-powered assistants helping clients match with suitable products
- Internal tools and chatbots for fast eligibility checks
- Fintech developers building integrations with Flexdoc

## 🧾 Data Structure

Each product object contains:

- `lender_name`: Name of the lender
- `product_name`: Internal or descriptive name
- `loan_type`: Residential, Commercial, or SMSF
- `product_type`: Full Doc, Alt Doc, Low Doc
- `loan_purpose`: Purchase, Refinance, Equity Release
- `lvr_limit`: Maximum Loan-to-Value Ratio (%)
- `income_verification`: Accepted types (e.g. BAS, Accountant Letter, Bank Statements)
- `credit_history`: General expectations or restrictions
- `gst_required`: Whether GST registration is required
- `abn_length`: Minimum ABN age (months or years)
- `notable_features`: Key highlights (interest-only, offset, etc.)
- `compliance_notes`: Licensing or disclosure notes
- `author`: Who compiled the entry
- `last_updated`: ISO date format
- `tags`: Optional keywords for search or categorisation

## 🔗 Access URL

- 📦 [Product Catalogue (JSON)](https://api.flexdoc.com.au/product_catalogue.json)  
- 🔀 [Decision Tree Logic (JSON)](https://api.flexdoc.com.au/decision_tree.json)


## 🔐 Licensing & Use

This catalogue is open for read access. Use is permitted for advisory, matching, or integration purposes. Please do not modify or re-host without permission. For questions or commercial partnerships, contact us via [flexdoc.com.au](https://flexdoc.com.au).

## 💡 Future Roadmap

- Add product-specific pages for deeper documentation
- Include product codes for stable reference
- Expand data fields to include funding timeframes and channel access

---

Built by [Flexdoc](https://flexdoc.com.au), better lending for the self-employed.
