# PolyFact Library

Polyfact is an Open Source Library of LLM-based dev tool packages.

Polyfact helps devs with (1) an SDK to help build those packages, (2) sharing them by adding them to the open-source library, and (3) running and deploying them through our hosted API.

## Usage

All the packages run with the Polyfact API and use the [Node.js SDK](https://www.github.com/polyfact/polyfact-node) to do so. This means you need to get an API Key [here](https://app.polyfact.com), and then export it or save it in your `.env`.

`export POLYFACT_TOKEN=[YOUR_API_KEY]`

## Packages

- [console-ai](https://github.com/kevin-btc/console-ai): use console.ai() to make your errors readable & understandable.
- [ai-docs](https://github.com/polyfact/ai-docs): set of functions to generate references, folder summaries and a getting started for a repository.
- [ai-tests](https://github.com/lowczarc/ai-tests): CLI to generate boilerplate for your unit tests.
- [code-vectorizer](https://github.com/kevin-btc/code-vectorizer): Allow to embed/vectorize an entire codebase.
- [simple-ai-agent](https://github.com/polyfact/simple-ai-agent): A very simple AI agent that can search on wikipedia and perform calculations.
- [question-asker](https://github.com/victorforissier/question-asker): Your AI teacher. Asks questions about physics that you have to answer.
- [dockerfile-ai-generator](https://github.com/lowczarc/dockerfile-ai-generator): Automatically generate a Dockerfile for a repository


## VS-Code extensions

- [TalkWithCode](https://marketplace.visualstudio.com/items?itemName=Polyfactdocs.talk-with-code): Turn your codebase into an interactive dialogue with this extension.
