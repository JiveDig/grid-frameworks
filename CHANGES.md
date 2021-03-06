# Flexington

## 2.5.0
* Negative margins for gutters are now equal on left and right for better RTL support.

## 2.4.0
* All margins are now divisible by 4 or 8. No longer by 10's.
* Added top margin utility classes.
* Top/bottom/gutter size classes now use xxs/xs/sm/md/lg/xl/xxl instead of numbers. Example: top-xs-md bottom-xs-lg gutter-xs-sm.

## 2.3.5
* Remove text-alignment from layout related classes
* Added text-{breakpoint}-left, text-{breakpoint}-center, text-{breakpoint}-right for specifically aligning text in an element. These classes do not require row or col.

## 2.3.4
* Fix col-*-auto IE bug

## 2.3.3
* Code organization

## 2.3.2
* Add .column support to allow easier alignment of items within a single column

## 2.3.1
* Add bottom-{breakpoint}-{value} bottom margin classes
* Fix col-*-auto classes when smaller breakpoint has a set size

## 2.3.0
* Add col-*-auto functionality
* fix gutter-* breaking center-* and end-*

## 2.2.0
* Change em to pixel breakpoints
* Add an -xl size for large screens

## 2.1.0
* Change name to Flexington to avoid confusion with the actual flexgrid CSS spec
* Add support for WordPress galleries (1, 2, 3, 4, 6 column only)

## 2.0.0
* Move from (nth) margins to calc() and negative margin on container

## 1.2.0
* Convert to simpler (nth) method of resetting margin

## 1.1.0
* null

## 1.0.0
* Initial Release
