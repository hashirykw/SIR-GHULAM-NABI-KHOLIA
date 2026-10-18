# Sir Ghulam Nabi Kholia · Accounting website

A multi-page site for Sir Ghulam Nabi Kholia: Cambridge O Level Accounting 7707, IGCSE Accounting 0452 and AS & A Level Accounting 9706, Karachi. Every page is one self-contained HTML file in one flat folder: styles, scripts and the photo are inside each page. No admin panel, no database.

## Files

| File | What it is |
|---|---|
| `index.html` | Home: photo folio, the double-entry desk (eight transactions posting live into ten T-accounts, a trial balance and the accounting equation), the three courses, where Paper 2 marks go missing, enrol band |
| `courses.html` | 7707, 0452 and 9706 paper by paper (9706 is the 2026–2028 syllabus), how a topic is worked through |
| `syllabus.html` | All seven O Level / IGCSE topics and all seventeen 9706 topics, with a progress tracker and a filter |
| `past-papers.html` | Every session 2018–2026 for all three courses (PastPapers.co + PapaCambridge), score log with chart, exam timer with focus mode |
| `study-room.html` | Debit/credit trainer, ratio calculator with formulae, depreciation schedule (straight line and reducing balance), principle cards |
| `about.html` | His background |
| `contact.html` | Enrolment form that opens a ready-written WhatsApp message, FAQ |
| `404.html` | Not-found page |
| `ghulam-nabi-kholia.png` | Share image for WhatsApp and social previews (1200 × 630) |
| `vercel.json`, `robots.txt`, `sitemap.xml` | Hosting and search files |

Every page also has light and dark themes, a `/` or Ctrl K search over pages, topics, principles and tools, an “Ask the desk” helper, smooth scrolling and view transitions.

## Confirm with Sir Kholia before launch

1. **WhatsApp number — needed.** No public number was found. Until one is added, every WhatsApp button opens WhatsApp with the message written and lets the visitor pick the chat. To add it, set `wa: '92XXXXXXXXXX'` and `waDisplay` in the `window.SITE` block at the bottom of every HTML file (find `wa: ''` and replace).
2. **YouTube and Facebook links.** The exact channel and page URLs weren’t available, so these currently open a search for his name. Find and replace `https://www.youtube.com/results?search_query=Ghulam+Nabi+Kholia` and the Facebook search URL with his real links.
3. **Hexis College** and **commerce faculty** come from a Hexis College poster for his O and A Level Accounts classes (2022 session). Confirm where he teaches now and add colleges if needed.
4. **Photo.** Taken from a public video frame, so it is low resolution. A sharp portrait will look much better.
5. **Fees and timings** are never shown; every such question goes to WhatsApp.
6. **Domain.** Canonical links, sitemap and robots use `https://ghulam-nabi-kholia.nexlyr.solutions`. Find and replace if you use another domain.

## Content notes

- Paper structure follows Cambridge’s 0452 syllabus for 2026 (7707 is examined the same way) and the 9706 syllabus for 2026–2028.
- The desk transactions, trainer questions, ratio defaults and principle wording were written for this site.
- Visitor progress (tracker, scores, trainer score, theme) stays in the visitor’s browser only.

## Deploy

Upload every file to the root of a GitHub repo and import it on Vercel (Framework preset: Other, no build command). `vercel.json` turns on clean URLs.

Website by Nexlyr Solutions.
