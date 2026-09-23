# Seedance 3 API

> **Status: awaiting a verified Seedance 3 API endpoint.**

This repository is the home for a Python SDK and examples for the Seedance 3 API, modeled on [Anil-matcha/Seedance-2-API](https://github.com/Anil-matcha/Seedance-2-API).

As of September 23, 2026, ByteDance's official Seedance materials publicly document Seedance 2.0 and Seedance 2.5. MuAPI's documented Seedance endpoints are also Seedance 2.x. This repository does not claim that a Seedance 3 model or MuAPI route is available, and it does not send requests to undocumented endpoints.

## Planned contents

- Python client for text-to-video, image-to-video, and supported reference workflows
- Async job polling and result retrieval
- API examples and parameter reference
- Optional MCP server, following the Seedance 2 API project

Implementation will begin when a supported provider publishes the Seedance 3 request, response, and model contract. Please open an issue with official API documentation if you have a verified endpoint to contribute.

## Existing supported APIs

For currently documented Seedance 2.x generation through MuAPI, see [Seedance-2-API](https://github.com/Anil-matcha/Seedance-2-API) and the [MuAPI Seedance 2.5 API guide](https://muapi.ai/playground/seedance-2.5-text-to-video/api).

## Sources

- [ByteDance Seed: Seedance 2.0 official launch](https://seed.bytedance.com/en/blog/seedance-2-0-official-launch)
- [ByteDance Seed: Introducing Seedance 2.5](https://seed.bytedance.com/en/blog/one-take-creation-flexible-referencing-introducing-seedance-2-5)

## License

MIT. See [LICENSE](LICENSE).
