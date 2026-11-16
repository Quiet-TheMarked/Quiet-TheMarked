# GitHub profile — installation

This package is prepared for GitHub user: `Quiet-TheMarked`.

## How the special profile repository works

Your profile README appears when you have a **public** repository named
exactly `Quiet-TheMarked`, with a nonempty `README.md` at the repository root.

## Recommended terminal setup (Ubuntu + GitHub CLI)

1. Extract this ZIP into a folder.
2. Open a terminal in that folder, which contains `README.md` and `assets/`.
3. If the `Quiet-TheMarked` repository does not exist yet:

   git init -b main
   git add README.md assets
   git commit -m "Create illuminated manuscript profile"
   gh repo create Quiet-TheMarked --public --source=. --remote=origin --push

   If Git asks for identity configuration, use your preferred Git name and email.

4. Visit https://github.com/Quiet-TheMarked to view the result.

## Manual browser setup

Create a new PUBLIC repository named `Quiet-TheMarked` under your account.
Upload `README.md` and the entire `assets` folder, preserving paths.
If you initialize the repo with a default README, replace its content
with the supplied `README.md`.

## Account avatar and repository preview (separate UI settings)

* Upload `assets/avatar.png` via GitHub → Settings → Profile picture.
  The profile README cannot change the account avatar.
* If desired, upload `assets/social-preview.jpg` via the special
  repository → Settings → Social preview. This affects links to that
  repository, not your account avatar or the main GitHub page design.
* Pin desired repositories through the profile's pinned-items controls.

## Limitations

GitHub renders the profile README as Markdown/limited HTML, not a
fully customizable website. Its global header, navigation, contribution
graph, colors, and visitors' themes cannot be re-skinned by this repo.
The manuscript-styled typography here is embedded in image assets;
there are no font files, external scripts, or remote image dependencies.

## Editing copy

Edit `README.md` in your usual editor. Images use repo-relative paths,
so they continue to work on GitHub after the files are pushed.
