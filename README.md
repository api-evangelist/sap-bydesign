# SAP Business ByDesign (sap-bydesign)

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

SAP Business ByDesign is a cloud ERP solution for midmarket companies providing OData REST and SOAP web service APIs for managing financials, CRM, procurement, supply chain, project management, and analytics. APIs support full CRUD operations on business objects, analytical data extraction, KPI access, and end-to-end business process automation across lead-to-quote, order-to-cash, and procure-to-pay workflows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sap-bydesign/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sap-bydesign/refs/heads/main/apis.yml)

## Tags

- ERP
- Cloud
- Midmarket
- Financials
- CRM
- Procurement
- Supply Chain
- Project Management
- OData
- SOAP
- SAP

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### SAP Business ByDesign OData Business Objects API

OData v2 REST API for UI-driven access to SAP Business ByDesign business objects. Supports querying, reading, creating, updating, deleting, and performing actions on business objects and documents across financials, sales, procurement, supply chain, and project management.

- **Human URL:** [https://community.sap.com/t5/enterprise-resource-planning-blog-posts-by-sap/sap-business-bydesign-odata-api-examples/ba-p/13400614](https://community.sap.com/t5/enterprise-resource-planning-blog-posts-by-sap/sap-business-bydesign-odata-api-examples/ba-p/13400614)
- **Base URL:** `https://{tenant}.bydesign.cloud.sap/sap/byd/odata/v1`

#### Tags

- OData
- Business Objects
- CRUD
- Financials
- Sales
- Procurement

#### Properties

- [Documentation](https://community.sap.com/t5/enterprise-resource-planning-blog-posts-by-sap/sap-business-bydesign-odata-api-examples/ba-p/13400614)
- [Github Repository](https://github.com/SAP-samples/byd-api-samples)

### SAP Business ByDesign OData Analytics API

OData API for accessing pre-processed and formatted analytical data from SAP Business ByDesign reports, KPIs, and data sources. Supports extraction of financial analytics, supply chain KPIs, sales reports, and raw analytical data in flat table format.

- **Human URL:** [https://community.sap.com/t5/enterprise-resource-planning-blog-posts-by-sap/sap-business-bydesign-odata-api-examples/ba-p/13400614](https://community.sap.com/t5/enterprise-resource-planning-blog-posts-by-sap/sap-business-bydesign-odata-api-examples/ba-p/13400614)
- **Base URL:** `https://{tenant}.bydesign.cloud.sap/sap/byd/odata/v1`

#### Tags

- OData
- Analytics
- Reports
- KPIs
- Data Sources

#### Properties

- [Documentation](https://community.sap.com/t5/enterprise-resource-planning-blog-posts-by-sap/sap-business-bydesign-odata-api-examples/ba-p/13400614)
- [Github Repository](https://github.com/SAP-samples/byd-api-samples)

### SAP Business ByDesign SOAP Web Services

SOAP-based web services API for system-to-system integration with SAP Business ByDesign. Provides access to business processes including financials, procurement, supply chain, CRM, and HR through standardized WSDL-defined service contracts.

- **Human URL:** [https://help.sap.com/docs/SAP_BUSINESS_BYDESIGN/34de7a7c1a7e43178141074817068fb1/37faab74f63049d7816184add8077065.html](https://help.sap.com/docs/SAP_BUSINESS_BYDESIGN/34de7a7c1a7e43178141074817068fb1/37faab74f63049d7816184add8077065.html)
- **Base URL:** `https://{tenant}.bydesign.cloud.sap/sap/bc/srt/wsdl`

#### Tags

- SOAP
- Web Services
- Integration
- Financials
- Procurement
- CRM

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_BUSINESS_BYDESIGN/34de7a7c1a7e43178141074817068fb1/37faab74f63049d7816184add8077065.html)

## Common Properties

- [Website](https://www.sap.com/products/erp/business-bydesign.html)
- [Documentation](https://help.sap.com/docs/SAP_BUSINESS_BYDESIGN)
- [Git Hub Org](https://github.com/SAP-samples/byd-api-samples)
- [LinkedIn](https://www.linkedin.com/showcase/sap-business-bydesign/)
- [Blog](https://community.sap.com/t5/c-khhcw49343/SAP+Business+ByDesign/pd-p/01200615320800000691)
- [Pricing](https://www.sap.com/products/erp/business-bydesign/pricing.html)
- [Status Page](https://www.sap.com/about/trust-center/cloud-service-status.html)
- [X (Twitter)](https://x.com/SAP)
- [Plans](plans/sap-bydesign-plans-pricing.yml)
- [Rate Limits](rate-limits/sap-bydesign-rate-limits.yml)
- [Fin Ops](finops/sap-bydesign-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
