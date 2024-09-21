# Sidub Platform Overview

Introducing **Sidub Platform**, a comprehensive collection of software libraries designed to facilitate structured and efficient enterprise .NET development. These libraries define essential concepts and offer reusable functionality to support business and enterprise systems developers. From localization support to core platform concepts and beyond, the Sidub Platform empowers developers to streamline their tasks and accelerate software development.

## Features

### Utility

- **Globalization / Localization:**  
  Provides comprehensive support for globalization and localization throughout the entire platform, ensuring that every layer – from system-level logging and exceptions to user-facing messages – is adaptable to different languages and regions.

- **Service Registry:**  
  Enables the registration and interaction with Sidub service references, providing a unified approach to service discovery and management within your system.

- **Filter / Query Strings:**  
  Offers domain-based filter models that can be parsed into any query language or syntax, enhancing data querying and filtering capabilities.

- **Numbering Sequences:**  
  Supports defining various number sequence types and structures essential for generating sequenced or random unique identifiers used in structured record identification.

### Entity Framework

- **Entity and Entity Relationships:**  
  Facilitates the definition and management of complex data models and their relationships, ensuring data integrity and consistency.

- **Entity (De)serialization:**  
  Allows for the serialization and deserialization of entities into JSON, XML, or any required format, supporting diverse data interchange needs.

- **Entity Partitioning:**  
  Supports programmatic or runtime-based partitioning of entities, optimizing data storage and retrieval.

- **Entity Change Tracking:**  
  Enables tracking of changes to entities, crucial for auditing purposes and enhancing CRUD (Create, Read, Update, Delete) performance.

### Storage / API Layer

- **Entity Persistence:**  
  Facilitates the retrieval and persistence of entities against various data stores, ensuring data durability and availability.

- **APIs Actions and Functions:**  
  Provides tools for calling API actions and functions, allowing seamless integration and interaction with external services.

- **Extensibility:**  
  Supports building custom handlers to communicate with any data source or API, offering data access and integration flexibility.

- **Authentication:**  
  Supports multiple authentication mechanisms for user and service-based identity, including public client flows for user authentication and confidential client flows for service authentication. This ensures secure and efficient authentication processes across various scenarios within the platform.

### Storage / API Extensions

- **Gremlin Storage Extension:**  
  Enables connectivity with Gremlin-based graph databases, facilitating complex data relationships and queries.

- **HTTP Storage Extension:**  
  Enables integration with HTTP-based storage services and APIs, including OData, Azure Table, Blob, and Queue Storage, as well as any HTTP-based API service. This extension provides connectors and handlers for seamless data management across these services, leveraging the platform's built-in authentication.

### Security & Cryptography

- **Encryption / Decryption:**  
  Supports encrypting and decrypting data and entities for secure information handling.

- **Signing / Verification:**  
  Enables signing and verification of data and entities to ensure integrity and authenticity.

- **Extensibility:**  
  Supports integration with local cryptographic hardware, Azure Key Vault, or custom handlers to connect with your chosen vault or cryptographic service.

## Libraries

The following libraries compose the Sidub Platform. Packages are distributed on NuGet.org, and source code is available on GitHub.com for open-source licensed projects. Licensing terms are available in each library’s public repository or project page.

| Library | Description |
| --- | --- |
| **Localization** | Provides localization support to allow adaptation of software for various languages and cultures. |
| **Filter** | Provides ability to define filters/queries which may be parsed to various query languages. |
| **Core** | Defines core platform concepts (entities, relationships, etc.) and provides a variety of functionality for interacting with core concepts. |
| **NumberSequence** | Provides concepts to allow the definition of identifiers using various number sequence concepts. Allows developers to generate and maintain structured identifiers to apply against records easily. |
| **Cryptography**<br>**Cryptography.AzureKeyVault** | Provides cryptographic functionality to allow developers to encrypt/decrypt, sign/verify data, and perform other cryptographic functions against data and entities. |
| **Authentication**<br>**Authentication.Credentials.Azure** | Provides authentication concepts and abstractions used to perform authentication throughout the platform; enables authentication against data sources and services. |
| **Authentication.Gremlin**<br>**Authentication.Http**<br>**Authentication.IsolatedFunction**<br>**Authentication.SignalR** | Provides specific authentication implementations against various connection or service types. |
| **Authorization**<br>**Authorization.IsolatedFunction** | Provides authorization concepts and abstractions used to perform authorization throughout the platform; enables authorization against data sources and services. |
| **Storage** | Provides data connectivity concepts and abstractions used to connect and communicate with various service and system types. |
| **Storage.Gremlin**<br>**Storage.Http** | Provides specific connectivity implementations against various service and system types. |

> **Note:** License dependencies are not cumulative; see package dependencies.

## Release State, Terms and Information

| Library | License | Release | Links |
| --- | --- | --- | --- |
| **Localization** | AGPLv3 / proprietary | Public | [GitHub](https://github.com/sidubsolutions/Sidub.Platform.Localization) • [NuGet](https://www.nuget.org/packages/Sidub.Platform.Localization) |
| **Filter** | AGPLv3 / proprietary | Public | [GitHub](https://github.com/sidubsolutions/Sidub.Platform.Filter) • [NuGet](https://www.nuget.org/packages/Sidub.Platform.Filter) |
| **Core** | AGPLv3 / proprietary | Public | [GitHub](https://github.com/sidubsolutions/Sidub.Platform.Core) • [NuGet](https://www.nuget.org/packages/Sidub.Platform.Core) |
| **NumberSequence** | AGPLv3 / proprietary | Public | [GitHub](https://github.com/sidubsolutions/Sidub.Platform.NumberSequence) • [NuGet](https://www.nuget.org/packages/Sidub.Platform.NumberSequence) |
| **Cryptography** | Private | Complete; pending public release | [GitHub](https://github.com/sidubsolutions/Sidub.Platform.Cryptography) • [NuGet](https://www.nuget.org/packages/Sidub.Platform.Cryptography) |
| **Cryptography.AzureKeyVault** | Private | Complete; pending public release | [GitHub](https://github.com/sidubsolutions/Sidub.Platform.Cryptography.AzureKeyVault) • [NuGet](https://www.nuget.org/packages/Sidub.Platform.Cryptography.AzureKeyVault) |
| **Authentication** | Private | Complete; pending public release | [GitHub](https://github.com/sidubsolutions/Sidub.Platform.Authentication) • [NuGet](https://www.nuget.org/packages/Sidub.Platform.Authentication) |
| **Authentication.Credentials.Azure** | Private | Complete; pending public release | [GitHub](https://github.com/sidubsolutions/Sidub.Platform.Authentication.Credentials.Azure) • [NuGet](https://www.nuget.org/packages/Sidub.Platform.Authentication.Credentials.Azure) |
| **Authentication.Gremlin** | Private | Complete; pending public release | [GitHub](https://github.com/sidubsolutions/Sidub.Platform.Authentication.Gremlin) • [NuGet](https://www.nuget.org/packages/Sidub.Platform.Authentication.Gremlin) |
| **Authentication.Http** | Private | Complete; pending public release | [GitHub](https://github.com/sidubsolutions/Sidub.Platform.Authentication.Http) • [NuGet](https://www.nuget.org/packages/Sidub.Platform.Authentication.Http) |
| **Authentication.IsolatedFunction** | Private | Complete; pending public release | [GitHub](https://github.com/sidubsolutions/Sidub.Platform.Authentication.IsolatedFunction) • [NuGet](https://www.nuget.org/packages/Sidub.Platform.Authentication.IsolatedFunction) |
| **Authentication.SignalR** | Private | Complete; pending public release | [GitHub](https://github.com/sidubsolutions/Sidub.Platform.Authentication.SignalR) • [NuGet](https://www.nuget.org/packages/Sidub.Platform.Authentication.SignalR) |
| **Authorization** | Private | Future release (in progress) | [GitHub](https://github.com/sidubsolutions/Sidub.Platform.Authorization) • [NuGet](https://www.nuget.org/packages/Sidub.Platform.Authorization) |
| **Authorization.IsolatedFunction** | Private | Complete; pending public release | [GitHub](https://github.com/sidubsolutions/Sidub.Platform.Authorization.IsolatedFunction) • [NuGet](https://www.nuget.org/packages/Sidub.Platform.Authorization.IsolatedFunction) |
| **Storage** | AGPLv3 / proprietary | Complete; pending public release | [GitHub](https://github.com/sidubsolutions/Sidub.Platform.Storage) • [NuGet](https://www.nuget.org/packages/Sidub.Platform.Storage) |
| **Storage.Gremlin** | AGPLv3 / proprietary | Complete; pending public release | [GitHub](https://github.com/sidubsolutions/Sidub.Platform.Storage.Gremlin) • [NuGet](https://www.nuget.org/packages/Sidub.Platform.Storage.Gremlin) |
| **Storage.Http** | AGPLv3 / proprietary | Complete; pending public release | [GitHub](https://github.com/sidubsolutions/Sidub.Platform.Storage.Http) • [NuGet](https://www.nuget.org/packages/Sidub.Platform.Storage.Http) |


## Dependencies

Certain libraries within the platform have interdependencies; a chart has been included within the appendix which exhibits these dependencies.

## Appendix

### License Dependency References

- **MIT**  
  [https://licenses.nuget.org/MIT](https://licenses.nuget.org/MIT)

- **DotNet Library License**  
  [https://dotnet.microsoft.com/en-us/dotnet_library_license.htm](https://dotnet.microsoft.com/en-us/dotnet_library_license.htm)

- **Metalama License**  
  [https://www.nuget.org/packages/Metalama.Framework/2024.0.11/license](https://www.nuget.org/packages/Metalama.Framework/2024.0.11/license)

- **Apache 2.0**  
  [https://licenses.nuget.org/Apache-2.0](https://licenses.nuget.org/Apache-2.0)

### Platform Interdependencies


```mermaid
graph TD;
    Core --> Localization
    NumberSequence --> Core
    Cryptography --> Core
    Cryptography.AzureKeyVault --> Cryptography
    Cryptography.AzureKeyVault --> Storage.Http
    Filter --> Core
    Storage --> Core
    Authorization --> Core
    
    Authentication --> Storage
    Authentication.Credentials.Azure --> Authentication
    Authentication.Gremlin --> Authentication
    Authentication.Http --> Authentication
    Authentication.SignalR --> Authentication
    
    Storage.Gremlin --> Storage
    Storage.Http --> Storage
    
    Authentication --> Authentication.IsolatedFunction
    Authorization --> Authorization.IsolatedFunction
```
