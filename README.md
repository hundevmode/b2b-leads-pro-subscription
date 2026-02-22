# B2B Leads PRO Subscription (Rental) | Fixed Monthly B2B Lead Extraction

**High-volume subscription actor on Apify** for teams that need predictable lead generation costs.

- Actor: [B2B Leads PRO Subscription](https://console.apify.com/actors/JZ1PjtruiQSJeMQ6i/source)
- Model: Rental / subscription
- Pricing: **$19.99/month**
- Capacity: **up to 1,000,000 leads/month**
- Per-run cap: **up to 50,000 leads**

This repository is intentionally **README-only** and points to the production actor.

---

## Why choose subscription

If your team runs frequent lead extraction jobs, subscription is often more cost-effective than pay-per-use.

### Built for scale

- Fixed monthly cost for predictable budgeting
- Unlimited run count within monthly cap
- High-volume extraction for agencies and sales teams
- Same B2B filtering power for job title, location, company, and quality criteria

---

## Powered by Dievio

This actor is aligned with Dievio workflows for scalable lead operations.

- Dievio preview: [https://dievio.com/dashboard/preview](https://dievio.com/dashboard/preview)
- Saved list workflows
- Pagination-friendly extraction process
- API-first integrations for recurring operations
- Team-ready data pipelines

---

## Subscription pricing model

### Rental plan

- **$19.99/month**
- **Up to 1,000,000 leads/month**
- **Up to 50,000 leads per run**

### Who should use it

- Agencies running recurring exports
- B2B sales teams with weekly campaign cycles
- Growth and outbound teams with large monthly targets
- Data ops teams that need stable costs

For live pricing, caps, and billing details, check:
[https://console.apify.com/actors/JZ1PjtruiQSJeMQ6i/source](https://console.apify.com/actors/JZ1PjtruiQSJeMQ6i/source)

---

## Input schema (typical)

The actor UI contains the exact schema. Typical controls include:

- `max_results`
- `job_titles`
- `job_title_seniority`
- `person_location_country`
- `person_location_region`
- `employee_size`
- `industries`
- `email_status`
- `include_emails`
- `include_phones`

### Example input

```json
{
  "max_results": 50000,
  "job_titles": ["Founder", "CEO", "Head of Growth"],
  "job_title_seniority": ["owner", "cxo", "director"],
  "person_location_country": ["United States", "Canada"],
  "employee_size": ["11-50", "51-200", "201-500", "501-1000"],
  "industries": ["Computer Software", "Marketing and Advertising"],
  "email_status": "verified",
  "include_emails": true,
  "include_phones": true
}
```

---

## Output data (typical fields)

Depending on source coverage and filters, output can include:

- Name and professional identity fields
- Title, seniority, department
- Company and location fields
- Work/personal email data
- Phone data (where available)
- LinkedIn URL and profile links
- Additional enrichment attributes

### Example output item

```json
{
  "full_name": "Alex Johnson",
  "job_title": "Head of Growth",
  "job_company_name": "Scale Labs",
  "industry": "Computer Software",
  "location_country": "United States",
  "work_email": "alex@scalelabs.com",
  "mobile_phone": "+1-212-555-0104",
  "linkedin_url": "https://linkedin.com/in/alexjohnson"
}
```

---

## Subscription vs standard plan

Need pay-as-you-go instead of monthly subscription?

- [B2B Leads Scraper (Like Apollo) - Standard](https://console.apify.com/actors/LurATYM4hkEo78GVj/source)

Use standard when volume is inconsistent.
Use subscription when monthly extraction is heavy and recurring.

---

## SEO keywords

b2b leads subscription, rental b2b scraper, monthly lead generation tool, linkedin lead extractor subscription, apollo alternative subscription, fixed-price b2b data scraping, apify rental actor

---

## Open actor

**Run now:** [https://console.apify.com/actors/JZ1PjtruiQSJeMQ6i/source](https://console.apify.com/actors/JZ1PjtruiQSJeMQ6i/source)
