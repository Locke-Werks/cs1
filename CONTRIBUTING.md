# Contributing

- Fork and open PRs against `main`.
- Keep the spec in `docs/SPEC.md` authoritative; mirror changes into `proto/` and `schema/` as needed.
- Include tests/examples when adding service methods or fields.

Those three lines are the whole contract. Everything below is context, not extra
requirements.

## Welcome

This project is open source because open source works better than the
alternative. Contributions are welcome from anyone, at any experience level, on
anything from a typo fix to a feature you thought up yourself.

There is no bar to clear before you're allowed to participate. You don't need to
be invited, you don't need to have contributed before, and you don't need
permission to open an issue or a PR.

## Ways to help

**Report a bug.** Tell me what you did, what happened, and what you expected
instead. Version numbers and error output help a lot. If you can't reproduce it
reliably, say so and file it anyway.

**Ask for a feature.** Describe the problem you're trying to solve, not only the
solution you have in mind. There may be an easier path.

**Send a pull request.** Small ones get merged fast. Big ones are welcome too,
but open an issue first so you don't spend a weekend on something that's already
half finished in a branch somewhere.

**Fix the docs.** Docs PRs are real contributions. If something was confusing to
you, it was confusing to everyone who didn't say anything.

**Answer someone else's question.** Costs you five minutes, saves them an hour.

## Pull requests

Nothing exotic:

1. Fork and branch off `main`.
2. Make the change.
3. Run the tests, and add tests or examples for any service method or field you
   introduced. If something was already broken before you touched it, mention
   that instead of quietly fixing it in the same PR.
4. If your change alters behavior described in `docs/SPEC.md`, update the spec
   in the same PR and mirror it into `proto/` and `schema/` as needed.
5. Match the style of the code around you. If the repo has a linter or formatter
   config, use it.
6. Write a commit message that says what changed and why.
7. Open the PR and describe what it does.

Draft PRs are fine. Work in progress is fine. "I'm not sure this is the right
approach, thoughts?" is fine and is often the most useful kind of PR. The spec
and test rules above are about what gets merged, not about what you're allowed to
push while you're still figuring it out.

If your PR sits without a response, ping it. That isn't nagging, I probably lost
track of it. If I don't merge something I'll tell you why. It won't be personal
and it won't be silence.

## Ground rules

The only real rule is don't be a dick. That covers more ground than it sounds
like, so here are the parts that actually come up:

- Assume the other person is smart and acting in good faith. They usually are.
- Criticize code, not people. "This breaks on empty input" is useful. "Did you
  even test this?" is not.
- Nobody owes you a response, a fix, or a merge. That includes me owing you
  those, and it includes you owing them to anyone else.
- Don't gatekeep. No "you should already know this," no "just read the source,"
  no making someone feel stupid for asking a beginner question. Everyone was new
  once and most of us still are about something.
- No harassment, slurs, or personal attacks, and no hostility about anyone's
  identity, background, or experience level. That gets you removed and I won't
  lose sleep over it.
- When a thread starts going in circles, let it go. Nobody has ever won a GitHub
  argument.

Enforcement isn't a process, it's just me. If someone is being a problem, open an
issue or email archon@lockewerks.com. I'll deal with it, and I'll err on the side
of the person getting treated badly.

## Licensing

By contributing you agree your contribution is licensed under the same terms as
the project, whatever the LICENSE file says. There's no CLA and there won't be.
You don't sign anything over.

## Credit

Contributors get credit. If you'd rather not be listed, say so and you won't be.
