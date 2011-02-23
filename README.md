What is INAppStoreWindow
====================

INAppStoreWindow is an NSWindow subclass that mimics the appearance of the main window in the Mac App Store application. These modifications consist of enlarging the title bar, and centring the traffic lights (**note that this subclass does not handle the creation of a toolbar**). The end result looks like this:

![INAppStoreWindow](http://i51.tinypic.com/15ydhjk.png)

Features of INAppStoreWindow:
- No use of private APIs, so it should (theoretically) be App Store friendly
- The title bar view is entirely customizable -- you can add subviews (toolbars, buttons, etc.) as well as customize the title bar itself to give it a different appearance (e.g. Reeder)
- The height of the title bar is easily adjustable

How to use it
====================

Using INAppStoreWindow is as easy as changing the class of the NSWindow in Interface Builder, or simply by creating an instance of INAppStoreWindow in code (if you're doing it programatically).

**NOTE: The title bar height is set to the standard window title height by default. You must set the 'titleBarHeight' property in order to increase the height of the title bar.**

Who am I?
====================

I'm Indragie Karunaratne, a 16 year old Mac OS X and iOS Developer from Edmonton AB, Canada. Visit [my website](http://indragie.com) to check out my work, or to get in touch with me.

Licensing
====================

INAppStoreWindow is licensed the [BSD license](http://www.opensource.org/licenses/bsd-license.php).