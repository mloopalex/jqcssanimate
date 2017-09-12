# jqcssanimate
jQuery plugin анимации при скролинге 
с использованием AnimateCss

## Getting Started
### 1. Include [animate.css](http://daneden.github.io/animate.css/)
```html
<head>
  <link rel="stylesheet" href="animate.min.css">
</head>
```
### 2. Include [jQuery](https://jquery.com/) and Scrolla
```html
<script src="jquery.min.js"></script>
<script src="scrolla.jquery.min.js"></script>
```
### 3. Add data attributes
```html
<div class="animate" data-animate="rubberBand" data-duration="1.0s" data-delay="0.1s" data-iteration="1">animate div</div>
```
### 4. Call Scrolla
```javascript
$('.animate').scrolla();
```
## JavaScript Options
```javascript
$('.animate').scrolla({
    mobile: false, // disable animation on mobiles 
    once: false // only once animation play on scroll
});
```
