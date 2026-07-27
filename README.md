# EndoVasc Bridge IR Request Web App — Version 4

## Main correction

The iPhone Files/WhatsApp document preview does not reliably execute JavaScript. Therefore, interactive controls such as readiness checking, referral generation, WhatsApp sharing, and file sharing may appear but do nothing.

Version 4 is prepared to be published as a real HTTPS website. Open the published link in Safari.

## Laboratory update

WBC and CRP are now separate fields and appear separately in the generated referral.

## GitHub Pages deployment

1. Create a GitHub repository.
2. Upload all files from this folder to the repository root.
3. Open repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save.
7. GitHub will generate an HTTPS website link.
8. Send that website link to referring doctors.
9. They open the link in Safari, complete the form, and use **Send by WhatsApp**.

## Important

This remains a front-end prototype. Do not use real patient-identifying information until the hospital approves the privacy, cybersecurity, authentication, data retention, and communication workflow.
