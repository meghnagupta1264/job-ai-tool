# ApplyAI — AI-Powered Job Application Generator

ApplyAI takes your CV and up to 5 job descriptions, and generates
perfectly tailored cover letters and cold emails in seconds —
streamed live, downloadable as a Word doc.

**Live demo → [Try it here](https://meghnagupta1264.github.io/job-ai-tool/)**

## What it does
- Upload your CV (PDF or text) + paste job descriptions or URLs
- Choose your output: Cover Letter, Cold Email, or both
- Pick a tone: Professional, Confident, Enthusiastic, or Concise
- Watch the AI generate content in real-time via streaming
- Expand/collapse individual outputs in the live console
- Download everything as a formatted .docx with one click

## How it's built
- **Frontend** — Vanilla HTML/CSS/JS, zero frameworks, zero build step
- **Backend** — Node.js + Express proxy server (hides the API key)
- **AI** — Anthropic Claude Sonnet via streaming API
- **PDF parsing** — Claude's native document API reads your CV directly
- **Export** — docx.js generates Word documents client-side in the browser
- **Hosting** — Frontend on GitHub Pages, backend on Render

## Why I built this
Most job application tools are either paywalled, generic, or don't
respect the nuance of your actual experience. This one reads your
real CV and the actual job description — and writes something that
sounds like you, not like a template.
