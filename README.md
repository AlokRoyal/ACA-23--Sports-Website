# MS Dhoni Tribute Website

![HTML](https://img.shields.io/badge/HTML5-page%20structure-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-styling-1572B6?logo=css3&logoColor=white)

A static tribute page about Mahendra Singh Dhoni. It presents a biography and selected achievements in a cricket-themed layout with photographic backgrounds and player imagery.

## What it demonstrates

- Organizing a single page into hero, biography, and achievements sections
- Styling a page with CSS backgrounds, flex layout, typography, and hover transitions
- Referencing local image assets from a static site

## Page contents

The hero introduces the tribute. The biography section summarizes Dhoni’s playing career and milestones. The achievements section presents selected awards and records beside a player image. This is a hand-authored static page; content is not loaded from an API or database.

## Architecture

Browser → index.html → style.css + local JPG image assets

The HTML defines the page structure. CSS controls the presentation and loads the background images. No JavaScript application or server-side component is required.

## Start locally

1. Clone or download this repository.
2. Keep the JPG assets in the repository root.
3. Open index.html in a modern browser.

There is no package installation or build step. For a hosted preview, publish the complete repository as a static site.

## Project layout

- index.html — markup and tribute content
- style.css — layout, backgrounds, colors, text, and hover effects
- Dhoni.jpg — player image
- First Background.jpg and Sec background.jpg — section backgrounds

## Notes

Image paths are rooted at the site directory, and filenames contain spaces and capitalization. Preserve them exactly on case-sensitive hosting. The repository does not include a license file; check ownership and reuse permissions for the included images before redistributing them.