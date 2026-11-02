# CoreBridge Technology Advisory – website package

A responsive, single-page company website built with HTML, CSS and vanilla JavaScript. It has no build step or framework dependency.

## Preview locally

1. Unzip the package (if using the ZIP).
2. Open `index.html` in a modern browser.
3. For best results, serve the folder from a local static web server. For example:

   `python3 -m http.server 8000`

   Then visit `http://localhost:8000`.

## Before publishing

The brand name **CoreBridge Technology Advisory** is provisional. Check trade-name, trademark and domain availability before using it commercially.

### Configure the enquiry form

Open `script.js` and configure one of the following near the top:

- `CONTACT_EMAIL = 'hello@yourdomain.ae'` to open a pre-filled email draft in the visitor's email application.
- `FORM_ENDPOINT = 'https://your-form-service-endpoint'` to submit the form as JSON to your selected form provider/backend. Configure CORS and spam protection with that provider.

The default form does not transmit data to a server. It copies the enquiry text where browser clipboard permissions allow and tells the visitor that the form is a preview.

## Content and publication checks

- Replace the provisional brand and confirm the exact licensed company name and activities.
- Add the final company email, telephone number, business address (if desired), domain and social links.
- Obtain permission before publishing employer/client names, logos, project details, screenshots or performance metrics from previous roles. This version intentionally avoids naming previous employers or asserting client case studies.
- Review all claims, industry experience and service descriptions for accuracy before publication.
- Add a privacy notice and terms appropriate to the final enquiry processing method and applicable UAE requirements.
- Connect analytics and a privacy-conscious cookie solution only if needed.
- Have a qualified adviser review the final website and regulated-service boundaries before launching.

## Files

- `index.html` – page structure and copy
- `styles.css` – responsive visual design
- `script.js` – mobile navigation and enquiry form behaviour
- `assets/favicon.svg` – site favicon
