[<img src="versacommerce.png" width="250px" height="60px" align="right" alt="VersaCommerce.de">](https://www.versacommerce.de/?utm_source=github)
[<img src="etracker-logo.png" width="175px" height="125px" align="right" alt="etracker.com">](https://www.etracker.com/?utm_source=www.versacommerce.de)

# etracker Integration for VersaCommerce

## etracker
etracker allows a detailed Shop analysis and Conversion-Optimizing.

## VersaCommerce

[VersaCommerce](https://www.versacommerce.de/?utm_source=github) is a popular european e-commerce plattform that allows to build and manage online stores and digital sales channels.

## Installation
This integration is pre-installed with every VersaCommerce store. To enable it, go to your store settings and to Integrations. You can configure and enable it with just a few clicks.

## Files

### head.liquid
All code for this integration takes places in head.liquid, which is injected inside ```<head>...</head>``` of the rendered html document.

### body.liquid
This file is empty because it's not needed for this integration.

### email.liquid
This file is empty because it's not needed for this integration.

## Configuration options for this integration.
| Label       | Key          | Default Value     | Validates presence?    |
| ----------- | ------------ | ----------------- | :--------------------: |
| ETRACKER_ID | ETRACKER_ID  |                   |          √             |


##  Customization
* Create a developer account at [https://www.versacommerce.de/partner](https://www.versacommerce.de/partner?utm_source=github).
* Create a free developer store.
* Create an integration in your developer area.

## License

```
WWWWWW||WWWWWW
 W W W||W W W
      ||
    ( OO )__________
     /  |           \
    /o o|    MIT     \
    \___/||_||__||_|| *
         || ||  || ||
        _||_|| _||_||
       (__|__|(__|__|

The MIT License (MIT)

Copyright (c) 2014 VersaCommerce GmbH

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
