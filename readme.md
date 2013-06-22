DocPad template for a site.
This is a demo site. Example on how to use DocPad templates.

# Setup DocPad #

To install docpad:
	npm install -g docpad@6.38

If upgrading, run
	rm -Rf node_modules; npm install

Run "npm install" to install all the required packages.
The root directory, from which to run npm, is the one containing this file.

For issues with proxy, check 
http://alensiljak.blogspot.co.at/2013/01/npm-proxy-configuration.html

# Setup modules #

Modules are installed with "npm install" since they are listed in packages.json. They can also be installed manually:

npm install --save docpad-plugin-eco docpad-plugin-marked
npm install --save docpad-plugin-partials


# Running #

To run:
	docpad run
Generated files are in out/ directory.

The local web site is served at
http://localhost:9778/

# Additional #

Install Live Reload plugin to have browser refresh on every source update.
	npm install --save docpad-plugin-livereload
