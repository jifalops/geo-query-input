[![Published on Vaadin  Directory](https://img.shields.io/badge/Vaadin%20Directory-published-00b4f0.svg)](https://vaadin.com/directory/component/jifalopsgeo-query-input)
[![Stars on vaadin.com/directory](https://img.shields.io/vaadin-directory/star/jifalopsgeo-query-input.svg)](https://vaadin.com/directory/component/jifalopsgeo-query-input)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/jifalops/geo-query-input)

# geo-query-input
Specify the center point and search radius for geographical queries.

## Installation

```
bower i -S geo-query-input      # Polymer 2.0 hybrid (1.x compatible)
bower i -S geo-query-input#^0.3 # Polymer 1.x based
```

## Usage
* Bind to the `query` property.
* Supply a Google Maps API key (will be optional in the future)

## Demo
<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="geo-query-input.html">
    <div>
      <dom-bind>
        <template is="dom-bind">
          <next-code-block></next-code-block>
        </template>
      </dom-bind>
    </div>
  </template>
</custom-element-demo>
```
-->

```html
<geo-query-input query="{{query}}" api-key="AIzaSyAUPOaJubJnaRTPUd_xX8MOA62gRtSlfCc"></geo-query-input>
<div>lat: [[query.lat]]</div>
<div>lng: [[query.lng]]</div>
<div>radiusKm: [[query.radiusKm]]</div>
<div>fromSearch: [[query.fromSearch]]</div>
<div>valid: [[query.valid]]</div>
```

Full demo:
[webcomponents.org](https://www.webcomponents.org/element/jifalops/geo-query-input/demo/demo/index.html)
| [github](https://jifalops.github.io/geo-query-input/components/geo-query-input/demo/).

API: [webcomponents.org](https://www.webcomponents.org/element/jifalops/geo-query-input/geo-query-input)
| [github](https://jifalops.github.io/geo-query-input).


## Contributing

1. Fork it on Github.
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## License

[MIT](https://opensource.org/licenses/MIT)
