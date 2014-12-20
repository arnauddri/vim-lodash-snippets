vim-lodash
==========

Vim snippets for most commonly used arrays/lodash/underscore functions

## each
Type 'each' and get:
```javascript
	${1:collection}.forEach(function(${2:obj}) {
		${0}
	});
```
## map
Type 'map' and get:
```javascript
	${1:collection}.map(function(${2:obj}) {
		${0}
	})
```
## indexby
Type 'indexby' and get:
```javascript
	_.indexBy(${1:collection}, ${2:'${3:key}'});
```
## groupby
Type 'groupby' and get:
```javascript
	_.groupBy(${1:collection}, ${2:'${3:key}'});
```
## reduce
Type 'reduce' and get:
```javascript
	_.reduce(${1:collection}, function(${7:memo}, ${2:obj}${4:, ${3:key}}) {
		${5:return $7 + $2;}
	}, ${6:initial});
```
## chain
Type 'chain' and get:
```javascript
	_.chain(${1:collection})
```
## pluck
Type 'pluck' and get:
```javascript
	_.pluck(${1:collection})
```
## max
Type 'max' and get:
```javascript
	_.max(${1:array});
```
## min
Type 'min' and get:
```javascript
	_.min(${1:array});
```
## filter
Type 'filter' and get:
```javascript
	_.filter(${1:array}, '${2:arg}');
```
## uniq
Type 'uniq' and get:
```javascript
	_.uniq(${1:array}, ${4:, '${3:false}'});
```
