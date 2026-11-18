<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:2c5364&height=200&section=header&text=Shashank%20Shekhar&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=AI%20Engineer%20%7C%20Voice%20AI%20%C2%B7%20RAG%20%C2%B7%20Agents&descAlignY=58&descSize=20" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1200&color=2C5364&center=true&vCenter=true&width=600&lines=Building+voice+AI+that+handles+real+calls;RAG+systems+grounded+in+real+data;Agents+with+LangChain+%26+LangGraph;Open+to+remote%2C+onsite+%26+freelance" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open%20to-Remote%20%7C%20Onsite%20%7C%20Freelance-2ea44f?style=for-the-badge" />
  <a href="mailto:[YOUR EMAIL]"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="http://linkedin.com/in/shashankshekhar05"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge" /></a>
</p>

# Hey, I'm Shashank 👋

I build AI systems that have to work when real people are on the other end, like phone calls that can't drop, CRMs that have to stay in sync, and answers that have to be grounded in real data.

I'm an AI engineer based in Chandigarh, India. I mostly work in Python and FastAPI, and I'm open to remote roles, onsite roles, and freelance projects.

---

## What I do

- **Voice AI:** AI calling agents, telephony, call transfers, recordings
- **RAG and document intelligence:** retrieval systems that answer from your data, not from guesses
- **AI agents:** tool-calling agents and workflows with LangChain and LangGraph
- **Backend engineering:** multi-tenant APIs, OAuth integrations, Postgres, Redis. Before AI I wrote Java and Spring Boot, and that background still shows in how I build.

---

## The project I'm proudest of: a multi-tenant AI voice dialer

I built the backend of a multi-tenant AI voice dialer at [COMPANY NAME or "a SaaS startup in Mohali"], a platform where businesses run AI-powered outbound calls and have the results flow into their CRM. It ran at 1000+ calls a day. (The code is private, so here's what's inside.)

```mermaid
flowchart LR
    A[Lead / Campaign] --> B[FastAPI Backend]
    B <--> C[(PostgreSQL)]
    B <--> D[(Redis)]
    B --> E[Twilio / Plivo]
    E <--> F[Ultravox / Bolna<br/>Voice AI]
    E -->|hunt-dial transfer<br/>+ whisper briefing| G[Human Agent]
    B <-->|OAuth2 sync| H[Zoho · HubSpot · GoHighLevel]
    E -->|recordings| I[(AWS S3)]
```

**What it does**
- Places AI-driven calls through Twilio and Plivo, with Ultravox and Bolna as voice providers
- Syncs with **Zoho CRM, HubSpot and GoHighLevel** through OAuth2: bidirectional contact sync, call notes pushed back after each call
- Hands off to a human mid-call with a hunt-dial transfer and a **warm whisper briefing**, so the human knows who they're talking to before they speak
- Stores recordings on S3, with each customer's data kept separate

**Stack:** Python, FastAPI, PostgreSQL, Redis, Twilio, Plivo, Ultravox, Bolna, AWS S3

**What I owned:** the backend, the CRM integrations, the call-transfer flows, and the setup guides customers used to connect their own CRMs.

**The unglamorous lessons:** CRM data is messy (I once chased a phone-number uniqueness bug across two systems), providers fail in different ways, and "works in a demo" and "works on call number 900" are different problems.

[Read the architecture write-up →]([LINK TO YOUR PDF OR BLOG])

---

## Public work you can actually read

<a href="https://github.com/Shashankshekhar05/finance-ai-platform">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=Shashankshekhar05&repo=finance-ai-platform&theme=tokyonight&hide_border=true" />
</a>
<a href="https://github.com/Shashankshekhar05/RAG-System-designed">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=Shashankshekhar05&repo=RAG-System-designed&theme=tokyonight&hide_border=true" />
</a>
<a href="https://github.com/Shashankshekhar05/paylane-agent">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=Shashankshekhar05&repo=paylane-agent&theme=tokyonight&hide_border=true" />
</a>
<a href="https://github.com/Shashankshekhar05/Ai_Assisted_interview">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=Shashankshekhar05&repo=Ai_Assisted_interview&theme=tokyonight&hide_border=true" />
</a>

- **finance-ai-platform:** an AI finance platform with RAG, deterministic calculations (so the numbers are never hallucinated), SQL analytics, hybrid AI routing, JWT/RBAC and conversational context
- **RAG-System-designed:** [ONE LINE: what makes this one different]
- **paylane-agent:** [ONE LINE: what it does]
- **Ai_Assisted_interview:** [ONE LINE: what it does]

---

## What I'm working on right now

- Going deep on **Google ADK** and comparing it with LangGraph for agent workflows
- Building a LangChain/LangGraph agent that I'll publish here soon
- Writing up my voice AI architecture so others can learn from it

---

## Tools I reach for

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS%20S3-569A31?style=flat-square&logo=amazons3&logoColor=white" />
</p>

**AI:** RAG pipelines, embeddings and vector search, prompt and tool-calling design, voice agents (Ultravox, Bolna)
**Backend:** REST, OAuth2, JWT, MySQL, webhooks, Plivo

---

## Work with me

**Hiring?** I'm looking for AI engineer, voice AI, agentic AI or Python backend roles, remote or onsite.
**Have a project?** I take freelance work on voice agents, RAG systems, CRM integrations and AI backends.

📧 [YOUR EMAIL]
💼 [LinkedIn](http://linkedin.com/in/shashankshekhar05)
🌐 [Portfolio](https://shashank-ai-essence.lovable.app)

I usually reply within a day.

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:2c5364&height=100&section=footer" width="100%" />
