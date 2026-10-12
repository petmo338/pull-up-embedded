# pull-up.se

Single-page Hugo site for Pull-up Embedded, no theme. Markup in `layouts/index.html`, styles in `assets/css/main.css`. Colours, type and logo follow the graphic profile (`Grafisk_profil_Pull-up_1.pdf`).

    hugo server      # local preview
    hugo --minify    # build to public/

Cloudflare (Workers Builds): root directory `/`, build command `hugo --minify`, deploy command `npx wrangler deploy`, build variable `HUGO_VERSION` = `0.167.0`.
