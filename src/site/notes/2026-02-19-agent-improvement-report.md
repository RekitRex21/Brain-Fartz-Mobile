---
dg-publish: true
---
# [2026-02-19] Agent Research Improvement Report

Here's an updated, comprehensive report on improving your Obsidian Vault AI agent for periodic AI market research. This incorporates the exact prompt you used (with minor typo corrections for clarity: "Do a deep research for the last 30 days for new AI stocks, AI tools, Local Ollama models, insiders buying AI stocks, up and coming tech companies and going public for trading. Use your researcher skill. Create a new folder to start housing these notes. Use your writing-pro skill to write a comprehensive note. Name the folder last 30 days and add today's note to the folder.").

The original agent output was a decent headline aggregator but felt "weak" due to factual slips (e.g., Gemini context window overstated, release dates off), lack of synthesis, and minimal sourcing. Recent developments (as of February 19, 2026) show the AI space remains explosive: frontier model races (e.g., Anthropic's Claude Opus/Sonnet 4.6 upgrades, OpenAI's GPT-5.3 Codex agentic coding push), open-source momentum (GLM-5 topping local reasoning leaderboards via Ollama), IPO speculation (OpenAI/Anthropic/SpaceX/xAI merger impacts), and insider signals (e.g., Salesforce/SentinelOne buying amid AI disruption fears). Your prompt captures the right categories but needs tightening for accuracy, depth, and Obsidian integration.

### Original Scoring Recap (Still Applies, 1–10 Scale)
- **Accuracy & Factual Alignment** — **6/10**  
  Good on GLM-5 launch (~Feb 11, 2026, 744B MoE topping open-source reasoning), xAI-SpaceX merger (early Feb 2026, ~$250B xAI in combined entity), and insider notes (Salesforce/ValueAct ~$25M+, SentinelOne director ~$600k). Errors persist (e.g., no 2M Gemini 3 Pro—it's 1M; Claude Opus 4.5/4.6 from Nov 2025/Feb 2026, not fresh "last 30 days").

- **Timeliness & Currency** — **7/10**  
  Captures Feb momentum (GLM-5 debut, Ollama support for new MoEs like Kimi K2.5/GLM-5), but "last 30 days" claims miss older releases and ignore Jan/Feb 2026 waves (e.g., Anthropic's Sonnet 4.6 Feb 17, OpenAI agentic tools).

- **Depth & Insight** — **5/10**  
  Headline dump; no "so what?" on implications (e.g., GLM-5's agentic focus + Ollama integration accelerating local adoption vs. cloud costs; IPO delays amid $100B+ funding rounds; insider buying as contrarian signal in software selloffs).

- **Actionability & Usefulness** — **6/10**  
  Watchlist items (IPO filings, Ollama testing) are solid for your workflow, but no prioritization, risks (e.g., regulatory/China momentum), or vault ties.

- **Overall Score** — **6/10**  
  Useful snapshot but needs rigor to become reliable intel.

### Recommendations & Action Plan to Make Your Agent Smarter
Prioritize these to push toward 9+/10 outputs—structured, sourced, insightful, and vault-optimized. Implement via prompt updates.

1. **Mandate Strict Sourcing, Date Verification & "Last 30 Days" Precision** (Highest Impact)  
   The prompt's "last 30 days" is good but leads to loose framing.  
   **Action to take:** Add to your core agent prompt:  
   "Conduct deep research strictly for the last 30 days (from today's date backward). For every claim (releases, funding, insider trades, features), cite 2+ independent sources with exact dates/links (e.g., company blogs, Reuters, Bloomberg, Hugging Face, SEC filings). Flag rumors/speculation. Verify model release dates against official announcements—do not assume recency."

2. **Enforce Obsidian-Optimized Folder/Note Structure** (High Impact)  
   Your prompt already instructs folder creation—build on it for consistency.  
   **Action to take:** Expand the prompt section:  
   "Create a new folder named 'AI Market Research - Last 30 Days [Current Month-Year]' (e.g., 'AI Market Research - Last 30 Days Feb-2026'). Inside it, generate a comprehensive note named '[YYYY-MM-DD] AI Market Snapshot.md' with today's date. Use Obsidian-friendly formatting: headings, tables for comparisons (e.g., model benchmarks), Dataview-compatible fields if possible, and internal links to prior notes. Append this note to the folder and suggest linking to a master MOC for AI research."

3. **Require Required Sections for Depth & Synthesis** (High Impact)  
   Force beyond bullets.  
   **Action to take:** Update prompt to mandate this template:  
   - Executive Summary (synthesize key trends, e.g., open-source surge vs. frontier races)  
   - Verified Updates by Category (use tables; include dates/sources)  
     - New AI Stocks & IPO/Going Public Developments  
     - New AI Tools & Releases  
     - Local Ollama Models & Updates  
     - Insider Buying/Selling in AI Stocks  
     - Up-and-Coming AI Startups & Funding  
   - Implications & Analysis ("So what?": e.g., how GLM-5 impacts local coding agents, IPO risks/delays)  
   - Risks & Watch Triggers (e.g., regulatory, compute shortages)  
   - Actionable Recommendations (prioritized for your use, e.g., "Test GLM-5 on Ollama for reasoning tasks")  

4. **Incorporate Researcher & Writing-Pro Skills Explicitly** (Medium-High Impact)  
   Lean into the prompt's "Use your researcher skill" and "writing-pro skill."  
   **Action to take:** Add:  
   "Act as an elite AI market researcher: cross-reference multiple sources, quantify where possible (e.g., benchmarks, valuations), and write in professional, concise prose with multi-faceted reasoning. Avoid hype; balance optimism with risks."

5. **Add Recency Filters & Category Balance** (Medium Impact)  
   Ensure China/open-source coverage (e.g., GLM/Kimi/DeepSeek).  
   **Action to take:** Prompt addition:  
   "Prioritize frontier + open-source balance. Include China models (GLM, Kimi, DeepSeek) as they often lead local reasoning/coding. Frame all as 'since [30 days ago date]'."

6. **Iterate & Version Control Prompts in Vault** (Ongoing)  
   **Action to take:** Create a vault note "AI Agent Prompt Versions.md". Start with v2 incorporating 1–5. Run your prompt monthly, score outputs, refine.

### Suggested Next 30-Day Prompt (Copy-Paste Ready)
Use this refined version every ~30 days (update date as needed):

"Do a deep research for the last 30 days (from today backward) for new AI stocks, AI tools, Local Ollama models, insiders buying/selling AI stocks, up-and-coming tech companies/startups, and companies going public/IPO developments. Use your researcher skill to verify facts with multiple sources and dates. Create a new folder named 'AI Market Research - Last 30 Days [Month-Year]' to house these notes. Use your writing-pro skill to write a comprehensive, professional note in this structure: Executive Summary, Verified Updates by Category (tables where useful), Implications & Analysis, Risks & Watch Triggers, Actionable Recommendations. Name the note '[YYYY-MM-DD] AI Market Snapshot.md' and add it to the folder. Flag rumors and prioritize open-source/local momentum alongside frontier developments."

Implement these changes—your agent should produce much stronger, vault-ready outputs.
