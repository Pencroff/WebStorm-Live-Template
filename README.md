#WebStorm Live Template

###How to instal

For installing templates, you need, just copy all XML files to matching folder and restart WebStopm (PHPStorm)

- Windows: [your home directory]\.[product name][version number]\config\templates

	Example: `C:\Users\Windows-User\.WebStorm6\config\templates\`

- Linux: ~\.[product name][version number]\config\templates
- MacOS: ~/Library/Preferences/[product name][version number]/templates

----------

## AMD
+ `define` - new full AMD module with name, dependensies and implementation. A directive `/*global define:true*/` added for telling JSHint/JSLint about global variables.

```javascript
/*global define:true*/
define('$MODULENAME$', [], function () {
    'use strict';
    $END$
    return {};
});
```
## JS (Java Script construction)

+ `?` - Conditional operator that assigns a value to a variable based on some condition

```javascript

```

+ `do` - Loop 'do-while' execute the code block once, before checking if the condition.

```javascript
do {
  $END$
} while ($CONDITION$);
```

+ `for` - Loop 'for' with index

```javascript
len=$ARRAY$.length;
for ($INDEX$ = 0; $INDEX$<len; $INDEX$ += 1) {
    $VAR$ = $ARRAY$[$INDEX$];
    $END$    
}
```

+ `forin` - Loop 'for-in' loops through the properties of an object

```javascript
for (prop in $OBJ$) {
    if ($OBJ$.hasOwnProperty(prop)) {
        $END$
    }
}
```

+ `if` - 'if' statement

```javascript
if ($CONDITION$) {
    $END$
}
```

+ `ife` - 'if-else' statement

```javascript
if ($CONDITION$) {
    $END$
} else {

}
```

+ `ifeif` - 'if-else if -else' statement

```javascript
if ($CONDITION$) {
    $END$
} else if ($NEXTCONDITION$) {

} else {

}
```

+ `snip` - desc

```javascript

```

+ `snip` - desc

```javascript

```

## Mocha test framework
	
+ `desc` - create new 'describe' function, group of tests

```javascript
describe('$TESTNAME$', function () {
    $END$
});
```

+ `it` - create new 'it' function, implementation one test

```javascript
it('$STATE$', function (done) {
    $END$
    done();
});
```
