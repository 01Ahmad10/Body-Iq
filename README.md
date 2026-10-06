# Body IQ Analytics

Static website and 24-question assessment for Body IQ Analytics. The home page uses hash routes for its sections and package pages.

## Run locally

Install [Node.js](https://nodejs.org/) 18 or newer, then run:

```sh
npm start
```

Open <http://localhost:3000/>. The assessment is at <http://localhost:3000/assessment.html>. Set `PORT` to use another port. No package installation or build step is needed.

The browser needs internet access for the React, Babel, and Google Fonts assets loaded from CDNs.

## Deploy

The repository root is the static site. On Vercel, select **Other** as the framework and leave the output directory unset. `vercel.json` configures clean URLs and asset caching.

The in-page chat uses built-in answers unless a host supplies an AI helper. Prices, names, references, and legal text marked “to confirm” are placeholders.
