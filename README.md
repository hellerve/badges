# badges

A little badge generation service. A more robust
version of the badge server example 
[in lang-server](https://github.com/hellerve/lang-server/blob/master/examples/badges/badges.zp).

## Installation

```
zeps install hellerve/badges
```

## Usage

Start the server using

```
zepto-serve badges/badges
```

Then you can access (via GET) the following routes:
* `/<service-name>/<status-name>`
* `/<service-name>/<status-name>/<color-hex>`
* `/<service-name>/<status-name>/<color-hex>/<width-pixels>`
* `/<service-name>/<status-name>/<color-hex>/<width-pixels>/<height-pixels>`

Anything else will return a discouraging HTTP status code
that scolds you.

<hr/>

Have fun!
