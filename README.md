# floatdom
Float tagged elements to top, currently.  As the script grows, float direction may vary.

This script will clone a set of elements and append them to the dom.  In the meantime, the original set of elements is hidden and sorted.  Once that is done, the clone acquires information from the original, now sorted set (top position and index), and animates after new top positions are embedded with a style.  The original is now made visible and the clone disappears.

Fiddle available
https://jsfiddle.net/sandraqu/2jt3og31/

The script is vanilla JS, and the HTML/CSS uses the BEM style approach.
