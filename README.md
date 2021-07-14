# My Notes

Links, notes, and things.

- [GIT tricks and commands](git.md)
- [Articles and Blog Posts](articles.md)
- [Google Analytics](#analytics)
- [Documentation](#documentation)
- [Email](#email)
- [Front End](#front-end)
- [Linux](#linux)
- [PHP](#php)
  - [CakePHP](#cakephp)
  - [Symfony](#symfony)
  - [Testing](#testing)
  - [Benchmarking](#benchmarking)
  - [static Analysis](#Static-analysis)
- [Security](#security)
- [Misc](#misc)

## Analytics

[Block Yourself from Analytics](https://chrome.google.com/webstore/detail/block-yourself-from-analy/fadgflmigmogfionelcpalhohefbnehm?hl=en) — Filter yourself out of Google Analytics using an extension instead of maintaining an IP address filter set. 

[Campaign URL Builder](https://ga-dev-tools.appspot.com/campaign-url-builder/) — Builds those fun utm_source tracking URLs.

## Documentation

[TermToSvg](https://github.com/nbedos/termtosvg) — Creates terminal animations

## Email

[Litmus](https://litmus.com/) — Non-free SaaS for testing email rendering in 90+ email clients.

[HTML to Text Email Converter](https://templates.mailchimp.com/resources/html-to-text/) — Convert HTML emails to text to increase sendability

[Mail Tester](https://www.mail-tester.com/) — Test the deliverability of your emails

## Front End

[Chart.css](https://github.com/ChartsCSS/charts.css) — Charts in CSS only

[Symfony/UX-Turbo](https://github.com/symfony/ux-turbo) — TurboUX for Symfony.

[Hotwire](https://hotwire.dev/) — Hotwire is an alternative approach to building modern web applications without using much JavaScript by sending HTML instead of JSON over the wire.

[TimelineJS](https://github.com/NUKnightLab/TimelineJS) — A Storytelling Timeline built in JavaScript.

## Linux

[ncdu](https://dev.yorhel.nl/ncdu) — Ncdu is a disk usage analyzer with an ncurses interface.

[tmpreaper](http://manpages.ubuntu.com/manpages/bionic/man8/tmpreaper.8.html) — Temporary file cleanup utility

[nushell/nushell](https://github.com/nushell/nushell) — A new shell for linux

## PHP

[Shopsys/Monorepo Tools](https://github.com/shopsys/monorepo-tools) — Another monorepo toolset

[JsonMachine](https://github.com/halaxa/json-machine) — Efficient, easy-to-use, and fast PHP JSON stream parser

#### CakePHP

[CakePHP PHP-PM](https://github.com/CakeDC/cakephp-phppm) — PHP-PM for CakePHP

[Galley](https://gitlab.com/amayer5125/galley) — Docker files for running a basic CakePHP application.

#### Symfony

[Symfony/Panther](https://github.com/symfony/panther) — A browser testing and web crawling library for PHP and Symfony

[Symfony/Monorepo Builder](https://github.com/symplify/monorepo-builder) — A symfony monorepo tool

#### Testing

[GrumPHP](https://github.com/phpro/grumphp) — Automated code quality and task runner for localhosts with integrated git hooks. 

[Infection](https://github.com/infection/infection) — AST based PHP Mutation Testing Framework.

[Paratest](https://github.com/paratestphp/paratest) — Parallel testing for PHPUnit.

[PHPUnit SpeedTrap](https://github.com/johnkary/phpunit-speedtrap) — Reports on slow-running PHPUnit tests right in the console.

#### Benchmarking

[PHP Bench](https://github.com/phpbench/phpbench) — PHPBench is a benchmark runner for PHP analagous to PHPUnit but for performance rather than correctness.

[Blackfire](https://www.blackfire.io/) — Continuous performance testing.

#### Static Analysis

[Tombstone](https://github.com/scheb/tombstone) — Deadcode detection

## Security

[Security Headers](https://securityheaders.com/) — Analyze your HTTP security headers.

## Misc

### Poor Mans Loggly

If you don't have the $80 or are to lazy to configure logstash etc... Sign up for mailjet (they have a free tier), configure postfix to relay through it, and then configure logwatch to send digests.

[Logwatch](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-logwatch-log-analyzer-and-reporter-on-a-vps)

[Mailjet](https://www.mailjet.com/)

[Mailjet SMTP Relay with Postfix](https://www.linuxbabe.com/mail-server/postfix-smtp-relay)
