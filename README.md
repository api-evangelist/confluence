# Confluence (confluence)
APIs for Atlassian Confluence - team collaboration and knowledge management software.

**URL:** [Visit APIs.json URL](https://developer.atlassian.com/cloud/confluence/rest/v1/intro/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Collaboration, Content Management, Documentation, Knowledge Base, Wiki

## Timestamps

- **Created:** 2024
- **Modified:** 2026-04-18

## APIs

### Confluence Cloud REST API v1
Primary REST API for Confluence Cloud for content, spaces, and user management.

**Human URL:** [https://developer.atlassian.com/cloud/confluence/rest/v1/intro/](https://developer.atlassian.com/cloud/confluence/rest/v1/intro/)

#### Tags:

 - Cloud, Content, Rest, Spaces

#### Properties

- [Documentation](https://developer.atlassian.com/cloud/confluence/rest/v1/intro/)
- [OpenAPI](https://dac-static.atlassian.com/cloud/confluence/swagger.v3.json)
- [Authentication](https://developer.atlassian.com/cloud/confluence/rest/v1/intro/#auth)
- [CodeExamples](https://developer.atlassian.com/cloud/confluence/rest-api-examples/)
- [GettingStarted](https://developer.atlassian.com/cloud/confluence/getting-started/)
- [ChangeLog](https://developer.atlassian.com/cloud/confluence/changelog/)

### Confluence Cloud REST API v2
Next generation Confluence Cloud REST API with improved performance and new features.

**Human URL:** [https://developer.atlassian.com/cloud/confluence/rest/v2/intro/](https://developer.atlassian.com/cloud/confluence/rest/v2/intro/)

#### Tags:

 - Cloud, Pages, Rest, V2

#### Properties

- [Documentation](https://developer.atlassian.com/cloud/confluence/rest/v2/intro/)
- [OpenAPI](https://developer.atlassian.com/cloud/confluence/rest/v2/api-spec/)
- [OpenAPI](openapi/confluence-cloud-v2.yml)
- [Authentication](https://developer.atlassian.com/cloud/confluence/rest/v2/intro/#authentication)
- [GettingStarted](https://developer.atlassian.com/cloud/confluence/getting-started/)
- [ChangeLog](https://developer.atlassian.com/cloud/confluence/changelog/)

### Confluence Content Properties API
Store and retrieve custom data against Confluence content.

**Human URL:** [https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-content-properties/](https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-content-properties/)

#### Tags:

 - Custom Data, Metadata, Properties

#### Properties

- [Documentation](https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-content-properties/)

### Confluence Search API
Search for content in Confluence using CQL (Confluence Query Language).

**Human URL:** [https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-search/](https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-search/)

#### Tags:

 - Cql, Query, Search

#### Properties

- [Documentation](https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-search/)
- [Documentation](https://developer.atlassian.com/cloud/confluence/advanced-searching-using-cql/)

## Common Properties

- [Portal](https://developer.atlassian.com/)
- [Documentation](https://www.atlassian.com/software/confluence)
- [GettingStarted](https://developer.atlassian.com/cloud/confluence/getting-started/)
- [DeveloperPortal](https://developer.atlassian.com/cloud/confluence/)
- [RateLimits](https://developer.atlassian.com/cloud/confluence/rate-limiting/)
- [ChangeLog](https://developer.atlassian.com/cloud/confluence/changelog/)
- [Support](https://support.atlassian.com/)
- [StatusPage](https://status.atlassian.com/)
- [Authentication](https://developer.atlassian.com/cloud/confluence/security-overview/)
- [Pricing](https://www.atlassian.com/software/confluence/pricing)
- [Marketplace](https://marketplace.atlassian.com/)
- [GitHubOrganization](https://github.com/atlassian)
- [YouTube](https://www.youtube.com/@Atlassian)
- [StackOverflow](https://stackoverflow.com/questions/tagged/atlassian-confluence)
- [LinkedIn](https://www.linkedin.com/company/atlassian)
- [Blog](https://www.atlassian.com/blog/confluence)
- [SignUp](https://www.atlassian.com/try/cloud/signup?bundle=confluence&edition=free)
- [Login](https://id.atlassian.com/login)
- [PrivacyPolicy](https://www.atlassian.com/legal/privacy-policy)
- [TermsOfService](https://www.atlassian.com/legal/cloud-terms-of-service)
- [SDK](https://developer.atlassian.com/server/framework/atlassian-sdk/)
- [SDK](https://github.com/atlassian-api/atlassian-python-api)
- [SDK](https://mrrefactoring.github.io/confluence.js/)

## Features

| Name | Description |
|------|-------------|
| Content Management | Create, read, update, and delete pages, blog posts, and other content types with full version history. |
| Space Management | Organize content into spaces with configurable permissions and settings. |
| Real-Time Collaboration | Multiple users can edit pages simultaneously with live cursor tracking. |
| Search with CQL | Advanced search using Confluence Query Language for precise content discovery. |
| Webhooks | Real-time event notifications for content changes, space updates, and user actions. |
| Content Templates | Standardized page creation using blueprints and customizable templates. |
| Labels and Organization | Tag and categorize content with labels for improved discovery and navigation. |
| Permissions and Access Control | Granular read and update restrictions at space and content level. |

## Use Cases

| Name | Description |
|------|-------------|
| Knowledge Base | Build and maintain internal knowledge bases for teams with structured content and search. |
| Project Documentation | Create and collaborate on project documentation with version tracking and approvals. |
| Content Migration | Programmatically migrate content between Confluence instances or from other platforms. |
| Compliance and Auditing | Track content changes, manage access controls, and maintain audit trails. |
| Automated Publishing | Generate and publish content programmatically from CI/CD pipelines or other systems. |

## Integrations

| Name | Description |
|------|-------------|
| Jira | Link Confluence pages to Jira issues for seamless project management workflows. |
| Slack | Receive Confluence notifications and preview pages directly in Slack channels. |
| Microsoft Teams | Collaborate on Confluence content within Microsoft Teams conversations. |
| Trello | Embed Trello boards in Confluence pages and link cards to documentation. |
| GitHub | Embed code snippets and link repositories to Confluence documentation. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Confluence Cloud REST API v2](openapi/confluence-cloud-v2.yml)

### AsyncAPI

- [Confluence Webhooks](asyncapi/confluence-webhooks.yml)

### JSON Schema

- [Confluence Page Schema](json-schema/confluence-page-schema.json)
- [Confluence Space Schema](json-schema/confluence-space-schema.json)

### JSON-LD

- [Confluence Context](json-ld/confluence-context.jsonld)
- [Confluence Cloud v2 Context](json-ld/confluence-cloud-v2-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Confluence Cloud REST API v2](capabilities/shared/cloud-v2.yaml) -- 27 operations for content, spaces, comments, blog posts, attachments, and labels management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Content Management](capabilities/content-management.yaml) | Cloud REST API v2 | 25 | Content Author / Knowledge Manager |

## Vocabulary

- [Confluence Vocabulary](vocabulary/confluence-vocabulary.yaml) -- 27 operations and 43 schemas across 7 tags

## Rules

- [Confluence Spectral Rules](rules/confluence-spectral-rules.yml) -- 7 rules enforcing Confluence API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
