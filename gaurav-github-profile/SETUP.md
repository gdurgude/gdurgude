# Setup

This package is designed to work as a GitHub profile README without custom JavaScript or external README widgets.

## 1. Create the profile repository

Create a public GitHub repository whose name is exactly the same as your GitHub username.

Example:

```text
username: gauravdurgude
repository: gauravdurgude/gauravdurgude
```

GitHub will recognize `README.md` in that repository as your profile README.

## 2. Upload these files

Keep this exact structure:

```text
your-username/
├── README.md
└── assets/
    ├── header.png
    ├── piano-live.gif
    └── equalizer.gif
```

Do not rename the `assets` folder unless you also update the image paths in README.md.

## 3. Update links

Open README.md and verify:

- LinkedIn URL
- Email address
- Project names/descriptions
- Add repository links later if you want each project title clickable

## Why the animation is reliable

GitHub strips JavaScript and most custom styling from README files. This version therefore uses local animated GIF files instead of JavaScript, iframe embeds, or fragile third-party profile services.

The result is intentionally self-contained: if the repository exists and the files are uploaded with the same names, the images and animations should render.

## Optional project links

When your repos are ready, change:

```md
**Lull**
```

to:

```md
[**Lull**](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY)
```

Do the same for the other projects.
