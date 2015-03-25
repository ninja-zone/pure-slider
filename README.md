pure-slider
===========

About
-----

Pure slider written in native web technologies without external libraries.

Assumptions
-----------

* Elements can not change its size.
* Container (contains elements) is scalable to parent container.
* Slider contains two arrows for move view in left and right.
* Slider has pagination for elements.
* After use (click in navigation element) the slider view is set to suitable position.
* After click in any arrow, the slider view is moving by total available view in appropriate direction to next element.


Usage
-----

#### HTML

```html
<script src="lib/pure-slider.js"></script>

<div class="pure-slider">
    <ul>
        <li>1</li>
        <li>2</li>
        <li>3</li>
        <li>4</li>
        <li>5</li>
        <li>6</li>
    </ul>
</div>
```

#### JS

```js
pureSlider.apply('.pure-slider');
```