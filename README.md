Why is jest to slow?

```
$ time npm run jest

> jest-is-slow@1.0.0 jest /home/james/dev/jest-is-slow
> jest --silent

PASS  test/main.test.js

Test Suites: 1 passed, 1 total
Tests:       100 passed, 100 total
Snapshots:   0 total
Time:        1.126s

real   0m2.052s
user   0m2.440s
sys    0m0.148s


$ time npm run mocha

> jest-is-slow@1.0.0 mocha /home/james/dev/jest-is-slow
> mocha --reporter dot


 ․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․․

100 passing (18ms)


real   0m0.497s
user   0m0.460s
sys    0m0.056s
```
