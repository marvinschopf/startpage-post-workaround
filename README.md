# startpage-post-workaround

A simple HTML page to be hosted locally, using the given `?q=%s` GET parameter to call the Startpage.com search with the request as POST parameter, so that the query is not transmitted and logged unencrypted.

## Usage

Add a custom search engine to your browser. Set the query URL to the local file, for example, for macOS and Chrom(e|ium- based Browsers):

`file:///Users/marvin/Documents/startpage-post-workaround/index.html?q=%s`
