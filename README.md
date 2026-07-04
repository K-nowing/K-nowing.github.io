# Injae Kim Homepage

This repository contains the source for:

```text
https://K-nowing.github.io/
```

## Update Checklist

The homepage follows an al-folio-style academic layout with:

- a fixed top navigation bar
- profile image and short bio on the about page
- selected publications on the about page
- a full publication list at `/publications/`

Academic content has been filled from the public Google Scholar profile:

```text
https://scholar.google.co.kr/citations?user=PS_6As8AAAAJ&hl=en
```

Remaining optional edits:

- Replace the profile placeholder image.
- Add email, CV, GitHub, or lab links if desired.
- Update publications when new papers are accepted or metadata changes.

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
<img class="profile-photo" src="assets/img/profile.jpg" alt="Profile photo of Injae Kim">
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
