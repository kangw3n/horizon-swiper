# Horizon Swiper
#### Version 1.1.1

You will love this light (~ 7kb) free swiper.
It comes with many options and it works with your simple native browser scrolling.
Try it on touch devices!

## Documentation
[http://horizon-swiper.sebsauer.de](http://horizon-swiper.sebsauer.de)

### HTML
```
<div class="horizon-swiper">
  <div class="horizon-item"></div>
  <div class="horizon-item"></div>
  <div class="horizon-item"></div>
</div>
```

### Javascript
```
$('.horizon-swiper').horizonSwiper();
```

### With Menu Active
```
$('.horizon-swiper').horizonSwiper({
  checkOn: true, // default true, to enable active position to be visible in view while item itself is out of position
  onClass: 'on', // default on, set class name that represent current active pages or classes.
  });
```



### Browser support
* Google Chrome
* Mozilla FireFox
* Safari
* Internet Explorer (11, 10, 9, 8)
* Microsoft Edge

## Author
Sebastian Sauer - [http://www.sebsauer.de](http://www.sebsauer.de)
