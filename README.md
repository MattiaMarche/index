# Private Projects

This repository lists some of the private or internal projects I've worked on over the years.

Most of these were developed for clients, research, or experimental purposes and are not publicly available due to confidentiality, ownership, or ongoing development.

If you're interested in any of these projects, want to discuss similar ideas, or explore collaboration opportunities, feel free to get in touch.

- Author: Mattia Marchesini
- Email: [info@mattiamarchesini.com](mailto:info@mattiamarchesini.com)
- Website (KLIK): [https://klikdevai.com](https://klikdevai.com)
- Website (Personal): [https://mattiamarchesini.com](https://mattiamarchesini.com)
- Linkedin: [Mattia Marchesini](https://www.linkedin.com/in/mattia-marchesini-030044b1/)

## Table of Contents

- [KLIK](#klik)
  - [Extension](#extension)
  - [Orchestrator](#orchestrator)
  - [Back-end - Data](#back-end---data)
  - [Front-end](#front-end)
  - [Theme Core](#theme-core)
  - [KLIK Theme](#klik-theme)
  - [Base - Back-end](#base---back-end)
  - [Base - Front-end](#base---front-end)
- [Industry and Automations](#industry-and-automations)
  - [XPM Framework](#xpm-framework)
  - [Theme](#theme)
  - [PHP API](#php-api)
  - [Documents Builder](#documents-builder)
  - [Back-office / MES](#back-office--mes)
  - [Local back-office / MES](#local-back-office--mes)
  - [OPC-UA Module](#opc-ua-module)
- [Strapi](#strapi)
  - [Custom Pages](#custom-pages)
  - [Automa](#automa)
  - [Generation Module](#generation-module)
- [Notion](#notion)
  - [Vision Notion](#vision-notion)
- [WordPress](#wordpress)
  - [Smart Modules](#smart-modules)
  - [Custom Fields](#custom-fields)
  - [XLog](#xlog)
- [Work in progress](#work-in-progress)

---

## KLIK

A set of private repositories related to the KLIK AI-driven meta-framework, designed to build full-stack web apps up to 10 times faster, without sacrificing control or quality.
These were the foundation of the system now used in KLIK.

**Current status**
- Currently used by ~10 developers in early projects (updated on June 2025)
- Validated on 50+ experimental prompts across front-end and back-end flows
- Fully functional in real-world dev environments (local + remote)
- Improving accuracy and generated code quality, currently running around 50% (like other solutions on the market), around November 2025 will rise to 75-90% (accordingly to current tests made on our new prototypes)

### Extension

First version of the KLIK extension for VS Code and Cursor, improves prompts and helps manage `cursorrules` to accelerate development without losing control over the generated code.

**Current status**
- Downloaded 100 times in [Cursor](https://open-vsx.org/extension/KLIK/klik-extension) or [VS Code](https://marketplace.visualstudio.com/items?itemName=KLIK.klik-extension) (updated on July 2025)

### Orchestrator

First version of KLIK orchestration back-end, handling assistants and logics.

**Current status**
- Handles ~300 API calls/day across local and staging environments (updated on June 2025)
- Powers AI-driven project creation and assistant orchestration in KLIK

### Back-end - Data

First version of data handling back-end, managing information and retrieving permanent data.

**Current status**
- Handles ~300 API calls/day (updated on June 2025)
- Allows the KLIK core to give results based on real data and protects users handling an advanced authentication

### Front-end

First version of the KLIK front-end, available both online and as a NPM package.

**Current status**
- Currently used by ~10 developers in early projects (updated on June 2025)

### Theme Core

Core module used to build AI driven themes, like the first one I built to test KLIK and let it create amazing dashboards and SaaS pages.

**Current status**
- Used in KLIK base projects
- Currently used in other ~10 early projects (updated on June 2025)

### KLIK Theme

First AI native theme built to be used with the KLIK framework, uses the `Theme Core` to make every component ready to be used with AI.

**Current status**
- Used in KLIK base projects
- Currently used in other ~4 early projects (updated on June 2025)

### Base - Back-end

First repository used by KLIK to generate a solid back-end project right after you write the first prompt.

**Current status**
- Included in 8 early KLIK projects as shared base modules (updated on June 2025)

### Base - Front-end

First repository used by KLIK to generate a solid front-end project right after you write the first prompt.

**Current status**
- Included in 8 early KLIK projects as shared base modules (updated on June 2025)

---

## Industry and Automations

### XPM Framework

Web framework built for environments where milliseconds matter.

In industry and manufacturing fields machines often need to connect with canonical OS (like Linux) that for various reasons need to show interfaces using web pages.

In those environments it's crucial to display a nice UI/UX avoiding unnecessary calculations, to decrease the workload of the machine rendering the page.

I created a basic framework that you could find similar to React, but way faster:

- Fewer features by design, making it suitable for medium-sized applications
- Allows development as fast as React (for small and medium scopes)
- Drastically reduces computation and re-renders, since rendering is fully developer-controlled
- It gives many automated behaviours to work with rendering, global data and calculations

For example you can choose how to re-render a list specifying:

- If it's expected to be ordered
- How is going to be updated (by adding, changing, removing items or all at once)
- When should be re-rendered and when it's not necessary

Those specifics makes it 2 to 5 times faster then React (tested rendering the same 100 elements both in XPM and React).

**Current status**
- In production since 2023
- Powers packaging systems handling ~3 items/second
- Used in mid-size manufacturing companies

### Theme

Web based UI theme used to build custom interfaces for industry and manufacturing fields, both for XPM and React.

**Current status**
- In production since 2023
- Used in 5 XPM and React projects

### PHP API

Module exposing a complete set of PHP REST API used in industry and manufacturing fields.

**Current status**
- In production since 2021
- Used in 5 projects

### Documents Builder

In some fields pages, documents or labels need to be created and then sent to devices like printers, PLCs or modbus as data to be processed or printed.

I built a system that allows users to create those documents from a web page, and export or transmit them to the correct devices.

**Current status**
- In production since 2025
- Used as part of 2 new softwares

### Back-office / MES

Back-office used in industries to handle data, orders or production related data.

Also compatible with the headless CMS Strapi.

**Current status**
- In production since 2025
- Used in 3 mid-size manufacturing companies

### Local back-office / MES

Local version of the back-office project built in Electron.

**Current status**
- In production since 2025
- Used in 1 mid-size manufacturing company requiring to run softwares without internet connection

### OPC-UA Module

NPM module for Node.js, also compatible with Strapi as plugin, that allows to communicate following the OPC-UA standard.

**Current status**
- In production since 2025
- Used as part of back-office in 3 mid-size manufacturing companies
- Allowing the adoption of the `Industry 4.0` model

---

## Strapi

### Custom Pages

Shows custom pages on the Strapi back-office UI, without creating conflicts.

Can also replace pages like the Strapi's home page, useful when it should be presented to final users accessing administration pages.

**Current status**
- Active in 2 back-offices

### Automa

Plugin listening for events and reacting by executing functions, hooks or custom code.

Created to be super-light, it runs code only when needed without including it in every request.

**Current status**
- Active in 2 Strapi installations

### Generation Module

Private module boosting Strapi capabilities without impacting performance.

No more details can be shared since is part of a KLIK module currently in development, that will boost the accuracy of Strapi-based projects.

Feel free to [reach out](mailto:info@mattiamarchesini.com) for additional informations.

**Current status**
- In development in the new KLIK core

---

## Notion

### Vision Notion

Bridge module, built with Next.js, with internal modules that perfectly adapt to the Notion's page logics, allowing to easily connect any kind of Notion data to custom pages or custom softwares.

Useful when Make, Zapier or other utilities can't be used or cannot handle Notion data deeply enough, triggering highly customized actions or showing custom interfaces.

**Current status**
- Used in 2 projects using Notion as back-office
- Connected to 3 custom interfaces, showing 2 internal custom interfaces
- Handling more than 5000 actions/month

---

## WordPress

Tools or plugins developed to work with complex WordPress websites.

### Smart Modules

Started as a code block for internal use that can be included in child themes, now it's a `MU-Plugin`.

It anticipated the `MU-Plugins` logic, allowing to develop separated, optimized and easily maintainable modules that can be added to the WordPress website with low efforts.

Now, thanks to the `MU` logic, is even more powerful since it enables an internal marketplace where shared and tested modules can be downloaded and used with minimal configuration.

It also introduces a new way to handle settings, way faster than the WordPress default, that works perfectly but also grants better performances and drastically reduces queries: a single query for all options used in all the modules, and no risk to load "too much" since the options retrieval system is optimized.

**Current status**
- Working in 3 websites and 1 SaaS
- Higher priorities stopped its diffusion, if you are interested we could improve it and share it as `MU-Plugin`

### Custom Fields

Plugin built for specific situations where:
- An high number of request are mode on posts or custom types
- Requests need to filter or manipulate data using custom fields
- Import and export needs to be simple and maintainable
- Introucing plugins like `ACF` decrease performances since every filtered request takes to much to join tables and perform checks or updates on custom fields
- Data should be visible and filtered by front-end users, in highly customizable tables with a tailor made UI

In this case it's the perfect plugin, since:
- It works with a single table perfectly integrated with `wp_posts` (without changing any WP native table or logic)
- It allows to filter any kind of data (also nested) with 1 or 2 (max) queries
- Allows to safely show only certain fields on front-end components
- Allows to use a tailor made table component where each column and filter can be customized (also injecting safe JS code in specific hooks)
- Allows to add buttons and panels to export data in CSV and XLSX formats

**Current status**
- Working in 1 website and used internally
- Higher priorities stopped its diffusion, if you are interested we could improve it and share it as `WordPress Plugin`

### XLog

`MU-Plugin` creating a logging system that tracks and shows in a custom webpage PHP warnings, informations and errors, setting a custom log level to:
- Debug while working
- Detect strange behaviours or unnecessary operations
- Run security checks

**Current status**
- Working when needed on 5 websites, activated only when needed (to debug, detect or run checks)

---

## Work in progress

This document is a work in progress.  
More private projects (30+) will be added over time as summaries are written and confidentiality constraints are reviewed.

If you're interested in one of these projects or would like to contribute to a similar initiative, feel free to reach out.