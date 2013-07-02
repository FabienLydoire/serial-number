Serial Number
=============

A simple Node.js module for accessing the serial number (a.k.a. Dell Service
Tag, asset tag) of the local machine. Currently supports Mac and Windows OSes
only.


Installation
------------
`npm install --save serial-number`


Usage
-----
The serial number value is retrieved from the system asynchronously and passed
to a callback.

```javascript
var getSerial = require('serial-number'),
    mySerialNumber;

getSerial(function (value) {
	mySerialNumber = value;
});
```


License
-------
MIT