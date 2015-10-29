Clippings Challenge
-------------------

A task to implement a small php package, for candidate evaluation.

The task
--------

Build a swiftmailer plugin for generating plain text message alternatives.

Details
-------

[Swiftmailer](http://swiftmailer.org/) package is great for sending email and we use it extensively. However we only have emails in HTML, and would like there to be a nice plain text alternatives too.

Swiftmailer supports plugins and is very configurable so it should be possible to implement a plugin that does that automatically with an acceptable quality. There are already quite a lot of plugins and [documentation how to use them](http://swiftmailer.org/docs/plugins.html), that should be of help.

We have already implemented several plugins for swiftmailer ourselves which can be used as further guide too, but you can do whatever you think is best.

| Clippings swfitmailer plugins                        |
| ---------------------------------------------------- |
| https://github.com/OpenBuildings/?query=swiftmailer  |
| https://github.com/clippings/?query=swiftmailer      |



The only requirements we have is this to be a [composer package](https://getcomposer.org/), and to have an acceptable test coverage. Added bonus is the use of (with a high score) of [scrutinizer-ci](https://scrutinizer-ci.com/) or another static code analysis tool, as you can see in our own packages.

If you don't want to start from scratch, we have our own template generator that will bring you up to speed - https://github.com/clippings/composer-init (you should use "clippings/package-template" template), however you can do whatever you think is best.

The resulting work should have a license compatible with BSD-3-Clause (e.g MIT), and will remain under your own copyright to do as you wish, present elsewere or promote as your own open-source project.

Good luck!




