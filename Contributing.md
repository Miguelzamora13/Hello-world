# Contributing

Contributions to this project are [released](https://help.github.com/articles/github-terms-of-service/#6-contributions-under-repository-license) to the public under the [project's open source license](LICENSE.md).

Everyone is welcome to contribute to Hello world. Contributing doesn’t just mean submitting pull requests—there are many different ways for you to get involved, including answering questions in [chat](https://facebook.com/djmiggie69/), reporting or triaging [issues](https://github.com/Miguelzamora13/Hello-world/issues), and participating in the [Hello world](https://github.com/Miguelzamora13/Hello-world) process.

No matter how you want to get involved, we ask that you first learn what’s expected of anyone who participates in the project by reading the [Contributor Covenant Code of Conduct](http://contributor-covenant.org). By participating, you are expected to uphold this code.

We love pull requests. Here's a quick guide:

1. If you're adding a new feature or changing user-facing APIs, check out the [Hello world](https://github.com/hello-wordio/evolution) process.
1. Check for [existing issues](https://github/hello-world/issues) for duplicates and confirm that it hasn't been fixed already in the [main branch](https://github/hello-world/commits/main)
1. Fork the repo, and clone it locally
1. `npm link` to make your cloned repo available to npm
1. Follow [Getting Started](docs/index.md) to generate a testbot
1. `npm link hubot` in your newly created bot to use your hubot fork
1. Create a new branch for your contribution
1. Add [tests](test/) (run with `npm test`)
1. Push to your fork and submit a pull request

At this point you're waiting on us. We like to at least comment on, if not
accept, pull requests within a few days. We may suggest some changes or improvements or alternatives.

Some things that will increase the chance that your pull request is accepted:

* Make sure the tests pass
* Update the documentation: code comments, example code, guides. Basically,
  update everything affected by your contribution.
* Include any information that would be relevant to reproducing bugs, use cases for new features, etc.

* Discuss the impact on existing [hello world installs](docs/index.md), [helloworld adapters](docs/adapters.md), and [helloworld scripts](docs/scripting.md) (e.g. backwards compatibility)
  * If the change does break compatibility, how can it be updated to become backwards compatible, while directing users to the new way of doing things?
* Your commits are associated with your GitHub user: https://help.github.com/articles/why-are-my-commits-linked-to-the-wrong-user/
* Make pull requests against a feature branch,
* Follow our commit message conventions:
  * use imperative, present tense: “change” not “changed” nor “changes”
  * Commit test files with `test: …` or `test(scope): …` prefix.
  * Commit bug fixes with `fix: …` or `fix(scope): …` prefix
  * Commit features with `feat: …` or `feat(scope): …` prefix
  * Commit breaking changes by adding `BREAKING CHANGE:` in the commit body.
    The commit subject does not matter. A commit can have multiple `BREAKING CHANGE:`
    sections
  * Commit changes to `package.json`, `.gitignore` and other meta files with
  `chore(filenamewithout.ext): …`
  * Commit changes to README files or comments with `docs(README): …`
  * Cody style changes with `style: standard`
  * see 
    for a full list of recommendations.

# Stale issue and pull request policy

Issues and pull requests have a shelf life and sometimes they are no longer relevant. All issues and pull requests that have not had any activity for 90 days will be marked as `stale`. Simply leave a comment with information about why it may still be relevant to keep it open. If no activity occurs in the next 7 days, it will be automatically closed.

The goal of this process is to keep the list of open issues and pull requests focused on work that is actionable and important for the maintainers and the community.

# Pull Request Reviews & releasing

Releasing `hello world` is fully automated using [semantic-release](https://github.com/semantic-release/semantic-release). Once merged into the `main` branch, `semantic-release` will automatically release a new version based on the commit messages of the pull request. For it to work correctly, make sure that the correct commit message conventions have been used. The ones relevant are

* `fix: …` will bump the fix version, e.g. 1.2.3 → 1.2.4
* `feat: …` will bump the feature version, e.g. 1.2.3 → 1.3.0
* `BREAKING CHANGE: …` in the commit body will bump the breaking change version, e.g. 1.2.3 → 2.0.0

# Contributing to messenger-bot-samples
We want to make contributing to this project as easy and transparent as
possible.

## Pull Requests
We actively welcome your pull requests.

1. Fork the repo and create your branch from `master`.
2. If you've added code that should be tested, add tests.
3. If you've changed APIs, update the documentation.
4. Ensure the test suite passes.
5. Make sure your code lints.
6. If you haven't already, complete the Contributor License Agreement ("CLA").

## Contributor License Agreement ("CLA")
In order to accept your pull request, we need you to submit a CLA. You only need
to do this once to work on any of Facebook's open source projects.

Complete your CLA here: <https://code.facebook.com/cla>

## Issues
We use GitHub issues to track public bugs. Please ensure your description is
clear and has sufficient instructions to be able to reproduce the issue.

Facebook has a [bounty program](https://www.facebook.com/whitehat/) for the safe
disclosure of security bugs. In those cases, please go through the process
outlined on that page and do not file a public issue.

## Coding Style  
* 2 spaces for indentation rather than tabs
* 80 character line length

## License
By contributing to messenger-bot-samples, you agree that your contributions will be licensed
under the LICENSE file in the root directory of this source tree.


Meta Platforms, Inc. Individual Contributor License Agreement ("Agreement"), v2.0

You accept and agree to the following terms and conditions for Your present and future Contributions submitted to Meta Platforms, Inc. ("Meta"). Except for the license granted herein to Meta and recipients of software distributed by Meta, You reserve all right, title, and interest in and to Your Contributions.

1. Definitions.

"You" (or "Your") shall mean the copyright owner or legal entity authorized by the copyright owner that is making this Agreement with Meta. For legal entities, the entity making a Contribution and all other entities that control, are controlled by, or are under common control with that entity are considered to be a single Contributor. For the purposes of this definition, "control" means (i) the power, direct or indirect, to cause the direction or management of such entity, whether by contract or otherwise, or (ii) ownership of fifty percent (50%) or more of the outstanding shares, or (iii) beneficial ownership of such entity.

"Contribution" shall mean any original work of authorship, including any modifications or additions to an existing work, that is intentionally submitted by You to Meta for inclusion in, or documentation of, any of the products owned or managed by Meta (the "Work"). For the purposes of this definition, "submitted" means any form of electronic, verbal, or written communication sent to Meta or its representatives, including but not limited to communication on electronic mailing lists, source code control systems, and issue tracking systems that are managed by, or on behalf of, Meta for the purpose of discussing and improving the Work, but excluding communication that is conspicuously marked or otherwise designated in writing by You as "Not a Contribution."

2. Grant of Copyright License. Subject to the terms and conditions of this Agreement, You hereby grant to Meta and to recipients of software distributed by Meta a perpetual, worldwide, non-exclusive, no-charge, royalty-free, irrevocable copyright license to reproduce, prepare derivative works of, publicly display, publicly perform, sublicense, and distribute Your Contributions and such derivative works.

3. Grant of Patent License. Subject to the terms and conditions of this Agreement, You hereby grant to Meta and to recipients of software distributed by Meta a perpetual, worldwide, non-exclusive, no-charge, royalty-free, irrevocable (except as stated in this section) patent license to make, have made, use, offer to sell, sell, import, and otherwise transfer the Work, where such license applies only to those patent claims licensable by You that are necessarily infringed by Your Contribution(s) alone or by combination of Your Contribution(s) with the Work to which such Contribution(s) was submitted. If any entity institutes patent litigation against You or any other entity (including a cross-claim or counterclaim in a lawsuit) alleging that your Contribution, or the Work to which you have contributed, constitutes direct or contributory patent infringement, then any patent licenses granted to that entity under this Agreement for that Contribution or Work shall terminate as of the date such litigation is filed.

4. You represent that you are legally entitled to grant the above license. If your employer(s) has rights to intellectual property that you create that includes your Contributions, you represent that you have received permission to make Contributions on behalf of that employer, that your employer has waived such rights for your Contributions to Meta, or that your employer has executed a separate Corporate CLA with Meta.

5. You represent that each of Your Contributions is Your original creation (see section 7 for submissions on behalf of others). You represent that Your Contribution submissions include complete details of any third-party license or other restriction (including, but not limited to, related patents and trademarks) of which you are personally aware and which are associated with any part of Your Contributions.

6. You are not expected to provide support for Your Contributions, except to the extent You desire to provide support. You may provide support for free, for a fee, or not at all. Unless required by applicable law or agreed to in writing, You provide Your Contributions on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied, including, without limitation, any warranties or conditions of TITLE, NON- INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A PARTICULAR PURPOSE.

7. Should You wish to submit work that is not Your original creation, You may submit it to Meta separately from any Contribution, identifying the complete details of its source and of any license or other restriction (including, but not limited to, related patents, trademarks, and license agreements) of which you are personally aware, and conspicuously marking the work as "Submitted on behalf of a third-party: [named here]".

8. You agree to notify Meta of any facts or circumstances of which you become aware that would make these representations inaccurate in any respect.


