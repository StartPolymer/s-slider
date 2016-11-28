[![Published on webcomponents.org][webcomponents-image]][webcomponents-url]

# \<s-slider\>

Up-to-date fork of [\<paper-slider\>](https://github.com/PolymerElements/paper-slider) with new features.

Material design: [Sliders](https://www.google.com/design/spec/components/sliders.html)

`s-slider` allows user to select a value from a range of values by
moving the slider thumb.  The interactive nature of the slider makes it a
great choice for settings that reflect intensity levels, such as volume,
brightness, or color saturation.

## New features

- `deselected` property
- `--s-slider-expanded-knob` mixin applied to the expanded knob

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="s-slider.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<s-slider value="50"></s-slider>
<s-slider value="21" deselected></s-slider>
```

[webcomponents-image]: https://img.shields.io/badge/webcomponents.org-published-blue.svg
[webcomponents-url]: https://beta.webcomponents.org/element/StartPolymer/s-slider
