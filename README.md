<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:3b0764,55:7c3aed,100:16a34a&height=190&section=header&text=Luan%20Magalh%C3%A3es&fontColor=ffffff&fontSize=44&fontAlignY=34&desc=Senior%20Software%20Engineer%20%C2%B7%20Full%20Stack%20and%20AI&descAlignY=55&descSize=18" alt="Luan Magalhães, Senior Software Engineer, Full Stack and AI" />

<p align="center">
  <a href="https://github.com/luanmagalhaes">
    <img src="https://readme-typing-svg.demolab.com/?lines=Full+stack+since+2021;Built+by+hand%2C+sped+up+with+AI;React%2C+Next.js%2C+Node.js+and+Python;Agents%2C+tool+use+and+MCP+servers;From+client+meeting+to+prototype+in+days&font=Fira%20Code&size=20&color=7C3AED&center=true&vCenter=true&width=560&height=45&pause=900" alt="Full stack since 2021, built by hand, sped up with AI" />
  </a>
</p>

<p align="center"><b>English</b> · <a href="./README.pt-BR.md">Português</a></p>

<p align="center">
  <a href="https://www.linkedin.com/in/luan-magalhaes-dev/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:m.agalhaes@hotmail.com"><img src="https://img.shields.io/badge/Email-16A34A?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Brazil%20%C2%B7%20remote%20(UTC--3)-7C3AED?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Brazil, remote (UTC-3)" />
  <img src="https://hits.sh/github.com/luanmagalhaes.svg?style=for-the-badge&label=Profile%20views&color=ca8a04" alt="Profile views" />
</p>

## About me

- Senior software engineer, working full stack since 2021 on products for companies in Denmark and Germany and for a credit marketplace in Brazil.
- I learned to build software before AI coding tools became common, writing everything by hand. Architecture, tests, code review and debugging are still the base of how I work.
- AI makes me faster. I use Claude Code every day, often with several agents in parallel, and I build AI into products: LLM analysis, tool-using agents and MCP servers.
- I like working close to clients: joining the meeting, agreeing on scope and getting a working prototype into production within a few days.
- Proficient English (C2). I taught English for five years and studied at the University of Manitoba, Canada, on a selective scholarship program.
- MSc from the Federal University of Bahia and former speech-language pathologist.

## Experience

### Antecipa Fácil · Full-stack software engineer
*Dec 2022 to present · Brazil, remote*

Credit marketplace where companies sell their receivables through a reverse auction among funders.

- Built the customer app from scratch and the core back-office modules.
- Built LLM analysis for the chat between companies and funders: summaries, sentiment, suggested replies and compliance alerts, with fallback between providers.
- Split the chat out of the Django monolith into its own microservice, with service-to-service auth, Celery and Azure APIM routing.
- Delivered the new onboarding end to end: around 40 screens behind feature flags, Google and Microsoft sign-in, document OCR, backend endpoints and product analytics.
- Brought Husky, ESLint, Storybook, Vitest and Playwright to the front-ends and wrote around 130 test files.

`Next.js` `React` `TypeScript` `Python` `Django` `PostgreSQL` `Celery` `Azure` `OpenAI` `Anthropic` `PostHog`

### Miinto · Frontend engineer
*Feb 2025 to Aug 2026 · Denmark, remote*

Fashion marketplace connecting independent boutiques and brands with customers across Europe.

- Maintained and extended the React design system (Stitches, Radix, Storybook, Jest) used by the store's micro-frontends.
- Redesigned the product listing page (filters, in-filter search, price filter, sorting, mobile) and the account area (sign-up, login, profile), integrated with server-rendered Go micro-frontends.
- Technical SEO on the Go-rendered pages, with indexing rules for pagination and filter combinations, and legal content across 12 sales channels.
- Delivered the order email history end to end in the Module Federation back office, with preview and resend.

`React` `TypeScript` `Go` `Stitches` `Radix` `Storybook` `Module Federation` `Jest`

### The Vintage Bar · Frontend engineer
*Aug 2024 to Feb 2025 · Denmark, remote*

Luxury fashion marketplace, now part of Miinto. Dynamic filters, inventory management and backend integrations with Angular, TypeScript, PHP and Shopify.

### Earlier

- **Engel & Völkers**, Berlin, remote (2022): Smart Money homepage in React, GraphQL, DatoCMS and Auth0, migrated to Next.js.
- **Taghos Tecnologia** (2021): subscription checkout for the Paulistão Play streaming service in React, TypeScript, Formik and Cypress.
- **Healthcare and teaching** (2011 to 2021): speech-language pathologist in neonatal, pediatric and adult ICUs, and English teacher. In 2020, as product owner, I led a patient follow-up PWA built with React and Firebase.

## Client projects (contract, 2026)

| Project | What I did |
| --- | --- |
| **Online course checkout for a driving school** | Live in 10 days. In the client presentation we changed the plan together: sell first, test demand, build the class platform later. Asaas checkout with PIX, card and commission split, idempotent webhooks, and Google Ads conversions moved to the server with the GA4 Measurement Protocol. |
| **AI agent for B2B orders** | Turned a manual process into 7 agent tools: read orders from email, extract PDF and Excel files, check stock and create a Shopify draft order, with human review before confirmation. Prototype in 5 days with the Anthropic SDK and SSE, plus a LangGraph version to compare both approaches. |
| **Live class platform (SaaS)** | Lead developer. 100ms video room as a Vite sub-app running next to React 19, WhatsApp Cloud API notifications, payments and affiliates on Asaas, roles with Clerk, monitoring with PostHog and Better Stack. Mentored a junior developer. |
| **Multi-tenant e-commerce ERP** | Front-end lead. Translated the app into English and Mandarin with 17 AI agents in parallel (2,569 keys, parity checked by script), migrated the front-end to the NestJS API with types generated from OpenAPI, and fixed a refresh token race that dropped sessions. |

## Applied AI

- **Agents and tool use:** agents on the Anthropic SDK and on LangGraph, structured output validated with Zod, prompt caching, streaming over SSE and human review where it matters.
- **MCP servers:** one in Python (FastMCP, stdio and token-authenticated HTTP) to log work hours through Claude, one in Node that syncs a bug board with Notion, and a LangGraph agent consuming its own MCP server.
- **AI in health (in development):** an assistant that follows up on therapy patients between sessions, with a router model, a generator and a reviewer that rejects or rewrites the answer, a deterministic safety filter and audio transcription with Whisper.
- **Claude Code, customized:** a subagent that challenges the proposed solution with evidence from the repository before any code is written, a hook that uses the TypeScript compiler to block forbidden patterns, PR workflow skills and verification workflows with more than 100 subagents.

## Side projects

Party games and small tools I play with my friends every week. Each one went from first commit to production in 2 to 9 days, with Next.js 16, React 19, Tailwind 4, Supabase and Vitest (around 750 tests in total).

| App | What it is | Play | Code |
| --- | --- | --- | --- |
| **Vitrola** | Music game: listen to a 30 second Deezer preview and place the song on your timeline | [a-vitrola.vercel.app](https://a-vitrola.vercel.app) | [vitrola](https://github.com/luanmagalhaes/vitrola) |
| **Cantarolá** | Team party game about songs, with an online mode that streams microphone audio | [cantarola.vercel.app](https://cantarola.vercel.app) | [cantarola](https://github.com/luanmagalhaes/cantarola) |
| **Não Vale** | Forbidden words game where the other team's judge sees the card on their own phone | [nao-vale.vercel.app](https://nao-vale.vercel.app) | [nao-vale](https://github.com/luanmagalhaes/nao-vale) |
| **FLOW** | Everyone writes what they think the table will write, 3 to 12 players, each on their own phone | [flow-seven-amber.vercel.app](https://flow-seven-amber.vercel.app) | [flow](https://github.com/luanmagalhaes/flow) |
| **De Fininho** | Each player gets secret phrases to sneak into the conversation without being caught | [de-fininho.vercel.app](https://de-fininho.vercel.app) | [de-fininho](https://github.com/luanmagalhaes/de-fininho) |
| **Flip Score** | Scoreboard for card game nights, with photos of the players | [flip-score.vercel.app](https://flip-score.vercel.app) | [flip-score](https://github.com/luanmagalhaes/flip-score) |
| **La Cuentita** | Does the bar bill math for a card game night, no calculator needed | [la-cuentita-green.vercel.app](https://la-cuentita-green.vercel.app) | [la-cuentita](https://github.com/luanmagalhaes/la-cuentita) |

**Private apps for my own routine** (no public link):

- **Reps:** workout tracker with a dashboard for my personal trainer, remembered loads and a rest timer that alerts even with the app closed.
- **Matilda:** everything about my dog. Baths with a payment cycle, vaccines, weight, food and expenses, with PIN access and per-tab permissions for whoever takes care of her.
- **Washing Issues:** prototype for my building's laundry. Residents send their laundry list with a photo of each item, the staff starts the wash and marks it ready, and residents confirm the pickup, with chat in between.
- **Game Night:** our game nights. Guests, RSVP and arrival, games played, badges and polaroid style photos.
- **Regalo:** gift list for our group of friends, with sizes, preferences and a birthday countdown.

## Toolbox

**Engineering**

<p>
  <img height="40" width="40" alt="TypeScript" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" />
  <img height="40" width="40" alt="JavaScript" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" />
  <img height="40" width="40" alt="React" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" />
  <img height="40" width="40" alt="Next.js" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg" />
  <img height="40" width="40" alt="Angular" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/angular/angular-original.svg" />
  <img height="40" width="40" alt="Tailwind CSS" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-original.svg" />
  <img height="40" width="40" alt="Storybook" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/storybook/storybook-original.svg" />
  <img height="40" width="40" alt="Node.js" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" />
  <img height="40" width="40" alt="NestJS" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nestjs/nestjs-original.svg" />
  <img height="40" width="40" alt="Python" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" />
  <img height="40" width="40" alt="Django" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/django/django-plain.svg" />
  <img height="40" width="40" alt="Go" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original-wordmark.svg" />
  <img height="40" width="40" alt="PHP" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" />
  <img height="40" width="40" alt="GraphQL" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/graphql/graphql-plain.svg" />
  <img height="40" width="40" alt="PostgreSQL" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" />
  <img height="40" width="40" alt="Prisma" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/prisma/prisma-original.svg" />
  <img height="40" width="40" alt="Supabase" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/supabase/supabase-original.svg" />
  <img height="40" width="40" alt="Redis" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original.svg" />
  <img height="40" width="40" alt="Docker" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" />
  <img height="40" width="40" alt="Azure" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/azure/azure-original.svg" />
  <img height="40" width="40" alt="Vercel" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vercel/vercel-original.svg" />
  <img height="40" width="40" alt="Vitest" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vitest/vitest-original.svg" />
  <img height="40" width="40" alt="Jest" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jest/jest-plain.svg" />
  <img height="40" width="40" alt="Playwright" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/playwright/playwright-original.svg" />
  <img height="40" width="40" alt="Git" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" />
</p>

**AI**

<p>
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude Code" />
  <img src="https://img.shields.io/badge/Anthropic%20SDK-191919?style=for-the-badge&logo=anthropic&logoColor=white" alt="Anthropic SDK" />
  <img src="https://img.shields.io/badge/OpenAI%20and%20Azure%20OpenAI-412991?style=for-the-badge" alt="OpenAI and Azure OpenAI" />
  <img src="https://img.shields.io/badge/LangChain%20and%20LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain and LangGraph" />
  <img src="https://img.shields.io/badge/MCP-16A34A?style=for-the-badge&logo=modelcontextprotocol&logoColor=white" alt="Model Context Protocol" />
  <img src="https://img.shields.io/badge/Vercel%20AI%20SDK-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel AI SDK" />
  <img src="https://img.shields.io/badge/Whisper-7C3AED?style=for-the-badge" alt="Whisper" />
</p>

## Education

- MSc in Interactive Processes of Organs and Systems, Federal University of Bahia (2022)
- Internet Systems Development (technologist degree), Unicesumar
- University of Manitoba, Canada: Health Sciences exchange on a selective scholarship program, with an intensive English course (2014 to 2015)
- BSc in Speech-Language Pathology, State University of Bahia (2015)

## Languages

![Portuguese](https://img.shields.io/badge/Portuguese-Native-7C3AED?style=for-the-badge)
![English](https://img.shields.io/badge/English-Proficient%20(C2)-16A34A?style=for-the-badge)
![Italian](https://img.shields.io/badge/Italian-Basic-CA8A04?style=for-the-badge)

## Matilda

<p align="center"><img src="./assets/matilda.jpg" width="220" alt="Matilda, my dog" /></p>
<p align="center">This is Matilda, my dog. Fun fact: she is psychic.</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/luanmagalhaes/luanmagalhaes/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/luanmagalhaes/luanmagalhaes/output/snake.svg" />
  <img alt="Contribution graph snake animation" src="https://raw.githubusercontent.com/luanmagalhaes/luanmagalhaes/output/snake.svg" />
</picture>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:16a34a,100:facc15&height=110&section=footer" alt="" />
