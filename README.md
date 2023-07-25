# Library Docs

Polyfact is an Open Source Library of LLM-based dev tool packages.

Polyfact helps devs with (1) an SDK to help build those packages, (2) sharing them by adding them to the open-source library, and (3) running and deploying them through our hosted API.

## Usage

All the packages run with the Polyfact API and use the [Node.js SDK](https://www.github.com/polyfact/polyfact-node) to do so. This means you need to get an API Key [here](https://app.polyfact.com), and then export it or save it in your `.env`.

`export POLYFACT_TOKEN=[YOUR_API_KEY]`

## Packages

- [ai-logger](https://github.com/kevin-btc/ai-logger): use console.ai() to make your errors readable & understandable.
- [ai-docs](https://github.com/polyfact/ai-docs): set of functions to generate references, folder summaries and a getting started for a repository.
