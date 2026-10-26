# Semester Mark Generator

A simple, responsive web app to calculate internal marks, estimate the final semester total, and find the semester exam score needed to reach the pass mark.

## Features

- Enter CAE 1 marks out of 50
- Enter CAE 2 marks out of 50
- Enter assignment marks out of 20
- Automatically calculate internal marks out of 50
- Try different semester exam marks out of 100
- View the projected final total out of 100
- Calculate the minimum semester exam mark needed to reach 50 overall
- Responsive layout for desktop and mobile
- Built with HTML, CSS, and JavaScript; no installation required

## 🌐 Live Website

**Try the Semester Mark Generator here:**

[Open Semester Mark Generator]([https://mahalakshmi13112006.github.io/Semester-mark-generator-SIST-/](https://mahalakshmi13112006.github.io/Semester-mark-generator-SIST-/?utm_source=chatgpt.com))

A simple, interactive calculator to estimate internal marks, final semester totals, and the minimum exam marks required to reach the pass mark.
## Mark calculation

- **Internal marks** = `(CAE 1 + CAE 2) × 0.3 + Assignment` (capped at 50)
- **Semester contribution** = `Semester exam mark × 0.5`
- **Final total** = `Internal marks + Semester contribution`
- **Pass target used by this calculator** = `50/100`

> Please confirm that these formulas and pass requirements match your institution's current rules.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a web browser.
3. Enter your marks and change the expected semester mark to see the result update automatically.

## Deploy with GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` and `README.md` to the repository's root.
3. Open **Settings → Pages**.
4. Under the build/deployment settings, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then save.
6. Wait for GitHub Pages to publish the site.

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
