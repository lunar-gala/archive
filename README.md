# How to Update
## 1. Edit the `index.html` File
- Open it in a code editor (e.g., VS Code, Sublime Text).

## 2. Add a New Entry
Inside the `<div class="content">` under the header, insert a new entry with the appropriate format:
```html
<div class = "entry">
	<p>YEAR</p>
	<p>
		<a href = "link to archive website">THEME</a>
	</p>
	<div class = "cds">
		<p>NAME OF CDS</p>
	</div>
</div>
```
To make a "Coming Soon" message show on link hover, follow this format.
```html

            <div class = "entry">
                <p>YEAR</p>
                <p>
                    <span class="tooltip-wrapper" id="elysium">
                        <a href="#">THEME</a>
                    </span>
                </p>
                <div id="tooltip" class="tooltip">Coming soon</div>
                <div class = "cds">
                    <p>NAME OF CDS</p>
                </div>
            </div>
```

## 3. Save the File
- Ensure all edits are saved before proceeding to the next step.

---

# Pushing Changes to GitHub

## 1. Open Terminal or Git Bash
Navigate to the project folder using the terminal:
```bash
cd path/to/your/archive-website
```

## 2. Check the Current Status
Run:
```bash
git status
```
This will show any modified or new files.

## 3. Stage the Changes
```bash
git add .
```
Or, if you want to add specific files:
```bash
git add filename.html
```

## 4. Commit the Changes
```bash
git commit -m "Added new entry to the archive index"
```

## 5. Push to GitHub
```bash
git push origin main
```
*(If using a different branch, replace `main` with the correct branch name.)*

## 6. Verify the Update
- Go to the GitHub repository and check if the changes are reflected.
- If the site is hosted via GitHub Pages, wait a few minutes for updates to deploy.

---

**Done!** The new entry should now appear on the website. 
