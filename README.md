# landing-site

[![Netlify Status](https://api.netlify.com/api/v1/badges/42e3c465-1b2f-4b7d-b95f-21713bea2d99/deploy-status)](https://app.netlify.com/sites/heuristic-colden-442ff0/deploys)

Repository hosting static content for https://callscreen.us.
Manual modifications to this repository should not be made.

Content is managed via [Wordpress](https://callscreen.us/wp-admin)
and made static by [WP Static Site Generator](https://wordpress.org/plugins/static-html-output-plugin/).
To generate static content, navigate to [Wordpress](https://callscreen.us/wp-admin)
and click on the WP Static Site Generator menu option.
From there, click the `Start static site export` button.
This populates the `_site/` directory.

Once the static site is exported (process usually takes about 12-18 minutes),
deploy the repository's `_site/` directory via [Netlify](https://netlify.com) using their UI.
