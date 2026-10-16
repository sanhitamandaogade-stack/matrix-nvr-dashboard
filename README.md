# Matrix NVR Web Client

Clickable prototype of the Matrix NVR web client: sign-in, role-based dashboards, widget editing, section pages, issue review with camera media, four colour themes and a responsive mobile layout.

## Try it

Sign in with one of the demo accounts. Every account uses the password `Matrix@123`.

| Username | Role |
|---|---|
| `admin` | Administrator |
| `operator` | Operator |
| `manager` | Manager |

All data is simulated. Changes you make (dashboards, widgets, theme) are saved only in your own browser.

## Hosting

The site is the single file `public/index.html`. `netlify.toml` tells Netlify to publish the `public` folder, open direct links in the app and add security headers. There is no build step.
