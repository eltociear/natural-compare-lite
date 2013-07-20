
[1]: https://raw.github.com/litejs/natural-compare-lite/master/min.natural-compare.js
[2]: https://raw.github.com/litejs/natural-compare-lite/master/natural-compare.js
[travis-img]: https://travis-ci.org/litejs/natural-compare-lite.png?branch=master
[travis-url]: https://travis-ci.org/litejs/natural-compare-lite


    @version  0.3.1
    @date     2013-07-21


Natural Order String Comparison
===============================

Sort strings containing a mix of letters and numbers.

Currently the algorithm isn't designed to work with negative signs 
or numbers expressed in scientific notation.

Download [compressed][1] 
(359 bytes, 250 bytes gzipped)
or [uncompressed][2] source.

[![Build Status][travis-img]][travis-url]

### Usage

```javascript
var a = ["z1.doc", "z10.doc", "z17.doc", "z2.doc", "z23.doc", "z3.doc"]
a.sort(String.naturalCompare)
// ["z1.doc", "z2.doc", "z3.doc", "z10.doc", "z17.doc", "z23.doc"]
```

External links
--------------

- [jsperf test](http://jsperf.com/natural-sort-2/2)


### Licence

Copyright (c) 2012 Lauri Rooden &lt;lauri@rooden.ee&gt;  
[The MIT License](http://lauri.rooden.ee/mit-license.txt)


