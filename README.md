# Project name

## Vision

*Approx 10-15 lines*.

The aim of this project is …

We’re solving … problem but you may also use this project to …

## Ethics

This project operates under the W3C's
[Code of Ethics and Professional Conduct](https://www.w3.org/Consortium/cepc):

> W3C is a growing and global community where participants choose to work
> together, and in that process experience differences in language, location,
> nationality, and experience. In such a diverse environment, misunderstandings
> and disagreements happen, which in most cases can be resolved informally. In
> rare cases, however, behavior can intimidate, harass, or otherwise disrupt one
> or more people in the community, which W3C will not tolerate.
>
> A Code of Ethics and Professional Conduct is useful to define accepted and
> acceptable behaviors and to promote high standards of professional
> practice. It also provides a benchmark for self evaluation and acts as a
> vehicle for better identity of the organization.

We hope that our community group act according to these guidelines, and that
participants hold each other to these high standards. If you have any questions
or are worried that the code isn't being followed, please contact the owner of the repository.


## Language

The development language is English. All comments and documentation should be written in English, so that we don't end up with “franglais” methods, and so we can share our learnings with developers around the world.

However, the domain language is French. We consider each tax, collecting organism and French regulation as a domain-specific term. In the same fashion, well-known abbreviations of these domain-specific terms are accepted.

OR

Par souci de lisibilité pour les partenaires, la langue utilisée pour la description et le suivi de fonctionnalités est le français.

En revanche, pour éviter le coût du changement de contexte, les discussions techniques peuvent se faire en anglais, la langue la plus utilisée dans le cadre du développement logiciel.

## History

We started this project on … for this particular use-case.

We open-sourced it on … / since the beginning because …

## Installation

We’re using these technologies: … because …

Once installed, you have to run these commands to setup the project:

```shell
pip install -r requirements/
bower install
fab runserver
```

Enjoy!

## Contributing

We’re really happy to accept contributions from the community, that’s the main reason why we open-sourced it! There are many ways to contribute, even if you’re not a technical person.

We’re using the infamous [simplified Github workflow](http://scottchacon.com/2011/08/31/github-flow.html) to accept modifications (even internally), basically you’ll have to:

* create an issue related to the problem you want to fix (good for traceability and cross-reference)
* fork the repository
* create a branch (optionally with the reference to the issue in the name)
* hack hack hack
* commit incrementally with readable and detailed commit messages
* submit a pull-request against the master branch of this repository

We’ll take care of tagging your issue with the appropriated labels and answer within a week (hopefully less!) to the problem you encounter.

If you’re not familiar with open-source workflows or our set of technologies, do not hesitate to ask for help! We can mentor you or propose good first bugs (as labeled in our issues). Also welcome to add your name to Credits section of this document.

### Submitting bugs

You can report issues directly on Github, that would be a really useful contribution given that we lack some user testing on the project. Please document as much as possible the steps to reproduce your problem (even better with screenshots).

### Discussing strategies

We’re trying to develop this project in the open as much as possible. We have a dedicated mailing-list where we discuss each new strategic change and invite the community to give a valuable feedback. You’re encouraged to subscribe to it and participate.

### Adding documentation

We’re doing our best to document each usage of the project but you can improve it or add you own sections. The documentation is available within the /docs/ folder. You don’t have to build anything, we’ll take care of it once your changes are merged.

### Improving User eXperience

You don’t have to install the whole project to fix a CSS or UI bug. We’re using a static [styleguide](http://styleguides.io/) that you can access to within the /statics/styleguide/ folder. You can edit the CSS/templates and just load the plain HTML page to see your changes. Once your pull-request merged, we’ll take care of integrating it within the whole project for you.

### Hacking backend

Hello fellow hacker, it’s good to have you on board! There is an extra step to install development dependencies if you plan to modify our core server:

* `pip install -r requirements/dev.txt`

Once you did it, the server will reload automagically upon your changes of the source code. You have to run tests periodically though to ensure that your changes don’t break existing functionalities. Our continuous integration server will run the whole test suite once you submit your pull-request (approx. 5 minutes).

Commit messages should be formatted using [AngularJS conventions](http://goo.gl/QpbS7) (one-liners are OK for now but body and footer may be required as the project matures).

Comments follow [Google's style guide](http://google-styleguide.googlecode.com/svn/trunk/pyguide.html#Comments).


## Financing

We accept donations and we have a bounty program to develop some big features:

* A plugin architecture - 3000€
* Accepting custom themes - 1000€

Please contact us if you want to collaborate on those features or mutualize your costs with other people/companies. If you pay for these developments, we offer half a day of support for you and your team.

Note that each feature will be discussed and developed in the open with the whole community, financing bounties doesn’t give you a stronger voice. If you’re looking for personal/closed-source improvements we can do consulting too.

## Versioning

Version numbering follows the [Semantic versioning](http://semver.org/) approach.

## License

We’re using the … license because we believe in …

## Rationale for forking (optional)

We forked that project because:

* it has been rather poorly maintained for x years
* we would like to develop … feature
* we disagree on the governance of the project
* etc

## Credits

* [John Snow](http://gameofthrones.wikia.com/wiki/Jon_Snow)
* etc
