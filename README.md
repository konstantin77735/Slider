Слайдер на чистом JS (без библиотек и зависимостей). Можно указать количество слайдов, скорость, автоматическую прокрутку, направление прокрутки, наличие точек и стрелочек и т.д.

Slider in pure JS (no libraries and dependencies). You can specify the number of slides, speed, auto scrolling, scrolling direction, dots and arrows, etc.

```
 
  let firstSlider = new Slider('.slider1', {
            //currentSlide: 1, // default = 0
            slidesToShow: 1, //slides on screen
            speed: 500, //ms, default = 1000
            //animationType: 'linear', // default = ease
            //keysEnable: false// default = true
            //autoplay: true, // default = false
            //autoplayDirection: 'right', //default = right
            //autoplaySlideTime: 2000, //ms, default = 4000

            //dotsEnable: false, // default = true
            //arrowsEnable: false, //default = true
            //dotsHeight: '12px', //default = 20px
            //dotsWidth: '12px' //default = 20px
        })
 
 
```
