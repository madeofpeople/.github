# How to contribute

I'm really glad you're reading this, because we need volunteer developers to help this project come to fruition.

If you haven't already, come find say high at our Spectrum community ([#debtcollective](https://spectrum.chat/debtcollective)).

Here are some important resources:

- [Code of Conduct](./CODE_OF_CONDUCT.md).
- [Spectrum Community](https://spectrum.chat/debtcollective).

## Testing

We have a handful of Jest tests and Cypress features. Please write tests for new code you create.

## Submitting changes

Please open a Pull Request with a clear list of what you've done. We have a Pull Request template you can use to document your changes. When you send a pull request, we will love you forever if you include tests. We can always use more test coverage. Please follow our coding conventions (below) and make sure all of your commits are atomic (one feature per commit).

Always write a clear log message for your commits. We prefer semantic commits using https://commitizen.github.io/cz-cli/

    $ git commit -m "feat(README): A brief summary of the commit"
    >
    > A paragraph describing what changed and its if the message alone is not enough."

## Coding conventions

Start reading our code and you'll get the hang of it. We optimize for readability:

- We indent using two spaces (soft tabs)
- We use [Prettier](https://github.com/prettier/prettier) and [ESLint](https://github.com/eslint/eslint) for linting. All of our projects will have this installed, so make sure you have this configured in your IDE.
