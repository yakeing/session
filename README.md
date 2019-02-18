# SESSION

This is a SESSION class function package, use more easily, just a few simple functions can use it.

### Travis CI

[![Travis-ci](https://api.travis-ci.org/yakeing/php_session.svg?branch=master)](https://travis-ci.org/yakeing/php_session)

### Packagist

[![Version](http://img.shields.io/packagist/v/yakeing/php_session.svg)](https://packagist.org/packages/yakeing/php_session)
[![Downloads](http://img.shields.io/packagist/dt/yakeing/php_session.svg)](https://packagist.org/packages/yakeing/php_session)

### Github

[![Downloads](https://img.shields.io/github/downloads/yakeing/php_session/total.svg)](https://github.com/yakeing/php_session)
[![Size](https://img.shields.io/github/size/yakeing/php_session/src/php_session/session.php.svg)](https://github.com/yakeing/php_session)
[![tag](https://img.shields.io/github/tag/yakeing/php_session.svg)](https://github.com/yakeing/php_session)
[![Language](https://img.shields.io/github/license/yakeing/php_session.svg)](https://github.com/yakeing/php_session)
[![Language](https://img.shields.io/github/languages/top/yakeing/php_session.svg)](https://github.com/yakeing/php_session)


BY: [yakeing](http://weibo.com/yakeing)

### Installation

Use [Composer](https://getcomposer.org) to install the library.

```

    $ composer require yakeing/php_session

```

### session init

- [x] example
```php
    $expire = 180;  //Default server 180 minutes client end
    $uid = md5('uid'); //user ID, Default automatic generation
    $name = "MYSESSION";
    $session = new session($expire, $uid, $name);
```

### FUNCTION

- [x] example
```php
    $name = 'admin';
    $value = 'pass';
    $session->set($name, $value); //Set up a session Value
    $session->get($name); //Get a session Value
    $session->deletes($name); //Write off a session Value
    $session->destroy(); //End all session Value
```

SINA CLOUD SERVICES
---

SAE provides a solution for Memcache storage Session

[MemcacheSessionHandler](http://www.sinacloud.com/doc/sae/php/runtime.html#session)


Donate
---
Your donation makes CODE better.

 Bitcoin (比特币赞助)

 1Ff2hTfr4EioWv2ZDLKTedUiF9wBBVYSbU

 ![Bitcoin](https://raw.githubusercontent.com/yakeing/Content/master/Donate/Bitcoin.png)

 WeChat (微信赞助)

 ![WeChat](https://raw.githubusercontent.com/yakeing/Content/master/Donate/WeChat.png)

 Alipay (支付宝赞助)

 ![Alipay](https://raw.githubusercontent.com/yakeing/Content/master/Donate/Alipay.png)
