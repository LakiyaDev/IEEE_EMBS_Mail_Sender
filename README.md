# IEEE EMBS Mail Sender

Responsive HTML email template for the IEEE EMBS Student Branch Chapter, University of Sri Jayewardenepura.

## Files

- `design.html` - responsive email template
- `IEEE EMBS LOGO.svg` - source IEEE EMBS logo
- `Minerva Logo.png` - source Minerva logo

## Before sending

Replace these placeholders in `design.html`:

- `{{NAME}}` - recipient name
- `{{POSITION}}` - selected committee position
- `{{WHATSAPP_LINK}}` - WhatsApp group invite URL
- `{{IEEE_EMBS_LOGO_URL}}` - public HTTPS URL for the IEEE EMBS logo
- `{{MINERVA_LOGO_URL}}` - public HTTPS URL for the Minerva logo

Email recipients cannot load files from your computer. Upload the logos to a public HTTPS host such as your university website, Cloudinary, or a GitHub Pages site. The image URL must open the image directly in a browser.

For best compatibility, export the SVG logo as PNG before hosting it. Keep the current `alt` text so the header remains understandable when images are blocked.

## Preview

For a local preview, temporarily replace the two image URL placeholders with the local filenames:

```html
src="IEEE EMBS LOGO.svg"
src="Minerva Logo.png"
```

Restore the HTTPS URLs before sending.

## Email testing checklist

1. Replace every `{{...}}` placeholder.
2. Send a test to Gmail and Outlook.
3. Confirm both images load and the WhatsApp link opens correctly.
4. Test the email on a phone before sending to the full list.
