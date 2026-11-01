# Profile repository notes

## Repository setup

1. Create a **public** repository named exactly `IndrajitSir`.
2. Ensure the repository owner is `IndrajitSir` (the repository must be `IndrajitSir/IndrajitSir`).
3. Upload the contents of this package to the repository root. Include hidden folders such as `.github`.
4. Commit to the default branch (usually `main`).
5. Open **Settings → Actions → General** and ensure workflows have permission to create and approve pull requests / write repository contents where applicable. The workflow declares `contents: write`.
6. Open **Actions → Generate contribution snake → Run workflow** once. The workflow publishes generated SVGs to an `output` branch.
7. After the first successful run, the snake image should appear in the profile README. Scheduled runs refresh it daily.

## Before publishing

- Review the project list and descriptions for accuracy.
- Add LinkedIn and a public contact email only if you want them displayed.
- Confirm the current repository URLs for individual projects before adding direct links.
- Check that the technologies listed under `toolbox` reflect your current experience.
- GitHub statistics and third-party badges are externally hosted and may occasionally be unavailable or rate-limited.

## Included files

- `README.md` — profile page content.
- `assets/header.svg` — custom dark engineering banner.
- `.github/workflows/snake.yml` — daily contribution animation workflow.
- `docs/PROFILE_SETUP.md` — these setup instructions.
