jMouseWheel
===========

The simple mouse wheel event handler jQuery plugin

# Installation:
All you need to to is downloading the `jMouseWheel-<version>.min.js` and import it into your HTML after the jQuery library like this:

    <script scr="https://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js"></script>
    <script src="/path/to/jMouseWheel-<version>.min.js"></script>
    

# Usage:
simply call `mousewheel()` method on the jQuery object:

    $('#scroll-object').mousewheel(function(evt){
        console.log(evt.deltaY); // print the distance you scrolled
    });
    
# Notes:
In this version, you cannot use `on`, `bind` or `unbind`. I am going to improve this plugin to fully support jQuery event API.