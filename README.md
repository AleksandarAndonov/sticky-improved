stickyjs-improved-stopper-fix
========

StickyJS is a jQuery plugin that gives you the ability to make any element on your page always stay visible. Sticky wasn't getting updated this has updates and imporvements. It has the same as the original sticky https://github.com/garand/sticky.

minWidthToStick ---- gives you responsive widths that is set on 640 by default, and you can make it responsive on the width you want to be unstickied.

checkHeight ---- Checks the height of the stopper class if it is set to true and doesn't apply sticky unless the size of the stopper class is longer than the wrapped class. For dynamic stopper classes.

Height and width get reseted to it's parents height and width on unstickied.


Sticky plugin throws error when stopper position is null or undefined
