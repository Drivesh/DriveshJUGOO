# Drivesh Jugoo — One-Page Portfolio

A single-page portfolio with a **built-in visual editor**. No database, no server, no build step, no cost.
Hosted free on GitHub Pages. Update it from your phone or computer by filling in forms.

```
index.html     The website (your content is stored inside it)
edit.html      The editor — open it on your live site to update everything
assets/        Your portrait
files/         CV, certificates, reports
gallery/       Gallery photos
```

---

## 1. Publish the site (once, ~10 minutes)

1. Create a free account at <https://github.com>.
2. Click **+ → New repository**.
   - Name: **`YOUR-USERNAME.github.io`** → your address will be `https://YOUR-USERNAME.github.io`.
   - Visibility: **Public** (required for free hosting). → **Create repository**.
3. Click **uploading an existing file**. Unzip the download, open the folder, select **everything inside it** (`index.html`, `edit.html`, `README.md`, `assets`, `files`, `gallery`) and drag it into the browser → **Commit changes**.
4. **Settings → Pages** → Source: **Deploy from a branch** → Branch **main**, folder **/ (root)** → **Save**.
5. After 1–2 minutes your site is live at `https://YOUR-USERNAME.github.io`.

## 2. Connect the editor (once per device, ~2 minutes)

The editor saves your changes straight into your GitHub repository. To allow that, it needs a **GitHub access token** — a key that only works on your website repository.

1. Open **<https://github.com/settings/personal-access-tokens/new>**.
2. **Token name:** `Website editor` · **Expiration:** 1 year.
3. **Repository access:** *Only select repositories* → choose `YOUR-USERNAME.github.io`.
4. **Permissions → Repository permissions → Contents → Read and write.** Nothing else.
5. **Generate token** and copy it (starts with `github_pat_`).
6. Open **`https://YOUR-USERNAME.github.io/edit.html`** (or click the small **Edit** link in the website footer).
   Username and repository are filled in automatically — paste the token → **Connect & load website**.

Tick *Remember on this device* on your own phone/computer so you never have to paste it again. The token stays in your browser only; it is never put on the website.

## 3. Update your website

On `…/edit.html`:

| To… | Do this |
|---|---|
| Change any text | Open the section, type. |
| Add a job, achievement, project, skill, qualification, photo or download | **+ Add …** at the bottom of the section. |
| Reorder | **▲ ▼** on the item. |
| Remove | **Delete** on the item. |
| Change portrait | Profile → *Portrait photo* → **Replace**. |
| Add / replace your CV | Profile → *CV file* → **Upload** / **Replace**. A **Download CV** button appears on the site. |
| Add gallery photos | Photo gallery → **+ Add photo** → **Upload** → caption. |
| Add a downloadable document | Downloads → **+ Add download** → title, description, **Upload**. |
| Check before going live | **Preview** (opens your site with the changes). |
| Go live | **Publish**. The live site updates in 1–2 minutes. |

Good to know:
- Photos are resized automatically. Files up to 20 MB (PDF, Word, Excel, PowerPoint, JPG/PNG/WEBP).
- Unpublished **text** changes are kept if you close the page; new **uploads** must be published before you leave.
- Replaced or removed files are deleted from the website automatically when you publish.
- **Backup** downloads a copy of the site with all your text.
- Every publish is saved in GitHub's history (repository → **Commits**), so any version can be restored.

## 4. If something goes wrong

| Message / problem | Fix |
|---|---|
| *The token is invalid or expired* | Create a new token (section 2) and reconnect. |
| *The token is not allowed to change this repository* | The token needs **Contents: Read and write** and access to this repository. |
| *Repository or branch not found* | Check username and repository name (`YOUR-USERNAME.github.io`) and branch `main`. |
| Change not visible on the site | Wait 1–2 minutes, then refresh (Ctrl + F5 / pull down on phone). Progress: repository → **Actions** tab. |
| Site shows *content could not be loaded* | A manual edit broke `index.html`. Repository → `index.html` → **History** → open the previous version → copy it back. Or upload your latest **Backup** as `index.html`. |
| Lost phone / shared the token by mistake | <https://github.com/settings/personal-access-tokens> → **Delete** the token, then create a new one. |

## 5. Good to know

- **Everything on the website is public** — only upload documents you are happy for anyone to download (no payslips, IDs or confidential company files).
- **No contact form** — visitors reach you by e-mail or LinkedIn.
- **Free limits (GitHub Pages):** site up to 1 GB, about 100 GB traffic per month — far beyond a portfolio's needs. No pausing, no expiry.
- **Phone preview of the file:** opening `index.html` directly from a phone's file manager shows the text and default portrait; uploaded photos and files appear on the live site.
- **Custom domain** (optional, paid at a registrar): Settings → Pages → *Custom domain*.
- Advanced: you can still edit the text by hand in `index.html` on GitHub, between the **▼ START** and **▲ END** lines.
