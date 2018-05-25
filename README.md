[![Published on Vaadin  Directory](https://img.shields.io/badge/Vaadin%20Directory-published-00b4f0.svg)](https://vaadin.com/directory/component/Link2Twentyl2t-paper-color)
[![Stars on vaadin.com/directory](https://img.shields.io/vaadin-directory/star/Link2Twentyl2t-paper-color.svg)](https://vaadin.com/directory/component/Link2Twentyl2t-paper-color)


# l2t-paper-color
Dialogue box for selecting colors

![gif](https://lh3.googleusercontent.com/-PwDk7mMnViE/WTHg2YVFCZI/AAAAAAAAdw4/V8CDBow09tcJMogh3EYGQsMQrMDLxxtkQCL0B/h296/2017-06-02.gif)

## Install with bower

First you need bower, [see their site](http://bower.io/) for details 

```
bower install --save l2t-paper-color
```

## Examples

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="l2t-paper-color.html">
	 <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
  <l2t-paper-color></l2t-paper-color>
```
  
## Styling

The following custom properties are available for styling:

| Custom property | Description | Default |
|----------------|-------------|-------------|
| --l2t-paper-color-width | width of input	 | 120px |
| --l2t-paper-color-indicator-icon | style for color indicator (programmatically set) | transparent |
| --l2t-paper-color-indicator-icon-display | display style for color indicator (programmatically set) | none |

## Attributes

### Public

| Attribute Name | Functionality | Type | Default |
|----------------|-------------|-------------|-------------|
| alwaysFloatLabel | always-float-label: boolean label always in float position | boolean  | false |
| colors | array to store list of colors | Array | false |
| disabled | boolean input diabled | Number | 5 |
| hideAdvanced | boolean to hide advance button | boolean | false |
| label | string to store hex color value | string | "Color select" |
| noLabelFloat | boolean remove label when value contains text | boolean  | false |
| readonly | boolean input read only | boolean | false |
| value | string for value of input | string | "" |

## Methods

### Private

| Method Name | Action |
|----------------|-------------|
| _colorUpdate() | Updates styles to match value |
| _createDialog | Create dialog on first request |
| _dialogHandler(e) | If dialog is confirmed update value |
| _openDialog() | Open dialog if not readonly |
