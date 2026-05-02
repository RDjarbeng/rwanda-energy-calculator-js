# Rwanda Energy Calculator — Netlify Site

A fully static, zero-dependency web app for calculating Rwanda Energy Group (REG) electricity costs.

## Deploy to Netlify

1. Push this folder (or its contents) to a GitHub repository.
2. Log in to [Netlify](https://netlify.com) and click **Add new site → Import an existing project**.
3. Connect your GitHub repo.
4. Build settings:
   - **Build command:** *(leave empty)*
   - **Publish directory:** `.`
5. Click **Deploy site**.

That's it. No build step, no server — pure HTML/CSS/JS.

## Features

- Calculate electricity units from a payment amount (RWF → kWh)
- Optional previous-balance field for accurate tier-offset pricing
- Calculate cost from units consumed (kWh → RWF)
- Toggle between October 2025 tariffs and 2020–2025 tariffs
- Full tier breakdown with VAT shown separately
- Fully responsive, works on mobile
- Real-time calculations as you type
