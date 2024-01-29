# Epic Stack Example with CSRF Tokens

CSRF tokens protect your users if you must use non-Lax/Strict cookies or you
need to perform actions on GET requests.

In this example, we use the utilities provided by
[`remix-utils`](https://github.com/sergiodxa/remix-utils) to generate and
validate CSRF tokens. We also have a `validateCSRF` utility that will
automatically validate the CSRF token and return a 403 if it is invalid.

Check
[this commit](https://github.com/epicweb-dev/epic-stack-example-csrf/commit/b83571a6747a4781dbe85dd15bef792b5f69c47c)
for details.
