# Global-failures-not-failing-tests

Demo repo to show that running `ember test` with `testem@^1.0.2` and
`ember-cli@2.3.0-beta.1` does not return a non-zero exit code (so CI thinks
the tests pass).

After cloning the repo, run the following:

```
npm install && bower install
ember test && echo $?
```
