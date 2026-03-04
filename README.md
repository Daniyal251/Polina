# Wedding Site

This repository contains the assets and HTML/CSS for a simple wedding landing page built from provided invitation content.

## Structure

- `index.html` &mdash; main page with invitation, program, dress code, gifts, venue, gallery.
- `rsvp.html` &mdash; guest RSVP form (mailto-based). Update email address as needed.
- `css/style.css` &mdash; basic styling for layout and responsive design.
- `images/` &mdash; image assets extracted from the PDF and other graphic files.
- `invitation.pdf` &mdash; original PDF invitation.
- `site_text.txt` &mdash; plain text extraction of PDF contents for reference.

## Usage

To preview the site locally, run a simple static server in the project folder:

```powershell
python -m http.server 8000
# or using PowerShell
Start-Process "powershell" -ArgumentList "python -m http.server 8000"
```

Then open `http://localhost:8000` in a web browser.

You can also deploy these files to any static hosting service (GitHub Pages, Netlify, Vercel, etc.).

## Customization

- Replace the placeholder email in `rsvp.html` with a real address or implement a backend form handler.
- Add more images or update text as necessary.
- Edit styles in `css/style.css` for branding or color themes.

> **Дизайн из PDF**
> Оригинальный макет сохраняется на странице через встроенный просмотрщик PDF в секции "Приглашение". Это позволяет гостям видеть приглашение точно так же, как в печатной версии. Пользователи на мобильных устройствах увидят изображение-резервную копию, а при необходимости можно скачать файл.

## Notes

- All content is currently in Russian, taken from the PDF invitation.
- The RSVP form uses `mailto:`; to collect responses automatically, integrate with a server or third-party service.

Enjoy the site, and congrats to Фёдор & Полин! 🎉
