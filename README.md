# Spring Boot 3 (spring-boot-3)

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

Spring Boot 3 is the major release of the opinionated Spring application framework, now built on Spring Framework 6, requiring Java 17 baseline and Jakarta EE 10. It delivers native image support via GraalVM, improved observability with Micrometer tracing, and a modernized auto-configuration system. Spring Boot 3 simplifies the development of production-ready stand-alone Spring applications with embedded servers, health endpoints, and externalized configuration.

**APIs.json:** [https://spring.io/projects/spring-boot](https://spring.io/projects/spring-boot)

## Tags

- Enterprise
- Framework
- Java
- Microservices
- REST API
- Spring Boot

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Spring Boot Actuator API

Production-ready features for monitoring and managing Spring Boot 3 applications. Provides over 50 built-in endpoints exposing health status, metrics (Micrometer), environment properties, loggers, thread dumps, heap dumps, HTTP trace, and more via HTTP or JMX.

- **Human URL:** [https://docs.spring.io/spring-boot/docs/3.2.x/reference/html/actuator.html](https://docs.spring.io/spring-boot/docs/3.2.x/reference/html/actuator.html)
- **Base URL:** `http://localhost:8080/actuator`

#### Tags

- Health Check
- Management
- Metrics
- Monitoring

#### Properties

- [Documentation](https://docs.spring.io/spring-boot/docs/3.2.x/reference/html/actuator.html)
- [A P I  Documentation](https://docs.spring.io/spring-boot/docs/3.2.x/actuator-api/htmlsingle/)
- [GitHub Repository](https://github.com/spring-projects/spring-boot)
- [OpenAPI](openapi/spring-boot-3-actuator-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spring-boot-3-actuator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-boot-3-actuator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral  Rules](rules/spring-boot-3-rules.yml)

### Spring Boot Core Framework

Core Spring Boot 3 framework providing auto-configuration, embedded server support (Tomcat, Jetty, Undertow), externalized configuration, profiles, and conditional bean registration.

- **Human URL:** [https://docs.spring.io/spring-boot/docs/3.2.x/reference/html/](https://docs.spring.io/spring-boot/docs/3.2.x/reference/html/)
- **Base URL:** `https://github.com/spring-projects/spring-boot`

#### Tags

- Auto-Configuration
- Embedded Server
- Framework
- Java

#### Properties

- [Documentation](https://docs.spring.io/spring-boot/docs/3.2.x/reference/html/)
- [A P I  Documentation](https://docs.spring.io/spring-boot/docs/3.2.x/api/)
- [GitHub Repository](https://github.com/spring-projects/spring-boot)
- [Getting Started](https://spring.io/guides/gs/spring-boot/)
- [Release Notes](https://github.com/spring-projects/spring-boot/releases)
- [Migration  Guide](https://github.com/spring-projects/spring-boot/wiki/Spring-Boot-3.0-Migration-Guide)
- [Maven  Central](https://mvnrepository.com/artifact/org.springframework.boot/spring-boot)
- [Postman Collection](collections/spring-boot-3-actuator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-boot-3-actuator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Web MVC API

Web MVC framework for building web applications and RESTful services with Spring Boot 3. Includes controllers, filters, interceptors, and content negotiation.

- **Human URL:** [https://docs.spring.io/spring-framework/docs/6.1.x/reference/html/web.html](https://docs.spring.io/spring-framework/docs/6.1.x/reference/html/web.html)
- **Base URL:** `http://localhost:8080`

#### Tags

- HTTP
- MVC
- REST
- Web

#### Properties

- [Documentation](https://docs.spring.io/spring-framework/docs/6.1.x/reference/html/web.html)
- [Tutorial](https://spring.io/guides/gs/rest-service/)
- [Postman Collection](collections/spring-boot-3-actuator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-boot-3-actuator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Data REST API

Automatically expose Spring Data repositories as hypermedia-driven REST resources using HAL. Integrates with Spring Data JPA, MongoDB, Neo4j, and other stores.

- **Human URL:** [https://docs.spring.io/spring-data/rest/docs/current/reference/html/](https://docs.spring.io/spring-data/rest/docs/current/reference/html/)
- **Base URL:** `http://localhost:8080/api`

#### Tags

- CRUD
- Data
- HAL
- REST

#### Properties

- [Documentation](https://docs.spring.io/spring-data/rest/docs/current/reference/html/)
- [A P I  Documentation](https://docs.spring.io/spring-data/rest/docs/current/api/)
- [Postman Collection](collections/spring-boot-3-actuator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-boot-3-actuator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Security API

Security framework for authentication and authorization in Spring Boot 3 applications. Supports OAuth2, OIDC, SAML2, JWT, and method-level security.

- **Human URL:** [https://docs.spring.io/spring-security/reference/](https://docs.spring.io/spring-security/reference/)
- **Base URL:** `http://localhost:8080`

#### Tags

- Authentication
- Authorization
- OAuth2
- Security

#### Properties

- [Documentation](https://docs.spring.io/spring-security/reference/)
- [A P I  Documentation](https://docs.spring.io/spring-security/site/docs/6.2.x/api/)
- [O Auth2  Guide](https://spring.io/guides/tutorials/spring-boot-oauth2/)
- [Postman Collection](collections/spring-boot-3-actuator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-boot-3-actuator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Getting Started](https://spring.io/guides/gs/spring-boot/)
- [GitHub Repository](https://github.com/spring-projects/spring-boot)
- [Release Notes](https://github.com/spring-projects/spring-boot/releases)
- [Migration  Guide](https://github.com/spring-projects/spring-boot/wiki/Spring-Boot-3.0-Migration-Guide)
- [Community](https://spring.io/community)
- [Blog](https://spring.io/blog)

## Maintainers

**Email:** spring-team@vmware.com
**URL:** https://spring.io/team
