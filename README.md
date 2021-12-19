<h1 align="center">Magento 2 Frostbite</h1>

A cache warming tool for Magento.


### Description
Magento needs better caching mechanisms.


Facts
-----
 * Version: 0.1.1
 * [Repository on Github](https://github.com/iods/magento2-frostbite)


Getting Started
---------------

#### Download Zip
Download a release.

#### Through Composer
Working on this.


### Requirements
 * [Git](http://git-scm.com)
 * [Composer](http://getcomposer.org)
 * [Magento <= 2.4]()

### Known Issues
 * Link to any Github issues, or list issues w/ Magento 2 compatibility or Extension compatibility


## Related Projects / Tickets / Stories
If you use your module internally, try to add links to related documentation covered in projects or tickets.

* [#00000](https://yourProjectManagementSystem.com/yourTicketNumber) - Task Title goes here


### Installation
Includes a series of step-by-step examples for installation and configuration.

```
$ composer require iods/module-frostbite
$ bin/magento module:enable Iods_Frostbite
$ bin/magento setup:upgrade
$ bin/magento cache:flush

$ bin/magento cache:warm:configure
$ bin/magento cache:warm:run
```

## Deployment
Add additional notes about how to deploy this on a live system

## Built With
* [Your Framework](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Your Dependency Management](https://maven.apache.org/) - Dependency Management
* [Other Tools, you use](https://rometools.github.io/rome/) - Any Kind of Generator for example

## Magento 2

### Components
Learn a bit more here.


### Extensions
Explain how to extend your module.

```
Give an example
```

### Configurations
Give an overview of the given configurations.

You have to disable merge css if you want to use CSS modifier functions.

| Section | Group | Field | Description |
| ------ | ----- | ----- | ----------- |
| web | default | cms_home_page | Select the CMS Home Page |
| web | default| cms_no_route | Select the 404 Page |
| web | default | cms_no_cookies | Select the No Cookies Page |

Development
-----------

### Structure
How does it work? What components in the module exist. What is different. Link to devdocs.

Finishing w/ an example of system information of demo of the module for your team.


### Extensibility
Includes a series of step-by-step examples for extending the module and code snippets of the extension points.

#### Events
A list of events dispatched by the module.

#### Layouts
Does it introduce layouts or layout handles?


### UI Components
Does the module introduce any UI components or the configuration files, where are they?


### Public API
Does the module introduce any public API? what services are introduced?

```bash
\Magento\Sales\Api\InvoiceOrderInterface
  * Create an Invoice
  * Change status and state
```

## Packagist Setting
- [Create account](https://packagist.org/register/)
- Connect with Github account
- [Submit package](https://packagist.org/packages/submit)
    - URL example: `https://github.com/rangerz/magento2-module-template`


### Tests
Includes a series of step-by-step examples for testing the module.


### Code Styles
Includes any relevant code style information or documentation.


### Configuration
Overview of the admin/configuration settings within the module.

| group | field | description |
|-------|-------|-------------|
|web    |default|example      |
|web    |default|example      |
|admin  |default|example      |


Support
-------
If you have any issues with this project, open an issue on [Github](https://github.com/iods/magento2-bones/issues)


Developer
---------
 * **Rye Miller** - *Initial work* - [GitHub](http://github.com/iods/), [Homepage](https://ryemiller.io)

See also the list of [contributors](https://github.com/iods/magento2-performance/contributors) who participated in this project.


Versioning
----------
For transparency into the release cycle and in striving to maintain backward compatibility, this project is
maintained under [the Semantic Versioning guidelines](http://semver.org/).


License
-------
This project/code is released under [the MIT license](https://github.com/iods/magento2-bones/LICENSE).


Copyright
---------
(c) 2020-2021 Rye Miller. All Rights Reserved.
