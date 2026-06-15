# Maven (maven)

Apache Maven is a software project management and build automation tool used primarily for Java projects. Maven Central is the default artifact repository for Maven, and Sonatype provides REST APIs for searching and publishing artifacts to Maven Central.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/maven/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/maven/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Artifacts
- Build Tools
- Java
- Maven
- Package Management
- Repository

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Maven Central Search API

REST API for searching and retrieving artifact metadata from Maven Central Repository. Supports Solr-based queries for finding Java libraries and their versions.

- **Human URL:** [https://central.sonatype.com/](https://central.sonatype.com/)
- **Base URL:** `https://search.maven.org/solrsearch`

#### Tags

- Artifacts
- Java
- Search

#### Properties

- [Documentation](https://central.sonatype.org/search/rest-api-guide/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/maven/refs/heads/main/openapi/maven-search-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maven-portal.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maven-portal.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/maven-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maven-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maven Central Portal Publishing API

API for publishing artifacts to Maven Central through the Sonatype Central Portal. Supports automated deployment of Java libraries and other JVM-based artifacts.

- **Human URL:** [https://central.sonatype.com/](https://central.sonatype.com/)
- **Base URL:** `https://central.sonatype.com/api/v1`

#### Tags

- Deployment
- Publishing
- Upload

#### Properties

- [Documentation](https://central.sonatype.org/publish/publish-portal-api/)
- [Authentication](https://central.sonatype.org/publish/generate-token/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/maven/refs/heads/main/openapi/maven-portal-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maven-portal.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maven-portal.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/maven-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maven-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/maven-hq)
- [Website](https://maven.apache.org)
- [Documentation](https://maven.apache.org/guides/)
- [GitHub Organization](https://github.com/apache/maven)
- [Support](https://maven.apache.org/mailing-lists.html)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
