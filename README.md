# Tumblr Importer

The Tumblr Importer class is made for [Thimle](https://github.com/oli4jansen/thimble)

## Usage

``` php
$TumblrImporter = new Tumblr_Importer('your public Tumblr API key');
if($TumblrImporter->importBlog('oli4jansen.tumblr.com', 'path/to/blog/data/'))
{
	echo 'Hooray, you\'ll now find a JSON file with the blog data in path/to/blog/data/';
}
```