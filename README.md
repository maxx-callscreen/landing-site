# landing-site

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
