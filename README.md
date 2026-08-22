# AEB (aeb)

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

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/aeb/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/aeb/refs/heads/main/apis.yml)

## Tags

- Logistics
- Supply Chain
- Germany
- Customs
- Trade Compliance
- Freight Forwarding
- Multi-Carrier Shipping
- Parcel
- Track and Trace
- Export Control
- Sanctions Screening
- Warehouse Management
- Transportation Management
- SAP

## Timestamps

- **Created:** 2026-07-30
- **Modified:** 2026-07-30

## APIs

### AEB Customs Management API

Electronic customs declaration filing for import, export and transit. Creates consignments and deliveries, transmits them to national customs systems (German ATLAS, EU AES/NCTS, UK CHIEF), and polls declarations, statuses, MRNs, documents and attachments back. Also exposes Intrastat, EMCS and tariff/fee calculation operations.

- **Human URL:** [https://customsmanagement.docs.developers.aeb.com/](https://customsmanagement.docs.developers.aeb.com/)
- **Base URL:** `https://rz3.aeb.de/test2ici/rest`

#### Tags

- Customs
- Trade Compliance
- Customs Declaration
- ATLAS
- NCTS
- AES
- Intrastat

#### Properties

- [OpenAPI](openapi/aeb-customs-management-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/aeb-customs-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aeb-customs-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://customsmanagement.docs.developers.aeb.com/)
- [API Reference](https://customsmanagement.docs.developers.aeb.com/reference/how-to-use-the-api-reference)
- [Getting Started](https://customsmanagement.docs.developers.aeb.com/docs/your-first-consignment)
- [Changelog](https://customsmanagement.docs.developers.aeb.com/changelog)
- [S O A P](https://rz3.aeb.de/test2ici/servlet/bf)

### AEB Customs Inventory Management API

Customs warehouse / bonded inventory management. Books goods receipts and issues against customs warehouse stock, tracks entries by MRN or ATLAS registration number, and reconciles inventory positions for the customs authority.

- **Human URL:** [https://customsmanagement.docs.developers.aeb.com/](https://customsmanagement.docs.developers.aeb.com/)
- **Base URL:** `https://rz3.aeb.de/test2cim/rest`

#### Tags

- Customs
- Customs Warehouse
- Inventory
- Bonded Warehouse

#### Properties

- [OpenAPI](openapi/aeb-customs-inventory-management-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/aeb-customs-inventory-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aeb-customs-inventory-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://customsmanagement.docs.developers.aeb.com/)
- [S O A P](https://rz3.aeb.de/test2cim/servlet/bf)

### AEB Customs Broker Portal API

The broker-facing surface of AEB's customs platform. Lets a customs broker or forwarder retrieve broker instructions and declarations filed on behalf of a principal, send broker instruction events back, and audit the exchange between the goods owner and the filing agent.

- **Human URL:** [https://customsmanagement.docs.developers.aeb.com/](https://customsmanagement.docs.developers.aeb.com/)
- **Base URL:** `https://rz3.aeb.de/test2broker/rest`

#### Tags

- Customs
- Customs Broker
- Freight Forwarding
- Trade Compliance

#### Properties

- [OpenAPI](openapi/aeb-customs-broker-portal-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/aeb-customs-broker-portal.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aeb-customs-broker-portal.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://customsmanagement.docs.developers.aeb.com/)
- [S O A P](https://rz3.aeb.de/test2broker/servlet/bf)

### AEB Product Classification API

Assigns and validates commodity/tariff classification for materials — HS and national tariff numbers, classification profiles, classification proposals and value templates — and serves the resulting customs content data to the customs and compliance products.

- **Human URL:** [https://customsmanagement.docs.developers.aeb.com/docs/about-product-classification](https://customsmanagement.docs.developers.aeb.com/docs/about-product-classification)
- **Base URL:** `https://rz3.aeb.de/test2cl/rest`

#### Tags

- Trade Compliance
- Product Classification
- HS Codes
- Tariff
- Customs

#### Properties

- [OpenAPI](openapi/aeb-product-classification-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/aeb-product-classification.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aeb-product-classification.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://customsmanagement.docs.developers.aeb.com/docs/about-product-classification)
- [S O A P](https://rz3.aeb.de/test2cl/servlet/bf)

### AEB Trade Compliance Management API

Restricted/denied party screening, export control and risk assessment as an API. Screens addresses and transactions against sanctions lists, manages good-guy releases and match handling, runs export control checks and licence management, and exposes compliance foundation master data.

- **Human URL:** [https://trade-compliance.docs.developers.aeb.com/](https://trade-compliance.docs.developers.aeb.com/)
- **Base URL:** `https://rz3.aeb.de/test4ce/rest`

#### Tags

- Trade Compliance
- Sanctions Screening
- Denied Party Screening
- Export Control
- Customs

#### Properties

- [OpenAPI](openapi/aeb-trade-compliance-management-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/aeb-trade-compliance-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aeb-trade-compliance-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://trade-compliance.docs.developers.aeb.com/)
- [API Reference](https://trade-compliance.docs.developers.aeb.com/reference/compliance-foundation)
- [Getting Started](https://trade-compliance.docs.developers.aeb.com/docs/accessing-the-rest-services)
- [GitHub Repository](https://github.com/AEB-labs/docs-trade-compliance)

### AEB Carrier Connect API

Multi-carrier shipping API covering 300+ carriers and parcel services. Creates shipments, packages and items, produces labels and shipping documents, builds and manifests pickups (AEB sends the carrier EDI on the customer's behalf), and manages carrier definitions, terms of delivery and shipment objectives across parcel, pallet, FCL/LCL, road, rail, ocean and air.

- **Human URL:** [https://transport-freight-management.docs.developers.aeb.com/](https://transport-freight-management.docs.developers.aeb.com/)
- **Base URL:** `https://rz3.aeb.de/demo1cai/rest`

#### Tags

- Multi-Carrier Shipping
- Parcel
- Shipping
- Labels
- Freight
- Logistics

#### Properties

- [OpenAPI](openapi/aeb-carrier-connect-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/aeb-carrier-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aeb-carrier-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://transport-freight-management.docs.developers.aeb.com/)
- [API Reference](https://transport-freight-management.docs.developers.aeb.com/reference/shipping)
- [Pricing](https://www.aeb.com/en/carrier-connect/carrier-connect-api.php)
- [Integrations](https://www.aeb.com/en/carrier-connect/all-transport-service-providers-carriers.php)
- [GitHub Repository](https://github.com/AEB-labs/docs-transport-freight-management)

### AEB Carrier Select API

Carrier selection and routing. Creates routing tasks for a shipment and returns the carrier, service and route determined from the customer's routing rules, rates and constraints.

- **Human URL:** [https://transport-freight-management.docs.developers.aeb.com/reference/createroutingtask](https://transport-freight-management.docs.developers.aeb.com/reference/createroutingtask)
- **Base URL:** `https://rz3.aeb.de/demo1routing/rest`

#### Tags

- Routing
- Carrier Selection
- Transport Planning
- Logistics

#### Properties

- [OpenAPI](openapi/aeb-carrier-select-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/aeb-carrier-select.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aeb-carrier-select.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [API Reference](https://transport-freight-management.docs.developers.aeb.com/reference/createroutingtask)
- [Documentation](https://transport-freight-management.docs.developers.aeb.com/)

### AEB Carrier Event Service API

Track-and-trace event aggregation across carriers. Registers shipments, configures per-carrier tracking connections, and returns resolved status events by shipment or reference number, including proof-of-delivery / entry certification. Also exposes an inbound PushApi endpoint that carriers and tracking providers post raw event data into.

- **Human URL:** [https://transport-freight-management.docs.developers.aeb.com/reference/getshipmentsevents](https://transport-freight-management.docs.developers.aeb.com/reference/getshipmentsevents)
- **Base URL:** `https://xnsg.dc.aeb.com/demo1ces/rest`

#### Tags

- Track and Trace
- Supply Chain Visibility
- Events
- Logistics
- Parcel

#### Properties

- [OpenAPI](openapi/aeb-carrier-event-service-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/aeb-carrier-event-service.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aeb-carrier-event-service.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [API Reference](https://transport-freight-management.docs.developers.aeb.com/reference/getshipmentsevents)
- [Documentation](https://transport-freight-management.docs.developers.aeb.com/docs/carrier-event-service/llms.txt)

### AEB Logistics Cost Management API

Freight cost management and freight settlement. Exposes billing scenarios, services, rates, settlements, settlement items and invoices so freight charges can be calculated, accrued and reconciled against carrier invoices.

- **Human URL:** [https://transport-freight-management.docs.developers.aeb.com/reference/getbillingscenario](https://transport-freight-management.docs.developers.aeb.com/reference/getbillingscenario)
- **Base URL:** `https://rz3.aeb.de/demo1billing/rest`

#### Tags

- Freight Cost
- Freight Settlement
- Billing
- Rates
- Logistics

#### Properties

- [OpenAPI](openapi/aeb-logistics-cost-management-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/aeb-logistics-cost-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aeb-logistics-cost-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [API Reference](https://transport-freight-management.docs.developers.aeb.com/reference/getbillingscenario)
- [Documentation](https://transport-freight-management.docs.developers.aeb.com/docs/logistics-cost-management/llms.txt)

### AEB Document Service API

Document and print output service for the AEB platform. Manages workstations, printers, output channels and document master data, and delivers the labels, customs papers and transport documents generated by the other AEB products.

- **Human URL:** [https://transport-freight-management.docs.developers.aeb.com/reference/getworkstations](https://transport-freight-management.docs.developers.aeb.com/reference/getworkstations)
- **Base URL:** `https://rz3.aeb.de/demo1docs/rest`

#### Tags

- Documents
- Printing
- Labels
- Logistics

#### Properties

- [OpenAPI](openapi/aeb-document-service-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/aeb-document-service.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aeb-document-service.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [API Reference](https://transport-freight-management.docs.developers.aeb.com/reference/getworkstations)
- [Documentation](https://transport-freight-management.docs.developers.aeb.com/docs/document-service/llms.txt)

### AEB BSM API

The bundled BSM (Business Solution Modules) HTTP API that AEB exposes for SAP and partner-system integration — one surface spanning BSM Carrier, AEB Delivery, BSM International Customs, Export Control, Origin & Preferences / Declaration of Origin, Routing and the SAP add-on endpoints, plus an /x360/handleEvent inbound event endpoint. Documented in the public AEB-labs docs-bsm repository; no live public ReadMe hub for it was found on 2026-07-30.

- **Human URL:** [https://github.com/AEB-labs/docs-bsm](https://github.com/AEB-labs/docs-bsm)
- **Base URL:** `https://rz3.aeb.de/test2bsm/rest`

#### Tags

- SAP
- Customs
- Export Control
- Origin and Preferences
- Shipping
- Logistics

#### Properties

- [OpenAPI](openapi/aeb-bsm-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/aeb-bsm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aeb-bsm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub Repository](https://github.com/AEB-labs/docs-bsm)
- [Documentation](https://sap-plugins.docs.developers.aeb.com/)

## Common Properties

- [Issue Tracker](https://github.com/AEB-labs/docs-trade-compliance/issues)
- [Website](https://www.aeb.com/)
- [Documentation](https://customsmanagement.docs.developers.aeb.com/)
- [Documentation](https://trade-compliance.docs.developers.aeb.com/)
- [Documentation](https://transport-freight-management.docs.developers.aeb.com/)
- [Documentation](https://sap-plugins.docs.developers.aeb.com/)
- [Support Portal](https://service.aeb.com/hc/en-us)
- [Changelog](https://customsmanagement.docs.developers.aeb.com/changelog)
- [Trust Center](https://www.aeb.com/en/trust-center/index.php)
- [GitHub Organization](https://github.com/AEB-labs)
- [Blog](https://www.aeb.com/en/magazine/index.php)
- [Pricing](https://www.aeb.com/en/carrier-connect/carrier-connect-api.php)
- [Integrations](https://www.aeb.com/en/carrier-connect/all-transport-service-providers-carriers.php)
- [S O A P](https://customsmanagement.docs.developers.aeb.com/page/soap-api)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
