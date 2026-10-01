# Tareekh: Court Case Monitoring for District Courts, High Courts and the Supreme Court


<div align="justify">

![Tareekh: case diary for advocates](docs/img/banner.jpg)

<p align="center"><a href="https://github.com/advocatesudippatra-spec/tareekh-court-case-monitoring/raw/main/Tareekh-2.4.apk"><img src="docs/img/download-button.png" alt="Download Tareekh 2.4 for Android (APK)" width="340"></a></p>

<p align="center">Tap the button on your Android phone to download the app directly · <a href="docs/Tareekh-Screen-Guide.pdf">Screen guide (PDF)</a> · <a href="docs/Tareekh-Features.pdf">Features (PDF)</a></p>

**Tareekh** (*tareekh*, the date of a hearing) is an Android case diary for advocates. It keeps every matter you appear in, in any district court in India, any of the 25 High Courts or the Supreme Court, and does the tiring part of practice for you: it finds each next date on eCourts, files the court's orders in a folder for every case, reminds you of hearings and fees, puts every date in your Google Calendar, and lets you send your client a WhatsApp reminder in one tap. It reads summonses, orders and eCourts screenshots with the phone's camera (and, if you wish, with an AI service using your own API key), and imports your whole eCourts app case list at once. Cases are searched **inside Tareekh** (district courts, High Courts and the Supreme Court), and **every order of every case is kept on your phone**, so it can be read even when the internet is off. With an AI service connected, it also **explains each order in simple terms** (English, Bengali or Hindi), tells you **where an appeal lies and by when**, and **answers your questions** about the order.

Tareekh works with the **public** case status pages of eCourts, the High Courts and the Supreme Court from inside the app: you choose the court, case type, number and year on Tareekh's own screen, the court's CAPTCHA picture is shown there, you type the answer, and the case opens in Tareekh. There is no need to visit the court's website yourself (it can still be seen with *Court's page*). Tareekh is not affiliated with eCourts, NIC or any court.

**Website:** https://advocatesudippatra-spec.github.io/tareekh-court-case-monitoring/ · **Guide (every feature, and every screen explained with arrows):** [`docs/guide.html`](docs/guide.html) · PDF: [screen guide](docs/Tareekh-Screen-Guide.pdf), [features](docs/Tareekh-Features.pdf) · **Download the app:** [Tareekh-2.4.apk](https://github.com/advocatesudippatra-spec/tareekh-court-case-monitoring/raw/main/Tareekh-2.4.apk)

`#Tareekh` `#CaseDiary` `#eCourts` `#CourtCaseStatus` `#CauseList` `#DistrictCourt` `#HighCourt` `#CalcuttaHighCourt` `#SupremeCourtOfIndia` `#LegalTech` `#AdvocateApp` `#LawyerApp` `#IndianLaw` `#NextDate` `#HearingReminder` `#CourtOrders` `#AndroidApp` `#PatrasLawChambers`

**Contents:** [What's new](#whats-new-in-24) · [Your day](#your-day-with-tareekh) · [How it works](#how-it-works) · [Features](#features) · [Screen guide](#screen-guide) · [Download and install](#install) · [Your data](#your-data) · [Copyright](#copyright) · [Questions](#questions) · [About](#about-patras-law-chambers)

---

## What's new in 2.4

**AI for whole cases, and for finding cases, at the lowest AI cost.** Every order is read **on the phone**, straight from the PDF (typed orders need no OCR; only scanned pages are read by OCR), kept as text, and indexed on the phone by keywords and by meaning. So only the passages that matter are sent to the AI service you connected.

- **Case synopsis**: a date-wise synopsis of the whole case from all its saved orders, in English, Bengali or Hindi. Tareekh shows the size and AI cost **before** it runs; each order is summarised once and kept, so later updates cost only the new orders.
- **Ask about this case**: questions about the whole case; only the 5 to 8 matching passages of the orders are sent, and every point names its order date.
- **Ask AI to find a case**: in your own words ("CS 213819/26 Bankshall, can't find it") or with a summons attached. Tareekh checks your saved cases first ("Already in your cases" or "New case"), suggests the exact searches as buttons, and gives tips for cases hard to find.
- **Ask AI about my cases**: "My High Court matters this month", "Lower court hearings next week"; the answer and the cases, ready to open.
- **Cause lists in plain words**: "Calcutta Original Side tomorrow" opens that list.
- **Lower cost everywhere**: Explain, Appeal and Ask on an order now send text only, without page pictures; an optional **economy model** can do the summaries.

| Case AI on a case | Cost before the synopsis | The synopsis | Ask about this case |
|:-:|:-:|:-:|:-:|
| <img src="docs/guide/new24-card.png" width="200"> | <img src="docs/guide/new24-plan.png" width="200"> | <img src="docs/guide/new24-syn.png" width="200"> | <img src="docs/guide/new24-ask.png" width="200"> |

| Ask AI to find a case | The case, found | Ask AI about my cases | Cause lists in plain words |
|:-:|:-:|:-:|:-:|
| <img src="docs/guide/new24-search.png" width="200"> | <img src="docs/guide/new24-find.png" width="200"> | <img src="docs/guide/new24-cases.png" width="200"> | <img src="docs/guide/new24-cause.png" width="200"> |

**Readable guide to 2.4:** [What's new in 2.4 (PDF)](docs/Tareekh-Whats-New-2.4.pdf) · [web page](docs/whats-new-2.4.html). *(Made-up example cases.)*

## What came in 2.3

**Check a case's next date without opening the court's website.** Every saved case now has **Check here** next to **Check on eCourts** (which stays exactly as before):

- **Check here**: Tareekh fills in the court's page out of sight (by CNR, else case number, else party name) and shows **only the court's CAPTCHA**. Type it, and the case is **updated in Tareekh**: next date, purpose, stage and hearings, **new orders saved** in the case's folder, and the calendar entry moved. A one-line summary says what changed, e.g. *"Next date Thu, 29 Oct 2026 · For Evidence · 2 new orders saved"*.
- **Check all here**: on the Notes tab (and in the 6:30 pm notification), goes through all the hearings to be checked, one after another: as soon as one case is updated, the next case's CAPTCHA appears. At the end: *"3 checked · 2 updated · 1 no change"*.
- Works for **district courts, High Courts and the Supreme Court**. If a court's site is down or needs a choice, Tareekh says so; **Skip** moves on, and **Show the court's page** opens it.

| Check here on a case | Check all here | Only the CAPTCHA | The case, updated | All checked |
|:-:|:-:|:-:|:-:|:-:|
| <img src="docs/guide/new23-detail.png" width="160"> | <img src="docs/guide/new23-notes.png" width="160"> | <img src="docs/guide/new23-cap.png" width="160"> | <img src="docs/guide/new23-s2.png" width="160"> | <img src="docs/guide/new23-done.png" width="160"> |

**Readable guide to 2.3:** [What's new in 2.3 (PDF)](docs/Tareekh-Whats-New-2.3.pdf) · [web page](docs/whats-new-2.3.html). *(Made-up example cases.)*

### How to check a case here
1. Open a case and tap **Check here** (or tap **Check here** on a case in the Notes tab).
2. Type the CAPTCHA shown and tap **Search**.
3. Read the summary: the case, its calendar entry and its orders are already updated.
4. In the evening, tap **Check all here** (Notes tab, or the 6:30 pm notification) and type each CAPTCHA as it comes.

## What came in 2.2

**AI help for every court order.** Each order saved under a case now has a **⋮** menu: *Open*, *Share*, and three new items that use the AI service you connect in Settings (Google Gemini, OpenAI, Claude, Qwen or Kimi, with your own API key):

- **Explain in simple terms**: what the court decided, what happens next and what the client must do, in **English, Bengali or Hindi**. Share it with the client on WhatsApp. Explanations are kept on the phone and open again without internet.
- **Appeal: where and by when**: the remedy (appeal, revision, intra-court appeal, SLP…), **the court where it lies**, the provision, **the limitation period and the last date** (with days left), time excluded by law and other remedies. **Add deadline to calendar** in one tap.
- **Ask about this order**: a chat about the order, with follow-up questions; answers point to the order's own words.

If no AI service is connected, Tareekh says **"Connect an AI service first"** and opens Settings; Open and Share always work. *AI can be wrong, especially on forum and limitation: treat the Appeal screen as guidance and verify before filing.*

| The ⋮ menu on an order | Explain in simple terms | Appeal: where and by when | Ask about this order |
|:-:|:-:|:-:|:-:|
| <img src="docs/guide/new-menu.png" width="200"> | <img src="docs/guide/new-explain.png" width="200"> | <img src="docs/guide/new-appeal.png" width="200"> | <img src="docs/guide/new-ask.png" width="200"> |

| In Bengali (or Hindi) | No AI connected yet | Connecting an AI service |
|:-:|:-:|:-:|
| <img src="docs/guide/new-bn.png" width="200"> | <img src="docs/guide/new-noai.png" width="200"> | <img src="docs/guide/new-settings.png" width="200"> |

**Readable guide to 2.2, every screen with numbered arrows:** [What's new in 2.2 (PDF)](docs/Tareekh-Whats-New-2.2.pdf) · [web page](docs/whats-new-2.2.html). *(The pictures use a made-up specimen order.)*

### How to use the order features
1. **Settings › Reading with AI (optional)**: choose the service and paste your API key.
2. Open a case; under **Orders**, tap **⋮** next to an order.
3. Choose **Explain in simple terms**, **Appeal: where and by when** or **Ask about this order**; switch with the tabs at the top.
4. Share the explanation with your client, or tap **Add deadline to calendar** on the Appeal screen.

## What came in 2.1

**1. Search inside Tareekh: no need to visit the court's website**

| Search in Tareekh | The CAPTCHA, in Tareekh |
|:-:|:-:|
| <img src="docs/guide/new-form.png" width="220"> | <img src="docs/guide/new-captcha.png" width="220"> |

- For **district courts, all 25 High Courts and the Supreme Court**, search from Tareekh's own screen in four ways: **case type + number + year**, **party name + year**, **filing number** (Supreme Court: **diary number**), or **CNR**.
- **Case types are chosen from lists**: every High Court bench's own list (WPA, CRR, FMA…), the Supreme Court's list, and each district court's own list (read from eCourts the first time a court is used, then remembered).
- The court's **CAPTCHA picture is shown in Tareekh**; type the answer and tap Search. The case opens on Tareekh's screen, or a list of matching cases to tap. Tap **Save to My Cases (with orders)** to keep it.
- *Court's page* (top right) shows the court's own website at any time, if you want to see it.

**2. Every order, on your phone, even without internet**
- Something the eCourts app does not do for you: once a case is saved from the court's page, **all its orders are downloaded** into a folder for that case, and new orders are added at every check. They open any time, **even when the internet is off**.

**3. Better reading of summons, and optional AI reading with your own API key**
- The phone now reads case numbers written like `CS/ 213819/26`, the person summoned (*To.*), the complainant, and short Act names (BNS, BNSS, BSA, IPC, CrPC, NI Act…).
- **Optional:** in *Settings › Reading summons with AI*, choose **Google Gemini, OpenAI (ChatGPT), Claude, Qwen or Kimi** and paste your **API key** from that service. Every summons, notice, order or WhatsApp photo you share or upload is then also read by that AI, which handles poor photos, handwriting and unusual layouts far better. The phone's own reading still fills anything the AI leaves out. It is **off by default**; the AI service bills your own account.

### How to use the new search
1. Open **Search** and tap **District courts**, **High Courts** or **Supreme Court**.
2. District courts: choose the court (state, district, court complex). High Courts: choose the High Court and bench/side.
3. Under **Search in Tareekh**, pick *Case no.*, *Party name*, *Filing no.* / *Diary no.* or *CNR*.
4. Pick the case type from the list (type a few letters to narrow it), then enter the number and year (or the party name and year, or the CNR). Tap **Search**.
5. Type the letters (or, for the Supreme Court, the answer to the sum) shown in the picture and tap **Search**. Tap the refresh button for a new picture.
6. The case opens in Tareekh. Tap **Save to My Cases (with orders)**: the case is saved and all its orders are downloaded.

### How to switch on AI reading (optional)
1. Get an API key from one of: Google AI Studio (Gemini), platform.openai.com (OpenAI), console.anthropic.com (Claude), Alibaba Cloud Model Studio (Qwen) or platform.moonshot.ai (Kimi).
2. In Tareekh, open **Settings › Reading with AI (optional)**, choose the service and paste the key. The model is filled in for you.
3. Tap **Test connection**: Tareekh confirms the key is saved and accepted, finds the right server (Kimi and Qwen have China and international servers), lists the models your key may use, and picks one that reads pictures. If an AI request ever says a model was *not found*, Tareekh finds a working one by itself and tries again.
4. Share or upload a summons as usual. Tareekh says *Reading with …* and fills the case form. If the service cannot be reached, Tareekh says so and uses the phone's own reading.

### Version history
- **2.4**: case synopsis and Ask about this case (orders read on the phone, indexed by keywords and meaning, only matching passages sent); Ask AI to find a case, from your words or a summons; Ask AI about my cases; cause lists in plain words; text-only AI for orders; optional economy model.
- **2.3** (1 Oct 2026): **Check here** on every case and **Check all here** for the evening checks: only the court's CAPTCHA is shown in Tareekh, and the case (next date, hearings, orders, calendar) is updated from it; Supreme Court cases can be checked too.
- **2.2** (1 Oct 2026): ⋮ menu on every order with **Explain in simple terms** (English, Bengali, Hindi), **Appeal: where and by when** (forum, provision, limitation, last date, calendar) and **Ask about this order**; without an AI service, Tareekh asks you to connect one first.
- **2.1** (1 Oct 2026): search inside Tareekh with the CAPTCHA on Tareekh's screen (district courts, High Courts, Supreme Court; case number, party name, filing/diary number, CNR); case types from lists; better summons reading; optional AI reading (Gemini, OpenAI, Claude, Qwen, Kimi) with your own API key.
- **2.0**: About section, justified text, public download page.
- **1.9**: party names read more reliably; full screen guide.
- **1.8**: WhatsApp reminder to the client.
- **1.7**: cases saved under the client's name first.
- **1.6**: case types of every High Court bench built in.
- **1.5**: import of the eCourts app's *My Cases* list.
- **1.4**: every order saved in a folder per case.
- **1.0 to 1.3**: next-date checks at 6:30 pm, calendar, reminders, cause lists, notes, dark mode.

## Your day with Tareekh

| When | What Tareekh does | You do |
|---|---|---|
| **8:00 AM** | Today's matters; a fee reminder for hearings 3 days away; a reminder for hearings 2 days away, with **Send WhatsApp reminder** to the client | Tap to send, if you wish |
| **During the day** | Every hearing is in your Google Calendar, with alerts 2 days before and at 8 am | Nothing |
| **6:30 PM** | *Check next date* for the day's hearings. Tap **Check all here**: each case's CAPTCHA is shown in Tareekh, one after another | **Type each CAPTCHA** |
| **After the CAPTCHA** | The next date, stage, hearing history and **every new order** are saved; the calendar moves the hearing | Nothing |
| **8:00 PM** | Tomorrow's matters, with court, purpose and client | Nothing |
| **Next two days** | If eCourts has not shown the new date yet, Tareekh asks again at 6:30 pm; after three days it tells you to check or enter it | Only if asked |
| **Any time** | A summons comes: share or upload it to Tareekh, which reads it and files the case | Check and save |

## How it works

```
 Summons / order / screenshot ──► read on the phone ──► your case list ◄── eCourts app "My Cases" import
                                                              │
  Search / 6:30 pm check ──► court's page, filled in ──► you type the CAPTCHA in Tareekh
                                                              │
                     next date · stage · hearings · orders (PDF, one folder per case)
                                                              │
        Google Calendar · 8 am / 8 pm reminders · fee reminder · WhatsApp reminder to the client
```

Everything is stored on your phone. Tareekh talks only to the court websites you open and, when you ask it to, to WhatsApp and your phone's calendar.

## Features

**Your cases in one place**
- Add a case by hand, by typing it the way you write it (*TS 245/2026 Baruipur*, *WPA 12345/2024*), or from a document.
- **Upload or share** a summons, order, notice, plaint or eCourts screenshot (PDFs up to 3 pages). The phone reads it and fills in the court, case type, number, year, hearing date and both parties. Tables in screenshots are read column by column.
- **Optional AI reading** (new in 2.1): with your own API key for Google Gemini, OpenAI, Claude, Qwen or Kimi, every paper you share (summons, notice, order, WhatsApp photo) is also read by that AI for the best accuracy.
- If an important detail is missing, Tareekh says **"Court details are missing"**: fill them in, or save as it is.
- You choose **whose name the case is saved under** (petitioner, respondent or your client), as *Name + case number* (`Saman WPA 12345-2024`) or *Name only*. The name always comes first.
- **Import your eCourts app case list** (*myCases.txt* and *hcMyCases.txt*) in one step; imported again, cases are updated, never duplicated.

**Next dates, found for you**
- **Search in Tareekh** (new in 2.1): case type + number + year, party name + year, filing / diary number, or CNR, for district courts, High Courts and the Supreme Court. The CAPTCHA is shown on Tareekh's screen and the case opens there.
- **Check on eCourts** opens the court's own page with the case already filled in (CNR, or case type, number and year).
- **Check here** (new in 2.3) does the same check inside Tareekh: only the CAPTCHA is shown, and the case is updated. **Check all here** checks the evening's hearings one after another.
- The next date, stage, judge, parties, acts and full hearing history are read and saved.
- **Manual override:** enter the date yourself when eCourts is down or late.
- When a court website is down, a plain message says so, with *Try again*.

**Court orders, filed per case**
- Every order uploaded on eCourts is downloaded when you open the case there, including orders that appear late on High Court pages.
- Saved in `Download/Tareekh/Orders/<client name> <case number>/`, one folder per case, each file named by date (`2026-09-12 Order 1.pdf`). Open or share them from the case (⋮ menu), **even with the internet off**; they stay even if the app is removed. (The eCourts app does not keep a case's orders for you like this.)

**AI help for orders** (new in 2.2, needs an AI service with your API key)
- **Explain in simple terms** in English, Bengali or Hindi, ready to share with the client.
- **Appeal: where and by when**: forum, provision, limitation period, last date, and a calendar entry for the deadline.
- **Ask about this order**: questions and follow-ups about the order.

**AI for whole cases** (new in 2.4, needs an AI service with your API key)
- **Case synopsis**, date-wise, from all saved orders; the cost is shown first, and each order is summarised once.
- **Ask about this case**: only the matching passages of the orders are sent.
- **Ask AI to find a case**, in your words or from a summons; **Ask AI about my cases**; **cause lists in plain words**.

**Reminders and calendar**
- Every hearing goes into your **Google Calendar** with alerts 2 days before and at 8 am, and moves when the date changes.
- 8 am and 8 pm lists, the 6:30 pm check, a fee reminder 3 days before, and a warning when two courts clash on one day.
- **Notes** with their own reminders, alone or linked to a case.

**Your clients**
- One-tap **Call**, **WhatsApp** and **Save contact** (saved under the client's name followed by the case number).
- **WhatsApp reminder to client**: opens the client's chat with the hearing reminder typed in your own words (case, court, date, purpose filled in). You tap Send. If no number is saved, Tareekh asks for it once.

**Courts across India**
- **District courts of every state:** choose state, district and court complex from eCourts' own lists.
- **All 25 High Courts and their 44 benches** (Appellate Side, Original Side, circuit and regional benches), each on its own eCourts page.
- The case types of every High Court bench (5,691 of them: WPA, CRR, CRM (A), FMA…) are built in, so a paper that shows only *"WPA 12345 of 2024"* is recognised as a Calcutta High Court case.
- **Supreme Court** case status and cause lists.

**Cause lists**
- High Court, district court and Supreme Court cause lists for yesterday, today, tomorrow or any date.
- High Court lists open by themselves (no CAPTCHA) and say *not published yet* when that is so. Lists are saved as PDF in `Download/Tareekh/Cause lists/`.

## Screen guide

Every screen of Tareekh, part by part. The numbered arrows point at each part of the screen; the list under each picture explains it. The cases shown are made-up examples. (The same guide as a PDF: [screen guide](docs/Tareekh-Screen-Guide.pdf).)

### 1 · Notes: your day at a glance

The first tab. It opens every time you start Tareekh.

<p align="center"><img src="docs/guide/notes.png" alt="1 · Notes: your day at a glance" width="420"></p>

1. **Today / Tomorrow**: How many matters are fixed today and tomorrow. Tap to open them in Cases.
2. **Checks due**: Hearings that have happened and whose next date is not yet known. Each needs a quick check on eCourts.
3. **Fees due**: Clients with a hearing in the next 3 days whose fee is not marked paid (only cases with a phone number).
4. **Check**: Opens eCourts for that case with everything filled in; you type the CAPTCHA, the new date is saved.
5. **WhatsApp (fees)**: Opens the client's WhatsApp with a polite fee reminder already typed.
6. **Notes**: Your own notes. A note can have a reminder (alarm) and can be linked to a case. Tick it when done.
7. **New note**: Write a note, set a reminder date and time, or link it to a case.

### 2 · Cases: every matter, by date

All your cases, with a month calendar of hearings.

<p align="center"><img src="docs/guide/cases.png" alt="2 · Cases: every matter, by date" width="420"></p>

1. **Search**: Type any part of a name, number, court or place to find a case.
2. **Court filter**: Show all courts, or only District, High Court or Supreme Court cases.
3. **By date / All / Disposed**: By date shows the calendar and upcoming hearings; All lists everything; Disposed shows closed cases.
4. **Sync**: Writes every hearing into your phone's Google Calendar (with alerts 2 days before and at 8 am).
5. **Calendar**: Each day shows how many matters are fixed. Tap a day to see only its cases and your other calendar entries.
6. **Clash warning**: Warns when you have matters in two different court towns on the same day.
7. **Add case**: Add a case by hand, or upload a summons, order or screenshot for Tareekh to read.

### 3 · A case

Tap any case to open it. Everything about the matter is on this one page.

<p align="center"><img src="docs/guide/case_top.png" alt="3 · A case" width="420"></p>

1. **Next date**: The next hearing date, its purpose and the case stage.
2. **Check on eCourts**: Opens the court's page filled in (CNR, or case type, number and year). Type the CAPTCHA; the next date, hearings and orders are saved.
3. **Enter date**: Manual override: type the next date yourself if eCourts is down or late. The calendar is updated too.
4. **Save contact as**: The name to save your client under in your phone: name first, then the case number. Tap to copy.
5. **WhatsApp reminder to client**: Opens the client's WhatsApp with the hearing reminder typed (case, court, date). You tap Send.
6. **Call / WhatsApp / Save**: Call the client, message them, or save them as a phone contact in one tap.
7. **Fee paid**: Mark the fee as paid so no fee reminder is sent for this date.
8. **Orders**: Court orders downloaded from eCourts, newest first. Tap to open; the share icon sends it on WhatsApp.

### 4 · Checking a case on eCourts (example)

What you see after tapping Check on eCourts and typing the CAPTCHA. (Illustration made with a sample page: on the real court site the layout is the court's own.)

<p align="center"><img src="docs/guide/check_page.png" alt="4 · Checking a case on eCourts (example)" width="420"></p>

1. **Next date read from the court**: Tareekh reads the next hearing date, stage, judge, parties and hearing history from the page.
2. **Orders on the page**: Every order listed on the court's page is downloaded into the case's folder: Download/Tareekh/Orders/<client> <case>.
3. **Saved automatically**: For a case already in your list, the new date and new orders are saved by themselves. You are told how many orders were saved.
4. **Open the case in Tareekh**: Jump back to the case page. A new case shows 'Save to My Cases (with orders)' here instead.

### 5 · Adding a case from a document

Upload (or share to Tareekh) a summons, order, notice or eCourts screenshot; PDFs up to 3 pages are read too.

<p align="center"><img src="docs/guide/add_found.png" alt="5 · Adding a case from a document" width="420"></p>

1. **Found in the document**: What Tareekh read: ✓ means found, – means not found. Check it before saving.
2. **Case details**: Case type, number, year, court, hearing date and both parties are filled in for you.
3. **Show document text**: See (and copy) exactly what the phone read, useful if something was read wrongly.
4. **Edit anything**: Every field can be corrected by hand before you save.

### 6 · Whose name to save the case under

Asked every time you save a new case.

<p align="center"><img src="docs/guide/saveas.png" alt="6 · Whose name to save the case under" width="420"></p>

1. **Petitioner / respondent**: Choose the party who is your client; the full name is used.
2. **Another name**: Or type your client's name, e.g. a company contact.
3. **Name + number / Name only**: Save as 'Name TYPE NO-YEAR' (the name always first) or just the name.
4. **Saved as**: Preview of the name used for the case, the contact and the orders folder.

### 7 · When court details are missing

If the document did not give an important detail, Tareekh says so before saving.

<p align="center"><img src="docs/guide/missing.png" alt="7 · When court details are missing" width="420"></p>

1. **What is missing**: Court, case number or CNR, case type, year, next date or parties: whatever could not be found.
2. **Save as it is**: Save with what the document gave. You can add the rest later with Edit.
3. **Fill them in**: Go back to the form and type the missing details now.

### 8 · Search: district courts

Court-wise search. The kind of court with most of your cases opens first.

<p align="center"><img src="docs/guide/search.png" alt="8 · Search: district courts" width="420"></p>

1. **Open eCourts search**: The full eCourts search page (party, advocate, FIR, Act and more).
2. **Choose court**: Any court in India: state, district and court complex, straight from eCourts' own lists. Recent courts are remembered.
3. **Find a case**: Type the case as you would write it; Tareekh fills the eCourts form and you type the CAPTCHA.
4. **Open by CNR**: The quickest search: the 16-character CNR number.

*New in 2.1:* the **Search in Tareekh** box below the court (case no., party name, filing no., CNR) does the whole search on Tareekh's screen, with the CAPTCHA shown in the app. See [How to use the new search](#how-to-use-the-new-search).

### 9 · Search: High Courts

All 25 High Courts and their 44 benches, opened on their own eCourts pages.

<p align="center"><img src="docs/guide/search_hc.png" alt="9 · Search: High Courts" width="420"></p>

1. **High Court**: Choose the High Court; your last choice is remembered.
2. **Bench / side**: Appellate Side, Original Side, circuit benches: every bench has its own page.
3. **All searches**: That bench's full eCourts menu (case number, party, advocate, orders, cause list).
4. **Case number**: WPA, CRR, FMA…: the case type, number and year are filled in; you type the CAPTCHA.

*New in 2.1:* **Search in Tareekh** for the chosen bench: case no. (case type from the bench's own list), party name, filing no. or CNR, with the CAPTCHA shown in the app. The Supreme Court has the same box (case no., diary no., party name, CNR).

### 10 · Choosing any court in India

State › district › court complex, with a filter box.

<p align="center"><img src="docs/guide/picker.png" alt="10 · Choosing any court in India" width="420"></p>

1. **Where you are**: The state already chosen; next the district, then the court complex.
2. **Type to filter**: Type a few letters to find a district or court quickly.
3. **Lists from eCourts**: The lists are read live from eCourts, so every court in India is there.

### 11 · Cause lists

Today's (or any day's) cause list for a High Court bench, a district court or the Supreme Court.

<p align="center"><img src="docs/guide/causelists.png" alt="11 · Cause lists" width="420"></p>

1. **Court**: High Court, District court or Supreme Court.
2. **Bench**: For High Courts, choose the bench or side.
3. **Yesterday / Today / Tomorrow**: One tap opens the list for that day.
4. **Any date**: Pick a date from the calendar, then Open.

### 12 · A High Court cause list

High Court lists open by themselves (no CAPTCHA).

<p align="center"><img src="docs/guide/hc_causelist.png" alt="12 · A High Court cause list" width="420"></p>

1. **What was found**: How many lists are published for the date, or 'not published yet'.
2. **View**: Downloads the bench's list as a PDF into Download/Tareekh/Cause lists and opens it.

### 13 · WhatsApp reminder without a number

If no phone number is saved for the case.

<p align="center"><img src="docs/guide/wa_number.png" alt="13 · WhatsApp reminder without a number" width="420"></p>

1. **Client's number**: Type it once: it is saved with the case.
2. **Save and open WhatsApp**: Saves the number and opens WhatsApp with the reminder typed; you tap Send.

### 14 · Reminders on your phone

Tareekh reminds you even when the app is closed.

<p align="center"><img src="docs/guide/notification_raw.png" alt="14 · Reminders on your phone" width="420"></p>

1. **2 days before**: Each hearing two days ahead, with the court, purpose and client.
2. **Send WhatsApp reminder**: Opens the client's WhatsApp with the reminder typed (or asks for the number first).
3. **Still no next date**: If eCourts still shows no new date 3 days after a hearing, check or enter it.
4. **6:30 pm check**: Hearings of the day: tap to check each on eCourts with one CAPTCHA.

### 15 · A note with a reminder

From the Notes tab or from any case.

<p align="center"><img src="docs/guide/note_dialog.png" alt="15 · A note with a reminder" width="420"></p>

1. **Note**: Anything you need to remember.
2. **Link to a case**: The note then also shows on that case's page.
3. **Reminder**: Pick a date and time; a notification comes then (it opens the case).

### 16 · Settings

Backup, your WhatsApp wording and the look of the app.

<p align="center"><img src="docs/guide/settings.png" alt="16 · Settings" width="420"></p>

1. **Export / Import**: Save all cases and notes to a backup file (keep it in Google Drive); Import also reads the eCourts app's My Cases export.
2. **WhatsApp reminder message**: Your own wording; {client} {case} {court} {date} {purpose} are filled in for each case.
3. **Appearance**: Phone setting, Light or Dark.
4. **Court websites**: If a court page keeps showing old results, clear what the built-in browser stored.
5. **Reading with AI (optional)**: Choose Google Gemini, OpenAI, Claude, Qwen or Kimi and paste your API key. Used for reading summons (2.1) and for Explain, Appeal and Ask on orders (2.2).

### 17 · About

Settings › About: the app, the firm and how to reach us.

<p align="center"><img src="docs/guide/about.png" alt="17 · About" width="420"></p>

1. **Patra's Law Chambers**: Tareekh is made by Patra's Law Chambers, Kolkata and New Delhi.
2. **Website**: Opens patraslawchambers.com. Call, WhatsApp and Contact buttons are below.

### 18 · Dark mode

Settings › Appearance › Dark (or follow the phone).

<p align="center"><img src="docs/guide/dark_notes.png" alt="18 · Dark mode" width="420"></p>

1. **Easy on the eyes**: Every screen, including the court pages' surroundings, works in dark mode.

## Install

<p align="center"><a href="https://github.com/advocatesudippatra-spec/tareekh-court-case-monitoring/raw/main/Tareekh-2.4.apk"><img src="docs/img/download-button.png" alt="Download Tareekh 2.4 for Android (APK)" width="340"></a></p>

1. On your Android phone, tap **Download Tareekh 2.4** above (or [this link](https://github.com/advocatesudippatra-spec/tareekh-court-case-monitoring/raw/main/Tareekh-2.4.apk)); the APK (about 47 MB) downloads directly.
2. Open it; allow installs from that source once; tap **Install**. A new version installs over the old one and keeps your cases, notes and orders.
3. Open Tareekh and tap **Allow** for notifications and calendar. Set **Battery › Unrestricted** for Tareekh so the 6:30 pm check always comes.
4. Add your cases: **Settings › Import** your eCourts app *My Cases* export, upload documents, or type them.
5. For faster court pages: phone **Settings › Network › Private DNS › `dns.google`** (some internet providers take 5 seconds to find eCourts).


## Your data

- Cases, notes and orders stay **on your phone**. Nothing is sent to Patra's Law Chambers or anyone else. Only if you connect an AI service is anything sent out: the picture of a paper you share, or an order you ask to explain, goes to the AI service you chose, under your own API key.
- **Settings › Export** saves a backup file (cases and notes) to keep in Google Drive; **Import** restores it on a new phone. Copy the `Download/Tareekh` folder to keep the order PDFs.
- Tareekh never types a CAPTCHA and never logs in to anything; it only fills in the court's public search forms.

## Questions

**Does it work without eCourts?** Yes: dates can be entered by hand, and all reminders, the calendar, notes and orders already saved work offline. Only new dates and new orders need the court's website.

**Why do I still type a CAPTCHA?** The courts protect their pages with one, and Tareekh respects it. The picture is shown on Tareekh's own screen; everything else is filled in for you.

**Can Tareekh update my cases without showing the court's page?** Yes: **Check here** on a case, or **Check all here** in the evening. You type only the CAPTCHA.

**Do I need to open the court's website?** No. Search in Tareekh does it for you out of sight; *Court's page* shows it only if you want to see it.

**Can I read orders without internet?** Yes. Every saved order is a PDF on your phone, in the case's own folder.

**Can Tareekh tell me where to appeal and by when?** Yes, with an AI service connected: order ⋮ › *Appeal: where and by when*. It is guidance: verify the forum and limitation before filing.

**Can my client read the order in Bengali or Hindi?** Order ⋮ › *Explain in simple terms* › বাংলা or हिन्दी, then *Share with client*.

**How much AI does a synopsis use?** Tareekh shows it before running. Typed orders are read from the PDF on the phone (no OCR), only text is sent, and each order is summarised once, so later updates cost only the new orders.

**Do I need an API key?** No. The phone reads papers by itself. An API key (Gemini, OpenAI, Claude, Qwen or Kimi) is optional, for better reading of difficult papers; that service bills your account.

**Can WhatsApp reminders go by themselves?** WhatsApp does not let any app send from your number without you; Tareekh opens the chat with the message typed and you tap Send.

**Which phones?** Android 8 or later. Some phones (Xiaomi, Oppo, Vivo, Realme) need *Battery › Unrestricted* for the evening check.

## Copyright

© 2026 **Patra's Law Chambers** (Advocate Sudip Patra), Kolkata and New Delhi. **All rights reserved.** Tareekh is proprietary software: its source code is not published. The app may be downloaded and used free of charge for your own practice; it may not be resold, repackaged, modified, decompiled or distributed under another name. The name Tareekh, the guide, the screenshots and the Patra's Law Chambers seal may not be reused without written permission. Permissions: https://patraslawchambers.com/ · +91 890 222 4444.

## About Patra's Law Chambers

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/img/seal-dark.png">
  <img src="docs/img/seal-light.png" alt="Patra's Law Chambers seal" width="150" align="right">
</picture>

Tareekh was built and released by **Patra's Law Chambers**, a litigation practice with chambers in Kolkata and New Delhi, out of its founder's daily practice at the Calcutta High Court.

**Advocate Sudip Patra**, Founder & Managing Partner, is an alumnus of IIT Kharagpur, with a B.Tech in Electrical Engineering, an LL.B. (Hons.) in Intellectual Property Law, a PG Diploma in Power Transmission & Distribution and a PG Executive Diploma in Business & Corporate Law from IIM Calcutta (Joka). He has over 10 years of practice in intellectual property, corporate law, arbitration, civil and criminal litigation, and High Court and Supreme Court matters.

Founded in 2020 in Kolkata, with a second chamber in New Delhi since 2023, the firm practises before the Supreme Court of India, the Calcutta High Court, the CAT, the AFT, the DRT and DRAT, the NCLT, and civil and criminal courts.

| | |
|---|---|
| **Kolkata** | NICCO House, 6th Floor, 2 Hare Street, Kolkata 700001 |
| **New Delhi** | 4455/5, 1st Floor, Gali Shahid Bhagat Singh, Paharganj, New Delhi 110055 |
| **Website** | https://patraslawchambers.com/ |
| **Phone / WhatsApp** | +91 890 222 4444 |

---

<p align="center"><a href="https://github.com/advocatesudippatra-spec/tareekh-court-case-monitoring/raw/main/Tareekh-2.4.apk"><img src="docs/img/download-button.png" alt="Download Tareekh 2.4 for Android (APK)" width="340"></a></p>

<p align="center">© 2026 Patra's Law Chambers · All rights reserved</p>

</div>
