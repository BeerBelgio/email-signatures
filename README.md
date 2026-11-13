# Email Signatures

Minimal HTML email signatures for **BeerBelgio** and **sonoDGTL**.

## Files

- `signatures/beerbelgio-en.html` — BeerBelgio (English).
- `signatures/sonodgtl-it.html` — sonoDGTL (Italian).
- `signatures/sonodgtl-en.html` — sonoDGTL (English).
- `assets/beerbelgio-logo.png` — BeerBelgio logo.
- `assets/sonodgtl-monogram.png` — sonoDGTL monogram.
- `.nojekyll` — serves the files directly through GitHub Pages, without Jekyll processing.

## Technical notes

The signatures use table-based HTML, inline CSS, system fonts, selectable text, and clickable links. They contain no JavaScript, web-font dependency, analytics, tracking pixels, or fixed background color.

The logos are separate PNG files, hosted at fixed public GitHub Pages URLs. Text and links remain usable if remote images are blocked. Rendering may vary between Apple Mail, Gmail, Outlook, and their mobile versions.

## Maintenance

Edit the HTML files directly to change text, spacing, or links. Keep the image paths in `assets/` consistent with the public URLs referenced in the signatures. After changing HTML, refresh or reinstall the signature in the email client and verify it in a sent message.

The BeerBelgio and sonoDGTL names, marks, and original artwork remain the property of their respective owner; publication here does not grant permission for third-party reuse.
