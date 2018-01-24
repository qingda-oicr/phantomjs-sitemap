# phantomjs-sitemap-generator [![npm version](https://badge.fury.io/js/phantomjs-sitemap-generator.svg)](https://badge.fury.io/js/phantomjs-sitemap-generator)

A nodejs module to generate sitemaps using PhantomJS

It can fetch AngularJS websites (or similar JS frameworks/libraries)

## Examples

Simple example:

	var PSG = require( 'phantomjs-sitemap-generator' );
	var p = new PSG( 'http://www.blocknot.es', { verbose: true } );
	p.crawl();

See examples folder for another one.
