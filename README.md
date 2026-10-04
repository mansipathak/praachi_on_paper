# Praachi on Paper

Portfolio and book site for Praachi, children's author and illustrator.
Instagram: [@praachi_on_paper](https://www.instagram.com/praachi_on_paper)

A single static page (`index.html`) with no build step, hosted on GitHub Pages.

## Updating the site

- **Book details**: search `index.html` for `class="ph"`. Every highlighted placeholder (title, blurb, price, contact email) is marked with it.
- **Buy links**: replace the `href="#"` on the "Buy on Amazon" and "Bookshop.org" buttons.
- **Instagram posts**: edit the `POSTS` list near the bottom of `index.html`. Add each image to `assets/` and set `img`, `url`, `caption` and `date`.
- **Look**: the "Try a look" button switches between five styles. Once one is chosen, set it as the default and remove the switcher.

## Contact form

The "Write me a letter" form doesn't send anything yet. Connect it to a form service (Formspree, Buttondown, etc.) before launch.
