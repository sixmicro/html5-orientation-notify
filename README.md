# html5-orientation-notify
HTML5 Orientation Notifier
- With this code you can detect your current Orientation Mode.

please do not forget to include jQuery.

Example Code:
```
<script>

$( document ).ready(function() {

$(window).on('orientationchange', function() {
console.log("MVL: Orientation Changed!");
var mvscreen = window.orientation;
    switch(mvscreen) {  
      case 90:
        alert('Landscape-Modus erkannt!');
		console.log("MVL: Landscape Orientation.");
        break; 
      default:
        alert('Portrait-Modus erkannt!');
		console.log("MVL: Portrait Orientation.");
        break; 
    }
});

});

</script>
```
