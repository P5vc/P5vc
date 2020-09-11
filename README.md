![](https://raw.githubusercontent.com/P5vc/Documentation/master/Logo/MerchDesign1Render.png)

------------

# Welcome to the community behind Priveasy!

If you are new here, please visit our [About](https://github.com/P5vc/Documentation/blob/master/About/About.md#overview "About") page to learn more about us!

## Core Repositories

Priveasy is made-up of three core repositories. These are the repositories responsible for powering all of Priveasy's services.

### [ServerConfigurations](https://github.com/P5vc/ServerConfigurations "ServerConfigurations")

**ServerConfigurations** is exactly what it sounds like: this repository contains the exact code that *FetchApply*, well, fetches and applies to our servers, in order to set them up from scratch, configure them, and then maintain them. If you are interested in server management or security, this is the repository for you!

### [WebserverBackend](https://github.com/P5vc/WebserverBackend "WebserverBackend")

**WebserverBackend** contains our web application backend. Unlike *ServerConfigurations*, which aims to configure and maintain the physical servers themselves, WebserverBackend focuses on processing requests made to Priveasy's website, and then properly communicating with our databases and other necessary entities in order to return a proper response. All of our webdesign elements are also included in this repository. If you enjoy webserver backends, web design, or Django, you'll definitely want to check this repository out!

### [VPNServerBackend](https://github.com/P5vc/VPNServerBackend "VPNServerBackend")

**VPNServerBackend** contains the code automatically run by our VPN servers in order to manage user accounts, create and implement VPN configurations, modify firewall rules, etc. If you want to contribute to (or learn more about) our VPN servers, you'll find what you're looking for here!

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
