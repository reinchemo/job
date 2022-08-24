# 006-website-page-design

This is my first study using Bootstrap and SASS to create a static website. I used '@use' method in SASS to import the stylesheets instead of using '@import' method. Because '@import' method  has a number of serious issues as described by it's official website as follows:

* @import makes all variables, mixins, and functions globally accessible. This makes it very difficult for people (or tools) to tell where anything is defined.

* Because everything’s global, libraries must prefix to all their members to avoid naming collisions.

* @extend rules are also global, which makes it difficult to predict which style rules will be extended.

* Each stylesheet is executed and its CSS emitted every time it’s @imported, which increases compilation time and produces bloated output.

* There was no way to define private members or placeholder selectors that were inaccessible to downstream stylesheets.

<br>
The new module system and the '@use' rule address all these problems.
<br><br>

https://asoylu06.github.io/006-website-page-design/

