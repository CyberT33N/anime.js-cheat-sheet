# anime.js-cheat-sheet
Anime.js Cheat Sheet



<br><br>
	
# Easing

## List of all easing variants
```javascript
IN	OUT	IN-OUT	OUT-IN
'easeInQuad'	'easeOutQuad'	'easeInOutQuad'	'easeOutInQuad'
'easeInCubic'	'easeOutCubic'	'easeInOutCubic'	'easeOutInCubic'
'easeInQuart'	'easeOutQuart'	'easeInOutQuart'	'easeOutInQuart'
'easeInQuint'	'easeOutQuint'	'easeInOutQuint'	'easeOutInQuint'
'easeInSine'	'easeOutSine'	'easeInOutSine'	'easeOutInSine'
'easeInExpo'	'easeOutExpo'	'easeInOutExpo'	'easeOutInExpo'
'easeInCirc'	'easeOutCirc'	'easeInOutCirc'	'easeOutInCirc'
'easeInBack'	'easeOutBack'	'easeInOutBack'	'easeOutInBack'
'easeInBounce'	'easeOutBounce'	'easeInOutBounce'	'easeOutInBounce'

```


<br><br>
	
# Restart Animation
```javascript
    const tl = anime({
        targets: '#XMLID_640_',
        translateX: [
            { value: '100%', duration: 5000 }
        ],
        translateY: [
            { value: '150%', duration: 5000 }
        ],
        easing: 'linear'
    })

    setInterval(() => {
        tl.pause()
        setTimeout(() => tl.restart(), 5000)
    }, 10000)
```


<br><br>
	
# Remove Animation
```javascript
anime.remove( document.querySelector('#layertwo') )
```

<br><br>
	
# Bouncing easing
```javascript
anime({
  targets: '.css-prop-demo .el',
  duration: 2000,
  easing: 'easeOutElastic(1, .2)'
});
```

<br><br>
	
# Color switch
```javascript
anime({
  targets: '.css-prop-demo .el',
  backgroundColor: '#FFF',
  easing: 'easeInOutQuad'
});
```
  
  <br><br>
	
# scale
```javascript
anime({
  targets: '.css-prop-demo .el',
  scale: 1.05,
  easing: 'easeInOutQuad'
});
```



  
  <br><br><br><br>
	
# keyframes
- https://animejs.com/documentation/#animationKeyframes
```javascript
anime({
  targets: '.animation-keyframes-demo .el',
  keyframes: [
    {translateY: -40},
    {translateX: 250},
    {translateY: 40},
    {translateX: 0},
    {translateY: 0}
  ],
  duration: 4000,
  easing: 'easeOutElastic(1, .8)',
  loop: true
});
```
