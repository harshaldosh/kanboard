Kanboard
========

Kanboard is a simple visual task board web application.

Official website: <http://kanboard.net>

- Inspired by the [Kanban methodology](http://en.wikipedia.org/wiki/Kanban)
- Get a visual and clear overview of your project
- Multiple boards with the ability to drag and drop tasks
- Minimalist software, focus only on essential features (Less is more)
- Open source and self-hosted
- Super simple installation

[![Build Status](https://travis-ci.org/fguillot/kanboard.svg)](https://travis-ci.org/fguillot/kanboard)

[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/fguillot/kanboard/badges/quality-score.png?s=2b6490781608657cc8c43d02285bfafb4f489528)](https://scrutinizer-ci.com/g/fguillot/kanboard/)

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

Features
--------

- Multiple boards/projects
- Boards customization, rename/add/remove columns
- Tasks with different colors, categories, sub-tasks, attachments, comments and Markdown support for the description
- Automatic actions based on events
- User management with a basic privileges separation (administrator or regular user)
- Email notifications
- External authentication: Google, GitHub, LDAP/ActiveDirectory and Reverse-Proxy
- Webhooks to create tasks from an external software
- A basic command line interface
- Host anywhere (shared hosting, VPS, Raspberry Pi or localhost)
- No external dependencies
- **Super easy setup**, copy and paste files and you are done!
- Translated in 18 languages (Brazilian, Chinese, Danish, Dutch, English, Finnish, French, German, Hungarian, Italian, Japanese, Polish, Russian, Serbian, Spanish, Swedish, Thai, Turkish)

Known bugs and feature requests
-------------------------------

See Issues: <https://github.com/fguillot/kanboard/issues>

License
-------

GNU Affero General Public License version 3: <http://www.gnu.org/licenses/agpl-3.0.txt>

Related projects
----------------

- [Kanboard Presenter by David Eberlein](https://github.com/davideberlein/kanboard-presenter)
- [CSV2Kanboard by @ashbike](https://github.com/ashbike/csv2kanboard)
- [Kanboard for Yunohost by @mbugeia](https://github.com/mbugeia/kanboard_ynh)
- [Trello import script by @matueranet](https://github.com/matueranet/kanboard-import-trello)
- [Chrome extension by Timo](https://chrome.google.com/webstore/detail/kanboard-quickmenu/akjbeplnnihghabpgcfmfhfmifjljneh?utm_source=chrome-ntp-icon), [Source code](https://github.com/BlueTeck/kanboard_chrome_extension)
- [Wunderlist To Kanboard script by EpocDotFr](https://github.com/EpocDotFr/WunderlistToKanboard)

Documentation
-------------

### Using Kanboard

#### Introduction

- [What is Kanban?](docs/what-is-kanban.markdown)
- [Kanban vs Todo Lists and Scrum](docs/kanban-vs-todo-and-scrum.markdown)
- [Usage examples](docs/usage-examples.markdown)

#### Working with projects

- [Creating projects](docs/creating-projects.markdown)
- [Editing projects](docs/editing-projects.markdown)
- [Sharing boards and tasks](docs/sharing-projects.markdown)
- [Automatic actions](docs/automatic-actions.markdown)
- [Project permissions](docs/project-permissions.markdown)
- [Swimlanes](docs/swimlanes.markdown)
- [Calendar](docs/calendar.markdown)
- [Budget](docs/budget.markdown)
- [Analytics](docs/analytics.markdown)

#### Working with tasks

- [Creating tasks](docs/creating-tasks.markdown)
- [Adding screenshots](docs/screenshots.markdown)
- [Task links](docs/task-links.markdown)
- [Transitions](docs/transitions.markdown)
- [Time tracking](docs/time-tracking.markdown)
- [Recurring tasks](docs/recurring-tasks.markdown)
- [Create tasks by email](docs/create-tasks-by-email.markdown)

#### Working with users

- [User management](docs/user-management.markdown)
- [Hourly rate](docs/hourly-rate.markdown)
- [Timetable](docs/timetable.markdown)
- [Two factor authentication](docs/2fa.markdown)

#### Settings

- [Keyboard shortcuts](docs/keyboard-shortcuts.markdown)
- [Application settings](docs/application-configuration.markdown)
- [Board settings](docs/board-configuration.markdown)
- [Link settings](docs/link-labels.markdown)
- [Currency rate](docs/currency-rate.markdown)
- [Config file](docs/config.markdown)

### Integrations

- [Bitbucket webhooks](docs/bitbucket-webhooks.markdown)
- [Github webhooks](docs/github-webhooks.markdown)
- [Gitlab webhooks](docs/gitlab-webhooks.markdown)
- [Hipchat](docs/hipchat.markdown)
- [Jabber](docs/jabber.markdown)
- [Mailgun](docs/mailgun.markdown)
- [Sendgrid](docs/sendgrid.markdown)
- [Slack](docs/slack.markdown)
- [Postmark](docs/postmark.markdown)

#### More

- [Syntax guide](docs/syntax-guide.markdown)
- [Frequently asked questions](docs/faq.markdown)

### Technical details

#### Installation

- [Installation instructions](docs/installation.markdown)
- [Upgrade Kanboard to a new version](docs/update.markdown)
- [Installation on Ubuntu](docs/ubuntu-installation.markdown)
- [Installation on Debian](docs/debian-installation.markdown)
- [Installation on Centos](docs/centos-installation.markdown)
- [Installation on FreeBSD](docs/freebsd-installation.markdown)
- [Installation on Windows Server with IIS](docs/windows-iis-installation.markdown)
- [Installation on Windows Server with Apache](docs/windows-apache-installation.markdown)
- [Installation on Heroku](docs/heroku.markdown)
- [Example with Nginx + HTTPS + SPDY + PHP-FPM](docs/nginx-ssl-php-fpm.markdown)

#### Database

- [Sqlite database management](docs/sqlite-database.markdown)
- [How to use Mysql](docs/mysql-configuration.markdown)
- [How to use Postgresql](docs/postgresql-configuration.markdown)

#### Authentication

- [LDAP authentication](docs/ldap-authentication.markdown)
- [Google authentication](docs/google-authentication.markdown)
- [GitHub authentication](docs/github-authentication.markdown)
- [Reverse proxy authentication](docs/reverse-proxy-authentication.markdown)

#### Developers and sysadmins

- [Email configuration](docs/email-configuration.markdown)
- [Command line interface](docs/cli.markdown)
- [Json-RPC API](docs/api-json-rpc.markdown)
- [Webhooks](docs/webhooks.markdown)
- [Run Kanboard with Vagrant](docs/vagrant.markdown)
- [Run Kanboard with Docker](docs/docker.markdown)

### Contributors

- [Contributor guide](docs/contributing.markdown)
- [Translations](docs/translations.markdown)
- [Coding standards](docs/coding-standards.markdown)
- [Running tests](docs/tests.markdown)
- [Build assets](docs/assets.markdown)

The documentation is written in [Markdown](http://en.wikipedia.org/wiki/Markdown).
If you want to improve the documentation, just send a pull-request.

FAQ
---

Go to the official website: <http://kanboard.net/faq>

Authors
-------

Original author: [Frédéric Guillot](http://fredericguillot.com/)

Contributors:

- Alex Butum
- [Aleix Pol](https://github.com/aleixpol)
- [Ashbike](https://github.com/ashbike)
- [Ashish Kulkarni](https://github.com/ashkulz)
- [Christian González](https://github.com/nerdoc)
- [Chorgroup](https://github.com/chorgroup)
- Claudio Lobo
- [Cluxter](https://github.com/cluxter)
- [Cmer](https://github.com/chncsu)
- [Colin Williams](https://github.com/crwilliams)
- [Crash5](https://github.com/crash5)
- [Creador30](https://github.com/creador30)
- [Cynthia Pereira](https://github.com/cynthiapereira)
- [David-Norris](https://github.com/David-Norris)
- [Draza (bdpsoft)](https://github.com/bdpsoft)
- [Esteban Monge](https://github.com/EstebanMonge)
- [Fengchao](https://github.com/fengchao)
- [Floaltvater](https://github.com/floaltvater)
- [Gavlepeter](https://github.com/gavlepeter)
- [Hendrik Stocker](https://github.com/hendrik-stoker)
- [Iterate From 0](https://github.com/freebsd-kanboard)
- [Jan Dittrich](https://github.com/jdittrich)
- [Janne Mäntyharju](https://github.com/JanneMantyharju)
- [Jean-François Magnier](https://github.com/lefakir)
- [Jesusaplsoft](https://github.com/jesusaplsoft)
- [Karol J](https://github.com/dzudek)
- [Kiswa](https://github.com/kiswa)
- [Kralo](https://github.com/kralo)
- [Lars Christian Schou](https://github.com/NegoZiatoR)
- [Levlaz](https://github.com/levlaz)
- [Lim Yuen Hoe](https://github.com/jasonmoofang)
- [Manish Lad](https://github.com/manishlad)
- [Mathgl67](https://github.com/mathgl67)
- [Matthieu Keller](https://github.com/maggick)
- [Mauro Mariño](https://github.com/moromarino)
- [Maxime](https://github.com/EpocDotFr)
- [mfoucrier](https://github.com/mfoucrier)
- [Mgro](https://github.com/mgro)
- [Michael Lüpkes](https://github.com/mluepkes)
- [Mihailov Vasilievic Filho](https://github.com/mihailov-vf)
- [Moraxy](https://github.com/moraxy)
- [Nala Ginrut](https://github.com/NalaGinrut)
- [Nekohayo](https://github.com/nekohayo)
- [Nicolas Lœuillet](https://github.com/nicosomb)
- [Norcnorc](https://github.com/norcnorc)
- [Nramel](https://github.com/nramel)
- [Null-Kelvin](https://github.com/Null-Kelvin)
- [Oliver Bertuch](https://github.com/poikilotherm)
- [Olivier Maridat](https://github.com/oliviermaridat)
- [Oren Ben-Kiki](https://github.com/orenbenkiki)
- Paolo Mainieri
- [Peller Zoltan](https://github.com/PierP)
- [Petja Touru](https://github.com/Petja)
- [Piotr Zęgota](https://github.com/ZegalPL)
- [Rafaelrossa](https://github.com/rafaelrossa)
- [Raphaël Doursenaud](https://github.com/rdoursenaud)
- [René Stoltenberg](https://github.com/rstoltenberg)
- [Rzeka](https://github.com/rzeka)
- [Sebastien Pacilly](https://github.com/spacilly)
- [Sebastian Reese](https://github.com/ReeseSebastian)
- [Semyon Novikov](https://github.com/semka)
- [Sylvain Veyrié](https://github.com/turb)
- [Timo](https://github.com/BlueTeck)
- [Tomáš Votruba](https://github.com/TomasVotruba)
- [Toomyem](https://github.com/Toomyem)
- [Tony G. Bolaño](https://github.com/tonybolanyo)
- [Torsten](https://github.com/misterfu)
- [Troloo](https://github.com/troloo)
- [Typz](https://github.com/Typz)
- [Vedovator](https://github.com/vedovator)
- [Vladimir Babin](https://github.com/Chiliec)
- [Ybarc](https://github.com/ybarc)
- [Yuichi Murata](https://github.com/yuichi1004)

There is also many people who have reported bugs or proposed awesome ideas.
