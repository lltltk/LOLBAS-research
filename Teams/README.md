# Microsoft Teams as a LOLbin

Article link: https://l--k.uk/2022/01/16/microsoft-teams-and-other-electron-apps-as-lolbins/

Proof of concept code as described in the above-linked article.

## AWL Bypass #1: Replace app.asar

1. Backup the existing file at `%LOCALAPPDATA%\Microsoft\Teams\current\resources\app.asar`
1. Copy the `app.asar` file in this repository to: `%LOCALAPPDATA%\Microsoft\Teams\current\resources\`

## AWL Bypass #2: Inject app directory

1. Copy the `app` directory in this repository to: `%LOCALAPPDATA%\Microsoft\Teams\current\resources\`
