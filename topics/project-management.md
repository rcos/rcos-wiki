# Project-management

**Website**:
[Project Management](https://en.wikipedia.org/wiki/Project Management)

The management of a project is one of the most important aspects, to the
point where in many enterprise environments there are people whose whole
job is to manage projects. However far more goes into it than most
people expect and things you might not have thought of are part of
project management.

## Repositories

Your repo is the most basic form of project management, but also one of
the most important.

Things like good commit messages, keeping branches up to date, and
tagging releases will make development much easier for you.

## Blessed Repository

A common paradigm for development, and one that GitHub promotes.

The main project repository is \"blessed\" where each change needs to go
through a pull request and be approved before being merged.

Each developer hacks on their own fork, allowing them to experiment
freely and only pull in the good changes.

## Communication

Having a clear channel of communication is an important aspect of a
project. Being able to talk with other developers, as well as offer a
place for users to ask questions can be critical.

## Issues

Having a issue/bug tracker is important, especially as a project grows.

Knowing what needs to be done and who is working on it, as well as
having a preserved log of discussion will help you not only as you
develop, but can provide valuable answers for anyone who looks later.

## Boards

Using kaban-style boards, such as Trello or GitHub Projects, is not for
everyone, but can be very beneficial to some projects.

Being able to see at a glance the status of each issue and who needs
help can be extremely useful to project leaders.

## Documentation

Having documentation is crucial to the long-term success of any project.
Code comments, GitHub wikis, Markdown files, whatever method works best
for you.

Every project should at least have some documentation such as an
up-to-date readme file.

## Milestones

Setting goals is important for every project. You have to know what
you\'re even trying to do with your project.

Having clear goals will help you progress faster, and checking them off
is a very satisfying feeling.

## Build Systems

New developers aren\'t going to know the exact set of steps required to
build your project. Even if they\'re written down you can almost always
simplify the process.

Build systems exist solely for this. Reducing that long `gcc ...`
command to a single `make` will speed up development and help new
members.

## CI/CD

Continuous integration (CI) and continuous delivery (CD) are more modern
techniques, where each change is compiled and tested and then deployed.

This can speed up development immensely and pairs well with the blessed
repository style, where each PR can be tested before it is merged.

## Publishing

When your project is finally ready to be released, it needs to be
published somewhere. This varies depending on your project, but it is
important to make sure that you release to in the right place and the
right way.

A simple way to publish your project is to tag a release on GitHub.

This goes very well with the CI/CD workflow.

## Rarer Methods

-   Mailing lists
-   Patch workflow
-   Integrated bug-trackers (Fossil)
-   BDFL

## Resources

-   [Project Management presentation by Steven
    vanZyl](https://gist.github.com/rushsteve1/d160cf1f629650bfe0605326d2b5458c)
