# 🧚🏻‍♀️✨ Contributing 🏰💕

Important things to know and general guidelines for contributions.  We also recommend that you have a look at our [code of conduct](https://github.com/miamatriarx/.github/blob/main/docs/code_of_conduct.md) and that you understand our purpose and mission, our goals and objectives and that the contribution you make is in alignment with what we're working for.

## Contribution

✔️ If you have any issues with software you can report it by creating a new issue.\
✔️ You can have a look at the projects page to see the current roadmap and things we're working on and you're welcome to make a pull request.\
✔️ If you'd like to contribute something that's not software you can get in [contact](https://github.com/miamatriarx/.github/blob/main/docs/support.md).\
✔️ You can contribute by [funding](https://github.com/miamatriarx/.github/blob/main/readme.md) us.

## Legal

✔️ All software created by Mia Matriarx or by the Matriarx brand are free and open source software ([FOSS](https://en.wikipedia.org/wiki/Free_and_open-source_software)) under the [MIT](https://github.com/miamatriarx/.github/blob/main/license) license.\
✔️ Any contribution made to software owned by Mia Matriarx or the Matriarx brand, or to any Matriarx community, falls under [MIT](https://github.com/miamatriarx/.github/blob/main/license) and in doing so you void all claims to any intellectual property or copyright without any exceptions.\
✔️ Developer Certificate of Origin ([DCO](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin)) is enforced on all repositories in order to verify that you have agreed to our terms.\
✔️ For more information have a look at [contributing](https://github.com/miamatriarx/.github/blob/main/docs/contributing.md).

## DCO

✔️ [Create a new GPG key](https://docsmiamatriarx.com/en/authentication/managing-commit-signature-verification/generating-a-new-gpg-key).\
✔️ [Add the GPG key to your GitHub account](https://docsmiamatriarx.com/en/authentication/managing-commit-signature-verification/adding-a-gpg-key-to-your-github-account).\
✔️ [Sign your commit](https://docsmiamatriarx.com/en/authentication/managing-commit-signature-verification/signing-commits) using your GPG key.\
✔️ You can then use `git commit -S -am "message"` in order to create a signed and verified commit.

## Semantic Versioning & Conventional Commits

We use semantic versioning with conventional commits which are used to automatically generate the version, changelog and release notes and to make it easier to debug with a neat commit history.

### Semantic Versioning

The version will be automatically generated from commits.

### Conventional Commits

We use conventional commits in order to automatically generate the version, changelog and release notes and to make it easier to debug with a neat commit history.

#### Commit

✔️ When making a commit do so using `type(scope): description` as the format in order to specifcy the type of commit, the scope, whether or not it's a breaking change and the description.\
✔️ Use the directory that is the primary focus of your changes as the scope.\
✔️ If the commit includes a breaking change then include `!` using `type(scope)!: description` as the format to specify that it changes existing code in a backwards incompatible way.\
✔️ Only use lowercase.

#### Example

`git commit -S -am "feature(module)!: a new module feature"`

✔️ The commit is a new feature.\
✔️ The changes are primarily scoped to the `module` directory.\
✔️ It contains a breaking change.\
✔️ It's lowercase.

#### Types

✔️ feature - A new feature.\
✔️ update - Changes to an existing feature.\
✔️ patch - A small change to a module or component.\
✔️ security - Changes specifically related to security.\
✔️ performance - Changes specifically related to performance.\
✔️ config - Changes to configurations.\
✔️ build - Changes to the build.\
✔️ ci - Changes to the continuous integration.\
✔️ cd - Changes to the continuous deployment.\
✔️ fix - A bug fix.\
✔️ deprecate - Changes to deprecate functionality.\
✔️ remove - Changes that removed functionality.\
✔️ revert - A rollback.\
✔️ task - A chore.\
✔️ refactor - Code refactoring.\
✔️ polish - Styling and formatting.\
✔️ documentation - Changes to the documentation.

#### Merging

We use a linear commit history in order to generate the changelogs and release notes and to make it easier to debug.  Use rebase or squash merge in order to keep the history neat.  For almost every use case you should be using rebase instead of squashing in order to preserve the commit history and to properly reflect changes in the generated changelog.  However there are some exceptions to that rule:
✔️ Only use rebase if the commits on your local branch have never been pushed to remote.  If you pushed those commits to remote, rebasing it can be a potentially destructive action and then you should squash it instead.\
✔️ Each commit should be a meaningful change, if you've made commits with silly messages like "fix: typo" then you should squash it.  Don't include meaningless commits in the history.

## Support

If you have any questions or concerns get in [contact](https://github.com/miamatriarx/.github/blob/main/docs/support.md).
