# Archive Briefs — Telegram Drop `Audit_Projects_2026-10-07`

Every item in **section A** below is carded on the portfolio (`Kareem_Ahmed_CV.html`, `Kareem_Ahmed_CV_v2_MISSION.html` and `Kareem_Ahmed_CV_GENERAL.html`) and listed under the catalog group **Archive Builds · Local**; those cards link back to this file for the long notes. Sections B and C document local copies, iterations and duplicates that were already covered by an existing card.
Second pass after the 42 cloned GitHub repositories. Source: two downloaded drops
(`Desktop\` = 17 folders, `Downloads\` = 23 folders → 23 unique projects after de-dup,
~156 MB, `node_modules`/`.git` ignored for stats). Machine-readable scan: `_analysis.txt`.

**Decision key:** `NEW CARD` = added to the portfolio · `EXISTING` = same project already carded
(local copy is an iteration) · `DUP` = byte-close copy of another folder · `BRIEF ONLY` = documented here, not carded.

---

## A. New to the portfolio — 10 cards

### `RAG` — Medical RAG · Herpes Zoster (simplified card)
Retrieval-augmented medical assistant: `SRC/` holds the pipeline (chunker → embeddings →
vector store → Streamlit `app.py`) driven by Ollama/Mistral, plus `Reports/` with architecture,
code-review, test and evaluation reports and a hackathon presentation. `Front-dev/` is a
React + Vite front end. Cards ship **simplified** (one shot of the hackathon deck + short copy)
per scope decision. **Asset:** `rag-hackathon.jpg`.

### `Library_Management_System` — Oracle Library System
Faculty of AI database course project: Oracle SQL/PL/SQL + Oracle Forms + Oracle Reports over
six tables (authors, categories, books, members, borrowings, details) with triggers, sequences,
master–detail forms and a static report. Ships an automation suite (`RUN_ALL.ps1`: install Oracle XE →
build → 11 auto tests `[PASS]/[FAIL]`) plus HTML runtime/workflow guides. **Asset:** `library-system.jpg`
(`WORKFLOW_VISUAL_GUIDE.html`).

### `orientation-dashboard` — Volunteer Reception Analytics
Arabic RTL analytics board for volunteer reception: centres, satisfaction, tasks and availability.
Plain HTML/CSS/JS with ECharts + word cloud, Tabulator, XLSX import, jsPDF/html2canvas export;
atmospheric grid/noise layers and the house palette (`#03263F` / `#FBAE42`). **Asset:** `orientation-dashboard.jpg`.

### `kobo-github` — Kobo Referral Bridge (Flask)
153 KB single-page referral form plus `server.py`: a Flask + CORS proxy that converts JSON posts to
OpenRosa XML and submits them to KoboToolbox (`/submission`), deployed via `render.yaml`.
**Asset:** `kobo-github.jpg`.

### `PROG2` — OOP Teaching Kit (21 HTML guides)
Self-contained Arabic/English OOP courseware: complete OOP guide, dual-screen variants, hard-mode
library system, inheritance/classes/structures practice, model answers and three solved exam sheets
(~20k lines of HTML/CSS/JS, all printable). **Asset:** `oop-guides.jpg`.

### `BASIC_NEEDS_SMART_SYSTEMS` — Needs & Aid Sync Engine (Apps Script)
`SYSTEM_COMPLETE.gs` (~1,010 lines) + 10 modules: reads one master sheet of qualifying families and
distributes rows per aid item and per centre (Drive folders), keeps every view in sync within a
minute (update-by-case-id, never rewriting sheets), runs a self-healing audit every minute and
manages water-connection approval/classification tabs. **Asset:** glyph card.

### `NTI_Summer_Training_Guide` — NTI Summer Training Handbook
57 Markdown files / ~6,100 lines documenting the NTI × ITIDA summer program: overview (4 weeks,
120 h, 15,000 students/year), all 8 tracks with modules, skills, tools and a study roadmap per track.
**Asset:** glyph card.

### `kobo_automation_tool` — Kobo → Excel Automation (Python)
`kobo_automation.py` (Selenium + pandas + openpyxl): pulls Kobo submissions through Chrome, normalises
them and writes `kobo_data.xlsx` on a schedule, with retry rules and a `kobo_automation.log`.
**Asset:** glyph card.

### `templates` — Documents Automation Toolkit
Office templates (purchase request, disbursement request, case sheet `.docx`) + `add_placeholders.py`
and `analyze.py` (python-docx placeholder injection and structure analysis) + Apps Script HTML partials
for a document service. **Asset:** glyph card.

### `مشروع تخرج فارما سينسAI` — PharmaSense AI (graduation project)
Deliverables for an AI pharmacy assistant: drug search, interaction checks, document/image analyzer,
list organizer, dashboard with statistics, dark mode — documented in `PharmaSense_AI_Delivery.docx`
+ PDF with 9 full app screenshots (1366×768). **Asset:** `pharmasense.jpg` (dashboard screenshot).

---

## B. Already carded — local copies are iterations (no new cards)

### `RequestFlow` — Requests management (Menoufia Life Makers)
3 of 4 files differ from the clone (README/index refresh). Existing card stands.

### `dashboard` — Volunteer acquisition analytics
20 files, README identical in intent to `dashboard_GAZB_MENOUFIA` (7 pages, 14 live filters, Apps Script
backend + Pages front end) but **every file differs in content** → newer iteration of the same card.

### `dashboard-report` — Dashboard report package
`dashboard_final.html` (93 KB) + `Dashboard_Report.pdf` (1.2 MB) + `report.html` — an older export of the
carded `dashboard_final` build. Documented only.

### `donation-app` — Donation collection app
6 of 7 files differ from the clone (deployment docs + app.js/style refresh). Existing card stands.

### `etganen14` — Etganen 14 campaign registration
2 of 3 files differ (newer `index.html`). Existing card stands.

### `kobo-dashboard` — Activations & registrations KPI board
3 of 4 files differ (sheet API refresh). Existing card stands.

### `media-team` — Media team recruitment
Folder replaced the single `Code.gs` of the `Media_unielm_report` clone with a full build
(`index.html` + `template.html` + `Code.gs`) → same project as the existing card.

### `nti-learning-platform` — NTI learning platform
1 of 4 files differs (`data.js` content update). Existing card stands.

### `CAMP_ITUELM` — Madarat / Roots Camp registration
Byte-identical to the clone (12/12 files) + `screenshot.png`. Nothing to do.

### `final-SKIN-VISION` — SKIN-VISION working copy
Same repository as the carded `SKIN-VISION` (identical `app.py`/`src/`), plus local `.env`, `.git`,
`__pycache__` and a built Chroma `vector_db_store/`. Nothing new to show.

### `sehatak-health-forms` — Sehatak health forms
8 of 24 files differ: 16 Arabic form pages, an `AI style/` variant, `create_shortcuts.ipynb/.py`
and offline utils. Existing card stands.

---

## C. Duplicates and non-projects

### `CAMP_ITUELM_repo` — duplicate
Near-copy of `CAMP_ITUELM` (same README, no `screenshot.png`). Skipped.

### `APP` — Calorie & Nutrition Tracker Pro (AI Studio prompt)
A 374-line specification written for Google AI Studio (design system, palette, RTL/dark modes,
localStorage data model). Prompts are not shipped builds — documented here, not carded.

---

## D. Decks & reports — Telegram drop `Audit_Documents_2026-10-07` (10 cards)

Documents-only drop (535 files · 808 MB). The ten entries below are carded in all three editions
and listed under the catalog group **Decks & Reports · Documents**; full audit: `DOCUMENT_BRIEFS.md`
in the drop.

### `AI_Data_Analysis_Mastery.pptx` — Data Analysis with AI · Ministry Playbook
Arabic briefing deck: *تحليل البيانات باستخدام الذكاء الاصطناعي — دليل الممارس الذكي لتحليل
البيانات في وزارات (2024–2026)*. 90-minute session, 60 slides of content, 30 applied exercises,
Excel-to-Python workflow. **Asset:** `deck-data-ai.jpg`.

### `AI_Mastery_Blueprint.pptx` — AI Mastery Fundamentals · Course Blueprint
15 slides: *من الصفر إلى هندسة الأوامر واختيار النموذج المناسب* — prompt engineering, model
selection and a fundamentals→application track for a partner institution's teams.
**Asset:** `deck-ai-mastery.jpg`.

### `Strategic_Training_Analysis.pptx` + `Strategic_Training_Impact` (6 revisions) — Program Evaluation
Evaluation pair: a 10-slide analytical report (impact measurement, content-quality scoring,
strategic recommendations for trainers) and a 13–15-slide impact deck (*تحويل الطاقات التطوعية إلى
كفاءات مؤسسية*) in six successive versions. **Asset:** `deck-training-eval.jpg`.

### `The_Growth_Blueprint.pptx` (+ `.pdf`) — Leadership Pipeline · Strategic Impact Report
Version-two impact report for *مشروع إعداد القادة: من التأسيس إلى التأثير المستدام* — measurement
framework and strategic recommendations for the association's development file (13 slides).
**Asset:** `deck-leadership.jpg`.

### `Technical_English_Blueprint.pptx` — The Technical English Playbook
Version 1.0, *mastering the language of engineering*: a functional toolkit for articulating
mechanics, materials and superior design (15 slides). **Asset:** `deck-technical-english.jpg`.

### `الذكاء_الاصطناعي_في_التصميم_والمونتاج2.pptx` (+ simplified cut) — AI in Design & Editing
28-slide Arabic deck (full and simplified) on using AI as a creative co-pilot for identity work,
video and content production, written for non-specialists. **Asset:** `deck-ai-design.jpg`.

### `الدليل التشغيلي للقوافل الطبية.docx` — Medical Convoys · Operations Manual
Arabic SOP for the medical convoys of the Menoufia medical file: planning, execution and
follow-up steps that standardise how services reach the neediest villages.

### `تقرير_Teachable_Machine.docx` (+ `بلا عنوان.docx`) — Teachable Machine · Vision Report
Report for a published image-classification model (Teachable Machine link included) plus field
notes on lighting, white balance and sample coverage and how each problem was solved.

### `Guide_ Using Claude Code with a Free Proxy.docx` — Claude Code & MCP · Field Guide
Five free MCP servers for Claude Code (search, browser control, scraping, image generation) with
install steps, plus proxy notes for running the toolchain without a paid plan.

### `presentation_EN.md` + `presentation_AR.md` + `pitch_1min.md` — Life Makers Dashboards · Presentation Pack
EN/AR technical walkthrough of the two Life Makers Menoufia dashboards (single merged Apps Script
backend, one request per page, Arabic-first RTL) plus a one-minute pitch — 1,291 volunteers, five
analytical pages, 30 ECharts visualisations.
