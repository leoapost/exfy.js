# Exfy.js

Read and write exif meta headers from assets (jpeg, tiff)

Work in progress -not yet complete-

## Getting Started

## Documentation
_(Coming soon)_

## Examples
```javascript

// source can be one of:
// {document.element} IMG DOM element or array or elements
// {jQuery} jQuery containing img elements
// {string} url pointing to desired jpeg
// {document.Image} instance of Image()
// {string} raw base64
// {Blob} raw blob type

// opt_fn callback when processed, providing status (pass or failed)
var e = Exfy(source, opt_fn);

// or
var e = Exfy();
e.add(source, opt_fn);


e.toObject(); // get all headers as a native JS object
e.get(headerName); // get a value of a header, undefined if not set
e.set(headerName, value);

```

## Contributing

## Release History
_(Nothing yet)_

## License
Copyright (c) 2012 Thanasis Polychronakis
Licensed under the MIT, GPL licenses.
