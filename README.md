# GraphQL Yoga

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

GraphQL Yoga is a fully-featured, cross-platform GraphQL server built on top of graphql-js and maintained by [The Guild](https://the-guild.dev). It supports all JavaScript environments including Node.js, Deno, Bun, Cloudflare Workers, and edge runtimes out of the box, with zero-configuration for subscriptions via server-sent events, file uploads, persisted documents, and WebSocket transport.

## Links

- **Website:** https://the-guild.dev/graphql/yoga-server
- **Documentation:** https://the-guild.dev/graphql/yoga-server/docs
- **GitHub:** https://github.com/dotansimha/graphql-yoga
- **LinkedIn:** https://www.linkedin.com/company/the-guild-of-developers/

## Key Features

- Works across all JavaScript runtimes (Node.js, Deno, Bun, Cloudflare Workers, edge)
- Subscriptions via Server-Sent Events (SSE) and WebSockets — zero configuration
- File uploads support
- Persisted documents (trusted documents)
- Request batching
- Extensible plugin system
- Built-in GraphiQL IDE
- CORS handling
- Federation support via Envelop plugins

## Catalog Contents

| Path | Description |
|---|---|
| `apis.yml` | Machine-readable API catalog entry (apis.io format) |
| `plans/graphql-yoga-plans.md` | Licensing and support plan details |
| `rate-limits/graphql-yoga-rate-limits.md` | Rate limiting guidance for self-hosted deployments |
| `finops/graphql-yoga-finops.md` | Infrastructure cost drivers and hosting platform pricing |

## About The Guild

GraphQL Yoga is maintained by [The Guild](https://the-guild.dev), an open-source development collective focused on GraphQL tooling. The Guild also maintains Envelop, GraphQL Code Generator, GraphQL Mesh, and other widely used GraphQL ecosystem libraries. Commercial support and consulting are available directly through The Guild.

## License

GraphQL Yoga is MIT licensed. See https://github.com/dotansimha/graphql-yoga/blob/main/LICENSE.
