# &lt;form is="xhr"&gt;

An extension for the form tag, providing a way to have forms that do XHR instead of browser requests.

> Maintained by [Filipe La Ruina](https://github.com/filaruina).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="lib/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/xhrform-element.html">
	```

3. Start using it!

	```html
	<form is="xhr" action="/foo/bar" method="get"></form>
	```

## Options

Attribute        | Options                        | Default             | Description
---              | ---                            | ---                 | ---
`is` (optional)  | *string*                       | `normal`            | Defines the type of xhr
`method`         | `get`, `post`, `put`, `delete` | `get`               | Method to use on the request, put and delete available only for xhr


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.0.1 August 26, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)