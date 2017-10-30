FM-BetterCalenarWidget
===========
A very easy to use calendar widget that can easily be used in your own solutions. 

While the popup calendar you can specify on fields is easy enough to use, you may want more flexibility when allowing your users to select dates via a calendar.

The built in calendar widget may also not be preferred on iOS devices. This provides a more friendly UI widget that works on FileMaker Go as well as WebDirect, and of course in FileMaker Pro.

You can easily modify to your needs and use with either variables or updating your fields. There is one script needed and no other dependencies.

With no schema to import or recreate this make it very easy to use in your own solutions.
Copy and paste the two scripts first, then you can copy and paste the popover object that contains all objects needed to draw the calendar widget.

The SELECTED DAY is highlighted in blue. The CURRENT DAY is shown in Red, if it is not the SELECTED DAY.

The calendar is drawn from setting a global variable and all other dates used to display are calculated automatically.

You should initialize that global variable, called "$$UI.THEDATE" when opening the file.

Resize to fit your layout as dictated by your solution. The calendar is made up of several button bars, so is easy to resize to your needs.

All objects have a Style in the Theme if you would like to include that in your solution to make it easy to adjust the appearance.

