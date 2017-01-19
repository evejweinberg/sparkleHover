# sparkleHover
a jQuery plugin to add sparkles to anything on hover -- made during 'Cave Day' on Jan 15th, 2017



##How to use it:
download the plugin here:https://github.com/evejweinberg/sparkleHover/blob/master/sparkleHover.js
Add it to your html. Also add jQuery to your html if you do not already have it in your project.

Instantiate it on any object, using jQuery:

```
$('element-id-or-class-goes-here').sparkleHover();

```

Parametize it!

```
$('#c').sparkleHover({
  colors : ['#297E97', "#2EB8D5",'#36BEC1'],
  num_sprites: 22,
  lifespan: 3000,
  radius: 500,
  sprite_size: 40,
  shape: 'circle',
  image: 'http://loganchamber.org/files/Pumplin.jpg'

});

```

##Options are:

-  **colors**: array or one color
-  **radius**: interger (this is the spread radius)
-  **sprite_size**: integer
-  **shape**: string (choose 'circle, 'triangle' or 'square')
-  **lifespan**: interger, in milliseconds
-  **num_sprites**: interget, number of sprites
-  **image**: url or relative path, if you want a clear background, make colors: rgba(0,0,0,0)
- **gravity**: string "true"/"false"
