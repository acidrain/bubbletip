## bubbletip ##

A jQuery based bubble-styled tooltip extension
  * multiple tips on a page
  * multiple tips per jQuery element
  * tips open outward in four directions:
    * up
    * down
    * left
    * right
  * tips can be:
    * anchored to the triggering jQuery element
    * absolutely positioned
    * opened at the current mouse coordinates
    * anchored to a specified jQuery element
  * IE png transparency is handled via conditional css and filters

### Tested (lightly) ###
  * IE 6 on XP
  * IE 7 and 8 on Vista
  * Firefox 3.6 on Vista
  * Chrome 3.0 on Vista
  * Safari 4.0 on Vista

### Demo at: ###
  * http://www.uhleeka.com/blog/2009/11/bubbletip/
  * http://www.uhleeka.com/demo/bubbletip

### Discuss at: ###
  * http://groups.google.com/group/bubbletip

### Changes: ###
v1.0.6 » 2010-03-15
  * fixed FF3.6 issue where horizontal off-screen tips rendered improperly
  * fixed tip positioning to account for margin and padding

v1.0.5 » 2010-01-20
  * tested (lightly on Windows) with jQuery-1.4.0, IE6+, FF3.5, Chrome3.0, Safari4.0
  * fixed IE6, IE7 window.resize bug
  * fixed $.fn.removeBubbletip()
  * added options.calculateOnShow

v1.0.4 » 2009-12-14
  * added $.fn.removeBubbletip() to allow a tip and its bindings to be removed from the DOM
  * renamed options.mouseoutDelay to options.delayHide
  * added options.delayShow
  * added namespace binding on all events
  * minor bug fixes
  * reworked documentation

v1.0.3 » 2009-12-09
  * added options.bindShow and options.bindHide to allow control over the event binding
  * added a check (which didn't work) to see if the tip is already a descendant of a table.bubbletip element
  * fixed a window.resize issue causing the tips to be active via .show()

v1.0.2 » 2009-11-16
  * fixed IE alpha filters relative path issue
  * added conditional IE css

v1.0.1 » 2009-11-11
  * minor bug fixes