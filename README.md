# neosnippet_chef_recipe_snippet

This is vim snippet for Chef. You can use this snippet with NeoSnippets.

<img src="https://gist.github.com/ryuzee/7b02a2a1026b57614835/raw/2a238c0ff067f55dd212ff60b8dbf289f56ceb00/chef_snippet.png" />

## Install

### Bundle

Add these lines as follows.

	Bundle 'ryuzee/neocomplcache_php_selenium_snippet'
	let g:neosnippet#snippets_directory='~/.vim/bundle/neosnippet_chef_recipe_snippet/autoload/neosnippet/snippets'

Then install snippet.

	:BundleInstall

## Usage

Set filetype as follow

	:set filetype=ruby.chef

or you can set this option in your recipe as follow.

	# vim: filetype=ruby.chef

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
