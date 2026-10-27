# Pulse Analytics

Read-only Pulse portfolio, holdings, executed trades, cash, performance and risk analytics, with English and Arabic product guidance for existing Pulse Pro users in Egypt.

This repository contains the distributable plugin bundle and public MCP Registry metadata. It does not contain the Pulse application, financial engine, database, credentials or customer data.

- Website: https://mypulseanalytics.com/pulse-plugin/
- Setup: https://mypulseanalytics.com/mcp
- Privacy: https://mypulseanalytics.com/pulse-plugin/privacy
- Terms: https://mypulseanalytics.com/pulse-plugin/terms
- Support: support@mypulseanalytics.com

The remote connection uses https://mypulseanalytics.com/api/mcp. Sign in on Pulse and approve the required permissions. Never paste credentials into chat. The integration cannot place trades, transfer money or edit your portfolio.

## Community discovery

The community distribution route uses this public GitHub repository and the MCP Registry. It does not require a paid Claude or ChatGPT publisher account. Official in-product directory submissions are on hold; community discovery is separate from approval or search placement in those directories.

**[Live MCP Registry listing](https://registry.modelcontextprotocol.io/v0.1/servers/io.github.ahmedmabdalla-ops%2Fpulse-analytics/versions/latest): version 1.1.0, active and searchable**, verified 27 October 2026.

Registry name: `io.github.ahmedmabdalla-ops/pulse-analytics`. The versioned declaration is in [server.json](server.json). A manually triggered GitHub Actions workflow validates and publishes it with short-lived GitHub OIDC authentication. It uses a standard public-repository runner and no saved API key, personal token, paid AI model call, build artifact storage or production deployment. The successful publication run is [available here](https://github.com/ahmedmabdalla-ops/pulse-analytics-plugin/actions/runs/40469557087).

## Connect from a supported host

1. Use an existing authorized Pulse Pro account in Egypt. Community distribution does not remove Pulse's account requirements.
2. Follow the [Pulse setup guide](https://mypulseanalytics.com/mcp) to add a custom remote MCP connection in a supported hosted ChatGPT or Claude client. Client plan availability and organization permissions are controlled by that client.
3. Use `https://mypulseanalytics.com/api/mcp` and complete sign-in and consent on Pulse's own page. Never paste a password or token into a conversation or configuration file.
4. Ask: “Summarize my portfolio and explain any data limitations.” Check the returned timestamps, currency and evidence.
5. Revoke access from Pulse Connected Apps and disconnect in your AI client when finished.

**Current compatibility:** the production OAuth policy allows the verified hosted ChatGPT and Claude identities only. Claude Code, VS Code and generic MCP clients are not currently enabled. Installing the bundle or finding it in a registry does not override that policy. There is deliberately no Claude Code marketplace install command promising unsupported account access.

## Publication status and security

The MCP Registry authenticates the publishing GitHub namespace. It does not certify Pulse's financial information or establish OpenAI/Anthropic approval. A registry entry does not guarantee that a particular client can connect or that it offers custom connections on a free plan. Existing Pulse hosting and users' client usage costs are separate from metadata publication.

The plugin has no local executable, hooks or portfolio write tools. Hypothetical results do not execute orders or save portfolio changes. See LICENSE for the limited plugin distribution permission.
