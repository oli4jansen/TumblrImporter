# Tumblr Importer

The Tumblr Importer class is made for [Thimle](https://github.com/oli4jansen/thimble). It imports Tumblr blog info and posts for use with the Thimble theme parser.

## Usage

``` php
$TumblrImporter = new TumblrImporter\Importer('your public Tumblr API key');
if($TumblrImporter->importBlog('oli4jansen.tumblr.com', 'path/to/blog/data/'))
{
	echo 'Hooray, you\'ll now find a JSON file with the blog data in path/to/blog/data/';
}
```