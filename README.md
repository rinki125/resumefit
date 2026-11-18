# ResumeFit – AI Resume Analyser & Job Match

Upload a resume (PDF or text), paste a job description and get a match score, missing skills, ATS checks, best-fit roles and interview questions. Runs fully in the browser.

## Features
- Match score = 0.65 × skill coverage + 0.35 × TF-IDF cosine similarity
- Skill dictionary with aliases (50+ skills)
- 9 ATS checks, best-fit roles, interview questions
- PDF reading with pdf.js, drag and drop, dark mode, print report

## Tech
HTML, CSS, JavaScript, TF-IDF, cosine similarity, pdf.js

## Deploy on GitHub Pages
1. Create a new repository on GitHub, for example `resumefit`.
2. Upload `index.html` and `README.md` to the repository (Add file > Upload files).
3. Go to **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. After 1–2 minutes your site is live at `https://your-username.github.io/resumefit/`.

## Before you submit
- In `index.html`, search for `Your Name` and `your-username` and replace them with your own.
