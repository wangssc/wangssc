### Hi, I'm wangssc 👋

I build **local-first** tools — software that runs on your machine, not in someone else's cloud.

**No upload. No account. No cloud.**

---

### What I'm building

| Project | What it does |
|---|---|
| **[doc-desensitizer](https://github.com/wangssc/doc-desensitizer)** | Local Word/TXT desensitizer for Chinese PII — documents never leave your disk. |
| **[crypto-scheme-audit](https://github.com/wangssc/crypto-scheme-audit)** | Offline checker for cryptography-compliance documents (GB/T 39786). |
| **[ai-security-audit-skills](https://github.com/wangssc/ai-security-audit-skills)** | Agent skills that audit what an attacker would exploit first. |
| **[creator-os](https://github.com/wangssc/creator-os)** | A local-first creator workbench — FastAPI + SQLite, single machine. |
| **[resume-tailor-skill](https://github.com/wangssc/resume-tailor-skill)** | An AI agent skill: JD → one-page A4 resume, fully offline. |
| **[dsh-delegation](https://github.com/wangssc/dsh-delegation)** | A working pattern for splitting AI work between a planner and a doer. |

---

### Why local-first

Most tools today are thin wrappers around someone else's API. Your documents, your resume, your audit findings get uploaded to a server you don't control.

I'd rather ship a smaller tool that keeps your data where it belongs.

---

### How these are built

Every project here is **single-file Python or a small FastAPI service**, standard library where possible, no telemetry, no outbound calls. They run behind a `start.cmd` next to the code — double-click, browser opens, done.

That constraint is deliberate. A tool that needs a vendor account to work is a tool that stops working when the vendor does.

`Python` · `FastAPI` · `SQLite` · `Local LLM agents` · `Cryptography compliance`
