# Hey, I’m Tommi. You’ll find me here as Cyb3rCricket. 🦗

### AI builder with an IT operations background and a soft spot for creative technology.

I build practical AI tools, interactive web experiments, and software that gets a little weird on purpose.

My background is in hands-on IT support, troubleshooting, ServiceNow, and workflow systems. I also have a **BS in Information Technology — Artificial Intelligence**, earned summa cum laude. These days, I’m putting that experience into projects that help me understand how AI applications actually work: the models, the memory, the interfaces, and what happens when something goes wrong.

I’m working toward **Applied AI Engineer, AI Product Engineer, and AI Automation Engineer** roles.

[Portfolio & case studies](https://cyb3rcricket.github.io/cyb3rcricket-site/index.html) · [Building in public on X](https://x.com/cyb3rcricket)

## What I’m building

### 🎫 [TinyDesk](https://cyb3rcricket.github.io/cyb3rcricket-site/tinydesk.html)

A help desk demo that brings my support background into an AI application. It has a working ticket queue, activity history, and an assistant that summarizes tickets, suggests categories, and drafts replies using local Ollama models or Grok through the xAI API.

The person working the ticket stays in control. Suggestions need review, applying a suggestion doesn’t save it, and drafts aren’t automatically sent. I’ve also compared models on fictional tickets to look beyond valid JSON and ask whether the answers are actually useful.

**What I’m learning:** model evaluation, structured outputs, API integration, context limits, and designing AI assistance around a real workflow.

`Python` · `FastAPI` · `JavaScript` · `Ollama` · `xAI API`

*Demo project with fictional data. Source repository is private; the link above opens the public case study.*

### 🧠 [TinyTalk](https://github.com/cyb3rcricket/TinyTalk)

This started as a rebuild of an old college chatbot. Then I started asking what “memory” actually means for an assistant, and the project got more interesting.

TinyTalk separates identity instructions, recent conversation, saved facts, and historical memories. It can use Ollama or Grok while keeping the same memory system. Recent work focuses on distinguishing current facts from old ones, handling unfinished memory updates, and showing which stored sources were supplied with an answer.

**What I’m learning:** persistent memory, retrieval, structured relationships, failure recovery, and keeping application behavior consistent when the model changes.

`Python` · `MemPalace` · `Knowledge graphs` · `Ollama` · `xAI API`

### 🏙️ [Commit City](https://github.com/cyb3rcricket/commit-city)

A GitHub contribution history turned into a 3D cyber-city. Contribution days become city lots, and heavier days rise into taller towers while keeping the familiar calendar shape from above.

This is the creative side of the work: taking data people already recognize and giving them another way to explore it.

`TypeScript` · `Three.js` · `Vite` · `GitHub data` · `3D interaction`

### 🔐 [Tennessee Digital Rights Tracker](https://github.com/cyb3rcricket/tennessee-digital-rights-tracker)

A civic-tech research project organizing Tennessee laws, court decisions, surveillance systems, and public records into structured entries with traceable sources.

The question behind it is pretty simple: can someone follow a claim back to the evidence and check it for themselves?

`Python` · `GitHub Actions` · `Structured research` · `Source validation`

## How I work

I use AI coding tools as collaborators. I also want to be able to open the code, follow what happens, explain the decisions, and investigate the parts that break. That’s an ongoing part of the work.

Some of the most useful lessons have come from small failures: a model asking a question the ticket already answered, an old memory showing up as a current fact, or a request getting too large for a local model’s context window.

Those are the parts I like digging into. They’re also why I care about clear state, useful error messages, focused tests, and honest documentation of what a project can and can’t do yet.

## More from the lab

I still love software that has personality.

- **[Gravity Well](https://github.com/cyb3rcricket/gravity-well)** — a webpage whose interface gives in to gravity, collisions, and a singularity.
- **[Mutation Microscope](https://github.com/cyb3rcricket/mutation-microscope)** — an interactive scientific visualization for exploring AlphaGenome variant-effect predictions.
- **[Mutiny Bot](https://github.com/cyb3rcricket/mutiny-bot)** — a Discord operations bot exploring local AI, scheduling, persistent memory, and permission checks.
- **[Dial-Up Fun](https://github.com/cyb3rcricket/dial-up-fun)** — AOL / Windows 95-style dial-up nostalgia in the browser.
- **[Y2K Oracle](https://github.com/cyb3rcricket/Y2K-Oracle)** — because software is allowed to be strange.

## Tools I’m working with

**AI applications:** `Python` · `FastAPI` · `Ollama` · `REST APIs` · `Structured outputs` · `Memory & retrieval`

**Web & creative builds:** `JavaScript` · `TypeScript` · `HTML` · `CSS` · `React` · `Three.js`

**Data & workflow:** `SQLite` · `Git` · `GitHub` · `GitHub Actions` · `ServiceNow` · `ITSM`

---

### Build useful things. Build weird things. Make them work.
