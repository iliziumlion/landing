# Landing

  Landing page effects & scroll spy script

## Instalation

  Via script tag in page sources:

```html
<script src="/static/js/landing.min.js">
```

  Set landing sections classes:

```html
<body data-landing=".landing-section" data-landing-nav=".landing-nav">
```

* `data-landing` - landing sections class
* `data-landing-nav` - scroll spy navigation class

## Effects

Effects defining through setting element attributes with start value.

### landing-opacity

  Opacity

```html
<h2 landing-opacity="0">...</h2>
```

### landing-x
  
  Horizontal movement

```html
<h2 landing-x="-350px">...</h2>
```

### landing-y

  Vertical movement

```html
<h2 landing-y="-200px">...</h2>
```

### landing-rotation

  Rotation

```html
<h2 landing-rotation="60deg">...</h2>
```

### landing-scale

  Rescaling

```html
<h2 landing-scale="0.5">...</h2>
```

## API

### landing.on(event, callback)

  Set function called by change current section

```js
landing.on('change', function(cur) {
  console.log(cur);
});
```

## Support

* Chrome
* Safari
* Firefox
* Opera
* Internet Explorer 9+