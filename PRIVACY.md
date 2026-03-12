# Privacy Policy — Web Text Highlighter

**Last updated: March 2026**

## Overview

Web Text Highlighter is a browser extension that helps users highlight text, detect idioms, and analyze vocabulary on webpages. This policy explains what data is handled by the extension and how.

---

## Data We Do NOT Collect

We do not operate any backend servers. We do not collect, store, transmit, or share any of your personal data. This includes:

- Browsing history
- Highlighted text or annotations
- API keys
- Personal identifiers of any kind

---

## Data Stored Locally on Your Device

The following data is stored exclusively in your browser's local storage (`chrome.storage.sync`) and never leaves your device except as described below:

| Data | Purpose |
|---|---|
| Highlight colors, styles, and annotations | To restore your highlights when you revisit a page |
| Idiom database (CSV) | To detect idioms as you browse |
| AI provider settings and API key | To send requests to your chosen AI provider |
| Notion API key and database ID | To export highlights to your Notion workspace |
| Anki settings | To export flashcards to your local Anki installation |
| Translation provider settings | To translate selected text |
| Learning mode progress | To track spaced repetition progress locally |

---

## Third-Party API Calls

When you use AI explanation, translation, or Notion export features, the extension sends selected text directly from your browser to the third-party service you have configured. These requests:

- Use **your own API key**, which you provide in the extension settings
- Are made **directly from your browser** to the third-party service
- Are **not routed through our servers** — we have no visibility into these requests

Relevant third-party services and their privacy policies:

- [OpenAI](https://openai.com/policies/privacy-policy)
- [Anthropic](https://www.anthropic.com/privacy)
- [Google Gemini](https://policies.google.com/privacy)
- [DeepSeek](https://www.deepseek.com/privacy)
- [Mistral AI](https://mistral.ai/privacy/)
- [Groq](https://groq.com/privacy-policy/)
- [OpenRouter](https://openrouter.ai/privacy)
- [Notion](https://www.notion.so/privacy)
- [Google Translate](https://policies.google.com/privacy)
- [DeepL](https://www.deepl.com/privacy/)

---

## AnkiConnect

When exporting to Anki, the extension communicates with AnkiConnect running locally on your machine (`localhost:8765`). No data leaves your device through this connection.

---

## PDF Files

When you open a PDF in the extension's built-in viewer, the file is accessed locally in your browser. PDF content is not uploaded to any server.

---

## Permissions Explanation

The extension requests the following browser permissions:

- **activeTab** — To inject the highlighting toolbar on the current page
- **contextMenus** — To add a right-click highlight option
- **storage** — To save your settings and highlights locally
- **tabs** — To detect the current page type (e.g., PDF) and open the PDF viewer
- **webNavigation** — To restore highlights when navigating between pages

---

## Children's Privacy

This extension is not directed at children under 13 and does not knowingly collect any data from children.

---

## Changes to This Policy

If this policy is updated, the new version will be published at this URL with a revised date.

---

## Contact

For questions or concerns, please open an issue on [GitHub](https://github.com/ShiyangZheng/web-text-highlighter) or contact via [shiyangzheng.top](https://shiyangzheng.top).
