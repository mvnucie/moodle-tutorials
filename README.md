# NCOS Moodle Tutorials Hub
This repository serves as the **Single Source of Truth** for HTML-based tutorials used across 21+ Moodle courses. By hosting the code here, we can update one file and have the changes reflect instantly across all courses.

## 🚀 The Workflow
1. **Create/Edit:** Use a plain text editor (Notepad) to write HTML with inline styles.
2. **Upload:** Add the `.html` files to this GitHub repository.
3. **Deploy:** GitHub Pages hosts these files at: `https://mvnucie.github.io/moodle-tutorials/[filename].html`
4. **Embed:** Use an `<iframe>` inside a Moodle "Page" activity to display the content.

## 🛠 Maintenance & Updates
To update a tutorial without touching Moodle:
1. Open the file here in GitHub (e.g., `facilitator-guide.html`).
2. Click the **Pencil Icon** to edit.
3. Paste your new code and click **Commit Changes**.
4. *Wait ~60 seconds* for the live site to refresh.

## 🖇 Active Links
* **Facilitator Guide:** [View Live](https://mvnucie.github.io/moodle-tutorials/facilitator-guide.html)
* **Student Guide:** [View Live](https://mvnucie.github.io/moodle-tutorials/student-guide.html)
* **Master Hub:** [View Index](https://mvnucie.github.io/moodle-tutorials/index.html)

## ⚠️ Important Implementation Notes
* **Iframe Code:** Use this snippet in Moodle's HTML view for a clean, responsive look:
  ```html
  <div style="width: 100%; overflow: hidden;">
      <iframe src="YOUR_URL_HERE" style="width: 1px; min-width: 100%; height: 1200px; border: none;" loading="lazy"></iframe>
  </div>
