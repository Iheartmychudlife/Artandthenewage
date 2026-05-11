# How to Host Your Art Page on GitHub Pages

This guide will walk you through publishing your interactive art page to the internet for free using GitHub Pages. By the end, you'll have a public URL like `https://yourusername.github.io/art-and-the-digital-age/` that you can share with anyone.

---

## What You're Going to Do (Big Picture)

1. Make a free GitHub account (if you don't have one).
2. Create a new "repository" — basically a folder that lives online.
3. Upload your `Interactive essay` folder contents to it.
4. Turn on a setting called GitHub Pages.
5. Wait a few minutes, then share your link.

You won't need to install anything. We'll use GitHub's website for everything.

---

## Before You Start: A Quick Fix

I already renamed one file for you: `ROjasNIno_PROGRESS#.jpeg` became `ROjasNIno_PROGRESS.jpeg`. The `#` symbol breaks on web servers, so this was necessary. You can delete the old file with the `#` in its name before uploading, or just leave it — it won't hurt anything.

Also, before uploading, **delete these two leftover files** from your folder:
- `Art_and_the_Digital_Age.zip` (the 0-byte empty zip)
- `Art_and_the_Digital_Age_v2.zip` (the 18 MB zip) — you don't need to upload your own zip to the repo

---

## Step 1: Create a GitHub Account

1. Go to **https://github.com** in your web browser.
2. Click **Sign up** in the top right corner.
3. Enter your email, choose a password, and pick a username. Your username will show up in your site's URL, so pick something you're comfortable sharing (for example: `andyrojasnino`).
4. Verify your email when GitHub sends you a confirmation message.
5. Choose the free plan when prompted.

If you already have a GitHub account, just sign in instead.

---

## Step 2: Create a New Repository

A "repository" (or "repo") is GitHub's word for a project folder.

1. Once logged in, look in the **top-right corner** of GitHub. Click the **+** icon.
2. Choose **New repository** from the dropdown.
3. On the new page:
   - **Repository name:** type `art-and-the-digital-age` (or anything you like — no spaces, use hyphens instead).
   - **Description:** optional, but you could write "Interactive art essay by Andy Rojas Nino".
   - Select **Public** (this is required for free GitHub Pages hosting).
   - **Do NOT check** "Add a README file." Leave all the initialization boxes unchecked.
4. Click the green **Create repository** button at the bottom.

You'll land on a page with code instructions you can ignore. Look for the line near the top that says **"uploading an existing file"** — that's a link. Click it.

If you don't see that link, go to the **Code** tab of your new repo, then click **Add file → Upload files**.

---

## Step 3: Upload Your Files

1. Open your `Interactive essay` folder on your computer in File Explorer.
2. Select all the files inside it: hit **Ctrl + A** to select everything (or click the first file, then Shift-click the last).
3. **Important:** make sure the `NetArt` subfolder is included in your selection.
4. Drag everything from File Explorer into the upload area on the GitHub page. You should see a list of files appear, including the `NetArt` folder.
5. Wait for all files to upload. The videos are large (several megabytes each), so this might take a minute or two on a slow connection. **Don't close the tab while uploading.**
6. Once everything is uploaded, scroll down to the **Commit changes** section.
7. Leave the default commit message ("Add files via upload") or type something like "Initial upload of art page".
8. Make sure **Commit directly to the main branch** is selected.
9. Click the green **Commit changes** button.

Your files are now stored on GitHub. You should see them all listed on the repository's main page.

---

## Step 4: Turn On GitHub Pages

1. On your repository's page, click the **Settings** tab near the top right (it has a gear icon).
2. In the left-hand menu, scroll down and click **Pages**.
3. Under **Source**, you'll see a dropdown that says "Deploy from a branch". Leave it on that option.
4. Under **Branch**:
   - In the first dropdown, select **main**.
   - In the second dropdown, leave it on **/(root)**.
5. Click **Save**.

GitHub will now start building your site. You'll see a message like "Your site is live at..." appear after a few minutes (sometimes up to 10).

---

## Step 5: Find and Share Your Link

1. Refresh the **Settings → Pages** page after a couple of minutes.
2. You'll see a green box with **"Your site is live at https://yourusername.github.io/art-and-the-digital-age/"**.
3. Click the link — your interactive art page should load, complete with floating images, the flower button, the essay, the deer gallery, and the cursor follower.
4. Share this link with anyone you like!

---

## Updating Your Site Later

If you want to change something (edit the essay, add new images, tweak the design):

1. Make your changes locally in the `Interactive essay` folder.
2. Go to your repo on GitHub.
3. Click **Add file → Upload files** and re-upload the changed files. They'll overwrite the old versions.
4. Commit the changes.
5. Wait 1–3 minutes for GitHub Pages to rebuild.
6. Refresh your live site (you may need to hard-refresh with **Ctrl + Shift + R**).

---

## Troubleshooting

**My site says "404 — page not found."**
GitHub Pages needs a couple of minutes to build. Wait 3–5 minutes and refresh. Also, make sure your file is named exactly `index.html` (lowercase, all one word).

**Some images don't load on the live site.**
The most common cause is a filename with a special character (`#`, `?`, `&`, etc.) or with different capitalization than what the HTML code expects. Web servers are case-sensitive even though Windows is not — so `Deer.jpg` and `deer.jpg` are treated as different files online. If an image is missing, check that the filename in your folder matches exactly what's in `index.html`.

**The videos in the NetArt gallery take forever to load.**
This is normal — the videos total around 15 MB. GitHub Pages serves them, but the first visit downloads them fresh. After the first view, your browser will cache them.

**Can I use a custom domain like andyrojas.com?**
Yes — GitHub Pages supports custom domains for free. You'd need to buy a domain from a registrar like Namecheap or Google Domains, then follow GitHub's custom domain setup instructions. This is a more advanced step.

---

## A Note on File Size

GitHub has a 1 GB total repo size recommendation and a 100 MB per-file limit. Your project (around 35 MB total) is well within those limits, so you're fine. If you ever add many more videos, just keep an eye on it.

---

That's it! In around 10–15 minutes total you can have your art page live on the internet.
