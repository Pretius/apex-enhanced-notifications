# Pretius APEX Notifications
##### Oracle APEX dynamic action plugin v1.0

The plugin is dynamic action plugin providing notifications for Oracle APEX 5 and Universal Theme. Due to highly configurable attributes, the plugin can be used as presentation layer for AJAX callbacks. Translated messages from the database can be easly presented in two types of notification.

## Preview
![Alt text](/preview.gif?raw=true "Preview")

## Table of Contents
- [Pretius APEX Notifications](#pretius-apex-notifications)
  - [Oracle APEX dynamic action plugin v1.0](#oracle-apex-dynamic-action-plugin-v10)
- [Preview](#preview)
- [Table of Contents](#table-of-contents)
- [License](#license)
- [Demo Application](#demo-application)
- [Features at Glance](#features-at-glance)
- [Roadmap](#roadmap)
- [Install](#install)
  - [Installation package](#installation-package)
  - [Install procedure](#install-procedure)
- [Usage guide](#usage-guide)
- [Changelog](#changelog)
  - [1.0](#10)
- [About Author](#about-author)
- [About Pretius](#about-pretius)
- [Free support](#free-support)
  - [Bug reporting and change requests](#bug-reporting-and-change-requests)
  - [Implementation issues](#implementation-issues)
- [Become a contributor](#become-a-contributor)
- [Comercial support](#comercial-support)


## License
MIT

## Demo Application
[http://apex.pretius.com/apex/f?p=105:NOTIFICATIONS](http://apex.pretius.com/apex/f?p=105:NOTIFICATIONS)

## Features at Glance
* APEX like appearance
* Message can be static text or result of the JavaScript function
* Floating and inline notifications
* Support for "Modal page close event" and "Custom event"
* Highly configurable:
  * floating and inline common attributes
    * three types: Success, Warning, Error
    * duration of presentation
    * remove animation: fade out, slide up, remove
    * show new notification on top or bottom of the queue
    * message can be single-line or single-line with additional list of messages
  * floating attributes
    * four positions: top right, top left, bottom left, bottom right
  * inline attributes
    * fixed position
    * scroll browser to notification
    * mergeable with existing notificaitions
    * remove existing notifications
    * show bullets for list elements    

## Roadmap
Not yet defined

## Install 

### Installation package
1. `src/dynamic_action_plugin_pretius_com_notifications.sql` - the plugin installation file for Oracle APEX 5.1 or higher

### Install procedure
To successfully install/update the plugin follow those steps:
1. Install the plugin file `dynamic_action_plugin_pretius_apex_nested_reports.sql` using Oracle APEX plugin import wizard
1. Configure application level componenets of the plugin
1. When asked whether "Use Universal Theme templates" select "No" and proceed with wizard.*

`* Selecting Yes means that the plugin will fetch SUCCESS_MESSAGE and NOTIFICATION_MESSAGE UT templates from APEX tables.`

`* Selecting No means that the plugin will use plugin SUCCESS_MESSAGE and NOTIFICATION_MESSAGE templates.`

## Usage guide

Please check [live demo](http://apex.pretius.com/apex/f?p=105:NOTIFICATIONS) for implementation description.

## Changelog

### 1.0
Initial release

## About Author
Author            | Website                                 | Github                                       | Twitter                                       | E-mail
------------------|-----------------------------------------|----------------------------------------------|-----------------------------------------------|----------------------------------------------------
Bartosz Ostrowski | [http://ostrowskibartosz.pl](https://www.ostrowskibartosz.pl) | [@bostrowski](https://github.com/bostrowski) | [@bostrowsk1](https://twitter.com/bostrowsk1) | bostrowski@pretius.com, ostrowski.bartosz@gmail.com

## About Pretius
Pretius Sp. z o.o. Sp. K.

Address | Website | E-mail
--------|---------|-------
Przy Parku 2/2 Warsaw 02-384, Poland | [http://www.pretius.com](http://www.pretius.com) | [office@pretius.com](mailto:office@pretius.com)

## Free support
Pretius provides free support for the plugins at the GitHub platform. 
We monitor raised issues, prepare fixes, and answer your questions. However, please note that we deliver the plug-ins free of charge, and therefore we will not always be able to help you immediately. 

Interested in better support? 
* [Become a contributor!](#become-a-contributor) We always prioritize the issues raised by our contributors and fix them for free.
* [Consider comercial support.](#comercial-support) Options and benefits are described in the chapter below.


### Bug reporting and change requests
Have you found a bug or have an idea of additional features that the plugin could cover? Firstly, please check the Roadmap and Known issues sections. If your case is not on the lists, please open an issue on a GitHub page following these rules:
* issue should contain login credentials to the application at apex.oracle.com where the problem is reproduced;
* issue should include steps to reproduce the case in the demo application;
* issue should contain description about its nature.

### Implementation issues
If you encounter a problem during the plug-in implementation, please check out our demo application. We do our best to describe each possible use case precisely. If you can not find a solution or your problem is different, contact us: apex-plugins@pretius.com.

## Become a contributor!
We consider our plugins as genuine open source products, and we encourage you to become a contributor. Help us improve plugins by fixing bugs and developing extra features. Comment one of the opened issues or register a new one, to let others know what you are working on. When you finish, create a new pull request. We will review your code and add the changes to the repository.

By contributing to this repository, you help to build a strong APEX community. We will prioritize any issues raised by you in this and any other plugins.

## Comercial support
We are happy to share our experience for free, but we also realize that sometimes response time, quick implementation, SLA, and instant release for the latest version are crucial. That’s why if you need extended support for our plug-ins, please contact us at apex-plugins@pretius.com.
We offer:
* enterprise-level assistance;
* support in plug-ins implementation and utilization;
* dedicated contact channel to our developers;
* SLA at the level your organization require;
* priority update to next APEX releases and features listed in the roadmap.