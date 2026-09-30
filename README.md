# Leadership EXchange October Series — Partner Activation Portal

A single-page portal for **The E1B2 Collective** (Anthony Vaughan) covering the four October Leadership EXchange dinners co-hosted by Achieve and Keka.

**Eight sections:** scope and events, goals and KPIs, who to invite, Keka and the topic, tracking links, messaging templates, FAQ, and collateral.

---

## Publishing this (browser only, no terminal)

This is a **new, separate repo** from the Keka kit. Everything sits flat at the top level, so there are no folders to get wrong.

### 1. Make the repo

1. Go to github.com, click **+** (top right) → **New repository**
2. Name it `lex-partner-portal`
3. Leave it **Public**, do not check "Add a README"
4. Click **Create repository**

### 2. Upload the files

1. On the empty repo page, click **uploading an existing file**
2. Unzip this folder on your computer, open it, select **everything inside** (Cmd+A / Ctrl+A)
3. Drag it into the GitHub box
4. Wait for all 14 files to finish loading
5. Click **Commit changes**

### 3. Connect Vercel

1. Go to vercel.com → **Add New** → **Project**
2. Find `lex-partner-portal`, click **Import**
3. **Leave every setting alone.** Framework Preset "Other", no Root Directory, no Build Command, no Output Directory.
4. Click **Deploy**

Done. Vercel gives you the URL. That's the link you send Anthony.

> If the build fails with something about an output directory, go to **Settings → Build and Deployment**, set **Output Directory** to a single period `.`, save, and redeploy.

---

## Updating it later

Every file lives at the top level, so you edit in place:

- **Change copy, goals, FAQ, anything:** click `index.html`, click the ✏️ pencil, edit, commit. Vercel redeploys on its own.
- **Swap a graphic:** upload a file with the exact same name and it replaces the old one.

No build step. No commands. What is in the repo is what is on the site.

---

## What is in here

| File | What it is |
|---|---|
| `index.html` | The whole portal. One file. |
| `banner__*.jpg` | 1200 × 627 — email headers, LinkedIn link shares, web |
| `square__*.jpg` | 1200 × 1200 — LinkedIn and Instagram posts |
| `cover__*.jpg` | 1584 × 396 — LinkedIn profile headers |

Four cities: `AUSTIN`, `HOUSTON`, `BOSTON`, `NEWYORK`.

---

## Things that are hard-coded and will need changing next series

- The four events, dates, and venues in section 01
- The tracking links in section 05 (`utm_source=e1b2`, `utm_campaign=lex-oct26-<city>`)
- The target account list URL, which appears in sections 01 and 03
- The topic and statistics in section 04

---

Questions: zechd@achievenet.org
