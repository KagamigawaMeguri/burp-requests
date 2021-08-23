Copy as requests plugin for Burp Suite
======================================

Copies selected request(s) as Python [requests][1] invocation.

## Alterations

- Update version with mjson 1.4.0 -> 2.0.0

- Replace with `session.cookies.update()` when use session
- Add my commonly usage

Building
--------

 - Use Gradle

Dependencies
------------

 - JDK 1.8+ (tested on OpenJDK `1.8.0_302`)
 - Gradle

License
-------

The whole project is available under MIT license, see `LICENSE.txt`,
except for the [Mjson library][3], where

> The source code is a single Java file. [...] Some of it was ripped
> off from other projects and credit and licensing notices are included
> in the appropriate places. The license is Apache 2.0.

[1]: http://docs.python-requests.org/
[2]: https://portswigger.net/burp/extender/api/burp_extender_api.zip
[3]: https://bolerio.github.io/mjson/
