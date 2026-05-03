# Spring Boot 3

Spring Boot 3 is the major release of the opinionated Spring application framework, built on Spring Framework 6, requiring Java 17 baseline and Jakarta EE 10. It delivers native image support via GraalVM, improved observability with Micrometer tracing, and a modernized auto-configuration system.

- **URL:** https://spring.io/projects/spring-boot
- **Type:** Open Source
- **Tags:** Enterprise, Framework, Java, Microservices, REST API, Spring Boot

## APIs

### Spring Boot Actuator API

Production-ready features for monitoring and managing Spring Boot 3 applications. Provides health checks, Micrometer metrics, environment inspection, logger configuration, thread dumps, and more.

- [Documentation](https://docs.spring.io/spring-boot/docs/3.2.x/reference/html/actuator.html)
- [API Documentation](https://docs.spring.io/spring-boot/docs/3.2.x/actuator-api/htmlsingle/)
- [GitHub Repository](https://github.com/spring-projects/spring-boot)

### Spring Boot Core Framework

Core Spring Boot 3 auto-configuration, embedded server, and application bootstrap support.

- [Documentation](https://docs.spring.io/spring-boot/docs/3.2.x/reference/html/)
- [Getting Started](https://spring.io/guides/gs/spring-boot/)

### Spring Web MVC API

Web MVC framework for building web applications and RESTful services with Spring Boot 3.

- [Documentation](https://docs.spring.io/spring-framework/docs/6.1.x/reference/html/web.html)

### Spring Data REST API

Automatically expose Spring Data repositories as hypermedia-driven REST resources.

- [Documentation](https://docs.spring.io/spring-data/rest/docs/current/reference/html/)

### Spring Security API

Security framework for authentication and authorization in Spring Boot 3 applications.

- [Documentation](https://docs.spring.io/spring-security/reference/)

## OpenAPI Specifications

| API | File |
|-----|------|
| Spring Boot 3 Actuator API | [openapi/spring-boot-3-actuator-openapi.yml](openapi/spring-boot-3-actuator-openapi.yml) |

## Spectral Rules

| Ruleset | File |
|---------|------|
| Spring Boot 3 Rules | [rules/spring-boot-3-rules.yml](rules/spring-boot-3-rules.yml) |

## Capabilities

### Shared Definitions

| API | File |
|-----|------|
| Spring Boot 3 Actuator API | [capabilities/shared/spring-boot-3-actuator.yaml](capabilities/shared/spring-boot-3-actuator.yaml) |

### Workflow Capabilities

| Workflow | Description | File |
|----------|-------------|------|
| Application Observability | Health, metrics, logging, and diagnostics | [capabilities/application-observability.yaml](capabilities/application-observability.yaml) |

## JSON Schemas

| Schema | File |
|--------|------|
| Health Response | [json-schema/spring-boot-3-health-schema.json](json-schema/spring-boot-3-health-schema.json) |
| Metric Detail | [json-schema/spring-boot-3-metrics-schema.json](json-schema/spring-boot-3-metrics-schema.json) |

## JSON Structures

| Structure | File |
|-----------|------|
| Actuator Domain Model | [json-structure/spring-boot-3-actuator-structure.json](json-structure/spring-boot-3-actuator-structure.json) |

## JSON-LD Contexts

| Context | File |
|---------|------|
| Spring Boot 3 | [json-ld/spring-boot-3-context.jsonld](json-ld/spring-boot-3-context.jsonld) |

## Examples

| Example | File |
|---------|------|
| Get Application Health | [examples/spring-boot-3-get-health-example.json](examples/spring-boot-3-get-health-example.json) |
| Get Metric Value | [examples/spring-boot-3-get-metric-example.json](examples/spring-boot-3-get-metric-example.json) |
| Set Logger Level | [examples/spring-boot-3-set-logger-level-example.json](examples/spring-boot-3-set-logger-level-example.json) |

## Vocabulary

| Vocabulary | File |
|------------|------|
| Spring Boot 3 Domain Terms | [vocabulary/spring-boot-3-vocabulary.yml](vocabulary/spring-boot-3-vocabulary.yml) |

## Common Properties

- [Getting Started](https://spring.io/guides/gs/spring-boot/)
- [GitHub Repository](https://github.com/spring-projects/spring-boot)
- [Release Notes](https://github.com/spring-projects/spring-boot/releases)
- [Migration Guide](https://github.com/spring-projects/spring-boot/wiki/Spring-Boot-3.0-Migration-Guide)
- [Community](https://spring.io/community)
- [Blog](https://spring.io/blog)

## Maintainers

- VMware Tanzu (Broadcom) — spring-team@vmware.com
