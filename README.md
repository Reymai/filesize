Filesize
========

A micro library that provides an easy way to get human readable file size strings

## Features

- Size can be passed as number or as string
- Optional parameter to specify numbers after comma/point
- Petabyte support

## Install 

```yaml
dependencies:
  filesize: ^1.0.0
```

## Examples

``` dart
filesize(1024);                   // "1 KB"
filesize(664365320);           	  // "633.59 MB"
filesize(4324324232343);          // "3.93 TB"
```

Optional parameter to specify numbers after comma/point:

``` dart
filesize(664365320, 4);          // "633.5881 MB"
filesize(4324324232343, 3);      // "3.932 TB"
```

## Information

Inspired by [filesize.js](https://github.com/avoidwork/filesize.js "filesize.js")


#### License

Licensed under [BSD-3](http://www.opensource.org/licenses/BSD-3-Clause "BSD-3")

