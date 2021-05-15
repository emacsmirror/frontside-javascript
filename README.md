# Frontmacs

[![Build Status](https://circleci.com/gh/thefrontside/frontmacs.svg?style=shield)](https://app.circleci.com/pipelines/github/thefrontside/frontmacs?branch=release)
[![Chat on Discord](https://img.shields.io/discord/700803887132704931?Label=Discord)](https://discord.gg/JNnzuSSSb4)
[![Created by Frontside](https://img.shields.io/badge/created%20by-frontside-26abe8.svg)](https://frontside.com)

A _package-based_, web-centric, customizable, awesome-by-default,
acceptance-tested Emacs distribution curated by your friends at
[Frontside][frontside].

We've been using Emacs for years here at [Frontside][frontside], and
have finally decided to share the configuration for our favorite
editor with the world. Why did we make our own?

### Package Based.

We've been satisfied users of many a starter kit over the years, from
the original [Emacs Starter Kit][2], to [Prelude][3] and
[Spacemacs][4]. Most starter kits you come across _begin_ with a
fork. You clone the repo, and then you're off to the races maintaining
your own version. Any customizations you make are made to files
under version control and so upgrading and keeping up with the
community is a constant battle of merges, rebases, throw-aways and
ultimately do overs. We know because we've [been there][5].

This is painful enough when you're maintaining your own fork, but
every time we wanted to make a customization from which the entire
team could benefit, it involved everybody doing the same merge, rebase,
throw-away dance. But, it turns out that Emacs has a mechanism to
distribute elisp code without having to use git. It's called `ELPA`
and it's awesome. You can think of it like a Ruby gem or an NPM
package, and this is what Frontmacs uses for deployment.

We don't want to maintain code, we just want to enter a few keystrokes
and download more awesome. And that's what we get by using elisp
packages to install Frontmacs. Now, anytime we fix a bug or make an
improvement, the entire team can benefit with a simple upgrade.

### Web technologies

We are specialists in UI, and so it is natural that our Emacs
distribution reflect that expertise. If you work in the web, then you
can be sure that Frontmacs will be an able partner in slinging modern
JavaScript using modern frameworks. Whether it's React, React Native,
Angular, Ember, SASS.... whatever.

### Awesome by Default

Emacs is true ultimate power! But that doesn't mean that it should be
intimidating or terrifying to set up. Frontmacs aims to have
everything you would expect to have a modern development environment
to have out of the box: navigation, completion, etc...

It draws power in a shared configuration in which everybody has a
stake. More knowledge shared means fewer bugs arise, and those that do
get resolved more quickly.


### Customizable

Just because the default set of packages is heavily curated, doesn't
mean that there shouldn't be room for you to innovate and exercise
your creative muscles.

In fact, because Frontmacs is distributed as an Emacs Lisp package, it is
_decoupled_ from git and so you are now free to maintain your own
customizations in your own repository without fear of conflicting with
the main distribution.

### Acceptance Tested

Most of the planet doesn't treat editor configuration as software. We
do.

Whenever you integrate a bunch of different packages from across the
internet, you're bound to run into conflicts over things like
key-bindings, or function advice.

Making changes to an editing experience shared by many people is a
responsibility we take very seriously. That's why Frontmacs makes sure
that critical behaviors are tested so that you won't get bad upgrades
that ruin your day. If you do, you can run the test suite to find out
exactly what went wrong and where.

## Installation & Development

It's in a state of intense flux at the moment, so if you're down for
the roller-coaster, get in touch on [DISCORD][discord].

[frontside]: http://frontside.com
[discord]: https://discord.com/invite/JNnzuSSSb4
[2]: https://github.com/technomancy/emacs-starter-kit
[3]: https://github.com/bbatsov/prelude
[4]: http://spacemacs.org/
[5]: https://github.com/thefrontside/.emacs.d
