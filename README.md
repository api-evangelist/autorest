# AutoRest (autorest)

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
