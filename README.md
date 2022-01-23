# anime.js-cheat-sheet
Anime.js Cheat Sheet





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
