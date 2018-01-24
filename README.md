Nerdamer
========

Forked version 0.5.0

Implemented in nerdamecore
```javascript         
//degree example
nerdamer.set('ANGLE_UNIT', 'deg'); 
var e = nerdamer('sin(30)');
console.log(e.text());

//result: 
//0.5

//radian example
nerdamer.set('ANGLE_UNIT', 'rad'); 
var e = nerdamer('sin(pi/6)');
console.log(e.text());

//result: 
//0.5
```            
