# &lt;weather-el&gt;

A card-style weather panel. Uses icon fonts and the weatherunderground API. 
![screen shot 2014-01-24 at 11 16 31 am](https://f.cloud.github.com/assets/425966/1996356/07793cde-8513-11e3-984f-7c36b7f75bca.png)

> Maintained by [Brad Oyler](https://github.com/bradoyler).

## Demo

> [Check it live](http://bradoyler.github.io/weather-el).

## Run locally (Mac)

```console
		$ git clone https://github.com/bradoyler/weather-el.git
		$ cd weather-el
		$ bower install
		$ python -m SimpleHTTPServer
```

## Usage

1. Import Web Components' polyfill:

	```html
	 <script src="bower_components/platform/platform.js"></script>
     <link rel="import" href="bower_components/polymer-jsonp/polymer-jsonp.html"/>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/weather-el.html">
	```

3. Start using it!

	```html
	<weather-el></weather-el>
	```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`autoupdate`      | *string*                  | `true`               | Updates the current weather every 60 secs


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.0.1 August 19, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License
[MIT License](http://opensource.org/licenses/MIT)

[Inspired by wu-weather](https://github.com/Polymer/wu-weather)
