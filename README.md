# pagecrew.github.io
Personal site and hosting space for small web projects (as of Aug '26).

## Live projects

- [Harlem Walking Map](https://pagecrew.github.io/harlem-map/) — interactive map of favorite & useful spots in Harlem

## Adding a new project

1. Go to this repo.
2. **Add file → Create new file**, and type `project-name/index.html` (pick a short name describing the project — the slash creates the folder automatically).
3. Paste in the full HTML (View Source → Select All → Copy in Chrome, or upload the file directly and rename it to `index.html`).
4. **Commit changes**.
5. Give it a minute — it's live at `https://pagecrew.github.io/project-name/`.

No new repo, no Settings changes, no re-enabling Pages needed.

Remember to add each new project to the "Live projects" list above.

## Finding the pastable code (full HTML file) from Claude
double-clicking opens a downloaded Claude html file and renders it in the browser, which hides the code. Below are two ways to get the actual text:

# Option A — View the source in Chrome (matches the "paste into GitHub" method I gave you)

With the map open in Chrome, press Cmd+Option+U (Mac) or Ctrl+U (Windows). This opens a new tab showing the raw HTML code as plain text.
Click anywhere in that tab, then Cmd+A / Ctrl+A to select all of it.
Cmd+C / Ctrl+C to copy.
Go to GitHub's "Create new file" editor and paste (Cmd+V / Ctrl+V) into the code box.

The file has one very long line in it (the mapping library is bundled in), so the source view might look like a giant wall of text with a lot of horizontal scrolling — that's normal, Select All still grabs everything correctly.

# Option B — Skip copy/paste entirely by uploading the file directly

This avoids the whole "where's the code" problem:

In your harlem-map folder on GitHub (create it first if needed, e.g. by making the folder via a new file), click Add file → Upload files.
Drag your downloaded .html file straight into the upload area and commit — no need to open or view it at all.
Afterward, click into that uploaded file, click the pencil (Edit) icon, and there's an editable filename field at the top of the page — change it to index.html and commit again. (GitHub Pages specifically looks for a file named index.html to serve as the page.)
