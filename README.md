# SchoolHop Foundation Website

Responsive React-enhanced website for SchoolHop Foundation, a fictional
non-profit providing safe rural school transport in the Eastern Cape.

## Features

- Responsive single-page website with accessible content and clear calls to action.
- React components for email signup, audience segments, campaign dashboard, lead
  capture, routing and final delivery evidence.
- React Router DOM `HashRouter` routes:
  - `#/home`
  - `#/impact`
  - `#/sponsor`
  - `#/contact`
- Interactive forms with required-field and email validation.
- Three-step sponsorship journey: sponsor details, support selection and
  confirmation before submission.
- Clear success and error messages.
- Browser `localStorage` lead storage under the `schoolhop-leads` key.
- Campaign dashboard with realistic sample data, KPIs, measurement plan,
  interpretation and optimisation recommendations.
- Welcome and promotional email copy with website-linked calls to action.
- Target-audience profiles with motivations, objections, needs and channels.
- Awareness-to-advocacy digital-marketing funnel.
- SEO keyword strategy, paid-search advert and monthly budget assumptions.
- Five social-media posts and a one-week content calendar.
- Customer persona, one-page optimisation recommendation, contribution log and
  individual learning reflection are included in the final delivery section.
- Detailed SEO keyword groups and on-page implementation checklist.
- Controlled paid-search pilot with CPC, traffic, enquiry and budget assumptions.
- Expanded sample email-funnel interpretation and pre-production testing checklist.
- Landing-page variants and an A/B testing hypothesis.
- Usability-test report and feedback-based improvements.
- Platform diagnostic for the final demonstration.

## Run locally

1. Open `index(schoolhopweek5).html` in a modern browser.
2. Ensure the browser can access the React, ReactDOM, React Router DOM and
   Babel CDN scripts.
3. Use the **Run platform check** button in the final delivery section.
4. Test the newsletter signup and lead form. Submitted demo leads are stored
   only in the current browser.

For more reliable local serving, run any static web server from this folder,
then open the displayed local URL. No build step is required for this
single-file demonstration.

## Project structure

```text
index(schoolhopweek5).html  Main website, React components and styles
README.md                   Project setup, feature and deployment notes
```

## Data and privacy

The demo stores lead records in browser `localStorage` as JSON containing a
name, email, interest and timestamp. This is intentionally a front-end
demonstration. Production use requires a secure HTTPS API or CRM, server-side
validation, access controls, retention rules, consent records and a privacy
policy. Do not use the demo storage for real sensitive customer data.

## Testing checklist

- Test each `#/home`, `#/impact`, `#/sponsor` and `#/contact` route.
- Confirm primary and secondary calls to action reach their destinations.
- Submit valid and invalid newsletter and lead forms.
- Confirm success and error messages are understandable.
- Confirm a successful lead submission increments the dashboard count.
- Test keyboard navigation and a narrow mobile viewport.
- Run the built-in platform check and resolve any failed checks.

## Deployment

The site can be deployed as a static page using GitHub Pages, Netlify or
Vercel:

1. Create a GitHub repository and push this folder.
2. Publish the folder as a static site, with the HTML file as the entry point.
3. Confirm HTTPS, CDN availability, responsive layout, form behavior and
   `localStorage` after deployment.
4. Replace the demo storage with a secure API before accepting real enquiries.

The repository includes `.github/workflows/deploy-pages.yml`, which copies the
long source filename to `site/index.html` and deploys it automatically on
pushes to `main`. In GitHub, enable **Settings → Pages → Source: GitHub
Actions** once. After the workflow succeeds, the public URL will be:
`https://anga-14.github.io/SchoolHop-3/`.

## Assessment handover

The deployed application includes the target-audience profile, named customer
persona, funnel, campaign strategy, SEO and paid-search plan, social assets,
two-email sequence, KPI and measurement plan, analytics dashboard, data-based
optimisation recommendation, individual contribution log and learning
reflection. The final group presentation remains a separate deliverable.

## Campaign summary

The sample dashboard uses 4,820 visitors, 318 email subscribers, a 42% email
open rate, 96 CTA clicks and 18 sponsorship applications. The open rate exceeds
the 40% KPI, while the calculated 2.0% CTA rate is below the 2.5% target.
Recommended next steps are to test the action-led headline, simplify the
sponsorship form, segment follow-up emails and retarget engaged non-converters.

## License

This educational demonstration is provided for the SchoolHop Foundation
project. Replace third-party image assets and confirm their licences before
public launch.
