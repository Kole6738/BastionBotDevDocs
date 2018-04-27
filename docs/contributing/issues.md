# Issues

* [How to Contribute in Issues](#how-to-contribute-in-issues)
* [Asking for Help](#asking-for-help)
* [Submitting an Issue](#submitting-an-issue)
* [Triaging an Issue](#triaging-an-issue)
* [Resolving an Issue](#resolving-an-issue)

## How to Contribute in Issues

For any issue, there are fundamentally three ways an individual can
contribute:

1.  By opening the issue for discussion: For instance, if you believe that you
    have uncovered a bug in Bastion or if you have a feature request/suggestion,
    creating a new issue in the respective repository's issue tracker, in any of
    [The Bastion Bot GitHub Organization] is the way to do it.
2.  By helping to triage the issue: This can be done either by providing
    supporting details (a test case that demonstrates a bug), or providing
    suggestions on how to address the issue.
3.  By helping to resolve the issue: Typically this is done either in the form
    of demonstrating that the reported bug is not a problem after all, or by
    suggesting how to implement the requested feature or suggestion, or more
    often, by opening a Pull Request that changes some bit of something in
    the code in a concrete and reviewable manner.

## Asking for Help

Because we only limit the issue trackers of all the repositories to bug reports
and feature request/suggestions, questions or requests for general help using
regarding Bastion and the project should be directed to the [Bastion HQ].

## Submitting an Issue

When opening a new issue in any issue tracker, of [The Bastion Bot GitHub
Organization], you will be presented with a basic template that should be filled
in.

```markdown
<!--
    Thank you for opening an issue.

    This issue tracker is for bugs and issues found within this repository, and
    for feature requests/suggestions for this repository.
    If you require general support or if you have some question, please ask in
    the Bastion HQ: https://discord.gg/fzx8fkt


    Please fill in as much of the template below as you're able.
-->


#### I'm opening this issue because:
<!--
    Put an X between the brackets on the following lines if a statement is true.
    For example,
      -  [X] - This statement is true.
      -  [ ] - This statement is false.
-->

 -  [ ] I want to report a bug/issue.
 -  [ ] I want to request a feature or suggest something.


#### Supporting Information:
<!-- Only required if you're reporting a bug/issue. -->

<!-- Displayed in the output of Bastion's `stats` or `changelog` command -->
 -  **Bastion Version**:

<!-- Output of `node -v` -->
 -  **Node.js Version**:

<!-- Output of `npm -v` -->
 -  **NPM Version**:

<!--
    In Linux/macOS, output of `uname -a` or the version of Windows.
    And if your Operating System is 32-bit or 64-bit.
-->
 -  **Platform**:


<!--
    Enter your issue details, in as much details as possible, after the end of
    this section.

    In case of filing a bug report, please provide us with the details so that
    we can recreate the issue/problem on our own, keeping it as simple as
    possible.
    And, in case of a feature request/suggestion, please provide us with
    enough detail so that we can understand what the feature should be able to
    do so that we can understand your requirements and implement it as soon as
    possible.
-->

```

If you believe that you have uncovered a bug/issue or if you have want to
request any feature or suggest something in any repository, please fill out this
form, following the template to the best of your ability. Some repository might
ask you for more details based on the requirements. Do not worry if you
cannot answer every detail, just fill in what you can.

The two most important pieces of information we need in order to properly
evaluate the report is a description of the behavior you are seeing or want to
suggest and, in case of bug reports, a simple test case we can use to recreate
the problem on our own. If we cannot recreate the issue, it becomes impossible
for us to fix.

In order to rule out the possibility of bugs introduced by userland code, you
shouldn't have modified any code of Bastion unless you've been told to do so
by a [member of The Bastion Bot Project](https://github.com/orgs/TheBastionBot/people).

If the bug occurs only when you're using a specific userland/custom module, or
when you've modified some part of the code, there is a very good chance that
either (a) the module has a bug or (b) something in the core has changed that
broke the module.

See [How to create a Minimal, Complete, and Verifiable example](https://stackoverflow.com/help/mcve).

## Triaging an Issue

Once an issue has been opened, it is not uncommon for there to be discussion
around it. Some contributors may have differing opinions about the issue,
including whether the behavior being seen is a bug or a feature or if the
requested feature/suggestion can already be done in some way using existing
features or they may see it as unneeded. This discussion is part of the process
and should be kept focused, helpful, and professional.

Short, clipped responses — that provide neither additional context nor
supporting detail — are not helpful or professional. To many, such responses are
simply annoying and unfriendly.

Contributors are encouraged to help one another make forward progress as much
as possible, empowering one another to solve/discuss issues collaboratively. If
you choose to comment on an issue that you feel either is not a problem that
needs to be fixed, or if you encounter information in an issue that you feel is
incorrect, or either if you think the requested feature/suggestion can be done
using existing features or if you think it is unneeded, explain *why* you feel
that way with additional supporting context, and be willing to be convinced that
you may be wrong. By doing so, we can often reach the correct outcome much
faster.

## Resolving an Issue

In the vast majority of cases, issues/feature requests are resolved/implemented
by opening a Pull Request. The process for opening and reviewing a Pull Request
is similar to that of opening and triaging issues, but carries with it a
necessary review and approval workflow that ensures that the proposed changes
meet the minimal quality and functional guidelines of The Bastion Bot Project.


<!-- Links -->
[The Bastion Bot GitHub Organization]: https://github.com/TheBastionBot 'The Bastion Bot GitHub Organization'
[Bastion HQ]: https://discord.gg/fzx8fkt 'The Official Discord Server of The Bastion Bot Project'
