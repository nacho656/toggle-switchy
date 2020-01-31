# Toggle Switchy
A pure CSS toggle switch for form input checkboxes

## Preview
<img src="http://adamculpepper.net/repos/preview-toggle-switchy-github.png">

## Installation

### CSS
```<link rel="stylesheet" href="toggle-switchy.css">```

### HTML
```
<label for="ID_HERE" class="toggle-switchy">
	<input checked type="checkbox" id="ID_HERE">
	<span class="toggle">
		<span class="switch"></span>
	</span>
</label>
```

## Options

| Option | Class |
| ------ | ------ |
| Rounded | `tgsw-rounded`
| No Text | `tgsw-text-off`
| Disabled | add the `disabled` attribute to the input tag
| Sizes | `tgsw-xl`<br>`tgsw-lg`<br>medium (default)<br>`tgsw-sm`<br>`tgsw-xs`
| Colors | `tgsw-red`<br>`tgsw-orange`<br>`tgsw-yellow`<br>`tgsw-green`<br>`tgsw-blue`<br>`tgsw-purple`<br>`tgsw-gray`
| Labels | `tgsw-label-left`<br>label on right (default)<br>

## Features
* CSS only - no JavaScript!
* No dependencies
* Fully reponsive
* Fully customizable
* Fully self contained
* 7 color schemes
* Labels on the left and the right
* Supports all modern browsers
* Search engine friendly
* Screen reader friendly
* Doesn't dump a bunch of global styles that'll screw with your other CSS

## TODO
* Better a11y (accessibility) support

## Known Issues
* IE10 and below doesn't support the smooth slide

#### See also [Toggle Radios](https://github.com/adamculpepper/toggle-radios) - A CSS only toggle switch for form input checkboxes (not Bootstrap dependent)
