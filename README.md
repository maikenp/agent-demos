# agent-demos

This repository contains examples and configuration files for experimenting with coding agents and AI-assisted development tools.

## Disclaimer
The technology is under rapid change, and these instructions may suddenly become outdated. The examples are created using a Mac, with limited testing on Windows, and may therefore not work as expected with Windows. 

To install the apps used here, UiO have the opencode-cli app available for download in Managed Software Centre, and previously had Codex, but no longer has it. UiO is working on adding more agent apps. If you are on Mac with admin rights, you can follow installation instructions on the apps own installation instructions. 


## Whats in this repo?

### `opencode/`

An [OpenCode]([url](https://opencode.ai/)) demo with:

- `config/opencode.json`: Example OpenCode configuration.
- [`opencode-select-model.mp4`](opencode/opencode-select-model.mp4): A video demonstration of selecting a model in OpenCode.

The demo illustrates how OpenCode can be used to create folders and files, generate synthetic test data, and produce a simple R script.

### `codex/`

Configuration examples for [Codex]([url](https://openai.com/nb-NO/codex/)). The `config/` directory contains a shared `config.toml` file and model-specific configuration files for several UiO-hosted models, including Gemma, GLM, GPT, and other models.

These examples are intended as a starting point for trying the tools and adapting the configurations to your own environment.


## Prerequisites to use opencode and codex with models through GPT UiO

1. Installed opencode and [codex](https://learn.chatgpt.com/docs/codex/cli?site_locale=en#getting-started)
2. Have followed the instructions in [GPT UiO - Bruke GPT UiO med API nøkler](https://www.uio.no/tjenester/it/ki/gpt-uio/hjelp/api-nokler.html) to get API access and to get hold of your API keys.
3. Have set up environment variables as described in [ Ta i bruk KI med API-tilgang  - Hvordan sette opp miljøvariabler](https://www.uio.no/tjenester/it/ki/gpt-uio/hjelp/bruk-api-tilgang.html#miljovariabler)

#### How to configure you opencode
1. Install opencode
2. Download the `config/opencode/opencode.json` file and place it in your `~/.config/opencode` folder.

## Currently not supported at UiO
Codex is currently not supported at UiO. Work is ongoing to change that. 


   
## Video demonstration

Watch the [OpenCode model selection video](opencode/opencode-select-model.mp4) to see the demo in action.
