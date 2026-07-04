# 🚀 Complete Setup Guide — GitHub Profile README

This guide walks you through every step, click by click, to publish your profile README.

---

## Step 1 — Understand the Special Repository

If you create a repository with the **exact same name as your username** and make it **public**, GitHub automatically shows its `README.md` at the top of your profile page.

- Your username: `tetalilahari`
- Your special repository must be named: `tetalilahari` (exactly, all lowercase)

---

## Step 2 — Create the Repository

1. Go to https://github.com/new (logged in as `tetalilahari`).
2. In **Repository name**, type: `tetalilahari`
3. GitHub will show a message confirming it's a special profile repository.
4. Set visibility to **Public**.
5. Check **"Add a README file."**
6. Click **Create repository**.

---

## Step 3 — Upload the Files

### Option A — Upload via Browser

1. Open `https://github.com/tetalilahari/tetalilahari`
2. Click **Add file → Upload files**.
3. Drag and drop `README.md` (confirm overwriting the existing one).
4. Add a commit message, click **Commit changes**.
5. Repeat for `LICENSE` at the root.

### Option B — Upload via Git

```bash
git clone https://github.com/tetalilahari/tetalilahari.git
cd tetalilahari
```

Copy `README.md`, `LICENSE`, and `assets/` from this package into the folder, then:

```bash
git add .
git commit -m "Add profile README and assets"
git push origin main
```

---

## Step 4 — Add the Assets Folder

**If uploading via browser:**
1. Click **Add file → Create new file**.
2. In the file name box, type `assets/banner.svg` — the slash automatically creates the folder.
3. Paste in the contents of `banner.svg` from this package.
4. Commit the file.

---

## Step 5 — Personalize the Placeholders

Open `README.md` and update:

| Find | Replace With |
|---|---|
| `youremail@example.com` | Your real email (appears twice) |
| `_Add your college name_` | Your actual college/university name |
| `_Add your achievement_` | Your real achievements |
| `_Certificate Name 1/2/3_` | The actual names of your certificates |

Everything else (badges, tech stack icons, project cards, visitor counter) works as-is with no editing needed.

---

## Step 6 — Pin Your Best Repositories

1. Go to your profile page: `https://github.com/tetalilahari`
2. Click **Customize your pins**.
3. Select up to 6 project repositories (Hospital Appointment System, InsureEase, House Price Prediction, Insurance Comparison Platform).
4. Click **Save pins**.

*(Pin your actual project repos, not the `tetalilahari/tetalilahari` profile repo itself.)*

---

## Step 7 — Replacing the Username Everywhere

If you ever rename your GitHub account, replace **`tetalilahari`** wherever it appears in `README.md` (coding profile links, visitor counter badge, and the GitHub badge link). Use your editor's **Find & Replace All** (`Ctrl+H` / `Cmd+H`) for a fast pass.

---

## 🛠️ Troubleshooting

**❌ README isn't showing on my profile page**
→ Confirm: (1) repository name matches your username exactly, (2) it's set to **Public**, (3) `README.md` is at the root, not inside a subfolder.

**❌ Skill icons or badges show as broken images**
→ These load from external services (skillicons.dev, shields.io) — a broken image usually means a temporary outage. Refresh after a minute.

**❌ Visitor counter shows 0 or doesn't update**
→ It only counts fresh page loads from new visitors/sessions — refreshing the page yourself repeatedly won't necessarily increase it.

---

## ✅ Final Checklist

- [ ] Repository named exactly `tetalilahari`, set to Public
- [ ] `README.md` uploaded/replaced at the root
- [ ] `LICENSE` uploaded at the root
- [ ] `assets/banner.svg` uploaded
- [ ] Email and college name placeholders personalized
- [ ] Achievements and certification names filled in
- [ ] Best project repositories pinned on profile

Once every box is checked, your profile is live. 🎉
