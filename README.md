# Dwij Bhatt: Personal Website

Personal portfolio site for Dwij Bhatt (John P. Stevens High School, Class of 2027): resume, projects, and research on the cybersecurity of connected medical devices.

## Pages
| File | Contents |
|---|---|
| `index.html` | About, resume, projects, contact |
| `research.html` | Research paper: *Securing the Connected Patient* (with an interactive risk-score calculator) |
| `resume.pdf` | One-page resume |
| `style.css` | Shared styles |

Plain HTML and CSS, with no build step or dependencies.

## Publish with GitHub Pages
1. Create a GitHub account (if needed) and a **new public repository**.
   - Name it `<your-username>.github.io` to get the address `https://<your-username>.github.io`.
   - Any other name also works; the site will be at `https://<your-username>.github.io/<repo-name>/`.
2. Upload the files:
   - **In the browser:** open the new repo → **Add file → Upload files** → drag in everything in this folder → **Commit changes**.
   - **Or with Git** (this folder is already a Git repo with one commit):
     ```bash
     git remote add origin https://github.com/<your-username>/<repo-name>.git
     git branch -M main
     git push -u origin main
     ```
3. In the repo, go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After a minute or two, the site is live at the address shown on that page.

## Updating
Edit the files, then commit and push (or upload the changed files in the browser). GitHub Pages redeploys automatically.

## Before publishing
Search `index.html` and `research.html` for `[ADD` and replace the yellow placeholders (email, about paragraph, optional links). Remove the `<span class="ph">` wrapper around each one you fill in.
