[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/rohithsathya/rsat-popup)

# &lt;rsat-popup&gt;

`<rsat-popup>` Is a popup/modal dialog component based on web component v1 standards.

## Demo

## [LIVE DEMO](https://rohithsathya.github.io/rsat-popup/example.html)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install rsat-popup --save
```

Or [download as ZIP](https://github.com/rohithsathya/rsat-popup/archive/master.zip)

## Usage

1. Import Web Components' polyfill (if needed, for older browsers):

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/rsat-popup/rsat-popup.html" />
    ```

3. Start using it!

	```html
	 <rsat-popup pos="center" backdrop="true" show="false">
        <h3>your content goes here</h3>
    </rsat-popup>
	```
#### options
| Options       | Explanation  | Allowed Values  |
| ------------- | ------------- |------------- |
| pos          |defines where to display the popup w.r.t window |'center','top-left','top-right','bottom-left','bottom-right'|
| show         |defines if the popup is shown or not, set to true to display popup  |'true' or 'false'|
|backdrop      |this flag when set to true will draw a backdrop underneath popup | 'true' or 'false'|


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## License

[The MIT License (MIT)](https://opensource.org/licenses/MIT)

Copyright (c) 2017 RSAT