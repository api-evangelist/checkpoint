# Check Point (checkpoint)

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

Check Point Software Technologies is a global cybersecurity vendor providing network, cloud, endpoint, mobile, and email security through its Quantum, CloudGuard, and Harmony product families. Check Point exposes a wide range of REST APIs for security automation, including the Smart-1 Management API, Gaia OS API, CloudGuard cloud security posture API, Identity Awareness API, Spark and Zero Touch device management APIs, Harmony Email and Collaboration API, Threat Hunting (TH) API, and CloudGuard WAF API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/checkpoint/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/checkpoint/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Cloud Security
- Cybersecurity
- Endpoint Security
- Firewall
- Identity Awareness
- Mobile Security
- Network Security
- Security
- Threat Prevention
- WAF

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-19

## APIs

### Check Point Management API

REST API for the Smart-1 Security Management Server. Automates policy and object management including host/network/service objects, access and NAT rulebases, and publish/install operations.

- **Human URL:** [https://sc1.checkpoint.com/documents/latest/APIs/](https://sc1.checkpoint.com/documents/latest/APIs/)
- **Base URL:** `https://management.example.com/web_api`

#### Tags

- Firewall
- Management
- Network Security

#### Properties

- [Documentation](https://sc1.checkpoint.com/documents/latest/APIs/)
- [OpenAPI](openapi/checkpoint-management-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/checkpoint-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Check Point Gaia API

REST API for the Check Point Gaia operating system. Manages gateway interfaces, routing, system info, and configuration.

- **Human URL:** [https://sc1.checkpoint.com/documents/latest/GaiaAPIs/](https://sc1.checkpoint.com/documents/latest/GaiaAPIs/)
- **Base URL:** `https://gateway.example.com/gaia_api`

#### Tags

- Gaia
- Operating System

#### Properties

- [Documentation](https://sc1.checkpoint.com/documents/latest/GaiaAPIs/)
- [OpenAPI](openapi/checkpoint-gaia-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/checkpoint-gaia-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-gaia-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Check Point CloudGuard API

REST API for CloudGuard Native cloud security posture management, cloud account onboarding, compliance findings, and rulesets across AWS, Azure, and GCP.

- **Human URL:** [https://docs.cgn.portal.checkpoint.com/reference/introduction](https://docs.cgn.portal.checkpoint.com/reference/introduction)
- **Base URL:** `https://api.dome9.com/v2`

#### Tags

- Cloud Security
- Compliance
- Posture Management

#### Properties

- [Documentation](https://docs.cgn.portal.checkpoint.com/)
- [OpenAPI](openapi/checkpoint-cloudguard-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/checkpoint-cloudguard-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-cloudguard-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Check Point Identity Awareness API

REST API for posting and revoking user-to-IP identity associations on Check Point gateways, enabling identity-aware policy enforcement.

- **Human URL:** [https://sc1.checkpoint.com/documents/latest/IdentityAPIs/](https://sc1.checkpoint.com/documents/latest/IdentityAPIs/)
- **Base URL:** `https://gateway.example.com/_IA_MU_Agent`

#### Tags

- Identity
- Network Security

#### Properties

- [Documentation](https://sc1.checkpoint.com/documents/latest/IdentityAPIs/)
- [OpenAPI](openapi/checkpoint-identity-awareness-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/checkpoint-identity-awareness-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-identity-awareness-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Check Point Spark Management API

REST API for centrally managing Check Point Quantum Spark SMB appliances including configuration and policy.

- **Human URL:** [https://sc1.checkpoint.com/documents/latest/SmpAPIs/](https://sc1.checkpoint.com/documents/latest/SmpAPIs/)

#### Tags

- SMB
- Spark

#### Properties

- [Documentation](https://sc1.checkpoint.com/documents/latest/SmpAPIs/)
- [Postman Collection](collections/checkpoint-cloudguard-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-cloudguard-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/checkpoint-gaia-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-gaia-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/checkpoint-harmony-email-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-harmony-email-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/checkpoint-identity-awareness-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-identity-awareness-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/checkpoint-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Check Point Zero Touch API

REST API for the Zero Touch deployment service that streamlines bring-up of new Check Point appliances.

- **Human URL:** [https://sc1.checkpoint.com/documents/Appliances/Zero_Touch_REST_API_Guide/EN/Content/Topics-API/Overview.htm](https://sc1.checkpoint.com/documents/Appliances/Zero_Touch_REST_API_Guide/EN/Content/Topics-API/Overview.htm)

#### Tags

- Deployment
- Zero Touch

#### Properties

- [Documentation](https://sc1.checkpoint.com/documents/Appliances/Zero_Touch_REST_API_Guide/EN/Content/Topics-API/Overview.htm)
- [Postman Collection](collections/checkpoint-cloudguard-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-cloudguard-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/checkpoint-gaia-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-gaia-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/checkpoint-harmony-email-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-harmony-email-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/checkpoint-identity-awareness-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-identity-awareness-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/checkpoint-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Check Point Harmony Email API

REST API for Harmony Email and Collaboration (formerly Avanan) surfacing email security events, quarantined items, and admin actions.

- **Human URL:** [https://sc1.checkpoint.com/documents/Harmony_Email_and_Collaboration_API_Reference/Topics-HEC-Avanan-API-Reference-Guide/Overview/API-Overview.htm](https://sc1.checkpoint.com/documents/Harmony_Email_and_Collaboration_API_Reference/Topics-HEC-Avanan-API-Reference-Guide/Overview/API-Overview.htm)
- **Base URL:** `https://smart-api.avanan.net/v2.0`

#### Tags

- Email Security
- Harmony

#### Properties

- [Documentation](https://sc1.checkpoint.com/documents/Harmony_Email_and_Collaboration_API_Reference/Topics-HEC-Avanan-API-Reference-Guide/Overview/API-Overview.htm)
- [OpenAPI](openapi/checkpoint-harmony-email-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/checkpoint-harmony-email-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-harmony-email-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Check Point Threat Hunting API

REST API for the Check Point Threat Hunting (TH) platform exposing threat intelligence, indicators, and hunting queries.

- **Human URL:** [https://sc1.checkpoint.com/documents/latest/ThAPIs/index.html](https://sc1.checkpoint.com/documents/latest/ThAPIs/index.html)

#### Tags

- Threat Hunting
- Threat Intelligence

#### Properties

- [Documentation](https://sc1.checkpoint.com/documents/latest/ThAPIs/index.html)
- [Postman Collection](collections/checkpoint-cloudguard-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-cloudguard-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/checkpoint-gaia-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-gaia-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/checkpoint-harmony-email-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-harmony-email-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/checkpoint-identity-awareness-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-identity-awareness-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/checkpoint-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Check Point CloudGuard WAF API

Management API for the CloudGuard WAF cloud-native web application and API protection product.

- **Human URL:** [https://waf-doc.inext.checkpoint.com/references/management-api](https://waf-doc.inext.checkpoint.com/references/management-api)

#### Tags

- WAF
- Web Security

#### Properties

- [Documentation](https://waf-doc.inext.checkpoint.com/)
- [Postman Collection](collections/checkpoint-cloudguard-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-cloudguard-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/checkpoint-gaia-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-gaia-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/checkpoint-harmony-email-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-harmony-email-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/checkpoint-identity-awareness-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-identity-awareness-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/checkpoint-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkpoint-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/check-point-software-technologies)
- [Website](https://www.checkpoint.com/)
- [Documentation](https://sc1.checkpoint.com/documents/)
- [Support](https://www.checkpoint.com/support-services/)
- [Login](https://portal.checkpoint.com/)
- [Blog](https://blog.checkpoint.com/)
- [Git Hub](https://github.com/CheckPointSW)
- [Terms of Service](https://www.checkpoint.com/about-us/terms-of-use/)
- [Privacy Policy](https://www.checkpoint.com/about-us/privacy-statement/)
- [JSON-LD](json-ld/checkpoint-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/checkpoint-host-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/checkpoint-access-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](spectral/checkpoint-spectral.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)
- [L L Ms Txt](https://docs.cgn.portal.checkpoint.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
