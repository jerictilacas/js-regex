# Building My Own Regex using JS

This is a test spec driven guide to build a simple regex engine.

This **regex engine** supports the following syntax:

| Syntax | Meaning | Example | matches |
|--------|---------|---------|---------|
| a | Matches the specified character literal | q | q |
| * | Matches 0 or more of the previous character | a* | "", a, aa, aaa  |
| ? | Matches 0 or 1 of the previous character | a? | "", a |
| . | Matches any character literal | . | a, b, c, d, e ... |
| ^ | Matches the start of a string | ^c | c, ca, caa, cbb ... |
| $ | Matches the end of a string | a$ | ba, baaa, qwerta ... |

The goal is to provide a syntax robust enough to match a large portion of regex use cases with minimal code.


## Install

```js
npm install
npm test
```

Now simply make changes to the `regex.js` file until the tests pass. Note that the tests are all pending the begin with. Just change the `xdescribe`s to `describe`s to switch the tests on.




## Ask a question?

If you have any query please contact at jericotilacas@gmail.com
