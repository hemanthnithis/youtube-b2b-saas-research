# 🎬 YouTube Content Strategy for B2B SaaS — Research Repository

> A deep-dive research project built in response to a real hiring brief from **100Hires**. The goal: find the strongest practitioners in B2B SaaS YouTube content strategy, collect and process their content using APIs and AI tools, synthesise the patterns, and turn them into a framework and playbook that a complete beginner could execute from day one.

---

## 📌 Why I Chose This Topic

Out of eight topics in the brief, I chose **YouTube content strategy for B2B SaaS** because it sits at the intersection of two things I understand well: how B2B buyers make decisions, and how content compounds into pipeline over time. YouTube is widely under-used in B2B — most SaaS companies either ignore it or treat it like a vanity channel. The practitioners who are doing it seriously are generating real inbound without ads. That gap between what's possible and what most companies actually do is exactly where good research is most useful.

---

## 🧠 My Key Takeaways

After spending 1–1.5 days across 11 expert sources — YouTube creators, LinkedIn authors, and long-form writing — these are the conclusions I'd stake a real content strategy on:

**1. The script is the product, not the video.**
A well-scripted video recorded on a phone outperforms a beautifully produced video with a weak hook. Every time. Most B2B teams invest in cameras before they invest in thinking. That's backwards.

**2. YouTube search is the most durable B2B traffic channel that almost nobody is using seriously.**
Unlike LinkedIn (where posts die in 24–48 hours) or paid ads (which stop the moment you stop paying), a well-optimised YouTube video keeps generating views and leads for months or years. The compounding effect is real — but it only kicks in after consistent publishing for 4–6 months. Most companies quit at month 2.

**3. Topic selection is where most channels fail before they even start.**
The majority of B2B YouTube channels make videos about what their company wants to talk about, not what their buyers are actively searching for. These are different things. Search-driven topics — pulled from YouTube autocomplete, competitor channels, Reddit, and sales call transcripts — are the foundation. Everything else is secondary until you have traction.

**4. The CTR + AVD combination tells you everything.**
Click-Through Rate tells you if your title and thumbnail are working. Average View Duration tells you if your content is working. If CTR is low, fix the packaging. If AVD drops before 30%, fix the hook. You don't need a dashboard — you need to look at these two numbers once a month and act on them.

**5. LinkedIn authors and YouTube creators teach the same principles differently.**
LinkedIn posts compress insight into a hook + 5–10 lines. YouTube scripts expand it into a hook + promise + content + CTA. The underlying logic — lead with the buyer's problem, not the company's product — is identical. The format is just different. This means cross-platform synthesis is possible and valuable.

**6. B2B YouTube is a trust channel, not a reach channel.**
The goal is not to go viral. The goal is to be the most useful resource in your niche for the specific person who is about to buy what you sell. Narrow, high-signal content aimed at one person outperforms broad content every time in B2B.

---

## 🛠️ Tools I Used — and Why

This project was deliberately built to show a working AI-assisted research workflow, not just a collection of links. Here's what I used and why each tool was the right choice for that task.

| Tool | What I Used It For | Why This Tool |
|------|--------------------|---------------|
| **Supadata** | Fetching YouTube transcripts via API | The cleanest free-tier solution for transcript extraction at scale without needing YouTube Data API quota management. Pulled transcripts for all major video sources. |
| **Perplexity** | Initial expert discovery and source validation | Fast at surfacing credible practitioners with real track records — not just people with high follower counts. Used it to cross-check that each source had genuine results, not just opinions. |
| **Google Gemini** | Comparative analysis across multiple sources | Useful for identifying patterns across long-form content from different creators. Helped surface where practitioners agreed and where they diverged. |
| **ChatGPT** | Drafting summary structures and content outlines | Used for rapid first-pass structuring of dense transcript content before refining in Claude. |
| **Claude (Anthropic)** | Synthesis, framework writing, playbook writing, and all final output | The primary tool for turning raw research into structured, usable outputs. Used for the framework, the playbook, the detailed summaries, and the interactive HTML version. Claude handled the reasoning-heavy work: identifying patterns, resolving contradictions between sources, and translating insight into actionable steps. |
| **GitHub** | Version control and repository structure | Committed regularly throughout the research process — not in one batch at the end. The commit history reflects the actual research timeline. |

### How These Tools Worked Together

The workflow was not "use one tool for everything." It was a deliberate pipeline:

```
Expert discovery          →  Perplexity + manual research
Transcript collection     →  Supadata API
Cross-source analysis     →  Gemini + ChatGPT
Synthesis + writing       →  Claude
Structuring + versioning  →  GitHub
```

Each tool was chosen for what it's actually good at. The result is faster and higher-quality than using any single tool for everything.

---

## 📁 Repository Structure

```
youtube-b2b-saas-research/
│
├── README.md                          ← You are here
│
└── research/
    ├── sources.md                     ← All 11 experts: who they are, why chosen, links, annotations
    │
    ├── youtube-transcripts/           ← Raw + summarised transcripts by creator
    │   ├── samu-kovacs/
    │   ├── alex-heiden/
    │   ├── exposure-ninja/
    │   ├── pat-walls/
    │   └── ...
    │
    ├── linkedin-posts/                ← Posts collected and summarised by author
    │   ├── brendan-hufford/
    │   ├── pierre-herubel/
    │   ├── tommy-walker/
    │   ├── devin-reed/
    │   └── ...
    │
    └── other/
        ├── framework.md               ← Strategic reference: the what and why
        └── playbook.md                ← Execution guide: exact templates, scripts, and checklists
```

---

## 👥 The 11 Experts — Why These, Not Others

The brief said: *10 high-signal sources beat 50 generic ones.* I took that seriously. Every source here was chosen because they have **documented results**, not just large audiences.

| # | Expert | Platform | Why They Made the Cut |
|---|--------|----------|-----------------------|
| 1 | **Samu Kovács** | YouTube | The clearest practitioner-level voice on B2B SaaS YouTube SEO. Documented channel growth case studies with real numbers. |
| 2 | **Alex Heiden** | YouTube | Founder-led content done right. Shows exactly how a solo founder can build a YouTube audience that generates inbound without a content team. |
| 3 | **Rob Walling** | YouTube + Podcast | SaaS Founder who has consistently built authority on long timelines. Understands compounding content better than almost anyone. |
| 4 | **TK Kader** | YouTube | Runs a rigorous weekly publishing cadence and talks openly about what metrics he tracks. Practical and numbers-driven. |
| 5 | **Exposure Ninja** | YouTube | High-frequency B2B content production at scale. Excellent on SEO-driven YouTube strategy and turning videos into search traffic. |
| 6 | **Pat Walls / Starter Story** | YouTube | Built a media company on top of a repeatable video format. The best example of systematising content production. |
| 7 | **Joanna Wiebe** | LinkedIn + Writing | The source for conversion copywriting principles applied to video scripts and hooks. Her frameworks on leading with the reader's problem are the foundation of the scripting approach in the playbook. |
| 8 | **Brendan Hufford** | LinkedIn | Writes clearly on the difference between content strategy and content tactics, and on how AI search is changing what "content that ranks" means in 2024–2025. |
| 9 | **Pierre Herubel** | LinkedIn | Best voice on content investment prioritisation for B2B SaaS — specifically on how to decide what's worth making before you make it. |
| 10 | **Tommy Walker** | LinkedIn | Deep on editorial craft and persona-driven storytelling. Helped sharpen the thinking on ideal viewer definition in the framework. |
| 11 | **Devin Reed** | LinkedIn | Content strategy at scale — specifically on audience trust, pipeline attribution, and building what he calls "trust at scale." The metrics thinking in Phase 6 of the playbook draws heavily from his approach. |

---

## 📄 What's in the `/other` folder — Framework vs. Playbook

I built two distinct documents from this research, and the difference matters:

**[`framework.md`](./research/other/framework.md)** — the strategic reference document. It explains what to do in each phase and why. It's designed to be read once to understand the full picture, and returned to for reference.

**[`playbook.md`](./research/other/playbook.md)** — the execution document. It has the actual script template (copy-paste ready), the hook examples (word-for-word), the title formula with weak vs. strong comparisons, the pre-recording checklist, and the monthly review decision rules. It's designed to be open on a second screen while you're actually making a video.

The framework tells you the strategy. The playbook tells you what to type.

I also built an **interactive HTML version** of the playbook (the file shared separately) with a sidebar navigation, interactive checklists with localStorage persistence, scroll progress tracking, and a phase roadmap — because I wanted to show what this looks like when it's actually designed for a human to use, not just read.

---

## ⏱️ How I Spent the 3 Days

**Day 1 — Research and source selection**
Spent the majority of the day on expert discovery: finding practitioners (not just thought leaders), verifying that each had real results, and rejecting sources that were generic or overly promotional. Used Perplexity for initial discovery, then manually vetted each source. Pulled YouTube transcripts via Supadata API. Collected LinkedIn posts manually.

**Day 2 — Processing and synthesis**
Turned raw transcripts and posts into detailed summaries. Used Gemini and ChatGPT for first-pass structure, Claude for synthesis and pattern identification. Identified the 6 recurring themes that became the 6 phases of the framework. Started committing to GitHub regularly.

**Day 3 — Framework, playbook, and polish**
Wrote the framework and playbook. Built the interactive HTML version. Reviewed the entire repository for coherence — making sure the sources, summaries, framework, and playbook all tell the same consistent story. Final commits and cleanup.

---

## ✅ Brief Checklist

Mapping what was asked for to what was delivered:

| Brief Requirement | Status | Notes |
|-------------------|--------|-------|
| Choose one topic | ✅ | YouTube content strategy for B2B SaaS |
| Find 10 experts | ✅ | 11 experts — 5 YouTube creators, 6 LinkedIn authors |
| Collect content via APIs | ✅ | YouTube transcripts via Supadata API |
| Collect LinkedIn posts | ✅ | Manually collected and organised by author |
| `/research/sources.md` | ✅ | All sources with links, dates, and annotations |
| `/research/linkedin-posts/` | ✅ | Organised by author |
| `/research/youtube-transcripts/` | ✅ | Organised by creator, includes summaries |
| `/research/other/` | ✅ | Framework + playbook |
| Updated `README.md` | ✅ | This document |
| Regular commits | ✅ | Committed throughout — not one batch at the end |
| Strong enough to support a real playbook | ✅ | Framework + playbook are both complete and usable |

---

## 🙋 A Note on What I Added Beyond the Brief

The brief asked for sources, transcripts, and a structured repository. I delivered that — and also added:

- **Detailed summaries** for every transcript and LinkedIn post, so the repository is useful to someone who hasn't watched the videos or read the posts
- **A framework** that synthesises all 11 sources into one coherent strategic document
- **A full playbook** with copy-paste templates, not just strategic advice
- **An interactive HTML playbook** with working checklists and navigation — because I wanted to show what good information design looks like, not just what good research looks like

I didn't add these to pad the repository. I added them because a research project that generates usable outputs is more valuable than one that just stores raw material.

---

*Built by [@hemanthnithis](https://github.com/hemanthnithis) · June 2026 · In response to a hiring brief from Alex Kravets, CEO, 100Hires*
