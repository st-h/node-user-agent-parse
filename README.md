# node-user-agent-parse

## Overview

Parse user agents a bit like PHP's get_browser() http://php.net/manual/en/function.get-browser.php

## Example

     var userAgent = require('user-agent')
     userAgent.parse('Mozilla/5.0 (Windows; U; Windows NT 5.1; en) AppleWebKit/526.9 (KHTML, like Gecko) Version/4.0dp1 Safari/526.8')
     // => { name: 'safari', version: '4.0dp1', os: 'Windows XP', full: '... same string as above ...', device_type:'desktop' }

## Credits

Blatantly ripped from heavily based *ahem* on https://github.com/soldair/node-ua-device-type and https://github.com/jujhars13/node-user-agent-parse

## TODO
BDD using vows

##License

License is MIT, go nuts. That's how we roll here at Buto.

http://opensource.org/licenses/mit-license.php