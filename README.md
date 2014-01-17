PHP OOP Tasks
=============
Note: This is not an original creation. The creator pulled it down from github and I don't recall who it was.
This is a small caching package. It can be used in conjunction with many storage methods (file, memcache, mysql, etc)

At the moment, it will only work with file storage. 

Files
-----

* index.php                   - A simple example
* bootstrap.php               - Class autoloader function
* datacache.php               - The main caching class
* datacache/item.php          - Class to store cached data
* datacache/driver.php        - The cache driver interface
* datacache/driver/file.php   - File storage class

Tasks
-----

1. Create a new driver for another storage method, this can be anything you like including (memcache, apc, mysql, etc)

2. Create a new class that extends Datacache_Item and add cache expiration feature.

3. Create a factory for Datacache

This should take around an hour or so to complete.