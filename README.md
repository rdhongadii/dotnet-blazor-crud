# BlazorCrud

[![CircleCI](https://circleci.com/gh/thbst16/BlazorCrud.svg?style=svg)](https://circleci.com/gh/thbst16/BlazorCrud)

Blazor CRUD is a demo application built with the [Blazor](https://blazor.net) framework using the client-side hosting model with WebAssembly and .NET Core REST APIs secured by a JWT service. To browse the two components of the application, follow the links below. For authenticated pages and APIs, use the credentials (user@beckshome.com / Password123).
* [Blazor CRUD Application](http://becksblazor.azurewebsites.net/) - A client-side hosted WASM application built using Blazor. The application highlights CRUD data entry for entities, data pagination, client-side validation using Data Annotations, and authentication and authorization using JWT tokens.
* [Blazor CRUD REST API](http://becksapi.azurewebsites.net) - A REST API for CRUD with non-read API calls secured with JWT. The API includes a call to authenticate users and receive a JWT bearer token.

Blazor CRUD uses the following DevOps environment and tools to support a CI / CD process:
* [GitHub Source Code Repository](https://github.com/thbst16/BlazorCrud) - All source code is stored in the GitHub repository, which is where you currently find yourself.
* [CircleCI for CI/CD](https://circleci.com/gh/thbst16/BlazorCrud) - CircleCI is used for continunous integration and continuous delivery (CI/CD). In it's current format, CircleCI is being used exclusively as a build server. Current project build status can also be followed using the CircleCI badge on this page.