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

