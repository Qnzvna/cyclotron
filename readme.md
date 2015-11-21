# Cyclotron
Inspired by [here](https://github.com/mahonnaise/cyclotron)

## 1. You need some element, div will be the best option. E.g.:

```html
<div class="cyclotron" style="height:512px"></div>
```

## 2. Cyclotronify:

```javascript
$(document).ready(function ($) {
	$('.cycle').cyclotron(moveable, autoscroll, dunpingFactor, historySize);
});
```

## 3. Options:

`moveable` - boolean value; if true user can drag panorama (default: true)

`autoscroll` - boolean value; if true panorama is moving automatically (default: true)

`speed` - integer value; speed of autoscrolling (default: 10)

`dampingFactor` - should be somewhere around 0.9, should be > 0 and < 1 (default: 0.93)

`historySize` - size of the array which stores the deltas (default: 5)
