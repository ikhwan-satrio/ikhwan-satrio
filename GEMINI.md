# Project Overview
This repository contains the GitHub Profile README for **Ikhwan Satrio** (wanto-production). It serves as a personal landing page on GitHub, highlighting a journey through various Linux distributions (Ubuntu, Debian, Arch, and currently NixOS), a diverse tech stack (SvelteKit, Next.js, Astro, Nuxt, and more), and active interests in web performance and open-source contributions.

# Directory Overview
The directory is structured to provide a visually engaging and informative profile page. It utilizes GitHub Actions for dynamic content generation and stores static assets locally.

## Key Files
- `README.md`: The primary file displayed on the GitHub profile. It uses Markdown and HTML for layout, including badges for tech stack identification and links to social profiles.
- `.github/workflows/snake.yml`: A GitHub Action that runs daily to generate a "snake" animation from GitHub contribution graphs. The output is pushed to a dedicated `output` branch.
- `assets/`: Stores local images used in the README, such as the profile banner and Linux "ricing" (customization) screenshots.

# Usage
- **Display**: The contents are automatically rendered by GitHub on the user's profile page.
- **Automation**: The `Generate Snake` workflow runs automatically at midnight (UTC) daily via a cron job, ensuring the contribution animation remains up-to-date.
- **Updates**: To update the profile, modify the `README.md` file or add/replace images in the `assets/` directory.
