# floatdom
Float tagged elements to top, currently.  As it grows, float direction may vary.

This script will clone a set of elements and append them to the dom.  In the meantime, the original set of elements is hidden and sorted.  Once that is done, the clone acquires information from the original, now sorted set (top position and index), and animates after new top positions are embedded with a style.  The original is now made visible and the clone disappears.
