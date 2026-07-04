# Personal Homepage Template

This is a simple GitHub Pages template that follows the same basic structure as the reference academic homepage:

- top navigation
- profile photo and short bio
- selected publications on the main page
- separate full publications page
- CV and email links

## What to Change

Search for `YOUR_` across the folder and replace each placeholder.

Required edits:

- `YOUR_NAME`: your full name
- `YOUR_POSITION`: e.g. M.S. Student, Ph.D. Student, Undergraduate Researcher
- `YOUR_LAB_NAME` / `YOUR_LAB_URL`: your lab name and URL
- `YOUR_ADVISOR_NAME` / `YOUR_ADVISOR_URL`: advisor name and URL
- `YOUR_DEPARTMENT`: department name
- `YOUR_UNIVERSITY` / `YOUR_UNIVERSITY_URL`: university name and URL
- `YOUR_CITY`, `YOUR_COUNTRY`: location
- `YOUR_RESEARCH_AREA_*`: short research keywords
- `YOUR_RESEARCH_INTEREST_SENTENCE`: one sentence about your research
- `YOUR_EMAIL`: your email address
- `YOUR_CV_FILE.pdf`: your CV file name
- `YOUR_VENUE_*`: e.g. CVPR, ICCV, NeurIPS, AAAI, WACV
- `YOUR_PAPER_TITLE_*`: paper titles
- `YOUR_AUTHOR_LIST_*`: author lists
- `YOUR_CONFERENCE_OR_JOURNAL_*`: full conference or journal names
- `YOUR_YEAR_*`: publication years
- `YOUR_PDF_URL_*`, `YOUR_CODE_URL_*`, `YOUR_PROJECT_URL_*`: links

## Profile Photo

Replace this file:

```text
assets/img/profile-placeholder.svg
```

with your own image, or put your photo at:

```text
assets/img/profile.jpg
```

Then update `index.html`:

```html
<img class="profile-photo" src="assets/img/profile.jpg" alt="Profile photo of YOUR_NAME">
```

## CV

Put your CV PDF inside:

```text
files/
```

For example:

```text
files/cv.pdf
```

Then update the CV link in `index.html`:

```html
<a href="files/cv.pdf">CV</a>
```

## Publish on GitHub Pages

1. Create a GitHub repository named:

```text
YOUR_GITHUB_ID.github.io
```

2. Upload all files in this folder to that repository.
3. Go to `Settings > Pages`.
4. Use the `main` branch as the source.
5. Your page will be available at:

```text
https://YOUR_GITHUB_ID.github.io/
```
