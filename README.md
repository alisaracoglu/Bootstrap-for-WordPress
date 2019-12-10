# Bootstrap for WordPress
`Bootstrap v3.3.7`

You can safely use the Bootstrap classes within WordPress.


## Usage
##### Enqueue
Firstly, enqueue the files to script. For more details -> [wp_enqueue_style](https://developer.wordpress.org/reference/functions/wp_enqueue_style/) / [wp_enqueue_script](https://developer.wordpress.org/reference/functions/wp_enqueue_script/)

##### Usage in Html
Create a parent element with the class="bs-for-wp". You can safely use the bootstrap classes within this element.
```html
<div class='bs-for-wp'>
  <!-- write your code in this area  -->
</div>
```


## How It Was Made
All of the less file in Bootstrap's source code has been recompiled into the "bs-for-wp" class. In addition, "! Important" has been added to all selectors in the "bs-for-wp" class to avoid conflicts. Values that already have "! Important" are left untouched.


## Warning
There are no studies on bootstrap js. In case of conflicts about javascript, a prefix can be added to the functions.
