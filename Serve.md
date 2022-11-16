## How to test pages with local server

Site content is rendered to the /docs directory, which is served via GH Pages.

Building and running the site
Run npm install, to setup dependencies.
Run gulp watch, which will compile changes every time you save a file and output the completed static pages.
If you don't already have the NPM serve package installed, install it globally with npm -g install serve.
CD into the /docs directory (cd docs) and run the serve command. This will start a local server that allows you to view the site via a localhost port.
