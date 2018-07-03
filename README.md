# simple_bar_chart
Bar chart library


![Packagist](https://img.shields.io/packagist/l/doctrine/orm.svg)
![Codacy grade](https://img.shields.io/codacy/grade/e27821fb6289410b8f58338c7e0bc686.svg)
![Chrome Web Store](https://img.shields.io/chrome-web-store/stars/nimelepbpejjlbmoobocpfnjhihnpked.svg)

## Description
Simple, light, easy to use Bar Chart Library.

![](https://github.com/witekk9/simple_bar_chart/blob/master/bar.PNG)

## Installation
Just download bar.min.js from dist directory and include it to your project:

```html
<script src="bar.min.js"></script>
```
## Usage
Create a block lavel container like div.

```html
<div id="chart"></div>

Then create new BarChart object in your js file.

```js
var chart = new BarChart(chartId, chartWidth, chartHeight, data);
```

### Parameters
- `chartId - containerId (string)`
Id of the chart container you created

- `chartWidth (integer)`
Width of the chart

- `chartHeight (integer)`
Height of the chart

- `data (Objects Array)`
The data object. Example: 

```js

var data = [
  {label: 'Jan', value: 100},
  {label: 'Feb', value: 200},
  {label: 'March', value: 50},
  {label: 'April', value: 100},
  {label: 'May', value: 300}
];

```

## License
[MIT](LICENSE.md) © [witekk9](https://github.com/witekk9)
