# Recruitment Role-Play Generator

A classroom web app for randomly assigning students to recruiter/applicant roles and one of three job cases.

## Use

1. Open the published website.
2. Paste each class list into its own box, one student name per line.
3. Choose Class A or Class B.
4. Click **Randomly assign roles & cases**.
5. Each class receives 3 recruiters (one per job); the remaining students are distributed as evenly as possible among the three cases.
6. Each case receives a randomly selected recruitment method, financial reward, non-financial reward and training type.
7. Print/save the results or copy the assignments.

## Publish with GitHub Pages

This repository includes a GitHub Actions workflow at `.github/workflows/deploy.yml`. It builds and deploys the static site to GitHub Pages whenever changes are pushed to `main`.

After the first workflow run completes, open **Settings → Pages** to find the website URL. It should be:

https://neo12phyte.github.io/recruitment-roleplay/

## Privacy

The app runs in the visitor's browser. Student names entered into the page are not uploaded to a database or written to this repository. Do not add student names to source code or commit them to GitHub.
