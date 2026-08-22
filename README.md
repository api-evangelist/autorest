# AutoRest (autorest)

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

AutoRest is an open source tool from Microsoft (MIT License) that generates client libraries for accessing RESTful APIs from OpenAPI specifications. It powers generation of Azure SDKs across C#, Python, Java, TypeScript, Go, PowerShell, and Swift with an extensible plugin architecture. Note: AutoRest is deprecated as of 2026 with retirement on July 1, 2026 — the recommended successor is TypeSpec.

**URL:** [https://github.com/Azure/autorest](https://github.com/Azure/autorest)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Code Generation, Microsoft, OpenAPI, SDK Generation, Azure SDK, Deprecated

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-04-19

## APIs

### AutoRest Core

The AutoRest Core package (@autorest/core) is the central engine that orchestrates code generation from OpenAPI specifications. It handles input processing, configuration resolution, pipeline management, and plugin coordination.

**Human URL:** [https://github.com/Azure/autorest](https://github.com/Azure/autorest)

#### Tags

 - Code Generation, OpenAPI, Plugin System, Pipeline

#### Properties

- [Documentation](https://github.com/Azure/autorest/blob/main/docs/readme.md)
- [Getting Started](https://github.com/Azure/autorest/blob/main/docs/install/readme.md)
- [GitHub Repository](https://github.com/Azure/autorest)
- [npm Package](https://www.npmjs.com/package/@autorest/core)

### AutoRest C# Generator

The @autorest/csharp generator produces .NET client libraries from OpenAPI specifications with strongly-typed C# code, HttpClient-based REST clients, and async/await patterns compatible with .NET 6+.

**Human URL:** [https://github.com/Azure/autorest.csharp](https://github.com/Azure/autorest.csharp)

#### Tags

 - C#, .NET, Code Generation, Azure SDK

#### Properties

- [Documentation](https://github.com/Azure/autorest.csharp)
- [GitHub Repository](https://github.com/Azure/autorest.csharp)

### AutoRest Python Generator

The @autorest/python generator produces Python client libraries from OpenAPI specifications, compatible with the Azure SDK for Python and azure-core library.

**Human URL:** [https://github.com/Azure/autorest.python](https://github.com/Azure/autorest.python)

#### Tags

 - Python, Code Generation, Azure SDK

#### Properties

- [Documentation](https://github.com/Azure/autorest.python)
- [GitHub Repository](https://github.com/Azure/autorest.python)

### AutoRest Java Generator

The @autorest/java generator produces Java client libraries from OpenAPI specifications compatible with azure-core and the Azure SDK for Java ecosystem.

**Human URL:** [https://github.com/Azure/autorest.java](https://github.com/Azure/autorest.java)

#### Tags

 - Java, Code Generation, Azure SDK

#### Properties

- [Documentation](https://github.com/Azure/autorest.java)
- [GitHub Repository](https://github.com/Azure/autorest.java)

### AutoRest TypeScript Generator

The @autorest/typescript generator produces TypeScript and JavaScript client libraries from OpenAPI specifications for Node.js and browser environments.

**Human URL:** [https://github.com/Azure/autorest.typescript](https://github.com/Azure/autorest.typescript)

#### Tags

 - TypeScript, JavaScript, Code Generation, Azure SDK

#### Properties

- [Documentation](https://github.com/Azure/autorest.typescript)
- [GitHub Repository](https://github.com/Azure/autorest.typescript)

### AutoRest Go Generator

The @autorest/go generator produces Go client libraries from OpenAPI specifications, generating idiomatic Go code compatible with the Azure SDK for Go.

**Human URL:** [https://github.com/Azure/autorest.go](https://github.com/Azure/autorest.go)

#### Tags

 - Go, Code Generation, Azure SDK

#### Properties

- [Documentation](https://github.com/Azure/autorest.go)
- [GitHub Repository](https://github.com/Azure/autorest.go)

## Common Properties

- [Website](https://github.com/Azure/autorest)
- [Documentation](https://github.com/Azure/autorest/blob/main/docs/readme.md)
- [GitHub Organization](https://github.com/Azure)
- [GitHub Repository](https://github.com/Azure/autorest)
- [Getting Started](https://github.com/Azure/autorest/blob/main/docs/install/readme.md)
- [Release Notes](https://github.com/Azure/autorest/releases)

## Features

| Name | Description |
|------|-------------|
| Multi-Language Code Generation | Generate client SDKs from OpenAPI specifications in C#, Python, Java, TypeScript, JavaScript, Go, PowerShell, and Swift using language-specific generator plugins. |
| Extensible Plugin Architecture | AutoRest uses a pipeline-based plugin architecture where language generators, transformers, and validators are loaded as npm packages. Custom plugins can be developed to extend the generation pipeline. |
| OpenAPI Processing | Supports OpenAPI 2.0 (Swagger) and OpenAPI 3.0 specification formats. The modelerfour plugin normalizes OpenAPI schemas into a consistent code model shared across all language generators. |
| Azure SDK Integration | Tightly integrated with Microsoft Azure SDK generation for all Azure services, producing SDK packages published to npm, PyPI, Maven, NuGet, and Go Modules. |
| Configuration File Support | Supports literate configuration using Markdown code blocks for per-client customization of generated output including namespace, output folder, and generator-specific options. |

## Use Cases

| Name | Description |
|------|-------------|
| Azure Service SDK Generation | Primary use case for generating Azure SDK client libraries for all Azure services from the azure-rest-api-specs OpenAPI repository. |
| REST API Client Generation | Generate strongly-typed client SDKs for any REST API described in OpenAPI format across multiple programming languages simultaneously. |
| SDK Customization | Use AutoRest configuration files and directives to customize generated code including renames, suppressions, and additional properties. |

## Integrations

| Name | Description |
|------|-------------|
| Azure REST API Specs | AutoRest is the primary tool consuming the Azure/azure-rest-api-specs repository to generate official Azure SDK client libraries. |
| TypeSpec | TypeSpec is the recommended successor to AutoRest for new API definitions, with AutoRest generators serving as code generation backends. |
| npm | AutoRest and all language generator plugins are distributed as npm packages under the @autorest scope. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
