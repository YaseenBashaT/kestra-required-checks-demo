# kestra-required-checks-demo

Test repository for a Kestra blueprint that finds required status checks no workflow reports anymore.

`main` is protected and requires the checks `lint` and `test`. Renaming the `test` job leaves every pull request waiting for a `test` check that never arrives ("Expected — Waiting for status to be reported").
CI runs on every pull request.
Reviews are welcome.
Thanks for contributing.
