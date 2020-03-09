<!-- # Project Title -->

# WebHealthManagement

<!-- Provide an introductory paragraph, describing
* What your project does
* Why people should consider using your project
* Link to project home page
* -->

A web based health management system that will be used for the administration of
a Hospital or Clinic.It will aid in alliviate a lot of the paper work done at
Hospitals that waste a lot of time and delay the ministring of health care to the
various patients that do need it


> CheckOut the Plan and Overview of the [Web Health Management System](https://gist.github.com/Ultra-Code/f83ad84e5c907352dccec467501f3e04)

<!-- ## Table of Contents
- [WebHealthManagement](#webhealthmanagement)
  - [Table of Contents](#table-of-contents)
- [About the Project](#about-the-project)
  - [Creating a virtual environment for your django project](
  - #creating-a-virtual-environment-for-your-django-project)
  - [Getting the Source](#getting-the-source)
  - [Building](#building)
    - [Other Tests](#other-tests)
  - [Installation Of Dependencies](#Dependencies)
- [Release Process](#release-process)
  - [Payload](#payload)
- [How to Get Help](#how-to-get-help)
  - [Running the tests](#running-the-tests)
    - [Break down into end to end tests](#break-down-into-end-to-end-tests)
    - [And coding style tests](#and-coding-style-tests)
  - [Deployment](#deployment)
  - [Built With](#built-with)
  - [Contributing](#contributing)
  - [Versioning](#versioning)
  - [Authors](#authors)
- [License](#license)
- [Acknowledgments](#acknowledgments)
-->

## Table of Contents

- [WebHealthManagement](#webhealthmanagement)
  - [Table of Contents](#table-of-contents)
- [About the Project](#about-the-project)
  - [Creating a virtual environment for your django project](#creating-a-virtual-environment-for-your-django-project)
  - [Getting the Source](#getting-the-source)
  - [Building](#building)
  - [Installation Of Dependencies](#dependencies)
    <!--- [Other Tests](#other-tests)
- [Release Process](#release-process)
  - [Payload](#payload)    -->
- [How to Get Help](#how-to-get-help)
  <!-- - [Running the tests](#running-the-tests)
    - [Break down into end to end tests](#break-down-into-end-to-end-tests)
    - [And coding style tests](#and-coding-style-tests)
  - [Deployment](#deployment)
  - [Built With](#built-with)  -->
  - [Contributing](#contributing)
  - [Versioning](#versioning)
  - [Authors](#authors)
- [License](#license)
- [Acknowledgments](#acknowledgments)

<!-- # About the Project -->

# About the Project

<!-- Here you can provide more details about the project
* What features does your project provide?
* Short motivation for the project? (Don't be too long winded)
* Links to the project site
-->

This project is a startup idea that is been supported by __KNUST BUSSINESS
INNOVATION HUB__
This system allows it's administrator to Login to verify credentials of patients
,register new patients and speed up some of the manual processes involved in the
process of health care delivery.

![A Sample Image Of Our Login Screen](https://i0.wp.com/wp.laravel-news.com/wp-content/uploads/2019/05/vue-modal.png?resize=2200%2C1125)

<!--
```
Show some example code to describe what your project does
Show some of your APIs
```
-->

**[Back to top](#table-of-contents)**

<!--
# Project Status
--
Show the build status if you have a CI server:
--
[![Build Status](http://your-server:12345/job/badge/icon)](http://your-server:12345/job/http://your-server:12345/job/badge/icon/)
--
Describe the current release and any notes about the current state of the project
Examples: currently compiles on your host machine, but is not cross-compiling for
ARM, APIs are not set, feature not implemented, etc.
--
**[Back to top](#table-of-contents)**
-->

<!-- # Getting Started -->

# Getting Started

*Clone this repository using git or your favorite __git client__ on either Windows
, Linux or Mac . Setup your Web Development Environment  ie.
your browsers , IDE , Code Editors and install the various extensions
that will be needed to develop this ( python3 , Ecmascript , Vue , Sass )
base on your editor or IDE . Setup your nginx local server and host the site*

<!-- ## Dependencies -->

## Dependencies

<!--
Describe what software and libraries you will need to install in order
 to build and use this project. Provide details on how to resolve these
 dependencies.
Remember: git-lfs is a dependency that developers will need to resolve before
 they can get started with a repo using LFS.
-->

 These instructions will get you a copy of the project up and running on your
 local machine for development and testing purposes

__`An ES6+ compatible browser`__

__`Install Node js with npm`__

We cover only installing node with npm for linux and windows but you can checkout
[Official Node Installation Page](https://nodejs.org/en/download/package-manager/)
For other Os's

>On Windows

<!--
```
Examples should be included
```
-->

```powershell
# Using Chocolatey:
cinst nodejs.install

Or

# Using Scoop:
scoop install nodejs
```

>On Linux

```bash
# Using Ubuntu
curl -sL https://deb.nodesource.com/setup_13.x | sudo -E bash -
sudo apt-get install -y nodejs

# Using Debian, as root
curl -sL https://deb.nodesource.com/setup_13.x | bash -
apt-get install -y nodejs
```

__`EcmaScript Frameworks and Libraries needed`__

- Vue

- @vue/cli

  - Vuetify and BootstrapVue

  - Babel

  - Eslint

  - Router

  - Vuex

- Sass

__`Install python3`__

>For Windows and Other Os

Download and install the latest python3 interpreter from
[Offical Python Download page](https://www.python.org/downloads/)

Make sure your add python to path environment variable ![Add python to PATH](https://files.realpython.com/media/win-install-dialog.40e3ded144b0.png)

>On Linux if you don't have python already installed __(pun intended)__

```bash
sudo apt update

sudo apt install python3.7
```

__`Python Frameworks and Libraries needed`__

- Django

- djongo

____When Done installing Python3.7 it is recommended that for your python Django
project development you create a virtual environment____

- Allows you to make isolated python development environments.

- Allows you to have different versions of python libraries and modules all
 isolated from one another.

- It helps to prevent dependency issues

- It makes testing of different versions of python projects , libraries and
modules easy.

**[Back to top](#table-of-contents)**

## Creating a virtual environment for your django project

### On linux you might have to install pythom3-venv

```bash
python3 -m venv /path/to/new/virtual/environment

cd /path/to/new/virtual/environment/

source bin/activate   #To activate the virtual environment

#This will install Django and djongo to your virtual environment
(environment)$ python3 install Django djongo

(environment)$ deactivate #To deactivate the virtual environment
```

For futher reading on Virtual Environment go to
[Python Virtual Environments Documentation](https://docs.python.org/3/library/venv.html)

__`Mongodb`__

Download and Install mongodb community edition for Linux , Windows and Mac using
[Mongodb Community Edition](https://docs.mongodb.com/manual/administration/install-community/)

__`Nginx`__

Download and install Nginx for Linux Os with [Nginx For Linux](http://nginx.org/en/linux_packages.html)

Download and install Nginx for Windows with [Nginx For Windows](http://nginx.org/en/download.html)

<!-- ## Getting the Source -->

## Getting the Source

<!--
Include a link to your github reposistory (you have no idea how people will
findy our code), and also a summary of how to clone.
This project is [hosted on GitHub]
(https://github.com/embeddedartistry/embedded-resources).
You can clone this project directly using this command:
```
git clone git@github.com:embeddedartistry/embedded-resources.git
```
-->

This project is [hosted on GitHub](https://github.com/Animosusoft/WebHealthManagement).
You can clone this project directly using this command:

```bash
git clone https://github.com/Animosusoft/WebHealthManagement.git
```

<!-- ## Building -->

## Building

<!--
Instructions for how to build your project
```
Examples should be included
```
-->

__`For the Django Project`__

Move to the Django Project directory __*healthmasys.com/backend/djangobackend*__
and execute this comand in your python virtual environment

```sh
  python manage.py runserver
```

Visit this url __127.0.0.1:8000__ in your Web browser to see the app.
Modify some of the application file and the developmental server will be hot reloded
and you will see the changes as you work on the project .

![Django backend](https://github.com/Animosusoft/WebHealthManagement/blob/master/healthmasys.com/images/Django_scaffold_project.png)

**[Back to top](#table-of-contents)**

__`For the Vue Project`__

Change directory to __*healthmasys.coms/frontend/vue-ui/healthmasys-ui*__ ;
In your shell execute

```bash
   npm install #To install all packages in the package.json file

   npm run serve

   OR

  ./node_modules/.bin/vue-cli-service serve
```

Open __localhost:8080__ url in your browser to see the vue user interface

![vue with vuetify interface in my browser](https://github.com/Nana-Oxzo/WebHealthManagement/blob/master/healthmasys.com/images/Current_State.png)

<!--
## Running Tests
--
Describe how to run unit tests for your project.
--
```
Examples should be included
```
--
### Other Tests
--
If you have formatting checks, coding style checks, or static analysis tests that
must pass before changes will be considered, add a section for those and provide
instructions
--
## Installation
--
Instructions for how to install your project's build artifacts
--
---`
Examples should be included
```
--
 ## Usage
--
Instructions for using your project. Ways to run the program, how to include it
in another project, etc.
--
```
Examples should be included
```
--
If your project provides an API, either provide details for usage in this document
or link to the appropriate API reference documents
--
**[Back to top](#table-of-contents)**
--
# Release Process
--
Talk about the release process. How are releases made? What cadence? How to get
new releases?
--
 ## Payload
--
**[Back to top](#table-of-contents)***

-->

# How to Get Help

<!--
Provide any instructions or contact information for users who need to get further
help with your project.
-->

If any further information is needed on how to use , setup or help improve this
project contact [UltraCode](https://github.com/Ultra-Code) at
[gmail](mailto:mega.alpha100@gmail.com)

<!--
# Further Reading
--
Provide links to other relevant documentation here
--
**[Back to top](#table-of-contents)** -->

<!--
Fill it up Later
And repeat
```
until finished
```
--
End with an example of getting some data out of the system or using it for a
little demo To be filled and Fleshed  out later
--
## Running the tests
--
To be Fleshed out latter
Explain how to run the automated tests for this system
--
### Break down into end to end tests
--
Explain what these tests test and why
--
```
Give an example
```
--
### And coding style tests
--
Explain what these tests test and why
--
```
Give an example
```
--
## Deployment
--
Add additional notes about how to deploy this on a live system
--
## Built With
--
* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds
-->

<!--
# Contributing
--
Provide details about how people can contribute to your project. If you have a
contributing guide, mention it here. e.g.:
--
We encourage public contributions! Please review [CONTRIBUTING.md]
(https://github.com/Animosusoft/WebHealthManagement/blob/master/CONTRIBUTING.md)
for details on our code of conduct and development process.
--
**[Back to top](#table-of-contents)**
-->

## Contributing

We encourage public contributions! Please review our
[CONTRIBUTING.md](https://github.com/Animosusoft/WebHealthManagement/blob/master/CONTRIBUTING.md)
for details on how to contribute to our project .And also our code of conduct
[CODE OF CONDUCT](https://github.com/Animosusoft/WebHealthManagement/blob/master/CODE_OF_CONDUCT.md)
and development process

<!--
## Versioning
--
This project uses [Semantic Versioning](http://semver.org/). For a list of available
versions, see the [repository tag list](https://github.com/your/project/tags).
-->

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available,
see the [tags on this repository](https://github.com/Animosusoft/WebHealthManagement/tag)

<!--
# Authors
--
* **[Phillip Johnston](https://github.com/phillipjohnston)** - *Initial work* -
* [Embedded Artistry](https://github.com/embeddedartistry)
--
See also the list of [contributors](https://github.com/your/project/contributors)
who participated in this project.
**[Back to top](#table-of-contents)** -->

## Authors

__**[Ultra-Code](https://github.com/Ultra-Code) and
[Optimus-Pryme](https://github.com/optimus-pryme)**__ *Initial work was by* - __[Ultra-Code](https://github.com/Ultra-Code)__

See also the list of
__[Contributors and Developers](https://github.com/Animosusoft/WebHealthManagement/people)__
who participated in the development and improvement of this project.

<!--
# License
--
Copyright (c) 2017 Embedded Artistry LLC
--
This project is licensed under the MIT License - see [LICENSE.md](LICENSE.md)
file for details.
--
**[Back to top](#table-of-contents)** -->

# License

Copyright (c) 2020 Animosusoft

This project is licensed under the GPL-3.0 License - see the [LICENSE.md](LICENSE)
file for details

**[Back to top](#table-of-contents)**

<!--
# Acknowledgments
--
Provide proper credits, shoutouts, and honorable mentions here. Also provide links
to relevant repositories, blog posts, or contributors worth mentioning.
--
Give proper credits. This could be a link to any repo which inspired you to build
this project, any blogposts or links to people who contributed in this project.
If you used external code, link to the original source.
--
**[Back to top](#table-of-contents)** -->

# Acknowledgments

>- __Shoutout to [Kekeli-star](https://github.com/kekele-star) for her inovative
ideas on how to implement certain portions of this project__
>- __Another thanks to all the developers who are working on this project and have
made ideas come to reality__
>- __Credit to PurpleBooth and embeddedartistry for their creative works__
>- __Thanks to the KNUST BUSINESS INOVATION HUB for supporting this project__

<!--* Hat tip to anyone whose code was used
* Inspiration
* etc
-->
