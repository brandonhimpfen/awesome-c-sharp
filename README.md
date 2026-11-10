# Awesome C# [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=github)](https://github.com/brandonhimpfen/support) 
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) <br />
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of resources for C#, .NET runtimes, ASP.NET Core web frameworks, ORMs, dependency injection, async patterns, Roslyn analyzers, and cross-platform desktop UI engines.

C# is a modern, object-oriented, type-safe programming language running on the cross-platform .NET runtime. Featuring language-integrated queries (LINQ), async/await concurrency primitives, pattern matching, record types, and source generators, C# powers cloud microservices, enterprise web backends, cross-platform desktop apps, mobile applications, and game development engines. This list is intended for .NET developers, backend engineers, cloud software architects, and C# application leads.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Web Frameworks & API Engines](#web-frameworks--api-engines)
- [Data Access & ORMs](#data-access--orms)
- [Serialization & Code Generation](#serialization--code-generation)
- [UI & Cross-Platform Application Frameworks](#ui--cross-platform-application-frameworks)
  - [Desktop & Mobile Frameworks](#desktop--mobile-frameworks)
  - [Web Assembly & Web UI](#web-assembly--web-ui)
- [Roslyn Analyzers & Developer Tooling](#roslyn-analyzers--developer-tooling)
- [Related Awesome Lists](#related-awesome-lists)

## Web Frameworks & API Engines

REST API micro-frameworks, gRPC communications, GraphQL servers, and real-time web backends.

- [ASP.NET Core](https://github.com/dotnet/aspnetcore) — Official cross-platform, high-performance open-source framework for building modern, cloud-enabled web applications.
- [FastEndpoints](https://github.com/FastEndpoints/FastEndpoints) — Developer-friendly alternative to ASP.NET Core Minimal APIs implementing the REPR (Request-Endpoint-Response) pattern.
- [Carter](https://github.com/CarterCommunity/Carter) — Thin library that allows ASP.NET Core Minimal APIs to be structured in elegant, maintainable modules.
- [Hot Chocolate](https://github.com/ChilliCream/graphql-platform) — High-performance GraphQL server engine for .NET and ASP.NET Core.
- [SignalR](https://github.com/dotnet/aspnetcore) — Real-time event framework for ASP.NET Core enabling bi-directional WebSocket communications.

## Data Access & ORMs

Object-relational mappers, lightweight micro-ORMs, event store drivers, and query generation toolkits.

- [Entity Framework Core](https://github.com/dotnet/efcore) — Official lightweight, extensible, open-source, and cross-platform object-database mapper for .NET.
- [Dapper](https://github.com/DapperLib/Dapper) — High-performance micro-ORM for .NET providing fast object mapping over raw SQL executions.
- [Marten](https://github.com/JasperFx/marten) — .NET document database library and event store using PostgreSQL as the underlying persistence engine.
- [FluentMigrator](https://github.com/fluentmigrator/fluentmigrator) — Migration framework for .NET providing a fluent DSL for managing SQL database schema changes.

## Serialization & Code Generation

High-performance binary serializers, JSON parsers, and compile-time Roslyn source generators.

- [MemoryPack](https://github.com/Cysharp/MemoryPack) — Zero-encoding, extreme-performance binary serializer designed for C# and Unity.
- [MessagePack-CSharp](https://github.com/MessagePack-CSharp/MessagePack-CSharp) — Extremely fast MessagePack serializer for C# (.NET, .NET Core, Unity).
- [Mapperly](https://github.com/riok/mapperly) — Roslyn source generator for generating object-to-object mappings without runtime reflection overhead.
- [System.Text.Json](https://github.com/dotnet/runtime) — Built-in high-performance, low-allocation JSON processing engine.

## UI & Cross-Platform Application Frameworks

Native desktop GUI toolkits, mobile development stacks, and browser-based WebAssembly engines.

### Desktop & Mobile Frameworks

- [Avalonia](https://github.com/AvaloniaUI/Avalonia) — Cross-platform XAML-based UI framework supporting Windows, macOS, Linux, iOS, Android, and WebAssembly.
- [.NET MAUI](https://github.com/dotnet/maui) — Official cross-platform framework for building native desktop and mobile apps with C# and XAML.
- [WPF UI](https://github.com/lepoco/wpfui) — Modern Fluent Design control library and intuitive themes for native Windows Presentation Foundation (WPF) applications.
- [Uno Platform](https://github.com/unoplatform/uno) — Open-source engine allowing single-source C# and XAML applications to run natively across desktop, mobile, and WebAssembly.

### Web Assembly & Web UI

- [Blazor](https://github.com/dotnet/aspnetcore) — Web framework enabling full-stack web UI development using interactive C# instead of JavaScript.

## Roslyn Analyzers & Developer Tooling

Static code analysis tools, IL decompilers, REPLs, and formatting utilities powered by the Roslyn compiler pipeline.

- [Roslyn](https://github.com/dotnet/roslyn) — The .NET Compiler Platform providing C# compilers with rich code analysis APIs.
- [ILSpy](https://github.com/icsharpcode/ILSpy) — Decompiler engine for inspecting .NET assemblies, generating PDBs, and examining ReadyToRun metadata.
- [Roslynator](https://github.com/josefpirt/roslynator) — Collection of over 500 static code analyzers, refactorings, and code fixes for C#.
- [CSharpier](https://github.com/belav/csharpier) — Opinionated code formatter for C# parsing syntax trees via Roslyn.

## Related Awesome Lists

- [Awesome Java](https://github.com/brandonhimpfen/awesome-java) — Enterprise object-oriented frameworks, JVM runtimes, and concurrency libraries.
- [Awesome Open Source](https://github.com/brandonhimpfen/awesome-open-source) — Best practices, licensing standards, and community management frameworks for open projects.
- [Awesome JavaScript](https://github.com/brandonhimpfen/awesome-javascript) — Web runtimes, frontend frameworks, and asynchronous event pipelines.
- [Awesome Functional Programming](https://github.com/brandonhimpfen/awesome-functional-programming) — Purely functional concepts, immutability, type systems, and pattern matching.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
