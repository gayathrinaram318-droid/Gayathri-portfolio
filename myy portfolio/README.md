# Naram Gayathri — Portfolio Starter

A responsive dark navy + teal portfolio built with HTML, CSS, and JavaScript.

## Open locally
1. Extract this folder.
2. Open it in VS Code using **File → Open Folder**.
3. Double-click `index.html` to preview it in a browser, or use VS Code Live Server.

## Personal details already added
- Name: Naram Gayathri
- Email: gayathrinaram318@gmail.com
- GitHub: https://github.com/gayathrinaram318-droid
- LinkedIn: https://www.linkedin.com/in/gayathri-naram-7bb269367

## Add your photo
The hero currently uses a stylized initials placeholder (NG). Put your photo in `assets/profile.jpg`, then replace the `.profile-placeholder` element in `index.html` with:
`<img class="profile-photo" src="assets/profile.jpg" alt="Naram Gayathri" />`
Add this CSS rule to `style.css`:
`.profile-photo{width:min(290px,70vw);aspect-ratio:1;object-fit:cover;border-radius:50%;border:5px solid var(--teal);outline:4px solid #132a4b;box-shadow:0 0 55px #20c9b333}`

## Resume
When you have a resume PDF, save it as `assets/resume.pdf`. The resume button already points to that location.

## Certificates
Put actual PDFs in `assets/certificates/` using the filenames referenced in `index.html`, or update the corresponding `href` to match your filenames. The buttons will open the actual PDF in a new tab once the file exists. Do not publish placeholder certificate links.

## Verify before publishing
Education and internship sections have been updated from your resume. Check project placeholder links and certificate PDF filenames before publishing.


Internship section lists AVAINTERN — Full Stack Intern (April 2026) and ExcelR — Python / Python Django Intern (April 2026), based on the supplied resume.
