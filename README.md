livescript-standalone
===

livescript-standalone is a standalone build of livescript for use in non-Node.js environments, including browsers.

Generated by running the following command on the LiveScript github repository
`browserify ./lib/browser.js --standalone livescript -p browserify-derequire > browser/livescript.js`