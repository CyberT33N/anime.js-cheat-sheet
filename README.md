# anime.js-cheat-sheet
Anime.js Cheat Sheet


# [Anime.js](#_animejs)
1. Remove Animation
2. Bouncing easing
3. Color switch







<a name="_animejs"><h1>Anime.js</h1></a>
<details><summary>Click to expand..</summary>

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

</details>

