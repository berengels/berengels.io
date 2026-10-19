# Bér Engels

Eenvoudige statische website voor Bér Engels. HTML en CSS, zonder JavaScript, cookies, tracking of externe lettertypediensten.

## Publicatie

GitHub-repository: https://github.com/berengels/berengels.io

GitHub Pages: https://berengels.github.io/berengels.io/

De workflow in `.github/workflows/pages.yml` publiceert de map `public` na een push naar `main`. GitHub Pages moet ingesteld staan op GitHub Actions.

## Lokaal bekijken

Start vanuit deze map: `python3 -m http.server 4173 --bind 127.0.0.1 --directory public`.

Open daarna http://127.0.0.1:4173/.

## Aanpassen

- Tekst en volgorde: `public/index.html`.
- Vormgeving: `public/assets/css/index.css`.
- Contactadres: twee mail-links in `public/index.html`.
- Foto’s: `public/assets/images`, in twee formaten voor mobiel en desktop.

De tekst komt uit het gesprek met Bér op 19 oktober 2026. De gewenste typering van zijn werkwijze is als eigen tekst verwerkt, zonder een fictieve klantgetuigenis.

## Credits

De drie door Bér aangeleverde Unsplash-foto’s:

- Michiel Ronde — `michiel-ronde-p7S6AxykCl0-unsplash.jpg` (bergen).
- Hannah Vorenkamp — `hannah-vorenkamp-mUfFvKR-xeY-unsplash.jpg` (sequoia’s).
- Presetbase — `presetbase-lightroom-presets-QN6NkYi3CKs-unsplash.jpg` (paddenstoelen).

Lettertype: Inter, lokaal opgeslagen. Zie `public/assets/fonts/OFL.txt` voor de licentie.
