# Ron Salama

**Software Engineer** · B.Sc. Software Engineering, Braude College of Engineering (2026) · Israel

At work I write **C# and C** (plus **LabVIEW**) at Omwise, building instrumentation & automation software that talks to real lab hardware: multithreaded C# (Tasks, locks, semaphores) running several units under test at once, continuous measurement monitoring and logging, Windows desktop GUIs for engineers, and device communication over SCPI/VISA, serial (RS-232/485), TCP/IP and Modbus/TCP. I cut a recurring 8-card initialization and measurement run from about 20 minutes to under 5 by optimizing the existing automation. That code is closed-source. Before that, I led a 7-person test & diagnostics team in the IDF.

On my own projects, Claude Code agents draft most of the code. I set the requirements and acceptance checks (for example, a hand-labeled answer key), then test and measure the result and challenge the agents' claims. Each project README says where the agents got it wrong.

## Featured projects

**[Financial Document AI](https://github.com/Ron-Salama/rag-support-agent)** · *Python · RAG · AI agents & tool calling · structured outputs · LLM evals · FastAPI REST API · Chroma · Gemini · Docker + GitHub Actions CI*\
Structured extraction, RAG with page citations, and a tool-calling agent whose answers a second model verifies, over 15 public financial documents (476 pages). I hand-labeled all 15 documents blind as the answer key. The first run scored **126 of 131 fields**; after fixing what the misses revealed, **128 of 131**. One miss had passed the pipeline's own grounding check: the quote was real, but the number wasn't in it. Only the hand labels caught it.

**JobScan** · *Python · data pipeline over REST/JSON APIs and scrapers · GitHub Actions CI/CD · regression tests · Claude Code multi-agent review (judge + skeptic)*\
One run: **7,256 postings from about 30 Israeli job sources, 483 past the rules, in 17 minutes** on GitHub Actions, gated by 64 regression tests. The pipeline itself calls no LLM. In a separate Claude Code step, judge agents score roles and skeptic agents attack each verdict (they changed 13 of 193).

**[Ellie Says](https://github.com/almograz1/Ellie-Says)** · *Next.js · TypeScript · React · REST API routes · Firebase · Gemini LLM*\
A Hebrew-learning web app, built as a course project with classmates. Server-side API routes call Gemini for translation and game rounds, and users sign in with email or Google. The Gemini key was switched off after the course, so translation is offline; the games fall back to a built-in word list. [Code](https://github.com/almograz1/Ellie-Says) · [Live app](https://ellie-says.vercel.app)

Also: co-developed **[SlimeKitten](https://store.steampowered.com/app/5095720/SlimeKitten/)**, a Unity / C# game released on Steam and Google Play.

## Tech

- **Languages:** C# (.NET) · C · Python · TypeScript · LabVIEW
- **AI engineering:** RAG · AI agents & tool calling · structured outputs · LLM evals · Claude Code (CLI), daily
- **Engineering:** REST APIs · GitHub Actions CI/CD · automated testing · multithreading · hardware/device integration · Git

## Contact

[LinkedIn](https://www.linkedin.com/in/ron-salama) · [ron.salama@gmail.com](mailto:ron.salama@gmail.com)
