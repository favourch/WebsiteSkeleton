Sidr
============

This is the Bower package for the Sidr jQuery Plugin. For a further description, 
documentation and others visit: [http://www.berriart.com/sidr](http://www.berriart.com/sidr)

<!-- Include Sidr bundled CSS theme -->
<link rel="stylesheet" href="javascripts/sidr/stylesheets/jquery.sidr.dark.css">

...
...
...

<!-- Include jQuery -->
<script src="javascripts/jquery.js"></script>
<!-- Include the Sidr JS -->
<script src="javascripts/sidr/jquery.sidr.min.js"></script>



Example:

*-> Option 1

<a id="simple-menu" href="#sidr">Toggle menu</a>

<div id="sidr">
  <!-- Your content -->
  <ul>
    <li><a href="#">List 1</a></li>
    <li class="active"><a href="#">List 2</a></li>
    <li><a href="#">List 3</a></li>
  </ul>
</div>

<script>
$(document).ready(function() {
  $('#simple-menu').sidr();
});
</script>



*-> Option 2

<a id="left-menu" href="#left-menu">Left Menu</a> 
<a id="right-menu" href="#right-menu">Right Menu</a>
 
<script>
$(document).ready(function() {
    $('#left-menu').sidr({
      name: 'sidr-left',
      side: 'left' // By default
    });
    $('#right-menu').sidr({
      name: 'sidr-right',
      side: 'right'
    });
});
</script>


