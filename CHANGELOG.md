CHANGELOG
=========

v0.11.0 - 04/19/15
* Add experimental features:
  * Add PNG decoder supporting true-color (+alpha) and index-color (with palette); supports auxiliary chunk tRNS
  * Add PNG encoder - currently saving always in true-color with alpha-channel
  * Add synchronous PNG loader (loadImageSync)
  * Add synchronous PNG writer (writeFileSync)
  * Add synchronous PNG dump (toBlobSync)

v0.10.0 - 03/28/15
* General cleanup
* Add support for Node 0.12
* Add support for IO.js

v0.9.3 - Initial release 11/04/14