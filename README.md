# Panika Production Agency

Static production build for https://panikaprod.github.io/.

GitHub Pages serves the site files. Forms are processed by a separate Google
Apps Script deployment and saved in a private Google spreadsheet before
Telegram notification delivery. This repository contains no bot credentials,
spreadsheet records, local environment files, or private server configuration.

Publish from the `main` branch, root directory (`/`). The `.nojekyll` file is
required so GitHub serves the `_next` assets without Jekyll processing.

The editable project and build scripts are maintained separately. Do not edit
compiled JavaScript by hand or upload secrets into this public repository.
