# Layoutch!
Layoutch! - Responsive layouts with flexbox inspired from [Layout App for Instagram](https://itunes.apple.com/us/app/layout-from-instagram/id967351793?mt=8)

###How to use

1. Include the layoutch.css in your website.
2. Add a layoutch class to one of your containers (the container should have defined width, height)
3. Celebrate. :boom:

example:

```html
<link rel="stylesheet" type="text/css" href="layoutch.css">
```

```html
<div class="layoutch-3-1">     
  <div> "Lorem ipsum dolor sit amet, consectetur
  adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna
  aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi
  ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in
  voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint
  occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim
  id est laborum."</div>         
  <div> "Lorem ipsum dolor sit amet, consectetur
  adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna
  aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi
  ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in
  voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint
  occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim
  id est laborum."</div> 
  <div> "Lorem ipsum dolor sit amet, consectetur adipiscing
  elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
  ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
  commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit
  esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
  non proident, sunt in culpa qui officia deserunt mollit anim id est
  laborum."</div> 
</div>

```

We should have a layout like:

![enter image description here](http://s30.postimg.org/6z21ujkdt/layoutch_3_1.png)

(I added some background colors to make the result more clear)

![enter image description here](http://s18.postimg.org/w0f3hrbg9/example.png)

###Helper classes to hide extra children. 

Layoutch has some extra helper classes that can be used to hide the extra children. e.g. our markdown has 3 children but we want to use the `.layoutch-2-1` and hide the 3rd extra child. We can combine `.layoutch-2-1` the class with the `.hide-more-than-2` class.
Layoutch has 5 classes for that `.hide-more-than-2`,`.hide-more-than-3`,`.hide-more-than-4`,`.hide-more-than-5`,`.hide-more-than-6`.

###Nesting layoutch classes
Ofcourse we can compine layoutch classes to create more complex layouts. Example:

```html
<div class="layoutch-2-1 democontainer">
  <div class="layoutch-6-2">
    <div class="box1">1</div>
    <div class="box2">2</div>
    <div class="box3">3</div>
    <div class="box4">4</div>
    <div class="box5">5</div>
    <div class="box6">6</div>
  </div>
   <div class="layoutch-5-1">
    <div class="box1">1</div>
    <div class="box2">2</div>
    <div class="box3">3</div>
    <div class="box4">4</div>
    <div class="box5">5</div>
  </div>
</div>
```
![enter image description here](http://s9.postimg.org/9zehpi91r/image.png)

###Layoutch classes
![enter image description here](http://s9.postimg.org/jo7xbnvpr/image.png)

![enter image description here](http://s9.postimg.org/6lcase5hr/image.png)

![enter image description here](http://s9.postimg.org/4i1vkq5ov/image.png)

![enter image description here](http://s9.postimg.org/6nw6f895b/image.png)

![enter image description here](http://s9.postimg.org/5mvxq3s5r/image.png)

![enter image description here](http://s9.postimg.org/7sq8klvm7/image.png)

![enter image description here](http://s9.postimg.org/bccohbrrj/image.png)

![enter image description here](http://s9.postimg.org/cso6zguof/image.png)

![enter image description here](http://s9.postimg.org/5qq9d9r2n/image.png)

![enter image description here](http://s9.postimg.org/qq6d4rsr3/image.png)

![enter image description here](http://s9.postimg.org/hjo2hhnin/image.png)

![enter image description here](http://s9.postimg.org/4pq0o5a33/image.png)

![enter image description here](http://s30.postimg.org/4kqhdqyjl/image.png)

![enter image description here](http://s30.postimg.org/cc77cb2ox/image.png)

![enter image description here](http://s30.postimg.org/ibuyfynhd/image.png)

###Contributing

Please feel free to submit any PR, Issue or Question. :smile:

###License

MIT
