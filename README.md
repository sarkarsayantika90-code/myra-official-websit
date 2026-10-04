# MYRA AI — Official Website

A polished, mobile-first official download website for MYRA AI.

## Files
- `index.html` — website
- `style.css` — design and responsive layout
- `config.js` — APK download URL and version
- `.github/workflows/pages.yml` — automatic GitHub Pages deployment

## Set your APK link
Open `config.js` and replace `apkUrl` with the direct GitHub Release asset URL.

Example:
`https://github.com/USERNAME/REPOSITORY/releases/latest/download/MYRA.apk`

The website does not store the 80–90 MB APK itself. The download buttons point to the GitHub Release asset.

## GitHub Pages
Create a public repository, upload these files to the root, then enable GitHub Pages using GitHub Actions. GitHub Pages uses `index.html` as the entry file. 
