# utils-normalize
[![travis](https://travis-ci.org/nypl-registry/utils-normalize.svg)](https://travis-ci.org/nypl-registry/utils-normalize/)

Simple functions for title/identifier/string normalize and comparison.

The most useful methods are normalizeAndDiacritics (noramlize names) singularize (normalize subject headings/terms)

```
var utils = require('nypl-registry-utils-normalize')
utils..normalizeAndDiacritics('Kerouac, Jack, 1922-1969')
>> 'kerouac jack 1922 1969
utils..normalizeAndDiacritics('González Hernández, Rafael')
>> 'gonzalez hernandez rafael'
```



