## mongotiles version history

#### v0.3.0

* Updated tests for tilelive 5.x compatibility
* Added writeConcern=1 for gridFS writes, to be sure that they are committed before callback
* Updated all npm dependencies

#### v0.2.0

* Added unit tests and publish/build infrastructure

#### v0.1.6

* Updated gridfs-locks

#### v0.1.5

* Updated gridfs-locks and mongodb driver. Mongo 2.6 and 2.4 now fully supported again.

#### v0.1.4

* Updated gridfs-locks version yet again to fix another mongodb 2.4.x compatibility issue

#### v0.1.3

* Updated gridfs-locks version again to fix a mongodb 2.4.x compatibility issue

#### v0.1.2

* Updated gridfs-locks version

#### v0.1.1

* Fixed issue when no query string is present

#### v0.1.0

* Added support for currency using gridfs locking
* Added x,y,z metadata to each written tile/grid file
* Updated mongodb driver to 1.4.0

#### v0.0.2

* Fixed some typos in documentation

#### v0.0.1

* Initial version.
