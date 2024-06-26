# Thanks
All of this lovely code is written by `Pascal Betting`. Thanks to them for that! I have literally changed one line to set the due date of the tasks to "today"
The original project is located here:
https://github.com/pascalbe-dev/ulauncher-todoist-capture

# ulauncher-todoist-capture

> [ulauncher](https://ulauncher.io/) Extension to capture an idea in your [Todoist](https://todoist.com/) inbox.

## Demo

https://github.com/pascalbe-dev/ulauncher-todoist-capture/assets/26909176/27b6ec34-4599-4f61-a358-89e2a0587130

## Features

- write idea and store it into todoist

## Requirements

- [ulauncher 5](https://ulauncher.io/)
- Python > 3

## Installation

Open ulauncher preferences window -> extensions -> add extension and paste the following url:

`https://github.com/pascalbe-dev/ulauncher-todoist-capture.git`

## Configuration

- Before usage you need to configure your Todoist API token in plugin preferences. Find or create your API token [here](https://app.todoist.com/app/settings/integrations/developer).

## Contribution

Please refer to [the contribution guidelines](./CONTRIBUTING.md)

## Local development

### Requirements

- `less` package installed
- `inotify-tools` package installed

### Steps

1. Clone the repo `git clone https://github.com/pascalbe-dev/ulauncher-todoist-capture.git`
2. Cd into the folder `cd ulauncher-todoist-capture`
3. Watch and deploy your extension locally for simple developing and testing in parallel `./watch-and-deploy.sh` (this will restart ulauncher without extensions and deploy this extension at the beginning and each time a file in this directory changes)
4. Check the extension log `less /tmp/ulauncher-extension.log +F`
5. Check ulauncher dev log `less /tmp/ulauncher.log +F`
