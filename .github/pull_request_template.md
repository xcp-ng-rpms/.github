### Main information

#### Work Item Reference

<!-- If this change is related to a Vates internal task or issue,
please provide a work item reference (e.g., XCPNG-12345), Otherwise,
remove this section and the next one. -->

XCPNG-XXXX or N/A

#### Related changes (optional)

<!--When several PRs are part of a single changeset, you can either fill
the form for each PR, or just once and link towards the PR with the filled
form. In the reference PR, the one with the form filled in, list all related
PRs.

You can also mention here constraints between PRs, if useful:
merge/build order, chained builds...-->

ANSWER, or N/A

#### Context & Motivation

<!-- Explain the context of the change, without assuming that the reviewers
know about it.  and why it would be good to accept
it as an update to XCP-ng? What problem does it solve, or benefit does it
bring. Are there known or envisioned drawbacks?

In case of an update based on an upstream's update,
the motivation, the problem being solved, or the benefit to users or
maintainers. Provide any necessary context, without assuming that the
reviewers know about it. -->

ANSWER

#### Release Target

- [ ] We already defined a release target with the release team.
- [ ] I haven't talked with the release team, but I have a proposed target.
- [ ] I'm not sure, let's talk about it.

<!-- Unless you have chosen "I'm not sure", you can specify the wanted release
target here: fast track, 8.3-next, 8.3-next+1, other specific target. For members
of Vates' XCP-ng team: the reference for this information is the related work
item's milestone. -->

TARGET, or remove this line.

---

### Release Notes and Documentation

#### Explain the change to users

<!-- Write a user-facing explanation that will serve as a basis for public
announcements. Explain what has changed, what the consequences are
for users (main bugs fixed, new features, etc.).  It is not a technical changelog. -->

ANSWER

#### Attention points

<!-- Consequences of the changes on existing setups. Include any manual steps,
changes to default behavior, compatibility issues, etc. Anything that we should
bring to the attention of user or people offering technical support -->

ANSWER, or N/A

#### Documentation update needed

- [ ] Yes
- [ ] No
- [ ] I'm not sure, help me

<!-- If yes, explain what needs to be updated and where. If no, explain why so that
the reviewer can understand the reason. -->

EXPLANATIONS

<!-- Add links to the documentation update PRs if/when they are created. -->

PR links: LINKS, TODO, or N/A.

---

### Testing and regression avoidance

<!-- Consider the change itself, but also regressions that could be caused
unwillingly by the change, due to what components or code paths were touched.
It's the right time to be paranoid. Consider what could go wrong in the
worst case. -->

#### What tests have you performed?

ANSWER

#### What manual tests should be performed after the build, and by whom?

<!-- Manual tests that should be repeated after the build (always consider that tests
performed before the build are not definitive proof), plus tests that we should invite
the user community to perform. -->

ANSWER

#### What's covered by the xcp-ng-tests test suite?

<!-- If you don't know, it's the perfect time to ask someone about it, and/or to dig into
the test suite. If there are any tests that you'd like to run before the merge rather than
after, mention them too. -->

ANSWER

#### What tests have been or will be added to CI for this change? If none, explain why.

ANSWER

---

### Xen Orchestra Impact

#### Does this affect existing features in Xen Orchestra, or add new features that could be useful?

- [ ] Yes
- [ ] No

<!-- If this affects existing features, describe which features are affected and how.
If this adds new features that Xen Orchestra could leverage (not just in the UI.

There's also the back-end and the REST API), describe them. -->
