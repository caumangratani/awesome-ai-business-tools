# I Reviewed 190+ AI Repos So You Don't Have To. Here Are the 32 That Actually Work.

> I'm a Chartered Accountant who stopped billing hours and started deploying AI agents. In the last 90 days, I've cloned 40+ repos, installed 200+ skills, and tested every "game-changing" AI tool that crossed my feed. Most are garbage. Recycled prompts dressed up as "skills." Toy demos that break on real data. README hype with no substance.
>
> This list is different. These are the repos I actually use — daily — to run four businesses, manage a team, and ship content. Rated honestly. No affiliate links. No sponsorships. Just what works.
>
> **If you run a business and want AI to actually do the work (not just answer questions), start here.**

---

## How This List Works

Every repo is rated on 3 criteria:

| Criteria | What It Means |
|----------|---------------|
| **Usefulness** | Does it solve a real problem or is it a demo? |
| **Production-Ready** | Can you use it today with real clients/data? |
| **Bookmark Rate** | High bookmark rate = people save it for later = genuinely useful |

**Rating Scale:** Skip (don't bother) / Reference (learn from it) / Install (use it) / Essential (can't work without it)

---

## The List

### ESSENTIAL — These Run My Businesses Daily

<details>
<summary><strong>1. agency-agents</strong> — 111 AI specialists ready to work | <code>ESSENTIAL</code></summary>

**Repo:** [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)

**What it does:** 111 pre-built AI agent definitions — PM, Architect, Dev, QA, CMO, Security Engineer, Reality Checker, Whimsy Injector. Each agent has personality, process, and deliverables defined. Drop them into Claude Code and you have an instant team.

**Why it's essential:** I run a 7-agent Bizgenix team (CTO, Backend Architect, Frontend Dev, AI Engineer, CMO, Product Manager, QA Lead) with org hierarchy and budgets. These agents don't just answer questions — they have opinions, they push back, they catch mistakes. The "Reality Checker" agent alone has saved me from shipping broken code 4 times.

**Best for:** Anyone managing AI workflows. Developers. Agency owners.

**Install:**
```bash
git clone https://github.com/msitarzewski/agency-agents.git
cp -r agency-agents/agents/* ~/.claude/agents/
```

</details>

<details>
<summary><strong>2. ai-marketing-skills</strong> — 12 battle-tested marketing modules | <code>ESSENTIAL</code></summary>

**Repo:** [ericosiu/ai-marketing-skills](https://github.com/ericosiu/ai-marketing-skills)

**What it does:** Complete marketing workflow system — not prompts, actual Python scripts with expert panels, scoring algorithms, and automation pipelines. Built by Eric Siu (Single Grain) on real pipelines generating millions in revenue. 12 modules: Content Ops, Growth Engine, Sales Pipeline, Outbound Engine, SEO Ops, Finance Ops, Revenue Intelligence, Conversion Ops, Podcast Ops, Team Ops, Security, Telemetry.

**Why it's essential:** The Content Ops module auto-assembles a panel of 7-10 experts and recursively scores your content until it hits 90+. The Growth Engine uses bootstrap confidence intervals and Mann-Whitney U tests — real statistics, not vibes. I installed 4 modules (content-ops, growth-engine, outbound, conversion) and they replaced 3 freelancers.

**The number:** 1,020 bookmarks on the tweet that shared this. 2.6% bookmark rate. That's insanely high.

**Best for:** Marketing teams. Agency owners. Solo founders doing their own marketing.

**Install:**
```bash
git clone https://github.com/ericosiu/ai-marketing-skills.git
cp ai-marketing-skills/content-ops/SKILL.md ~/.claude/skills/content-ops/SKILL.md
cp ai-marketing-skills/growth-engine/SKILL.md ~/.claude/skills/growth-engine/SKILL.md
```

</details>

<details>
<summary><strong>3. awesome-claude-skills</strong> — The community bible | <code>ESSENTIAL</code></summary>

**Repo:** [BehiSecc/awesome-claude-skills](https://github.com/BehiSecc/awesome-claude-skills)

**What it does:** Curated collection of Claude Code skills — the starting point for anyone building a skill-based workflow. This is where I found brainstorming, systematic-debugging, TDD, verification-before-completion, and 11 other skills I use daily.

**Why it's essential:** Skills > prompts. If you're still copy-pasting prompts into Claude, you're working 10x harder than you need to. Skills run automatically, enforce quality, and improve over time. This repo is the best starting index.

**Best for:** Anyone using Claude Code. Absolute first stop.

</details>

<details>
<summary><strong>4. Anthropic skills (Official)</strong> — The standard | <code>ESSENTIAL</code></summary>

**Repo:** [anthropics/skills](https://github.com/anthropics/skills)

**What it does:** Official Anthropic skills repository. The reference implementation for how skills should be built. Includes Google Workspace integrations (Gmail, Calendar, Drive, Sheets, Docs, Chat), recipe patterns, persona templates, and workflow automations.

**Why it's essential:** If awesome-claude-skills is the community bible, this is the official scripture. 30+ Google Workspace skills alone. I use `gws-gmail-triage` every morning to scan my inbox in 10 seconds.

**Best for:** Google Workspace power users. Anyone who wants official, maintained skills.

</details>

---

### INSTALL — High Value, Use These

<details>
<summary><strong>5. jackbutcher.md</strong> — 50,000 tweets, every pattern extracted | <code>INSTALL</code></summary>

**Repo:** [visualizevalue/jackbutcher.md](https://github.com/visualizevalue/jackbutcher.md)

**What it does:** 50,000 tweets from Jack Butcher (Visualize Value). Every content pattern, hook, and writing principle extracted into one file. This isn't a prompt — it's a dataset that teaches your AI how a master content creator thinks.

**Why it matters:** I plugged this into my content pipeline and my writing voice score went from 6/10 to 8.5/10. The AI stopped writing like a robot and started writing like a human who understands business. If you create content for LinkedIn, X, or newsletters — this is gold.

**Best for:** Content creators. Founders building personal brands. Anyone writing for business audiences.

</details>

<details>
<summary><strong>6. vvriter</strong> — Article generator powered by jackbutcher.md | <code>INSTALL</code></summary>

**Repo:** [visualizevalue/vvriter](https://github.com/visualizevalue/vvriter)

**What it does:** MCP server that generates articles from Jack Butcher's tweet archive and visual library. Connect it and say "write me an article." It pulls patterns, hooks, and structures from 50K tweets.

**Why it matters:** Pairs with jackbutcher.md. Together they form a content engine that writes in a proven voice. Not AI slop — structured, punchy business content.

**Best for:** Anyone who wants to write like Jack Butcher but doesn't have 10 years of practice.

</details>

<details>
<summary><strong>7. google-workspace-cli</strong> — Gmail, Calendar, Drive from the terminal | <code>INSTALL</code></summary>

**Repo:** [googleworkspace/cli](https://github.com/googleworkspace/cli)

**What it does:** Official Google Workspace CLI — manage Gmail, Calendar, Drive, Sheets, Docs, and more from the command line. This is the backbone that powers all the `gws-*` skills.

**Why it matters:** Makes Claude Code your Google Workspace autopilot. Create events, send emails, manage files — all through AI. I use it to triage 100+ emails every morning in under a minute.

**Best for:** Anyone deep in Google Workspace (which is most businesses).

</details>

<details>
<summary><strong>8. whatsapp-mcp</strong> — WhatsApp through Claude | <code>INSTALL</code></summary>

**Repo:** [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp)

**What it does:** MCP server for WhatsApp — read messages, send replies, manage conversations through Claude Code.

**Why it matters:** In India, WhatsApp IS business communication. This repo turns Claude into a WhatsApp-native assistant. Read client messages, draft replies, manage groups — all through AI. If your business runs on WhatsApp, this is non-negotiable.

**Best for:** Indian businesses. Service businesses. Anyone whose clients communicate via WhatsApp.

</details>

<details>
<summary><strong>9. claude-seo</strong> — Full SEO audit from the terminal | <code>INSTALL</code></summary>

**Repo:** [AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo)

**What it does:** Comprehensive SEO audit skill for Claude Code — crawlability, indexability, security, URL structure, mobile optimization, Core Web Vitals, JavaScript rendering. Runs a full audit and gives you a prioritized action list.

**Why it matters:** Replaces $500/month SEO tools for most small businesses. Run it on your website, get the same analysis that agencies charge thousands for.

**Best for:** Small business owners. Freelance marketers. Anyone with a website.

</details>

<details>
<summary><strong>10. mission-control</strong> — Admin dashboard for AI agent teams | <code>INSTALL</code></summary>

**Repo:** [builderz-labs/mission-control](https://github.com/builderz-labs/mission-control)

**What it does:** Centralized ops + governance platform for OpenClaw/AI agent teams. Multi-client management, approval workflows, activity timeline.

**Why it matters:** Once you're running 5+ agents, you need a dashboard. This gives you visibility into what every agent is doing, when they last ran, and what they produced. Think of it as the "office manager" for your AI workforce.

**Best for:** Agencies managing multiple AI agents. Teams with 5+ active agents.

</details>

---

### REFERENCE — Learn From These

<details>
<summary><strong>11. agents-towards-production</strong> — Taking agents from demo to production | <code>REFERENCE</code></summary>

**Repo:** [NirDiamant/agents-towards-production](https://github.com/NirDiamant/agents-towards-production)

**What it does:** Comprehensive guide on production-grade AI agents — error handling, testing, monitoring, deployment patterns. The gap between "it works on my laptop" and "it works for clients" is massive. This repo bridges it.

**Best for:** Developers building commercial AI products.

</details>

<details>
<summary><strong>12. claude-code-best-practice</strong> — Make Claude Code actually work for you | <code>REFERENCE</code></summary>

**Repo:** [shanraisshan/claude-code-best-practice](https://github.com/shanraisshan/claude-code-best-practice)

**What it does:** Best practices for Claude Code — CLAUDE.md structure, memory management, context optimization, hook patterns.

**Best for:** New Claude Code users who want to start right. Intermediate users hitting context limits.

</details>

<details>
<summary><strong>13. 500-AI-Agents-Projects</strong> — Idea vault | <code>REFERENCE</code></summary>

**Repo:** [ashishpatel26/500-AI-Agents-Projects](https://github.com/ashishpatel26/500-AI-Agents-Projects)

**What it does:** 500+ AI agent project ideas and use cases. Not implementations — ideas. But good ideas, organized by category.

**Best for:** Brainstorming what to build next. Workshop material. Client conversations.

</details>

<details>
<summary><strong>14. system-prompts-and-models</strong> — How every AI tool actually works | <code>REFERENCE</code></summary>

**Repo:** [x1xhlol/system-prompts-and-models-of-ai-tools](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools)

**What it does:** Leaked/extracted system prompts from ChatGPT, Claude, Gemini, Perplexity, and 50+ other AI tools. See exactly how they're built.

**Best for:** Competitive intelligence. Understanding how AI products are designed. Building your own AI tools.

</details>

<details>
<summary><strong>15. Product-Manager-Skills</strong> — PM workflow for Claude | <code>REFERENCE</code></summary>

**Repo:** [deanpeters/Product-Manager-Skills](https://github.com/deanpeters/Product-Manager-Skills)

**What it does:** Product management skills for Claude Code — PRDs, user stories, roadmaps, prioritization frameworks.

**Best for:** Product managers. Founders wearing the PM hat. Anyone building features.

</details>

---

### APRIL 2026 ADDITIONS (Newly Tested)

<details>
<summary><strong>16. Postiz</strong> — Open-source social scheduler replacing Buffer/Hootsuite | <code>INSTALL</code></summary>

**Repo:** [gitroomhq/postiz-app](https://github.com/gitroomhq/postiz-app)

**What it does:** Open-source social media command center for 25+ platforms — X, Instagram, LinkedIn, TikTok, YouTube, Reddit, Facebook, Threads, Pinterest, Bluesky, Mastodon, Discord, Slack, Telegram. AI post generation + Canva-like editor + analytics + team collaboration + public API.

**Why it's install-worthy:**
- Buffer charges $6/channel/mo, Hootsuite $199/mo, Sprout Social $249/mo
- Postiz replaces all of them, self-hosted, free
- For agencies: productize it as a client add-on at ₹15K/mo (near 100% margin)

**Best for:** Content creators. Agencies managing multiple client brands. Anyone posting to 3+ platforms.

**Discovered via:** [@heynavtoor tweet](https://x.com/heynavtoor/status/2043966500512616510)

</details>

<details>
<summary><strong>17. Rowboat</strong> — Open-source Claude Cowork alternative | <code>REFERENCE</code></summary>

**Repo:** [rowboatlabs/rowboat](https://github.com/rowboatlabs/rowboat)

**What it does:** Local-first desktop app that connects to your email + meeting tools, automatically builds a living knowledge graph of your work. Voice-enabled, works with any LLM, MCP extensibility, Obsidian-compatible vault (plain markdown), background agents, web search, Apache 2.0 license.

**Why it matters:** Direct validation that the LLM-wiki pattern (Karpathy's April 2026 gist) is becoming a real product category. The market is moving toward local-first, markdown-native, knowledge-compounding AI — exactly the architecture we've been building. Monitor for features to steal. Indian compliance angle (ICAI, DPDP Act) is a goldmine.

**Best for:** Studying the pattern. Not directly for MSME clients yet (too early, requires Docker).

**Discovered via:** [@akshay_pachaar tweet — 185K views](https://x.com/akshay_pachaar/status/2041856590341677378)

</details>

<details>
<summary><strong>18. Open-Higgsfield-AI</strong> — Open-source AI image & video cinema studio | <code>REFERENCE</code></summary>

**Repo:** [Anil-matcha/Open-Higgsfield-AI](https://github.com/Anil-matcha/Open-Higgsfield-AI)

**What it does:** 200+ models (Flux, SDXL, Midjourney, Ideogram, Kling, Sora, Veo) in one self-hosted UI. Image Studio, Video Studio, Cinema Studio (pro camera controls), Lip Sync Studio. Desktop app for macOS + Windows. MIT licensed. 4.2k stars, 760 forks.

**Why it's a reference:** If you ever need AI-generated visuals for content (reels, thumbnails, ads, workshop materials), this replaces paid subscriptions. Not core to business automation — but essential for content-heavy use cases.

**Best for:** Content creators needing visuals. Video production. Marketing teams.

**Discovered via:** [@ihtesham2005 tweet](https://x.com/ihtesham2005/status/2041546716806357435)

</details>

<details>
<summary><strong>19. Open-Higgsfield Alternative (Magika)</strong> — Google's open-source file detection AI | <code>REFERENCE</code></summary>

**Repo:** [google/magika](https://github.com/google/magika)

**What it does:** AI-powered file content type detection. Trained on 100M files, 200+ content types, 99% accuracy, 5ms per file. `pip install magika`. Google ran this internally for years (Gmail, Drive, Safe Browsing) before open-sourcing it.

**Why it's a reference:** Critical safety layer for any AI agent that processes client files. Rename malware to "invoice.pdf"? Magika sees through it. If you deploy BizClaw-style agents for CA firms or finance teams, this should sit at the infrastructure layer — not in the agent's memory (which compacts).

**Best for:** Anyone building production AI agents that handle client files. Security engineering for agent systems.

**Discovered via:** [@_vmlops tweet — 410K views](https://x.com/_vmlops/status/2043624154646409708)

</details>

<details>
<summary><strong>20. Karpathy CLAUDE.md Template</strong> — 15K stars behavioral rules file | <code>ESSENTIAL</code></summary>

**Repo:** Search GitHub for "claude-md karpathy" (originated from Karpathy's coding rules observations)

**What it does:** A single CLAUDE.md file dropped into your repo that gives Claude Code a structured set of behavioral guidelines. Prevents the 3 predictable LLM mistakes: over-engineering, ignoring existing patterns, adding unasked-for dependencies.

**Why it's essential:** "Developers are moving past 'use AI to write code' and into 'engineer the AI's behavior so the code is actually good.'" This is the tight harness pattern applied to code. If you use Claude Code daily, this single file can save you hours.

**Best for:** Every Claude Code user. Put this in every repo.

**Discovered via:** [@akshay_pachaar tweet](https://x.com/akshay_pachaar/status/2043374229199151351)

</details>

---

### NOVEMBER 2026 ADDITIONS (Newly Installed)

> In November I went through 205 saved X posts and about 130 linked repos. Every repo was checked on GitHub (stars, licence, last push), the skill files were read line by line before anything was copied, and the ones rated INSTALL or ESSENTIAL below were installed on my own machine. Each card says what was actually tested.

<details>
<summary><strong>21. HyperFrames</strong> — Video built in HTML, rendered to MP4 | <code>ESSENTIAL</code></summary>

**Repo:** [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes)

**What it does:** You write a video as HTML and GSAP animation. It renders to MP4 at any size. It ships Claude Code skills for composing, captions, audio and launch videos.

**Why it's essential:** This is now my default engine for product videos, feature tours and reels. One source renders both 16:9 and 9:16. No editor, no timeline, and every change is a text edit. Apache-2.0.

**Tested:** In daily use since October 2026 for product launch and company videos.

**Watch out:** Telemetry is on by default. Switch it off in its config file.

**Best for:** Founders and agencies who ship product videos often.

</details>

<details>
<summary><strong>22. gitleaks</strong> — Find leaked keys before a client does | <code>ESSENTIAL</code></summary>

**Repo:** [gitleaks/gitleaks](https://github.com/gitleaks/gitleaks)

**What it does:** Scans git history and folders for API keys, tokens and passwords.

**Why it's essential:** AI-written code leaks keys into commits more often than people admit. One command before every handover removes the most embarrassing failure in client work.

**Tested:** Ran it on a live client project. Git history was clean. The only hits were in local environment files that git already ignores.

**Install:**
```bash
brew install gitleaks
gitleaks detect --no-banner --redact
```

**Best for:** Anyone who hands code to a client or makes a repo public.

**Discovered via:** [@mdjunaidap](https://x.com/mdjunaidap/status/2119422187408851116)

</details>

<details>
<summary><strong>23. anydoc</strong> — Word, Excel, PowerPoint and PDF to Markdown | <code>INSTALL</code></summary>

**Repo:** [firecrawl/anydoc](https://github.com/firecrawl/anydoc)

**What it does:** One local command turns office files into clean Markdown that an AI can read. It ships a Claude skill.

**Why it's install-worthy:** Business owners send Excel sheets and Word files, not APIs. This is the fastest path from a client's file to something Claude can work with. MIT.

**Tested:** A 14-page Word document converted cleanly in 8 seconds. A designed multi-column PDF came out as messy tables, so use the source Word or PowerPoint file when you have it.

**Watch out:** The `--ocr hosted` option uploads the whole document. Keep it off for client files.

**Best for:** Consultants, CAs and anyone who receives documents from clients.

**Discovered via:** [@firecrawl](https://x.com/firecrawl/status/2084670366803218774)

</details>

<details>
<summary><strong>24. Cloudflare security-audit skill</strong> — A security review that checks its own findings | <code>INSTALL</code></summary>

**Repo:** [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill)

**What it does:** A source-first security review for any codebase. Each finding is re-checked by a fresh agent, so you get fewer false alarms. It has a short guidance mode and a full audit mode.

**Why it's install-worthy:** It refuses to run target code without a sandbox, and it reports what it could not verify. That honesty is rare. MIT, about 70K stars.

**Tested:** Read in full and scripts scanned (no network calls). First full audit on a production app is next.

**Best for:** Small teams shipping AI-written apps without a security person.

**Discovered via:** [@RoundtableSpace](https://x.com/RoundtableSpace/status/2112397145412091969)

</details>

<details>
<summary><strong>25. diagram-design</strong> — 45 diagram types in your brand colours | <code>INSTALL</code></summary>

**Repo:** [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)

**What it does:** Flowcharts, swimlanes, architecture, org charts, funnels, timelines and more as clean HTML, SVG or PNG. It imports draw.io, Mermaid and Excalidraw files and asks for your brand colours once.

**Why it's install-worthy:** Proposals and workbooks need diagrams, and default AI diagrams look generic. This one has a design system and a "delete until nothing can be removed" rule. MIT, no telemetry.

**Best for:** Proposals, training workbooks, pitch decks.

**Discovered via:** [@RoundtableSpace](https://x.com/RoundtableSpace/status/2108992207999128036)

</details>

<details>
<summary><strong>26. rea-video</strong> — How was this reel made? | <code>INSTALL</code></summary>

**Repo:** [JuneYaooo/rea-video](https://github.com/JuneYaooo/rea-video)

**What it does:** Breaks a reference video down shot by shot: live action, AI video or code render; captions and overlays; voice, music tempo and sound effects; edit rhythm. Then it writes a remake plan.

**Why it's install-worthy:** Studying what works is half of content. This replaces an hour of frame-stepping. Runs locally. Apache-2.0.

**Tested:** On a 59-second reel of my own it found 10 shots, correctly called the whole video a code render, and separated voice from music at 84.7 BPM. It took 4 minutes with no vision model.

**Watch out:** Use it to study structure and pacing. Do not copy another brand's footage or music. The skill file is in Chinese; pass `--lang en`.

**Best for:** Content teams and anyone scripting reels.

**Discovered via:** [@rileybrown](https://x.com/rileybrown/status/2119935865933725888)

</details>

<details>
<summary><strong>27. reanimate</strong> — Clone a web animation and prove the match | <code>INSTALL</code></summary>

**Repo:** [NiazMorshed2007/reanimate](https://github.com/NiazMorshed2007/reanimate)

**What it does:** Captures a reference animation from a URL or video, writes a motion spec (timing, easing, stagger), rebuilds it in your code, then compares the two frame by frame until they match.

**Why it's install-worthy:** "Make it move like that site" is the hardest brief to hand to an AI. This measures the motion, so the result does not depend on guesswork. MIT.

**Tested:** Setup completed (Bun, Chromium, ffmpeg). First real clone is next.

**Watch out:** Very new repo. Match motion, not another brand's assets.

**Best for:** Agencies building landing pages.

**Discovered via:** [@dr_cintas](https://x.com/dr_cintas/status/2119555538144911525)

</details>

<details>
<summary><strong>28. single-agent-loop-kit</strong> — Fewer subagents, more skills | <code>INSTALL</code></summary>

**Repo:** [anthropics/single-agent-loop-kit](https://github.com/anthropics/single-agent-loop-kit)

**What it does:** Anthropic's own kit for moving a multi-agent setup toward one agent that loads skills and tools on demand. Every change is measured against the same test before and after.

**Why it's install-worthy:** Most of us built too many agents in 2025. Anthropic's testing says one agent with good skills often does better. This gives you the method to check that on your own setup. Apache-2.0.

**Best for:** Anyone with more than five subagents.

**Discovered via:** [@cherry_mx_reds](https://x.com/cherry_mx_reds/status/2113969070118666670)

</details>

<details>
<summary><strong>29. harness-creator</strong> — Make a repo easy for an AI agent to work in | <code>INSTALL</code></summary>

**Repo:** [walkinglabs/learn-harness-engineering](https://github.com/walkinglabs/learn-harness-engineering)

**What it does:** A course on harness engineering plus a skill that creates and audits the five things an agent needs in a repo: instructions, state, verification, scope and session handoff.

**Why it's install-worthy:** When an agent forgets context or says "done" too early, the fix is usually in the repo, not the model. MIT, about 24K stars.

**Best for:** Teams running long builds with Claude Code or Codex.

**Discovered via:** [@liangzhu_AI](https://x.com/liangzhu_AI/status/2114325601326649846)

</details>

<details>
<summary><strong>30. social-media-skills</strong> — Score a post against your own history | <code>INSTALL</code></summary>

**Repo:** [charlie947/social-media-skills](https://github.com/charlie947/social-media-skills)

**What it does:** Seventeen skills for LinkedIn and video content. I installed three: a post scorer that compares a draft with your own best posts, an analytics dashboard from the LinkedIn export, and a weekly niche research brief with dated sources.

**Why it's install-worthy:** It separates "scored against real data" from "editorial opinion only" and says which one you got. MIT.

**Best for:** Founders who post on LinkedIn every week.

**Discovered via:** [@tom_doerr](https://x.com/tom_doerr/status/2109075011923329337)

</details>

<details>
<summary><strong>31. TypeSafe skills</strong> — Small judgments from the model, decisions in code | <code>INSTALL</code></summary>

**Repo:** [typesafe-ai/skills](https://github.com/typesafe-ai/skills)

**What it does:** One guidance file for building with decision models such as Jev: models that answer typed questions (pick one, yes or no, a score) with a probability, fast and cheap.

**Why it's install-worthy:** The design rule inside is useful with any model. Write each business decision as a truth table. The model answers the small questions. Your code holds the rule and the threshold. The model never writes a price or a total. MIT.

**Best for:** Anyone building scoring, routing or classification into a product.

**Discovered via:** [@DeRonin_](https://x.com/DeRonin_/status/2100917158922387537)

</details>

<details>
<summary><strong>32. Anthropic commerce-agents</strong> — The best public example of "draft, then approve" | <code>REFERENCE</code></summary>

**Repo:** [anthropics/commerce-agents](https://github.com/anthropics/commerce-agents)

**What it does:** A blueprint for shopping and merchant agents. The merchant agent stages every change and waits for a person to approve it.

**Why it's a reference:** If your agent will ever send, pay, order or delete, copy this write path: the agent drafts, a person commits. Apache-2.0.

**Best for:** Anyone designing an agent that acts on business data.

**Discovered via:** [@ClaudeDevs](https://x.com/ClaudeDevs/status/2095233745167282602)

</details>

#### Also added since April (design, motion, knowledge)

| Repo | What | Rating |
|------|------|--------|
| [emilkowalski/skills](https://github.com/emilkowalski/skills) | Motion and interface craft skills | INSTALL |
| [jakubkrehel/skills](https://github.com/jakubkrehel/skills) | Better UI surfaces, typography and colour | INSTALL |
| [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | Design taste, minimal UI, redesign of existing projects | INSTALL |
| [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | Searchable styles, palettes and font pairings | INSTALL |
| [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) | Obsidian markdown, CLI, bases and canvas | INSTALL |
| [AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo) | v2.6 adds maps, backlinks, clusters and Google API skills (see #9) | INSTALL |
| [anthropics/claude-cookbooks](https://github.com/anthropics/claude-cookbooks) | The knowledge-graph recipe: extract, resolve, assemble, query | REFERENCE |
| [anthropics/cwc-long-running-agents](https://github.com/anthropics/cwc-long-running-agents) | Default-FAIL gate and a fresh-context evaluator for long builds | REFERENCE |
| [trycompai/crm](https://github.com/trycompai/crm) | Evidence bands on facts and an agent task queue | REFERENCE |

---

### Honorable Mentions (Worth Knowing About)

| Repo | What | Why |
|------|------|-----|
| [claude-hud](https://github.com/jarrodwatts/claude-hud) | Real-time dashboard for Claude Code | Cool UI, shows context usage and agent status |
| [claude-mem](https://github.com/thedotmack/claude-mem) | Persistent memory across sessions | Good if you don't have a custom memory system |
| [awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases) | OpenClaw use case gallery | Inspiration for what to build with AI employees |
| [hyperbrowser-app-examples](https://github.com/hyperbrowserai/hyperbrowser-app-examples) | Browser automation examples | If you need AI to control a browser |
| [MoneyPrinterV2](https://github.com/FujiwaraChoki/MoneyPrinterV2) | Automated short video creation | Fun experiment, not production-grade |

---

## What I Skipped (and Why)

I tested 25+ more repos that didn't make this list. Common reasons:

- **README hype, no substance** — Great marketing, empty repo
- **Prompts disguised as skills** — Wrapping a prompt in SKILL.md doesn't make it a skill
- **Demo-only** — Works with toy data, breaks on real business data
- **Abandoned** — Last commit 6+ months ago, issues ignored
- **Duplicates** — Same concept, worse execution than something already on this list

**New in November 2026 — skipped on safety grounds.** These patterns are now common enough to name:

- **It sends your whole session somewhere** — "context compaction" and "agent memory" plugins that forward every prompt and tool result to a third-party API. Client names and keys go with it.
- **Pooled free API keys** — routers that stack the free tiers of many providers. They break provider terms and your prompts go wherever is free today.
- **Hosted bots that hold your logins** — one connected Gmail or CRM is open to every bot on the account, with no audit log and no dry run.
- **Installers piped from the web into the shell** — two repos this month also carried text written to make an AI agent install them. Read before you run.
- **Scraped contact lists and "get past bot protection" scrapers** — a legal and reputation risk, not a growth hack.
- **Famous-name hype** — a "leaked file" that never leaked, lectures credited to people who did not give them, star counts wrong in both directions. Check the repo, not the post.

---

## My Setup

For context, here's what I actually run:

- **600+ skills** installed (from the repos above + custom-built), curated down twice
- **111 AI agents** (from agency-agents)
- **4 businesses** managed through this setup
- **7-agent team** with org hierarchy and budgets
- **Daily workflows:** Email triage, content creation, client management, code reviews, financial analysis

Total monthly cost: Claude Pro subscription. That's it.

---

## How to Start (If You're New)

Don't install everything. Start here:

1. **Day 1:** Install [awesome-claude-skills](https://github.com/BehiSecc/awesome-claude-skills) — get brainstorming, debugging, verification skills
2. **Day 3:** Install [agency-agents](https://github.com/msitarzewski/agency-agents) — pick 3-5 agents relevant to your work
3. **Week 2:** Install [ai-marketing-skills](https://github.com/ericosiu/ai-marketing-skills) — if you do any marketing
4. **Week 3:** Install [jackbutcher.md](https://github.com/visualizevalue/jackbutcher.md) + [vvriter](https://github.com/visualizevalue/vvriter) — if you create content
5. **Month 2:** Build custom skills for YOUR specific workflows

The order matters. Skills first (how AI thinks), then agents (who AI becomes), then domain tools (what AI does).

---

## Updates

I'll update this monthly as I test new repos. Star this repo to stay updated.

**Last updated:** November 2026
**Repos reviewed:** 190+ (every one checked on GitHub; the INSTALL and ESSENTIAL ones installed on my machine)
**Skills installed:** 600+
**Businesses running on this stack:** 4

### Recent Additions (November 2026)
- HyperFrames — video built in HTML
- gitleaks — secrets scan before every handover ([@mdjunaidap](https://x.com/mdjunaidap/status/2119422187408851116))
- anydoc — office files to Markdown ([@firecrawl](https://x.com/firecrawl/status/2084670366803218774))
- Cloudflare security-audit skill ([@RoundtableSpace](https://x.com/RoundtableSpace/status/2112397145412091969))
- diagram-design — 45 branded diagram types ([@RoundtableSpace](https://x.com/RoundtableSpace/status/2108992207999128036))
- rea-video — reel teardown ([@rileybrown](https://x.com/rileybrown/status/2119935865933725888))
- reanimate — measured animation cloning ([@dr_cintas](https://x.com/dr_cintas/status/2119555538144911525))
- single-agent-loop-kit — fewer subagents ([@cherry_mx_reds](https://x.com/cherry_mx_reds/status/2113969070118666670))
- harness-creator ([@liangzhu_AI](https://x.com/liangzhu_AI/status/2114325601326649846))
- social-media-skills ([@tom_doerr](https://x.com/tom_doerr/status/2109075011923329337))
- TypeSafe skills ([@DeRonin_](https://x.com/DeRonin_/status/2100917158922387537))
- Anthropic commerce-agents ([@ClaudeDevs](https://x.com/ClaudeDevs/status/2095233745167282602))

### Recent Additions (April 2026)
- Postiz — social scheduler ([@heynavtoor](https://x.com/heynavtoor/status/2043966500512616510))
- Rowboat — Claude Cowork alternative ([@akshay_pachaar](https://x.com/akshay_pachaar/status/2041856590341677378))
- Open-Higgsfield-AI — image/video studio ([@ihtesham2005](https://x.com/ihtesham2005/status/2041546716806357435))
- Google Magika — file detection AI ([@_vmlops](https://x.com/_vmlops/status/2043624154646409708))
- Karpathy CLAUDE.md template ([@akshay_pachaar](https://x.com/akshay_pachaar/status/2043374229199151351))

---

## About

I'm **Dr. CA Umang Ratani** — a Chartered Accountant who traded billable hours for AI agents. I run 4 businesses from Ahmedabad, India, and most of my daily operations are handled by AI.

- Building: [Bizgenix AI Solutions](https://bizgenix.in) — AI employee systems for Indian businesses
- Teaching: Scale With AI workshops for business owners
- Managing: Virtual CEO Program (200+ companies)

This list comes from real usage, not research. Every repo here runs in my actual business stack.

**Connect:** [@umangratani](https://x.com/umangratani) on X

---

*If this saved you time, star the repo. It helps others find it.*
