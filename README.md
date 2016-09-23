# gmKickstarter
Replacing the gargantuan style sheets using Greasemonkey.

The crowdfunding platform Kickstarter (http://www.kickstarter.com) is one of these modern sites with excessive HTML nesting and over 10.000 CSS style rules (over 1 MB in size). This is not only adding traffic, but also taxes the hardware.

Can't do much about the first problem, but by blocking the .css file and inserting custom styles via the Firefox extension Greasemonkey (https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) one can cut down on this unnecessary crap.

It should be noted that the script is not (yet) able to reproduce the full functionality of the site. Its main goal is to make browsing possible. Backing or creating projects will probably always require to load the site with the adblocker and Greasemonkey disabled.


How to use the scripts:

1. Block the CSS files by adding "||static.kickstarter.com/assets/packages/*" to an adblocker.
2. Add the Greasemonkey scripts gmKickstarter-overview.js and gmKickstarter-project.js.
