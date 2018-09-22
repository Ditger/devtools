# 1. PhpStorm

## 1.1. Settings

The behavior of PhpStorm can be influenced through a complex GUI. In this section we'll guide you through a few interesting and helpful settings.

### 1.1.1. Languages & Frameworks

#### 1.1.1.1. JavaScript

**1.1.1.1.1. Setting up Ecmascript**

By default PhPStorm will validate Javascript as Ecmascript 5.1. This will let the IDE run into issues while working with newer version of Ecmascript.

By going into the Languages & Frameworks settings you can find the JavaScript settings. In here you can switch through a simple dropdown to for example the newer Ecmascript 6.

**1.1.1.1.2. Libraries**

The validating of Javascript can be further extended with additional libraries.

* jQuery
  * Front-end developers working with jQuery can add this library to add jQuery validation to PhpStorm.
* Node.js Core
  * Adds the core library of NodeJS to PhpStorm. This will let the IDE read most of your syntax for validation.
* Express
  * To add specific validation for ExpressJS you will need to add this library on top of the NodeJS core library.

**1.1.1.1.3. Code Quality Tools**

The vanilla version of PhpStorm comes with the industry standard of validators and linters for Javascript by default. It is required however to enable these _per project_.

#### 1.1.1.2. PHP

At the parent level of the PHP category you can find settings to tell PhpStorm with which version of PHP you're working with. _Version 7.1_ or higher is recommended for this setting to let the IDE support you with all the new syntax since previous versions.

#### 1.1.1.3. Node.js and NPM

Next to the Node related settings in the Javascript category, Jetbrains has also provided us with a specific category dedicated to Node.js. When your core library for Node has been setup it may still be required for you to enable the library at this page.

This section also shows an automatically generated list of installed NPM packages, both globally and project specific. It's even possible to install more packages through this GUI, if you don't prefer your terminal of choice.

After clicking on a package you can also choose to upgrade it from within PhpStorm.

#### 1.1.1.4. Stylesheets

**1.1.1.4.1. Stylelint**

Stylelint can be enabled for PhpStorm through a setting in the category Stylelint under Stylesheets. This will require you to have installed both Node and the Stylelint package. If you have Stylelint and Node installed PhpStorm will usually be able to find both paths. If not, you can manually enter the paths by clicking the _..._ button.

## 1.2. Extensions

### 1.2.1. .ignore

This extension can automatically add the right ignore files to your PhpStorm projects. Below you can find a table with supported ignore languages.

| Name | Name |
| :--- | :--- |
| .gitignore \(Git\) | .p4ignore \(Perforce\) |
| .hgignore \(Mercurial\) | .prettierignore \(Prettier\) |
| .npmignore \(NPM\) | .flooignore \(Floobits\) |
| .dockerignore \(Docker\) | .eslintignore \(ESLint\) |
| .cvsignore \(CVS\) | .cfignore \(Cloud Foundry\) |
| .bzrignore \(Bazaar\) | .jpmignore \(Jetpack\) |
| .boringignore \(Darcs\) | .stylelintignore \(StyleLint\) |
| .mtn-ignore \(Monotone\) | .stylintignore \(Stylint\) |
| .ignore-glob \(Fossil\) | .swagger-codegen-ignore \(Swagger Codegen\) |
| .jshintignore \(JSHint\) | .helmignore \(Kubernetes Helm\) |
| .tfignore \(Team Foundation\) | .upignore \(Up\) |
| .prettierignore \(Prettier\) |  |
|  |  |

[.Ignore \| Plugin Page](https://plugins.jetbrains.com/plugin/7495--ignore)

### 1.2.2. CodeGlance

Embeds a code mini map similar to the one in Sublime into the editor pane.

[CodeGlance \| Plugin Page](https://plugins.jetbrains.com/plugin/7275-codeglance)

### 1.2.3. PHP Composer.json support

[CodeGlance \| Plugin Page](https://plugins.jetbrains.com/plugin/7631-php-composer-json-support)

### 1.2.4. PHP Inspections \(EA Extended\)

[PHP Composer.json support \| Plugin Page](https://plugins.jetbrains.com/plugin/7622-php-inspections-ea-extended-)

### 1.2.5. Swagger Plugin

[Swagger Plugin \| Plugin Page](https://plugins.jetbrains.com/plugin/8347-swagger-plugin)

### 1.2.6. LiveEdit

[LiveEdit \| Plugin Page](https://plugins.jetbrains.com/plugin/7007-liveedit)

### 1.2.7. Symfony Plugin

[Symfony Plugin \| Plugin Page](https://plugins.jetbrains.com/plugin/7219-symfony-plugin)

### 1.2.8. Mongo Plugin

Integrates MongoDB in PHPStorm. This plugin allows you to start, edit, view your server. Can be a replacement for Robo3T.

[Mongo Plugin \| Plugin Page](https://plugins.jetbrains.com/plugin/7141-mongo-plugin)

### 1.2.9. .env files support

[.env files support \| Plugin Page](https://plugins.jetbrains.com/plugin/9525--env-files-support)

### 1.2.10. Git Flow

[Git Flow \| Plugin Page](https://plugins.jetbrains.com/plugin/7315-git-flow-integration)

### 1.2.11. PhoneGap / Cordova Plugin

[PhoneGap / Cordova Plugin \| Plugin Page](https://plugins.jetbrains.com/plugin/7436-phonegap-cordova-plugin)

### 1.2.12. Twig Support

Adds support for the Twig Template Language

[Twig Support \| Plugin Page](https://plugins.jetbrains.com/plugin/7303-twig-support)

### 1.2.13. Bitbucket Linky

[Bitbucket Linky \| Plugin Page](https://plugins.jetbrains.com/plugin/8015-bitbucket-linky)

### 1.2.14. GitToolBox

[GitToolBox \| Plugin Page](https://plugins.jetbrains.com/plugin/7499-gittoolbox)

### 1.2.15. CamelCase

[CamelCase \| Plugin Page](https://plugins.jetbrains.com/plugin/7160-camelcase)

### 1.2.16. JS ToolBox

[JS ToolBox \| Plugin Page](https://plugins.jetbrains.com/plugin/7353-js-toolbox)

### 1.2.17. gfm

View a md file just like it would if you watched it on Github

[gfm \| Plugin Page](https://plugins.jetbrains.com/plugin/7701-gfm)

### 1.2.18. PHP Annotations

[PHP Annotations \| Plugin Page](https://plugins.jetbrains.com/plugin/7320-php-annotations)

## 1.3. Tips to make your work environment faster

* [1.3.1. Disable Reopen Last Project on Startup](phpstorm.md#131-Disable-Reopen-Last-Project-on-Startup)
* [1.3.2. Disable Unused Plugins](phpstorm.md#132-Disable-Unused-Plugins)

### 1.3.1. Disable Reopen Last Project on Startup

By default, PhpStorm opens your last opened project on startup. This is alright when you work on the same project most of the days, but when you switch projects often, you might want to disabled this.

Go to: preferences -&gt; type ‘reopen’ -&gt; Uncheck ‘Reopen last project on startup’

### 1.3.2. Disable Unused Plugins

There are a lot of useful plugins but there might be some you don't really need on a regular basis. So you might disable those unused plugins to improve loading time.

Go to: preferences -&gt; plugins and disable everything you don’t need.