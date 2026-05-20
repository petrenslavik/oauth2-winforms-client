# OAuth2 WinForms Client

A small example of integrating an OAuth 2.0 / OIDC client into a Windows
Forms application. Built primarily to explore the browser-redirect-and-
exchange flow in a desktop context (where there's no convenient HTTP
listener like a web app would have).

## Stack
- .NET (WinForms)
- Custom `AuthClient` implementing the authorisation-code flow
- Pluggable `IOidcClientOptionsBuilder` with an Okta-specific implementation
- `WinFormsBrowsers` for embedded browser flow handling

## Status
Personal exploration. Built to learn how OIDC integrates with desktop
applications in 2022.
