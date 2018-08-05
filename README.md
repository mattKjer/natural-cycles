# natural-cycles
A JavaScript challenge. 
-------------
    Intro & Improvements
-------------

I built this as a single html page as opposed to use React/Angular/Vue.
Using in a framework for a simple one page JS demonstration would have been far too much bloat.
Best tool for the job etc.

Improvements
  * Rename variables to be more explicit (don't like using divs in variable names).
  * Add persistent state via local storage and logic to populate fields.
  * Fine tune the algorithm for determining font size (font size can be increased by 2-3 at times)
  * Bugs:
  *     If you reduce the slider with no input, default text breaks.
  *     Max value of range finder set to 1500. Would be nice to transfer this to VW units.
  *     Make mobile friendly, range slider disappears on mobile view.
  *     Move javascript to .js file, kept in the same file for interviewers sake.
  *     Investigate efficiency of getFontSize.
  *     Lint.
  *     Unit test.
