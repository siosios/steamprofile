About SteamProfile
==================

*TODO*

Installation and Usage
----------------------

Extract archive to desired location on your webserver. The directory _cache_ is used for caching, therefore it must be read- and writable for the web server process.

You can change configurations for the XML proxy in _xmlproxy.php_. For client configuration and template editing, open _steamprofile.xml_.

See example.html for examples and instructions for proper embedding into your website.

Requirements
------------

### Server Requirements

 * Any PHP-compliant webserver (tested with Apache/2.2.11)
 * PHP 5.0.0 or higher, 5.2.x recommended (tested with PHP/5.2.6-3ubuntu4.2)

#### Required PHP extensions

 * SteamProfile Ajax
  * cURL (libcurl 7.x)
 * SteamProfile Image
  * cURL (libcurl 7.x)
  * GD2 (libgd 2.0.x)

### Client Requirements

 * Any modern browser with enabled JavaScript

#### Browser Compatibility

 * **no problems:**
  * Firefox 3.5
  * Opera 10.0
  * Internet Explorer 8
  * Safari 4.0
  * Chrome 3.0
 * **minor problems:**
  * Internet Explorer 7 & Internet Explorer 8 in compatibility mode:
   * "Loading..." is not displayed
   * icons are not showing up
 * **major problems:**
  * Internet Explorer 6:
   * unable to display transparent 32-bit PNG images
   * slider menu unusable
   * flawed layout
   * annoys web developer
   * causes cancer
   * eats small babies