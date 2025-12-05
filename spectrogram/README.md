# Spectrogram

This project uses [Gulp.js](https://gulpjs.com/) as a build tool and task runner to automate development tasks.

## Prerequisites

This project was originally built in 2016 and has been updated to run on modern versions of Node.js (tested on v22+).

The `package.json` includes an `overrides` section to force updated versions of legacy dependencies. This is required for the project to install and run correctly on current Node.js environments.

## Setup

1.  Clone the repository.
2.  Install dependencies using npm:
    ```bash
    npm install
    ```
    *Note: `sudo` is likely not required if you have Node.js and npm configured correctly.*

## Development

To build the project and start a local development server with live-reloading, run:
```bash
npx gulp
```
This will open the project in your default browser. Gulp will watch for file changes and automatically rebuild assets and reload the page.

**This is not an official Google product**