# Faculty Profile Website

This is a lightweight public faculty profile site designed for GitHub Pages.
It has no build step: GitHub can publish the files directly.

## Edit Your Details

Update the placeholder content in `index.html`:

- `Your Name, Ph.D.`
- department, university, office, office hours, and recruiting status
- research description and interest tags
- publications, courses, students, and news
- email address and profile links
- the editable CV page in `cv.html`

Replace the generated banner at `assets/faculty-profile-hero.png` if you want a
different hero image. To use a headshot, replace the `.profile-photo` block in
`index.html` with an image:

```html
<img class="profile-photo" src="assets/headshot.jpg" alt="Your Name">
```

Then add `assets/headshot.jpg`.

## Publish on GitHub Pages

Option A: user site

1. Create a public repository named `yourusername.github.io`.
2. Add these files to the repository.
3. Push to the `main` branch.
4. Open `https://yourusername.github.io`.

Option B: project site

1. Create any public repository, for example `faculty-profile`.
2. Add these files to the repository.
3. In GitHub, open Settings -> Pages.
4. Set the source to deploy from the `main` branch root.
5. Open the URL shown by GitHub Pages.

## Local Preview

Open `index.html` in a browser. Because this is a static site, no local server is
required.
