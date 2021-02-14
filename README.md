![](https://raw.githubusercontent.com/P5vc/Documentation/master/Logo/LogoWithURLTextHighResolutionRender.png)

------------

# Welcome to the community behind Priveasy!

If you are new here, please visit our [About](https://github.com/P5vc/Documentation/blob/master/About/About.md#overview "About") page to learn more about us!

## Core Repositories

Priveasy is made-up of four, core repositories. These are the repositories responsible for powering all of Priveasy's main services.

### [ServerConfigurations](https://github.com/P5vc/ServerConfigurations "ServerConfigurations")

**ServerConfigurations** is exactly what it sounds like: this repository contains the exact code that *FetchApply*, well, fetches and applies to all of our servers, in order to set them up from scratch, configure them, and then maintain them. If you are interested in server management or security, this is the repository for you!

### [PriveasyWebserverBackend](https://github.com/P5vc/PriveasyWebserverBackend "PriveasyWebserverBackend")

**PriveasyWebserverBackend** contains our web application backend. Unlike *ServerConfigurations*, which aims to configure and maintain the servers themselves, WebserverBackend focuses specifically on processing requests made to Priveasy's website, and then communicating with our database and other necessary entities in order to return a proper response. If you enjoy webserver backends, dynamic web design, or Django, you'll definitely want to check this repository out!

### [PriveasyWebDesign](https://github.com/P5vc/PriveasyWebDesign "PriveasyWebDesign")

**PriveasyWebDesign** is used to model our web pages in a static format, before converting them to Django templates and adding them to *PriveasyWebserverBackend*. This repository is useful for quickly testing changes in popular editors, and then easily serving those changes locally, for instant review. Because our official web pages are dynamic and optimized, there may be additional files for modeling various views, higher-quality resources, and plenty of filler text in this repository. If you're someone who loves web design (HTML, CSS, JS, Bootstrap, etc.), and you want to make changes to the site, this will be your best resource!

### [VPNServerBackend](https://github.com/P5vc/VPNServerBackend "VPNServerBackend")

**VPNServerBackend** contains the code automatically run by our VPN servers in order to manage user accounts, create and implement VPN configurations, modify firewall rules, etc. If you want to contribute to (or learn more about) our VPN servers, you'll find what you're looking for here!

## Extensions

Extensions are projects supported by Priveasy, and often developed in collaboration with other, important organizations. While extensions may be developed or published by Priveasy, and coincide with our ideals, they do not make up any of Priveasy's main services. Projects in this section may have various licenses and/or contribution requirements.

### BadApple

**BadApple** is a collaboration between Priveasy and the Aaron Swartz Day Police Surveillance Project, aiming to provide valuable resources to help hold law enforcement accountable. This repository contains BadApple resources and documentation, and will be made public once base development is complete.

### BadAppleBackend

**BadAppleBackend** contains the web application backend for BadApple: a collaboration between Priveasy and the Aaron Swartz Day Police Surveillance Project, aiming to provide valuable resources to help hold law enforcement accountable. This repository will be made public once base development is complete.

### BadAppleWebDesign

**BadAppleWebDesign** is used to model Bad Apple web pages in a static format, before converting them to Django templates and adding them to *BadAppleWebserverBackend*. This repository is useful for quickly testing changes in popular editors, and then easily serving those changes locally, for instant review. Because finalized Bad Apple web pages are dynamic and optimized, there may be additional files for modeling various views, higher-quality resources, and plenty of filler text in this repository. If you're someone who loves web design (HTML, CSS, JS, Bootstrap, etc.), and you want to make changes to Bad Apple's website, you're in the right place! This repository will be made public once base development is complete.

## Base Repositories

Priveasy has two base repositories. These repositories are special-purpose repositories which support Priveasy indirectly, providing documentation and other resources necessary/useful for development, without strictly containing code.

### [Documentation](https://github.com/P5vc/Documentation "Documentation")

**Documentation** is used to store all of the data relevant to Priveasy's backend and internal operations. In this repository you'll find helpful, technical information for both users and contributors, along with other resources such as code standards, logo files, and DNS records.

## [P5vc](https://github.com/P5vc/P5vc "P5vc")

**P5vc** is our profile repository. Its unique purpose is to provide you with this greeting message.

## Community Contributions

Community Contributions are repositories containing code which Priveasy acknowledges as being potentially useful to a much wider audience, and therefore have been designed to avoid conforming only to Priveasy's unique needs. These repositories are released under an MIT license, and do not require that contributors sign our CLA.

### [FetchApply](https://github.com/P5vc/FetchApply "FetchApply")

**FetchApply** is a lightweight configuration tool designed to allow for complete server configuration and management, while maintaining the maximum amount of transparency possible. We use FetchApply on all of our servers.

### [BotBlock](https://github.com/P5vc/BotBlock "BotBlock")

**BotBlock** is a modern, self-hosted, privacy-respecting, completely automated, public Turing test, to tell computers and humans apart. We use this upon registration to help prevent bots from spamming our servers with fake accounts.

## Retired Repositories

Retired repositories contain code that is no longer used in our production environment, yet still serves as important reference material and to document the history of Priveasy.

### [WebserverBackend](https://github.com/P5vc/WebserverBackend "WebserverBackend")

**WebserverBackend** contains our old web application backend. Retired at the end of 2020, this repository has been succeeded by [PriveasyWebserverBackend](https://github.com/P5vc/PriveasyWebserverBackend "PriveasyWebserverBackend").
