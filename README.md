# bootstrap-template

[bootstrap-template](https://github.com/thecdil/bootstrap-template) is a basic template repository to create a [Bootstrap](https://getbootstrap.com/) site using Jekyll on GitHub Pages (or where every you want to host it). 
The layout is based on the [Bootstrap starter template example](https://getbootstrap.com/docs/4.5/examples/) with a navbar, search box (using lunr.js), and sticky footer.
It is intended as a quick starting point for creating new web projects.

Demo: <https://thecdil.github.io/bootstrap-template/>

## Get Started 

- Click green "Use this template" button to make a new copy of the code (alternatively, use Import or manually copy files)
- Edit `_config.yml` with your site information
- In your new repository visit "Settings" to activate GitHub Pages
- Edit and create pages in the "pages" folder (probably in Markdown). Use page yml front matter to populate the navbar:
    - `title` will appear as h1 at top of the page content.
    - `nav` if this option has a value, it will appear in the navbar as link to this page.
    - `nav_order` navbar items will be sorted using this number. 
- Use `includes` to simplify adding Bootstrap features to Markdown pages (see comments in `_include/` files for instructions).

See [docs/create-website.md](https://github.com/thecdil/bootstrap-template/blob/main/docs/create-website.md) for more details.

## Customize 

- Tweak base variables in `assets/css/custom.scss` (text color, link color, container size)
- Tweak bootstrap theme colors using `_data/theme-colors.csv` (add a css color in the color column next to the BS color-class to override, or create a new class name. This will generate btn-, text-, and bg- classes.)
- Add custom CSS to `_sass/_custom.scss` (content of `_sass/_template.scss` relates to template components)
- Use Bootstrap to customize `_layouts/` and `_includes/template/`.

## Template Assets

Included in assets/lib folder:

- [Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/) 4.5.3
- [JQuery](https://jquery.com/) 3.5.1
- [Bootstrap Icons](https://icons.getbootstrap.com/) 1.1.0
- [lunr.js](https://lunrjs.com/) 2.3.9
