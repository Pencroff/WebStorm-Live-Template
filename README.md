#WebStorm Live Template


##How to instal

For installing templates, you need, just copy all XML files to matching folder and restart WebStopm (PHPStorm)

- Windows: [your home directory]\.[product name][version number]\config\templates

	Example:
	`C:\Users\Windows-User\.WebStorm6\config\templates\`

- Linux: ~\.[product name][version number]\config\templates
- MacOS: ~/Library/Preferences/[product name][version number]/templates

## Mocha test framework
	
+ desc - create new 'describe' function, group of tests

```javascript
describe('$TESTNAME$', function () {
    $END$
});
```

+ it - create new 'it' function, implementation one test

```javascript
it('$STATE$', function (done) {
    $END$
    done();
});
```
