# Laravel Generative A.I. Project

## laravel new

* Start a new Laravel project with `laravel new <project>`
* pick the start kit you prefer (authentication, Livewire, Vue/React, ...)
* required first: [`composer global require laravel/installer`](https://laravel.com/docs/12.x/installation)

## add /docs

* Create a /docs folder with `mkdox new .`
* Preview the docs with `mkdox serve`
* required first: [`basher install pforret/mkdox`](https://github.com/pforret/mkdox)


## add LLM clients

* OpenAI ChatGPT: `composer require openai-php/laravel`
* Anthropic Claude: `composer require mozex/anthropic-laravel`
* Google Gemini: `composer require google-gemini-php/laravel`
* ...


## resources/views/prompts

* use Blade to create prompts
* version control with git


## app/AI folders

* app/AI/Agents/Planner.php
* app/AI/Guardrails/PII.php
* app/AI/Handlers/ExcelConverter.php
* app/AI/Handlers/MarkdownConverter.php
* app/AI/Memory/LongTerm.php
* app/AI/Memory/ShortTerm.php
* app/AI/Multimodal/Audio/Transcribe.php
* app/AI/Multimodal/Image/Upscale.php
* app/AI/Multimodal/Music/Mashup.php
* app/AI/Multimodal/Video/Describe.php
* app/AI/Pipelines/ProposalMaker.php
* app/AI/Retrieval/Load.php
* app/AI/Retrieval/Split.php
* app/AI/Skills/WebSearch.php
* app/AI/Utils/Logging.php
* app/AI/Utils/Token.php
