# Team TMC Leadership Tools

Built by Rico White, Area Sales Director — Okta

Two web-based tools for the new leader intake process. Deploy both HTML files to Vercel via GitHub.

---

## Tools

### 1. tmc_questionnaire.html — 1:1 Discovery Form
A branded web form with 23 standardized discovery questions across 6 sections. Use this during or after each 1:1 conversation.

**Sections covered:**
- Background and Journey
- What Drives You
- How You Work Best
- What You Need From Me
- The Business
- Trust and Transparency

**Features:**
- Autosaves to browser localStorage as you type
- Copy All Responses button formats everything for Claude analysis
- Download as .txt for per-rep file storage
- Print-friendly layout

---

### 2. tmc_analyzer.html — AI Transcript Analyzer
Paste a Zoom transcript and Claude automatically extracts answers to all 23 questions. No manual note-taking required.

**Workflow:**
1. Run your 1:1 on Zoom with transcription enabled
2. Copy the transcript from Zoom after the call
3. Open the analyzer, enter the rep name and date
4. Paste the transcript and hit Analyze with Claude
5. Claude maps the conversation to all 23 questions
6. Copy the profile or download it as a .txt file

**Requires:** Anthropic API key (stored in your browser only, never on a server)

---

## Pattern Analysis

After completing all 6 rep 1:1s, use the Copy All button on each profile and paste all six into a single Claude conversation. Ask Claude to identify patterns across the team — who needs autonomy vs coaching, shared frustrations, career ambitions, coaching style preferences, and blockers to quota attainment.

---

## Deployment

1. Create a GitHub repo (suggested name: team-tmc-tools)
2. Push both HTML files and this README
3. Connect the repo to Vercel
4. Vercel auto-deploys on every push

---

## File Structure

```
team-tmc-tools/
  tmc_questionnaire.html
  tmc_analyzer.html
  README.md
```

---

*okta · Team TMC · Rico White, Area Sales Director · 2026*
