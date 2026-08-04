# Figshare (figshare)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Figshare is a research data repository platform that enables researchers, institutions, and organizations to upload, manage, and publicly share scientific outputs including datasets, figures, media, papers, posters, and software. The platform provides persistent DOI assignment for all published research outputs, enabling proper citation and long-term discoverability. Figshare's REST API v2 allows programmatic access to articles, collections, projects, file uploads, statistics, and administrative functions across both public and private (authenticated) endpoints.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/figshare/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/figshare/refs/heads/main/apis.yml)

**Naftiko Fleet:** [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=figshare-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=figshare-api-evangelist&utm_content=repo)

## Tags

- Research Data
- Data Repository
- Open Science
- DOI
- Datasets
- Academic
- File Storage
- Open Access

## APIs

| API | Base URL | Documentation |
|-----|----------|---------------|
| Figshare API | https://api.figshare.com/v2 | https://docs.figshare.com/ |

## Plans, Rate Limits, and FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/figshare-plans-pricing.yml](plans/figshare-plans-pricing.yml) |
| Rate Limits | [rate-limits/figshare-rate-limits.yml](rate-limits/figshare-rate-limits.yml) |
| FinOps | [finops/figshare-finops.yml](finops/figshare-finops.yml) |

### Pricing Summary

| Plan | Type | Cost |
|------|------|------|
| Free | Free | $0 (20GB storage) |
| Figshare+ up to 250GB | Paid one-time | $1,225 DPC |
| Figshare+ up to 500GB | Paid one-time | $2,450 DPC |
| Figshare+ up to 750GB | Paid one-time | $3,675 DPC |
| Figshare+ up to 1TB | Paid one-time | $4,900 DPC |
| Figshare+ up to 5TB | Paid one-time | $24,500 DPC |
| Figshare+ over 5TB | Enterprise | Custom quote |
| Institutional Figshare | Enterprise | Custom quote |

### Rate Limits Summary

Figshare does not enforce hard automatic rate limits. The recommended usage guideline is no more than 1 request per second. Abuse monitoring is active and Figshare reserves the right to throttle (HTTP 429) or block excessive requests.

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Property | URL |
|----------|-----|
| Website | https://figshare.com/ |
| Documentation | https://docs.figshare.com/ |
| GitHub Organization | https://github.com/figshare |
| Blog | https://info.figshare.com/blog/ |
| Pricing | https://info.figshare.com/figshare-plus/ |
| Status Page | https://status.figshare.com/ |
| LinkedIn | https://www.linkedin.com/company/figshare/ |
| X (Twitter) | https://x.com/figshare |
| Support | https://support.figshare.com/ |
| User Documentation | https://info.figshare.com/user-guide/how-to-use-the-figshare-api/ |

## Maintainers

- **Kin Lane** — kin@apievangelist.com
