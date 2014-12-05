$p vs $('p')
You probably noticed that we used both $ and $() in the last exercise:

var $p = $('p');
There's a subtle difference between the two.

$p is just a variable name. There is no magic associated with the $ in $p; it's just a convention for saying, "hey, this variable contains a jQuery object." We could call $p anything we want: $paragraph, paragraph, space_cows, whatever! It's just helpful for people reading our code to see $p, since this is a concise way of saying "hey, there's a 'p' jQuery object in here."

$(), on the other hand, is magic. This is the function in disguise that creates jQuery objects. If you're making a jQuery object, you gotta use it!

===

$(document).ready(function() {
    $('thingToTouch').event(function() {
        $('thingToAffect').effect();
    });
});