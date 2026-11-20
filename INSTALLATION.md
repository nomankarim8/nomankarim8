# Install the Noman Karim profile README

## 1. Open the special profile repository

Open: https://github.com/nomankarim8/nomankarim8

This repository name must match your GitHub username exactly.

## 2. Upload the files

Copy these items from this package into the root of that repository:

- `README.md`
- `assets/`
- `.github/workflows/snake.yml`

Keep the directory structure unchanged. The README uses relative paths such as `./assets/projects/ncover.svg`.

## 3. Enable the contribution animation workflow

In the repository, open **Settings → Actions → General → Workflow permissions** and select **Read and write permissions**. Save the setting.

Then open the **Actions** tab, select **Generate contribution snake**, and choose **Run workflow**. The workflow also runs on pushes to `main` and daily on its schedule.

After a successful run, GitHub will create/update an `output` branch containing the generated snake SVG and GIF. The README uses the GIF from that branch.

## 4. Check the result

Open https://github.com/nomankarim8 and check that the project images and GIFs load. The first contribution-snake image will not appear until the workflow has completed successfully.

## 5. Repository link notes

The README contains direct links for Smart Parking, Ncover, Project NILA, and Admin Panel Finder. The Location Tracker, Hacker Terminal Portfolio, and WiFi_Hack items were named on the portfolio page, but their direct repository URLs were not confirmed when this package was assembled. Their cards therefore link to the public repository list instead of using guessed URLs.

## Notes

- The local project cover images are original SVG artwork made for this profile kit; they are illustrations, not screenshots of the running applications.
- The Smart Parking GIF is based on the generated concept visual and adds a subtle ALPR-detection highlight; it is not a recording of a live system.
- GitHub Stats, streak, typing, visitor-count, and contribution graph widgets depend on external services and may occasionally be delayed or unavailable.
