# MCVE

This is a database of public disclosures of security problems in Minecraft
software. As more and more software is created with varying complexity, there
have been multiple instances where mistakes introduced into some part of
Minecraft software resulted in a server becoming vulnerable to a variety of
attacks.

The purpose of this database is to catalog these deficiencies in an effort to
improve the security of servers. This database is educational - the primary
purpose is to inform owners about vulnerabilities within software and to inform
developers about ways which have previously caused vulnerabilities. The purpose
is not a shame board - learn from mistakes, don't point fingers for mistakes.

## Looking up vulnerabilities

If you have a number, simply look in the `entries/` folder for its folder. If
you want to look up a plugin, simply search the repository for its name. Its
all text anyways.

## Submitting vulnerabilities

There are a variety of ways to add an entry to this list:

+ PR it. Copy `template/` into a new folder within `entries/` with the proper
  format specified in `entries/README.md`. Do not assign it a number - when
  merging, a contributor will properly number the entry.

+ Make an issue. Fill out an issue with the proper info within
  `template/entry.yml`. A contributor will add the entry.

+ Email `vuln@ibj.io`. Send appropriate info. I will hold onto the issue for
  publication at a later date if so requested.

+ Message on Discord. Join https://discord.gg/keqCQm and tell @ichbinjoe about
  it. Same as email, if requested I will hold the issue for publication at a
  later date.

## What entries are valid for submission?

Entries should be made with good intent - remember, this is an educational
database, not a database of mistakes. Entries may be submitted for any software
by anyone - if you do not manage the software, it is recommended you alert the
maintainer. If you want help, a database maintainer can help assist you
reaching out and communicating the problems.

Entries in this database should be vulnerabilities - something which a
malicious user may exploit in order to compromise security or degrade
performance on server. Entries may target open source or paid resources - there
is no limitation. The database will not stop an entry from being published,
even if learning of a vulnerability requires 'breaking a TOS'.

This database isn't the right place for purposefully malicious plugins. This
database also isn't the right place for general defects in software - only
defects which result in users being able to cause service degradation or
security compromise.

## Removing vulnerabilities

Vulnerabilities will not be removed unless they are invalid.

