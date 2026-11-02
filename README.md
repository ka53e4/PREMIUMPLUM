# Premium Plumbing website redesign

A responsive, multi-page static website for Premium Plumbing, designed for deployment on Netlify.

## Included
- Responsive homepage with services, process, about, FAQ and service request form
- Mobile navigation and reduced-motion support
- Netlify Forms markup for service requests
- Custom SVG favicon
- Terms & Conditions and draft Privacy Notice pages
- Customer portal placeholder that does not pretend authentication is functional
- Basic metadata, robots.txt, sitemap.xml, and Netlify headers

## Before going live
1. Replace all placeholder business contact details and service-area references.
2. Confirm the business's actual service list, hours, service areas, and policies.
3. Update `robots.txt` and `sitemap.xml` to use the real production domain.
4. Review the Privacy Notice and Terms & Conditions for the actual business and applicable law.
5. Deploy to Netlify and confirm form detection is enabled. In Netlify, check the deployed site's Forms area and submit a test request. If Netlify Forms is not enabled for the site/account, connect a real form endpoint before collecting customer details.
6. The `thank-you.html` page is only shown after the form posts to the configured action; test the complete flow after deployment.
7. The customer portal is intentionally a placeholder. Do not collect passwords until a secure authentication service and backend are implemented.
8. Replace externally hosted sample photography with approved company photography when available. The images currently load from Unsplash and require internet access.
9. Add the actual domain to the sitemap and submit it in Google Search Console.
10. Run PageSpeed Insights, accessibility checks, and device tests against the deployed site.

## Deploy
Upload the contents of this folder to a new Netlify site or deploy this folder from a Git repository. `netlify.toml` publishes the root directory.
