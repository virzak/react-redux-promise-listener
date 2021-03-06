# Contributing

Thanks for your interest in contributing to React Redux Promise Listener! Please take a
moment to review this document **before submitting a pull request**.

We are open to, and grateful for, any contributions made by the community.

## Reporting issues and asking questions

Before opening an issue, please search
the[issue tracker](https://github.com/erikras/react-redux-promise-listener/issues) to
make sure your issue hasn’t already been reported.

**We use the issue tracker to keep track of bugs and improvements** to React
Redux Promise Listener itself, its examples, and the documentation. We encourage you to open
issues to discuss improvements, architecture, internal implementation, etc. If a
topic has been discussed before, we will ask you to join the previous
discussion.

For support or usage questions, please search and ask on
[StackOverflow with a `react-redux-promise-listener` tag](https://stackoverflow.com/questions/tagged/react-redux-promise-listener).
We ask you to do this because StackOverflow has a much better job at keeping
popular questions visible. Unfortunately good answers get lost and outdated on
GitHub.

**If you already asked at StackOverflow and still got no answers, post an issue
with the question link, so we can either answer it or evolve into a bug/feature
request.**

## Sending a pull request

**Please ask first before starting work on any significant new features.**

It's never a fun experience to have your pull request declined after investing a
lot of time and effort into a new feature. To avoid this from happening, we
request that contributors create
[an issue](https://github.com/erikras/react-redux-promise-listener/issues) to first
discuss any significant new features.

Please try to keep your pull request focused in scope and avoid including
unrelated commits.

After you have submitted your pull request, we’ll try to get back to you as soon
as possible. We may suggest some changes or improvements.

Please format the code before submitting your pull request by running:

```sh
npm run precommit
```

## Coding standards

Our code formatting rules are defined in
[.eslintrc](https://github.com/erikras/react-redux-promise-listener/blob/master/.eslintrc).
You can check your code against these standards by running:

```sh
npm start lint
```

To automatically fix any style violations in your code, you can run:

```sh
npm run precommit
```

## Running tests

You can run the test suite using the following commands:

```sh
npm test
```

Please ensure that the tests are passing when submitting a pull request. If
you're adding new features to React Redux Promise Listener, please include tests.
