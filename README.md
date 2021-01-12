Pip All
===

Fixing pip's problems, one package at a time


Pip
---

Python package manager! Install Python modules with ease! Pin them! Upgrade
them! The world is yours!

Pip All
-------

Okay, so upgrading packages en masse isn't really a "pip thing". All you can do
is ask pip "hey, what are my outdated packages?" and pip will tell you. If you
then ask pip "please, sir, I want some updates" I mean "update all the
packages" pip responds with ~~"What!"~~ "lol, no".

![Please, sir, I want some updated pip packges](.binary-assets/Oliver-Twist-begging.jpeg)

Enter `pip-all`. It fills in the void in our hearts, and our bowls.

It's also written in perl.

TODO
----

Re-write this in python. That feels more right. I don't know python, so I am
going to subcontract this out to someone else to at least get the basics in.
Such as "exec a process; read from that process; manipulate some JSON; run more
processes". Basically, what the current one does but in Python and with eating
JSON so I can see the current and updated versions since I can't do that easily
in Perl without screen scraping.

BUGS
----

* Uses regular expressions. I have [enough problems][CH], thank you.

* Assumes pip, and ignores pip3. May be a problem for [homebrew][HB], not so
  much for [`virtualenv`][VE].


[CH]: https://blog.codinghorror.com/regular-expressions-now-you-have-two-problems/
[HB]: https://brew.sh/
[VE]: https://virtualenv.pypa.io/en/latest/
