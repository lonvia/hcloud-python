=======
History
=======

master(XXXX-XX-XX)
------------------

* Feature: Add status filter for servers, images and volumes
* Feature: Add 'created' property to Floating IP domain

1.2.1 (2019-03-13)
------------------

* Fix: BoundVolume.server server property now casted to the 'BoundServer'.

1.2.0 (2019-03-06)
------------------

* Feature: Add `get_by_fingerprint`-method for ssh keys
* Fix: Create Floating IP with location raises an error because no action was given.

1.1.0 (2019-02-27)
------------------

* Feature: Add `STATUS`-constants for server and volume status

1.0.1 (2019-02-22)
------------------

  Fix: Ignore unknown fields in API response instead of raising an error

1.0.0 (2019-02-21)
------------------

* First stable release.
  
  You can find the documentation under https://hcloud-python.readthedocs.io/en/latest/

0.1.0 (2018-12-20)
------------------

* First release on GitHub.
