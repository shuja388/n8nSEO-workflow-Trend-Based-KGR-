# n8nSEO-workflow-Trend-Based-KGR-
n8n made workflow SEO trend based keywords and KGR )keywords golden ratio ) finding  are not difficult  now
# n8n SEO Content Automation – Trend-Based KGR Keyword Finder  
**32+ Daily Low-Competition Blog Ideas → Google Sheets + Gmail Alert**  
**Fully Automated | No Manual Work | Free to Use**

A powerful, daily-running n8n workflow that turns a few seed keywords into 28+ high-volume, low-competition (KGR ≤ 0.25) blog post ideas with AI-generated SEO titles, meta descriptions, outlines, search intent, volume, and KGR — all saved to Google Sheets with a beautiful Gmail summary.

Perfect for bloggers, agencies, and SEO professionals who want fresh, rank-ready content ideas every single day.

### Features
- Daily execution (easily changeable)
- Real Google Trends data via SerpAPI
- Automatic KGR calculation & filtering
- GPT-4o generates perfect SEO titles, meta descriptions, and 5× H2 outlines
- All data appended to Google Sheets
- One HTML email alert with total rows + top keyword + clickable sheet link
- No secrets in the JSON (uses environment variables)

### Screenshot
![Workflow Overview](<img width="1190" height="488" alt="SEO workflow full overview" src="https://github.com/user-attachments/assets/dbe2557b-0aaf-4fc6-98b2-2e2fc3073cc9" />
)  
![Google Sheet Result](<img width="1194" height="469" alt="google sheet" src="https://github.com/user-attachments/assets/a6f31ffc-6ee8-4bba-91fe-9f1b280db1bb" />
)  
![Gmail Alert](<img width="1276" height="299" alt="Gmail conformation" src="https://github.com/user-attachments/assets/81e4a0e8-b46f-4c2c-bb34-4b07b28d0db6" />
)

### How to Install (2 minutes)

1. Import `workflow.json` into n8n
2. Add your credentials:
   - SerpAPI key
   - OpenAI key
   - Google Sheets OAuth2
   - Gmail OAuth2
3. Set environment variables (Hostinger VPS → `.env` file):
   ```env
   SERPAPI_KEY=your_serpapi_key_here
   OPENAI_API_KEY=your_openai_key_here
   GOOGLE_SHEET_ID=your_sheet_id_here
   ```
4. Update the Google Sheets node with your sheet ID (or use `$env.GOOGLE_SHEET_ID`)
5. (Optional) Change seed keywords in the “Set Seeds” node
6. Click **Activate** → runs daily

### Google Sheet Template (Copy This)
https://docs.headers.google.com/spreadsheets/d/1MN2pLEcIqgg_7-qHGWjsPzhBv0R4iAbAEFRhY/copy

Headers (Row 1):
```
Keyword | Title | Meta Description | Outline | Search Intent | Volume | KGR
```

### Video Demo (Live Execution)
[Watch the full live demo](https://files.catbox.moe/grm8ue.mp4)

### Future Upgrades
- Real allintitle KGR
- WordPress auto-post
- Google Docs auto-creation
- CSV + Google Drive backup

Made with ❤️ by Shujaat Ali Khan  
