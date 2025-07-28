# Private Projects

This repository lists some of the private or internal projects I've worked on over the years.

Most of these were developed for clients, research, or experimental purposes and are not publicly available due to confidentiality, ownership, or ongoing development.

If you're interested in any of these projects, want to discuss similar ideas, or explore collaboration opportunities, feel free to get in touch.

- Author: Mattia Marchesini
- Email: [info@mattiamarchesini.com](mailto:info@mattiamarchesini.com)
- Website (KLIK): [https://klikdevai.com](https://klikdevai.com)
- Website (Personal): [https://mattiamarchesini.com](https://mattiamarchesini.com)
- Linkedin: [Mattia Marchesini](https://www.linkedin.com/in/mattia-marchesini-030044b1/)

---

## KLIK

A set of private repositories related to the KLIK AI-driven meta-framework, designed to build full-stack web apps up to 10 times faster, without sacrificing control or quality.
These were the foundation of the system now used in KLIK.

### Back-end - Core

First version of KLIK back-end, handling assistants and logics.

### Back-end - Data

First version of data handling back-end, managing information and retrieving permanent data.

### Front-end

First version of the KLIK front-end, available both online and as a NPM package.

### Extension

First version of the KLIK extension for VS Code and Cursor, improving prompts and help manage `cursorrules` to accelerate development without losing control over the generated code.

### Theme Core

Core module used to build AI driven themes, like the first one I built to test KLIK and let it create amazing dashboards and SASS pages.

### KLIK Theme

First AI native theme built to be used with the KLIK framework, uses the `Theme Core` to make every component ready to be used with AI.

### Base - Back-end

First repository used by KLIK to generate a solid back-end project right after you write the first prompt.

### Base - Front-end

First repository used by KLIK to generate a solid front-end project right after you write the first prompt.

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

### Theme

Web based UI theme used to build custom interfaces for industry and manufacturing fields, both for XPM and React.

### PHP API

Module exposing a complete set of PHP REST API used in industry and manufacturing fields.

### Documents Builder

In some fields pages, documents or labels need to be created and then sent to devices like printers, PLCs or modbus as data to be processed or printed.

I built a system that allows users to create those documents from a web page, and export or transmit them to the correct devices.

### Back-office / MES

Back-office used in industries to handle data, orders or production related data.

Also compatible with the headless CMS Strapi.

### OPC-UA Module

NPM module for Node.js, also compatible with Strapi as plugin, that allows to communicate following the OPC-UA standard.

---

## Work in progress

This document is a work in progress.  
More private projects (30+) will be added over time as summaries are written and confidentiality constraints are reviewed.

If you're interested in one of these projects or would like to contribute to a similar initiative, feel free to reach out.