# Foundation for Emails forked repository

## Variables to reduce generated code

```
// VAE Control
// ---------
// these options are to control the CSS generated by 
// the framework Foundation For Emails in the Mobile CSS

$small-alignments-used: true;
/* 
  $small-alignments-used: true; // Normal Behavior
  $small-alignments-used: false;
    classes removed with this option in FALSE
      .small-float-center
      .small-text-center
      .small-text-left
      .small-text-right
    reducing the code by 332 characters
*/

$visibility-framework-classes-used: true;
/* 
  $visibility-framework-classes-used: true; // Normal Behavior
  $visibility-framework-classes-used: false;
    classes removed with this option in FALSE
      .hide-for-large
      .show-for-large
    reducing the code by 626 characters
*/

$collapse-columns-used: true;
/* 
  $collapse-columns-used: true; // Normal Behavior
  $collapse-columns-used: false;
    classes removed with this option in FALSE
      .collapse .columns
      .collapse .column
    reducing the code by 128 characters
*/

$small-columns-used: (1,2,3,4,5,6,7,8,9,10,11,12);
/* 
  $small-columns-used: (1,2,3,4,5,6,7,8,9,10,11,12); // Normal Behavior
  removing the numbers of the size not used in the project will remove 
  the CSS not used in the build

  Examples:
    if you only use framework columns size 6 and 12 in mobile
    the code should be like this
    $small-columns-used: (6,12);
    and this will generate only those classes
    .small-6 and .small-12
    reducing the code
    --------------------------------------------
    if you only use full width columns (small-12) in mobile 
    $small-columns-used: (12);
    this will reduce 1072 characters

  this remove the classes for the columns in mobile
    .small-#
  the code can be reduced up to 1072 characters
*/

$small-offset-columns-used: true;
/* 
  $small-offset-columns-used: true; // Normal Behavior
  $small-offset-columns-used: false;
    classes removed with this option in FALSE
      .small-offset-1
      .small-offset-2
      .small-offset-3
      .small-offset-4
      .small-offset-5
      .small-offset-6
      .small-offset-7
      .small-offset-8
      .small-offset-9
      .small-offset-10
      .small-offset-11
    reducing the code by 1526 characters
*/

$text-left-right-padding-used: true;
/* 
  $text-left-right-padding-used: true; // Normal Behavior
  $text-left-right-padding-used: false;
    classes removed with this option in FALSE
      .right-text-pad
      .text-pad-right
      .left-text-pad
      .text-pad-left
    reducing the code by 189 characters
*/

$menu-used: true;
/* 
  $menu-used: true; // Normal Behavior
  $menu-used: false;
    classes removed with this option in FALSE
      .menu
      .menu.vertical
      .menu.small-vertical
      .menu[align="center"]
    reducing the code by 348 characters
*/

$buttons-used: true;
/* 
  $buttons-used: true; // Normal Behavior
  $buttons-used: false;
    classes removed with this option in FALSE
      .button.small-expand
      .button.small-expanded
    reducing the code by 472 characters
*/

$callout-used: true;
/* 
  $callout-used: true; // Normal Behavior
  $callout-used: false;
    classes removed with this option in FALSE
      .callout-inner
    reducing the code by 50 characters
*/

// End VAE Control
```