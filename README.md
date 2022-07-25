# Roundcube plugin for customize character encoding of sending message.

## Overview
This plugin adds a option to mail composing preference.
The option specifies which charset to be used in sending message.


## Installation
To install, get the plugin with composer in your roundcube directory.

```
composer require shirosaki/sendcharset
```

## Configuration
Copy config.inc.php.dist to config.inc.php and edit that.
There is only a option which specifies default sending charset.
If it is not set, keeps default behavior(UTF-8 may be used).
