# Private Projects

This repository lists some of the private or internal projects I've worked on over the years.

Most of these were developed for clients, research, or experimental purposes and are not publicly available due to confidentiality, ownership, or ongoing development.

If you're interested in any of these projects, want to discuss similar ideas, or explore collaboration opportunities, feel free to get in touch.

## Web version

A web version is available on the link: [https://marchesini-portfolio.vercel.app/portfolio](https://marchesini-portfolio.vercel.app/portfolio)

Spoiler: created in less than 15 minutes with **KLIK**!

## Contacts

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
- [React Projects](#react-projects)
  - [Teletherapy Mobile App](#teletherapy-mobile-app)
  - [Management](#management)
  - [Medical Front-end](#medical-front-end)
- [Angular](#angular)
  - [Boat Management (Angular 2)](#boat-management-angular-2)
  - [Coltivation App (Ionic 4)](#coltivation-app-ionic-4)
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
- [Other Front-end Projects](#other-front-end-projects)
  - [Diagnosis Assistant](#diagnosis-assistant)
- [WordPress](#wordpress)
  - [Smart Modules](#smart-modules)
  - [Custom Fields](#custom-fields)
  - [WPLog](#wplog)
- [Passions](#passions)
  - [Echoes of Battles](#echoes-of-battles)
  - [Echo](#echo)
- [Work in progress](#work-in-progress)

---

## KLIK

A set of private repositories related to the KLIK AI-driven meta-framework, designed to build full-stack web apps up to 10 times faster, without sacrificing control or quality.
These were the foundation of the system now used in KLIK.

**Current status**
- Currently used by ~10 developers in early projects (updated on June 2025)
- Validated on 50+ experimental prompts across front-end and back-end flows
- Fully functional in real-world dev environments (local + remote)
- Improving accuracy and generated code quality, currently running around 40% (like other solutions on the market), around November 2025 will rise to 75-90% (accordingly to current tests made on our new prototypes)

**Created at**
2022-04

### Extension

<img src="/projects/klik/extension/extension-1.jpg" width="45%">
<div style="display: flex; gap: 5px;">
  <img src="/projects/klik/extension/extension-2.jpg" width="22.5%">
  <img src="/projects/klik/extension/extension-3.jpg" width="22.5%">
</div>

First version of the KLIK extension for VS Code and Cursor, improves prompts and helps manage `cursorrules` to accelerate development without losing control over the generated code.

**Current status**
- Downloaded 742 times in [Cursor](https://open-vsx.org/extension/KLIK/klik-extension) and [VS Code](https://marketplace.visualstudio.com/items?itemName=KLIK.klik-extension) (updated on November 2025)

**Created at**
2025-09

### Orchestrator

<img src="/projects/klik/orchestrator/orchestrator-1.jpg" width="45%">

First version of KLIK orchestration back-end, handling assistants and logics.

**Current status**
- Handles ~300 API calls/day across local and staging environments (updated on June 2025)
- Powers AI-driven project creation and assistant orchestration in KLIK

**Created at**
2025-05

### Back-end - Data

<img src="/projects/klik/back-end-data/back-end-data-1.jpg" width="45%">
<img src="/projects/klik/back-end-data/back-end-data-2.jpg" width="22.5%">

First version of data handling back-end, managing information and retrieving permanent data.

**Current status**
- Handles ~300 API calls/day (updated on June 2025)
- Allows the KLIK core to give results based on real data and protects users handling an advanced authentication

**Created at**
2025-05

### Front-end

<img src="/projects/klik/front-end/front-end-1.jpg" width="45%">

First version of the KLIK front-end, available both online and as a NPM package.

Demo videos are available in Loom:
- [Onboarding](https://www.loom.com/share/25991d95d6cf42a0b48e72ba1a454be0)
- [Demonstration](https://www.loom.com/share/257d27c87c4a4afdbfc15ae404e5e836)
- [Conclusions](https://www.loom.com/share/adff09e6307c4a12adf0f3997f9bdbeb)

**Current status**
- Currently used by ~10 developers in early projects (updated on June 2025)

**Created at**
2025-05

### Theme Core

<img src="/projects/klik/theme-core/theme-core-1.jpg" width="45%">
<img src="/projects/klik/theme-core/theme-core-2.jpg" width="22.5%">

Core module used to build AI driven themes, like the first one I built to test KLIK and let it create amazing dashboards and SaaS pages.

**Current status**
- Used in KLIK base projects
- Currently used in other ~10 early projects (updated on June 2025)

**Created at**
2025-04

### KLIK Theme

<img src="/projects/klik/klik-theme/klik-theme-1.jpg" width="45%">
<img src="/projects/klik/klik-theme/klik-theme-2.jpg" width="22.5%">

First AI native theme built to be used with the KLIK framework, uses the `Theme Core` to make every component ready to be used with AI.

**Current status**
- Used in KLIK base projects
- Currently used in other ~4 early projects (updated on June 2025)

**Created at**
2025-04

### Base - Back-end

<img src="/projects/klik/base-back-end/base-back-end-1.jpg" width="45%">
<img src="/projects/klik/base-back-end/base-back-end-2.jpg" width="22.5%">

First repository used by KLIK to generate a solid back-end project right after you write the first prompt.

**Current status**
- Included in 8 early KLIK projects as shared base modules (updated on June 2025)

**Created at**
2025-05

### Base - Front-end

<img src="/projects/klik/base-front-end/base-front-end-1.jpg" width="45%">

First repository used by KLIK to generate a solid front-end project right after you write the first prompt.

**Current status**
- Included in 8 early KLIK projects as shared base modules (updated on June 2025)

**Created at**
2025-05

---

## React Projects

Projects developed using React or React Native in production environments, when a declarative UI approach and rapid component reuse were beneficial to project goals.

### Teletherapy Mobile App

<img src="/projects/react-projects/teletherapy-mobile-app/teletherapy-mobile-app-1.jpg" width="45%">
<div style="display: flex; gap: 5px;">
  <img src="/projects/react-projects/teletherapy-mobile-app/teletherapy-mobile-app-2.jpg" width="22.5%">
  <img src="/projects/react-projects/teletherapy-mobile-app/teletherapy-mobile-app-3.jpg" width="22.5%">
</div>

React Native app used to deliver and track therapy plans remotely, available for both Android and iOS.

Built with Expo, also showing a complex UI where the user can both record and watch videos at the same time, to perform therapy based exercises while watching their execution.

**Current status**
- Live since 2020
- Used by ~150 professionals, also italian universities
- Connected to a secure back-end with JWT auth and encrypted data

**Created at**
2020-06

### Management

<img src="/projects/react-projects/management/management-1.jpg" width="45%">

Admin dashboard built in React for internal use in mid-size companies, offering CRUD operations on products, customers and production data.

**Current status**
- In production since 2024
- Used by 2 companies, managing ~2000 products, customers and procedures
- Features include login, access levels, editable tables and CSV export

**Created at**
2023-01

### Medical Front-end

<img src="/projects/react-projects/medical-front-end/medical-front-end-1.jpg" width="45%">
<div style="display: flex; gap: 5px;">
  <img src="/projects/react-projects/medical-front-end/medical-front-end-2.jpg" width="22.5%">
  <img src="/projects/react-projects/medical-front-end/medical-front-end-3.jpg" width="22.5%">
</div>

React-based front-end used in a healthcare SaaS, displaying medical records, therapies and appointments with dynamic filtering and real-time updates.

**Current status**
- In production since 2025
- Currently working on users onboarding (updated on July 2025)

**Created at**
2025-03

---

## Angular

Projects developed using Angular or Ionic in production environments, when Angular features were beneficial to project goals.

### Boat Management (Angular 2)

<img src="/projects/angular/boat-management-angular-2/boat-management-angular-2-1.jpg" width="45%">

Restyling and rebuilding of an Angular 2+ management dashboard to control boat positions, users and operations from a central UI.

Also compatible and exported as a Ionic application.

**Current status**
- In production from 2020
- Used by a company for internal fleet management

**Created at**
2023-04

### Coltivation App (Ionic 4)

<img src="/projects/angular/coltivation-app-ionic-4/coltivation-app-ionic-4-1.jpg" width="45%">
<div style="display: flex; gap: 5px;">
  <img src="/projects/angular/coltivation-app-ionic-4/coltivation-app-ionic-4-2.jpg" width="22.5%">
  <img src="/projects/angular/coltivation-app-ionic-4/coltivation-app-ionic-4-3.jpg" width="22.5%">
  <img src="/projects/angular/coltivation-app-ionic-4/coltivation-app-ionic-4-4.jpg" width="22.5%">
  <img src="/projects/angular/coltivation-app-ionic-4/coltivation-app-ionic-4-5.jpg" width="22.5%">
</div>

Mobile app (Android/iOS) built with Ionic 4, designed to connect with coltivation panels and allowing the user to control:
- General status
- Irrigation
- Lights (adjusting colors and intensities)
- Programs: selecting or creating custom programs that periodically change parameters to optimize the environment for any kind of seed

**Current status**
- Distributed through a private commercial network, exclusively to selected clients, due to the need for centralized maintenance of vertical vegetation systems
- Demo video available on [YouTube](https://www.youtube.com/watch?v=N1WZnwVHzeQ)
- Real use case video also available on [YouTube](https://www.youtube.com/watch?v=jN_NeBPBpRc)

**Created at**
2019-05

---

## Industry and Automations

### XPM Framework

<img src="/projects/industry-and-automations/xpm-framework/xpm-framework-1.jpg" width="45%">
<div style="display: flex; gap: 5px;">
  <img src="/projects/industry-and-automations/xpm-framework/xpm-framework-2.jpg" width="22.5%">
  <img src="/projects/industry-and-automations/xpm-framework/xpm-framework-3.jpg" width="22.5%">
  <img src="/projects/industry-and-automations/xpm-framework/xpm-framework-4.jpg" width="22.5%">
</div>

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
- Live since 2023
- Powers packaging systems handling ~3 items/second
- Used in mid-size manufacturing companies

**Created at**
2022-04

### Theme

<img src="/projects/industry-and-automations/theme/theme-1.jpg" width="45%">

Web based UI theme used to build custom interfaces for industry and manufacturing fields, both for XPM and React.

**Current status**
- In production since 2023
- Used in 5 XPM and React projects

**Created at**
2022-08

### PHP API

<img src="/projects/industry-and-automations/php-api/php-api-1.jpg" width="45%">

Module exposing a complete set of PHP REST API used in industry and manufacturing fields.

**Current status**
- Live since 2021
- Used in 5 projects

**Created at**
2020-11

### Documents Builder

<img src="/projects/industry-and-automations/documents-builder/documents-builder-1.jpg" width="45%">

In some fields pages, documents or labels need to be created and then sent to devices like printers, PLCs or modbus as data to be processed or printed.

I built a system that allows users to create those documents from a web page, and export or transmit them to the correct devices.

**Current status**
- Live since 2025
- Used as part of 2 new softwares

**Created at**
2025-01

### Back-office / MES

<img src="/projects/industry-and-automations/back-office-mes/back-office-mes-1.jpg" width="45%">

Back-office used in industries to handle data, orders or production related data.

Also compatible with the headless CMS Strapi.

**Current status**
- Live since 2025
- Used in 3 mid-size manufacturing companies

**Created at**
2025-02

### Local back-office / MES

<img src="/projects/industry-and-automations/local-back-office-mes/local-back-office-mes-1.jpg" width="45%">

Local version of the back-office project built in Electron.

**Current status**
- Live since 2025
- Used in 1 mid-size manufacturing company requiring to run softwares without internet connection

**Created at**
2025-03

### OPC-UA Module

<img src="/projects/industry-and-automations/opc-ua-module/opc-ua-module-1.jpg" width="45%">

NPM module for Node.js, also compatible with Strapi as plugin, that allows to communicate following the OPC-UA standard.

**Current status**
- Live since 2025
- Used as part of back-office in 3 mid-size manufacturing companies
- Allowing the adoption of the `Industry 4.0` model

**Created at**
2025-01

---

## Strapi

### Custom Pages

<img src="/projects/strapi/custom-pages/custom-pages-1.jpg" width="45%">

Shows custom pages on the Strapi back-office UI, without creating conflicts.

Can also replace pages like the Strapi's home page, useful when it should be presented to final users accessing administration pages.

**Current status**
- Active in 2 back-offices

**Created at**
2024-10

### Automa

<img src="/projects/strapi/automa/automa-1.jpg" width="45%">

Plugin listening for events and reacting by executing functions, hooks or custom code.

Created to be super-light, it runs code only when needed without including it in every request.

**Current status**
- Active in 2 Strapi installations

**Created at**
2024-10

### Generation Module

<img src="/projects/strapi/generation-module/generation-module-1.jpg" width="45%">

Private module boosting Strapi capabilities without impacting performance.

No more details can be shared since is part of a KLIK module currently in development, that will boost the accuracy of Strapi-based projects.

Feel free to [reach out](mailto:info@mattiamarchesini.com) for additional informations.

**Current status**
- In development in the new KLIK core

**Created at**
2025-03

---

## Notion

### Vision Notion

<img src="/projects/notion/vision-notion/vision-notion-1.jpg" width="45%">
<div style="display: flex; gap: 5px;">
  <img src="/projects/notion/vision-notion/vision-notion-2.jpg" width="22.5%">
  <img src="/projects/notion/vision-notion/vision-notion-3.jpg" width="22.5%">
</div>

Bridge module, built with Next.js, with internal modules that perfectly adapt to the Notion's page logics, allowing to easily connect any kind of Notion data to custom pages or custom softwares.

Useful when Make, Zapier or other utilities can't be used or cannot handle Notion data deeply enough, triggering highly customized actions or showing custom interfaces.

**Current status**
- Used in 2 projects using Notion as back-office
- Connected to 3 custom interfaces, showing 2 internal custom interfaces
- Handling more than 5000 actions/month

**Created at**
2025-02

---

## Other Front-end Projects

### Diagnosis Assistant

<img src="/projects/other-front-end-projects/diagnosis-assistant/diagnosis-assistant-1.jpg" width="45%">

Medical web tool built entirely in TypeScript (no framework) to simulate AI-assisted diagnosis based on scientific heuristics and real-time user inputs.

- Includes modular prediction engine and customizable symptom trees
- Simulated accuracy tuning based on test cases and probability paths
- Highly optimized UI without any external dependencies

**Current status**
- Internal prototype completed in 2021
- Currently used for tests in universities

**Created at**
2021-07

---

## WordPress

Tools or plugins developed to work with complex WordPress websites.

### Smart Modules

<img src="/projects/wordpress/smart-modules/smart-modules-1.jpg" width="45%">

Started as a code block for internal use that can be included in child themes, now it's a `MU-Plugin`.

It anticipated the `MU-Plugins` logic, allowing to develop separated, optimized and easily maintainable modules that can be added to the WordPress website with low efforts.

Now, thanks to the `MU` logic, is even more powerful since it enables an internal marketplace where shared and tested modules can be downloaded and used with minimal configuration.

It also introduces a new way to handle settings, way faster than the WordPress default, that works perfectly but also grants better performances and drastically reduces queries: a single query for all options used in all the modules, and no risk to load "too much" since the options retrieval system is optimized.

**Current status**
- Working in 3 websites and 1 SaaS
- Higher priorities stopped its diffusion, if you are interested we could improve it and share it as `MU-Plugin`

**Created at**
2023-01

### Custom Fields

<img src="/projects/wordpress/custom-fields/custom-fields-1.jpg" width="45%">
<div style="display: flex; gap: 5px;">
  <img src="/projects/wordpress/custom-fields/custom-fields-2.jpg" width="22.5%">
  <img src="/projects/wordpress/custom-fields/custom-fields-3.jpg" width="22.5%">
  <img src="/projects/wordpress/custom-fields/custom-fields-4.jpg" width="22.5%">
</div>

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

**Created at**
2024-11

### WPLog

<img src="/projects/wordpress/wplog/wplog-1.jpg" width="45%">

`MU-Plugin` creating a logging system that tracks and shows in a custom webpage PHP warnings, informations and errors, setting a custom log level to:
- Debug while working
- Detect strange behaviours or unnecessary operations
- Run security checks

**Current status**
- Working when needed on 5 websites, activated only when needed (to debug, detect or run checks)

**Created at**
2024-09

---

## Passions

In this section you can find a tiny piece of my world, the one I build after work.

In some of those website I also used public modules I published:
- [I18n TypeScript](https://github.com/MattiaMarche/i18n-lite-ts)
- [I18n JavaScript](https://github.com/MattiaMarche/i18n-lite-js)
- [Slideshow JavaScript](https://github.com/MattiaMarche/slideshow-js)

### Echoes of Battles

<img src="/projects/passions/echoes-of-battles/echoes-of-battles-1.jpg" width="45%">
<div style="display: flex; gap: 5px;">
  <img src="/projects/passions/echoes-of-battles/echoes-of-battles-2.jpg" width="22.5%">
  <img src="/projects/passions/echoes-of-battles/echoes-of-battles-3.jpg" width="22.5%">
</div>

Do you like strategy? And board games?

What if you could live an historical battle on your table, with your friends, without compromises: the real feeling of an ancient, or modern battle.

Even in my childhood I loved strategy and wondered how history and nations were created, and I wanted to watch or play something real to really understand how things worked.

So I decided to try and create it on my own, I did and many people asked me to buy the game or to play agian together.

That's why I started:
- The full game with rules, units, maps, cards all 100% playable and balanced
- Database and website used to track data and give a digital support for players
- Two game modes, basic and advanced, to lead new players through this new world and teach them how to really reproduce a real battle on their table
- A community to play it together
- An early version of the digital game (closed alpha)

**Current status**
- Completed and playable
- Events where we play together
- Registered look and feel, trademark, rules and concepts

**Created at**
2025-01

### Echo

<img src="/projects/passions/echo/echo-1.jpg" width="45%">
<div style="display: flex; gap: 5px;">
  <img src="/projects/passions/echo/echo-2.jpg" width="22.5%">
  <img src="/projects/passions/echo/echo-3.jpg" width="22.5%">
  <img src="/projects/passions/echo/echo-4.jpg" width="22.5%">
  <img src="/projects/passions/echo/echo-5.jpg" width="22.5%">
</div>

A deep narrative I kept in my mind for too long, I decided to start writing it years ago, and now it's taking a clear shape.

So I decided to create a presentation website, with the look and feel I have in mind and the possibility to ask for previews, drafts and chapters.

I'ld love to receive any kind of feedback, I hope to complete the story soon sharing my thoughts, beliefs and imagination with everyone.

**Current status**
- Website: published and working, explaining the whole concept and setting behind the book
- Book: still writing it, taking a clear shape that I'm loving more and more

**Created at**
2014-01

---

## Work in progress

This document is a work in progress.  
More private projects (30+) will be added over time as summaries are written and confidentiality constraints are reviewed.

If you're interested in one of these projects or would like to contribute to a similar initiative, feel free to reach out.