# AEB

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

AEB SE is a German supply chain and global trade software company, headquartered in Stuttgart and 100% employee-owned, whose platform is used by 7,300+ companies for customs filing, trade compliance, multi-carrier shipping, transport and freight cost management, and warehouse management. In the logistics chain AEB sits at the intermediation layer of customs and trade tech: it is the certified filer between the shipper or forwarder and the customs authority (German ATLAS, EU AES/NCTS/ICS, EMCS, Intrastat, UK CHIEF), and the multi-carrier abstraction between the shipper and 300+ carriers, generating the carrier EDI so the customer never has to. Its API posture is unusually open for this tier: four public ReadMe developer hubs (Customs, Trade Compliance, Transport & Freight Management, SAP add-ons) publish machine-readable OpenAPI 3.0.1 for every product, served live and unauthenticated from AEB's own test and demo instances, with shared try-it credentials in the docs. But the contract is entirely proprietary — a REST-over-RPC business-facade shape unique to AEB, with a legacy SOAP business facade still exposed beside it — and production access requires registering with AEB and licensing the products, so it is a documented, quotable, contract-gated API rather than a self-serve one.

**Areas:** Logistics · Supply Chain · Germany · Customs · Trade Compliance · Freight Forwarding · Multi-Carrier Shipping · Parcel · Track and Trace · Export Control · Sanctions Screening · Warehouse Management

## AEB on APIs.io

Everything profiled for AEB is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/aeb/](https://apis.io/providers/aeb/)** — or go straight to one of the APIs or properties below.

### APIs (67)

- [AEB Delivery API](https://apis.io/apis/aeb/aeb-aeb-delivery-api/) — API for the AEBDelivery
- [AEB Billing API](https://apis.io/apis/aeb/aeb-billing-api/) — API for the billing of services
- [AEB Billing Scenario API](https://apis.io/apis/aeb/aeb-billingscenario-api/) — REST API for billing scenarios
- [AEB BIS Audit BF Bean API](https://apis.io/apis/aeb/aeb-bisauditbfbean-api/) — Business facade for auditing of BrokerInstructions.
- [AEB BISBF Bean API](https://apis.io/apis/aeb/aeb-bisbfbean-api/) — Business facade for handling BrokerInstructions.
- [AEB BSM Carrier API](https://apis.io/apis/aeb/aeb-bsm-carrier-api/) — The API for BSM Carrier operations
- [AEB BSM International Customs API](https://apis.io/apis/aeb/aeb-bsm-international-customs-api/) — API for BSM International Customs operations
- [AEB BSM Sync API](https://apis.io/apis/aeb/aeb-bsm-sync-api/) — API for synchronizing data asynchronous from an engine to a client system
- [AEB Carrier API](https://apis.io/apis/aeb/aeb-carrier-api/) — Rest API for carriers
- [AEB Carrier Definition API](https://apis.io/apis/aeb/aeb-carrierdefinition-api/) — Rest API for carrier definitions
- [AEB Carrier Description API](https://apis.io/apis/aeb/aeb-carrierdescription-api/) — Rest API for carrier descriptions
- [AEB Carrier Event Service BF Bean API](https://apis.io/apis/aeb/aeb-carriereventservicebfbean-api/) — Carrier event service related business facade methods. Supports methods for shipments, events and configuration.
- [AEB Carrier Setup API](https://apis.io/apis/aeb/aeb-carriersetup-api/) — Rest API for carrier setups
- [AEB Classification Proposal BF Bean API](https://apis.io/apis/aeb/aeb-classificationproposalbfbean-api/) — API for classification proposals.
- [AEB Companies API](https://apis.io/apis/aeb/aeb-companies-api/) — Rest API for companies
- [AEB Compliance Foundation API](https://apis.io/apis/aeb/aeb-compliance-foundation-api/) — API for the compliance foundation.
- [AEB Compliance Screening API](https://apis.io/apis/aeb/aeb-compliance-screening-api/) — API for restricted party list screening
- [AEB Compliance Screening Applications API](https://apis.io/apis/aeb/aeb-compliance-screening-applications-api/) — Get URLs to various parts of the Compliance Screening application.
- [AEB Compliance Screening Internal API](https://apis.io/apis/aeb/aeb-compliance-screening-internal-api/) — Internal API for compliance screening
- [AEB Consignment profiles API](https://apis.io/apis/aeb/aeb-consignment-profiles-api/) — Consignment profiles API
- [AEB Core BF Bean API](https://apis.io/apis/aeb/aeb-corebfbean-api/) — API for the XNSGFoundation
- [AEB Customs Inventory Management API](https://apis.io/apis/aeb/aeb-customs-inventory-management-api/) — REST endpoint for Customs Inventory Management
- [AEB Customs Content Service BF API](https://apis.io/apis/aeb/aeb-customscontentservicebf-api/) — API providing services around customs content (nomenclatures, export control lists).
- [AEB Customs Transit BF Bean API](https://apis.io/apis/aeb/aeb-customstransitbfbean-api/) — Business facade for transit processes
- [AEB Data Feed BF Bean API](https://apis.io/apis/aeb/aeb-datafeedbfbean-api/) — DataFeedBFBean
- [AEB Declaration of Origin API](https://apis.io/apis/aeb/aeb-declaration-of-origin-api/) — The API with all about declaration of origin
- [AEB Document extractions API](https://apis.io/apis/aeb/aeb-document-extractions-api/) — Document extractions API
- [AEB Document Service API](https://apis.io/apis/aeb/aeb-documentservice-api/) — REST API for the Document Service
- [AEB Document Service Master Data API](https://apis.io/apis/aeb/aeb-documentservice-masterdata-api/) — REST API for the Document Service master data maintenance
- [AEB Export Control API](https://apis.io/apis/aeb/aeb-export-control-api/) — API for export control
- [AEB Export Control Applications API](https://apis.io/apis/aeb/aeb-export-control-applications-api/) — Get URLs to various parts of the Export Controls application.
- [AEB Export Control Internal API](https://apis.io/apis/aeb/aeb-export-control-internal-api/) — Internal API for export control
- [AEB External Telemetry BF Bean API](https://apis.io/apis/aeb/aeb-externaltelemetrybfbean-api/) — API for sending telemetry data from a third party system.
- [AEB Finance Data CHBF Bean API](https://apis.io/apis/aeb/aeb-financedatachbfbean-api/) — Interface overview for Finance data API for Switzerland
- [AEB Foundation AF Bean API](https://apis.io/apis/aeb/aeb-foundationafbean-api/) — Business facade for the XNSGFoundation UI API
- [AEB Foundation BF Bean API](https://apis.io/apis/aeb/aeb-foundationbfbean-api/) — REST endpoint for FoundationBF
- [AEB FT Material Classification20 BF Bean API](https://apis.io/apis/aeb/aeb-ftmaterialclassification20bfbean-api/) — API for the foreign trade material classification (version 2.0)
- [AEB Generic AF Bean API](https://apis.io/apis/aeb/aeb-genericafbean-api/) — API to open views that support this generic interface.
- [AEB International Customs API](https://apis.io/apis/aeb/aeb-international-customs-api-api/) — Interface overview for Customs Management
- [AEB International Customs AF Bean API](https://apis.io/apis/aeb/aeb-internationalcustomsafbean-api/) — Application facades for Customs Management
- [AEB International Customs BF Bean API](https://apis.io/apis/aeb/aeb-internationalcustomsbfbean-api/) — Interface overview for Customs Management
- [AEB Invoices API](https://apis.io/apis/aeb/aeb-invoices-api/) — API for handling external invoices
- [AEB License Management API](https://apis.io/apis/aeb/aeb-license-management-api/) — API for License Management
- [AEB LISBF20 Bean API](https://apis.io/apis/aeb/aeb-lisbf20bean-api/) — Business facade for LIS, version 2.0
- [AEB Logon API](https://apis.io/apis/aeb/aeb-logon-api/) — Authentication handler for the XNSGFoundation
- [AEB Material BF Bean API](https://apis.io/apis/aeb/aeb-materialbfbean-api/) — API for maintaining and requesting classification master data.
- [AEB Material Configuration BF Bean API](https://apis.io/apis/aeb/aeb-materialconfigurationbfbean-api/) — API for requesting settings regarding materials.
- [AEB O&P API](https://apis.io/apis/aeb/aeb-o-p-api/) — The API with all about Origin and Preferences
- [AEB O&P UI API](https://apis.io/apis/aeb/aeb-o-p-ui-api/) — The API with all about Origin and Preferences UIs
- [AEB Push API Rest Endpoint API](https://apis.io/apis/aeb/aeb-pushapirestendpoint-api/) — PushApi for carrier events.
- [AEB Rates API](https://apis.io/apis/aeb/aeb-rates-api/) — API for handling rates
- [AEB Remote Admin BF Bean API](https://apis.io/apis/aeb/aeb-remoteadminbfbean-api/) — Remote Administration tools use this methods. The main player are the Identity Access Manager (IAM) and the Installation Repository (IR).
- [AEB Risk Assessment API](https://apis.io/apis/aeb/aeb-risk-assessment-api/) — API for Risk Assessment
- [AEB Risk Assessment Applications API](https://apis.io/apis/aeb/aeb-risk-assessment-applications-api/) — Get URLs to various parts of the Risk Assessment application.
- [AEB Routing API](https://apis.io/apis/aeb/aeb-routing-api/) — API for the handling of routing tasks
- [AEB SAP® API](https://apis.io/apis/aeb/aeb-sap-api/) — All SAP® specific APIs to interact with the BSM.
- [AEB Service API](https://apis.io/apis/aeb/aeb-service-api/) — REST API for services
- [AEB Settlement API](https://apis.io/apis/aeb/aeb-settlement-api/) — REST API for settlements
- [AEB Settlement Item API](https://apis.io/apis/aeb/aeb-settlementitem-api/) — REST API for settlementitems
- [AEB Shipment Objectives API](https://apis.io/apis/aeb/aeb-shipmentobjectives-api/) — Rest API to get shipment objectives
- [AEB Shipping API](https://apis.io/apis/aeb/aeb-shipping-api/) — API for the CarrierEngine service
- [AEB Sync BF Bean API](https://apis.io/apis/aeb/aeb-syncbfbean-api/) — API for synchronizing data asynchronous from an engine to a client system.
- [AEB Tariff Content20 BF Bean API](https://apis.io/apis/aeb/aeb-tariffcontent20bfbean-api/) — API for the tariff content solution (version 2.0).
- [AEB Tariff Content Fee Calculation BF Bean API](https://apis.io/apis/aeb/aeb-tariffcontentfeecalculationbfbean-api/) — API for fee calculation using the tariff content solution
- [AEB Terms Of Delivery API](https://apis.io/apis/aeb/aeb-termsofdelivery-api/) — Rest API for terms of deliveries
- [AEB Workstation Service Agent API](https://apis.io/apis/aeb/aeb-workstationserviceagent-api/) — Connection handler for the Workstation Service Agent
- [AEB X360 API](https://apis.io/apis/aeb/aeb-x360-api/) — All Haufe x360 specific APIs to interact with the BSM.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Collections (11)

Postman and Open Collection request collections.

- [BSM (TEST2) HTTP API](https://apis.io/collections/aeb/open-aeb-bsm/)
- [Carrier Connect HTTP API](https://apis.io/collections/aeb/open-aeb-carrier-connect/)
- [Carrier Event Service HTTP API](https://apis.io/collections/aeb/open-aeb-carrier-event-service/)
- [Carrier Select HTTP API](https://apis.io/collections/aeb/open-aeb-carrier-select/)
- [Customs Broker Portal HTTP API](https://apis.io/collections/aeb/open-aeb-customs-broker-portal/)
- [Customs Inventory Management HTTP API](https://apis.io/collections/aeb/open-aeb-customs-inventory-management/)
- [Customs Management HTTP API](https://apis.io/collections/aeb/open-aeb-customs-management/)
- [Document Service (DEMO1) HTTP API](https://apis.io/collections/aeb/open-aeb-document-service/)
- [Logistics Cost Management HTTP API](https://apis.io/collections/aeb/open-aeb-logistics-cost-management/)
- [Product Classification HTTP API](https://apis.io/collections/aeb/open-aeb-product-classification/)
- [Trade Compliance Management HTTP API](https://apis.io/collections/aeb/open-aeb-trade-compliance-management/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.aeb.com/)
- [Documentation](https://customsmanagement.docs.developers.aeb.com/)
- [Pricing](https://www.aeb.com/en/carrier-connect/carrier-connect-api.php)
- [Changelog](https://customsmanagement.docs.developers.aeb.com/changelog)
- [Blog](https://www.aeb.com/en/magazine/index.php)
- [Trust centre](https://www.aeb.com/en/trust-center/index.php)
- [GitHub](https://github.com/AEB-labs)

## API Evangelist rating

**Kin Score 31.2** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 46.9 |
| Contract governance | 0.0 |
| Operational transparency | 10.5 |
| Developer ergonomics | 21.4 |
| Access clarity | 18.4 |

**Agent readiness 25.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | mostly |

**Regulatory alignment 4.2** — Telecommunications

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/aeb/](https://apis.io/providers/aeb/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for AEB: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/aeb/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
