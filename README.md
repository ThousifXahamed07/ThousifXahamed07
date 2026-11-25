<div align="center">

<h1>Thousif Ahamed</h1>

<p><b>AI Engineer</b> · Production LLM agents, retrieval systems & on-premise vision models</p>

<p>
I build AI systems that take real actions for real users in government, telecom, healthcare and retail,<br/>
and I design them to be grounded and verifiable, and to know when to hand off to a human.
</p>

<p>
<a href="https://thousif.me"><img src="https://img.shields.io/badge/Portfolio-thousif.me-111111?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/thousif-ahamed-59263b24b/"><img src="https://img.shields.io/badge/LinkedIn-Thousif%20Ahamed-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:ahamedthousif07@gmail.com"><img src="https://img.shields.io/badge/Email-ahamedthousif07%40gmail.com-111111?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
<img src="https://img.shields.io/badge/Based%20in-Bengaluru%2C%20India-111111?style=flat-square" alt="Location"/>
</p>

</div>

<br/>

## About

- **Freelance AI Engineer (2025 to present).** I've shipped **5 production AI systems** for clients in the Gulf and India.
- **Previously:** SDE Intern at **HashedIn by Deloitte** (Spring Boot microservices, LLM conversational systems, Kafka pipelines) and Backend Intern at **KodNest Technologies** (REST APIs in Go, Java and Python).
- **Research:** co-author of *Blood Type Detection from Biometric Data Using Deep Learning Model* (IJSCI, May 2025).
- **Interests:** agent reliability, evaluation and AI safety, specifically checking that agents do only what users approve.

<br/>

## Production work

> Client systems. The source code is private, so each one links to a case study on my portfolio.

<table>
<tr>
<td width="50%" valign="top">

### Alhamra Tower · Receipt Intelligence
**Receipt validation, fraud detection & loyalty**

Reads purchase receipts, checks they're genuine through several layers of validation, and awards loyalty points only for spend it has verified. Runs on an **on-premise vision-language model (Qwen 3.5 VL on NVIDIA A100s)**, so customers' financial data never leaves the client's servers.

`Qwen VL` `On-prem GPU` `Fraud detection` `FastAPI`

[Case study →](https://thousifxahamed07.github.io/portfolio-project/projects/alhamra-receipt-ocr)

</td>
<td width="50%" valign="top">

### Ooredoo · Enterprise HR Agent
**Grounded HR assistant for a large telecom operator**

Answers employee questions and automates HR workflows using internal documentation. Retrieval is **filtered by department, language and document type**, so users only get answers from sources they should see. Uncertain answers go to HR staff instead of being guessed.

`RAG` `Metadata filtering` `Confidence gating` `Human-in-the-loop`

[Case study →](https://thousifxahamed07.github.io/portfolio-project/projects/ooredoo-hr-agent)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Ministry of Communications, Kuwait · MOC Chatbot
**Bilingual government assistant**

A production RAG chatbot that answers citizens' questions from an internal knowledge base and handles **Arabic dialect queries** alongside English.

`Bilingual NLU` `Arabic` `RAG` `Enterprise automation`

[Case study →](https://thousifxahamed07.github.io/portfolio-project/projects/moc-chatbot)

</td>
<td width="50%" valign="top">

### Tripdeal AI · Travel Agent Platform
**AI travel discovery and booking assistant**

A travel agent for destination discovery, travel Q&A and personalised recommendations, backed by **OpenSearch retrieval** and room-mapping logic, and delivered as both a website agent and a ChatGPT app.

`OpenSearch` `ChatGPT Apps` `Room mapping` `Agents`

[Case study →](https://thousifxahamed07.github.io/portfolio-project/projects/tripdeal-ai)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Asnan Tower · Appointments Agent
**Scheduling agent for a dental clinic**

Handles availability checks, bookings and reminders through natural-language conversation, so patients can book the way they'd talk to a receptionist.

`Scheduling` `Conversational AI` `Tool use`

[Case study →](https://thousifxahamed07.github.io/portfolio-project/projects/asnan-tower-appointments)

</td>
<td width="50%" valign="top">

### How I build agents
**The patterns these systems share**

- Grounded answers from retrieval, with metadata scoping
- Confidence gating with a human-in-the-loop fallback
- Multi-layer validation before anything irreversible happens
- On-prem deployment when the data is sensitive
- Evaluations built into the production loop

[See all case studies →](https://thousifxahamed07.github.io/portfolio-project/projects)

</td>
</tr>
</table>

<br/>

## Open source & side projects

<table>
<tr>
<td width="50%" valign="top">

### [Milk Price Forecasting](https://github.com/ThousifXahamed07/milk-price-forecasting)
A hybrid ML system that forecasts milk procurement prices (₹/litre) across India's major dairy regions. It uses a **Prophet + XGBoost ensemble** with trust scoring and a Streamlit dashboard.

`Python` `Prophet` `XGBoost` `Streamlit`

</td>
<td width="50%" valign="top">

### [Gatekeeper](https://github.com/ThousifXahamed07/Gate-Keeper)
A fast Go CLI that checks environment variables against a YAML schema **at startup**, so a missing or malformed config fails loudly before it can cause trouble in production.

`Go` `CLI` `YAML schemas` `CI`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [TapKit](https://github.com/ThousifXahamed07/tapkit)
Turns your phone into a drum machine. Tap the table and the **accelerometer** works out where the tap came from to choose the drum, and how hard to set the volume. One web page, no dependencies.

`DeviceMotion API` `Signal processing` `Web Audio`

</td>
<td width="50%" valign="top">

### [PitchPrompter](https://github.com/ThousifXahamed07/pitchprompter)
A **voice-following teleprompter** for practising pitches. Your script floats near the webcam, words highlight as you speak, and lines advance automatically. Ships as a macOS app.

`JavaScript` `On-device speech` `macOS app`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [CineCircle](https://github.com/ThousifXahamed07/CineCircle)
A social network for watching movies together. Friends create rooms, share recommendations, and post reviews with mood tags and community insights.

`FastAPI` `MongoDB (async)` `JWT + Google OAuth` `TMDB API`

</td>
<td width="50%" valign="top">

### [Mac Chick Focus](https://github.com/ThousifXahamed07/mac-chick-focus)
A macOS-style Pomodoro timer that grows a chicken while you focus. It has spring physics, system light/dark themes, a synthesised ambient soundtrack, and original vector art.

`React 19` `Tailwind v4` `Framer Motion` `Web Audio`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Tranzio · Market Dashboard](https://github.com/ThousifXahamed07/Tranzio-dashboard)
Market intelligence for **Tranzio**, the digital-display ad network I'm building on Bengaluru auto-rickshaws: transit advertising market data, projections and insights.

`Market research` `Data viz` `HTML`

</td>
<td width="50%" valign="top">

### [Tranzio · Landing Page](https://github.com/ThousifXahamed07/tranzio-landing-page)
Tranzio's marketing site. A minimal, Apple-style design in plain HTML, CSS and JS with no build step, including a live simulation of the in-vehicle screen.

`HTML` `CSS` `JavaScript` `GitHub Pages`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [QueueFlow](https://github.com/ThousifXahamed07/Qrify-QMS)
A QR-based queue management SaaS for Indian clinics and salons. Patients join from their phone and track their position live, staff run the queue from a dashboard, and a TV display calls tokens aloud. Multi-tenant with **Postgres row-level security**.

`Next.js 15` `Supabase Realtime` `JWT` `English + Hindi` `Vitest`

</td>
<td width="50%" valign="top">

### [Cognita](https://github.com/ThousifXahamed07/Apple-math-padclone)
An AI maths notepad. Draw an equation by hand, and a **vision-language model** reads it, solves it and places the typeset answer on the canvas. Variables carry over between expressions. The first version ran **LLaVA-1.5-7B locally with 4-bit quantisation**.

`React` `FastAPI` `Gemini Vision` `LLaVA` `MathJax`

</td>
</tr>
</table>

**Building privately:**
**Mochi**, a free offline macOS dictation app built on whisper.cpp ·
**Atlas**, an LLM-maintained knowledge layer for founding teams ·
**LaneScout**, a real-time PWA that tracks which lanes you've covered while house hunting in Indian cities

<br/>

## Stack

<p align="left">
<img src="https://skillicons.dev/icons?i=python,go,java,ts,js,postgres,mongodb,redis,fastapi,spring,docker,kafka,git&perline=13" alt="Tech stack"/>
</p>

| Area | Tools |
|---|---|
| **AI / LLM** | OpenAI GPT-4o · Qwen VL (on-prem) · LangChain · RAG · semantic search · prompt engineering · evals |
| **Backend** | FastAPI · asyncio · Spring Boot · Go (Gin) · Flask · REST · WebSockets · Kafka |
| **Data & search** | PostgreSQL · MySQL · MongoDB · OpenSearch · vector databases · Redis |
| **Infrastructure** | Docker · NVIDIA A100 · on-premise deployment · cloud |

<br/>

## Experience

| Role | Company | When |
|---|---|---|
| **Freelance AI Engineer** | Independent: government, telecom, hospitality and healthcare clients | 2025 – present |
| **SDE Intern** | HashedIn by Deloitte | Oct – Dec 2025 |
| **Backend Developer Intern** | KodNest Technologies | Jan – May 2025 |

**Education:** B.E. Information Science, Bapuji Institute of Engineering & Technology (VTU), 2021–2025, GPA 8.78/10<br/>
**Awards:** Winner, Tech Zone 2k24 Web Development Competition · Winner, GDSC Solution Challenge Ideathon (2024)

<br/>

<div align="center">

<sub>Open to AI engineering roles and research collaborations on agent reliability and evaluation.<br/>
<a href="mailto:ahamedthousif07@gmail.com">ahamedthousif07@gmail.com</a></sub>

</div>
