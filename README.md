![](https://source.priveasy.org/Priveasy/resources/raw/branch/main/logo/Priveasy%20Logo%20with%20Text%20BG-Transparent.png)

# Welcome to the Priveasy Development Community!

#### Here you will find all of the code, documentation, and resources that make up Priveasy's infrastructure, websites, projects, and services.

Priveasy currently hosts its own development server from which most of its development work is done. This server includes a custom registry, [Gitea instance](https://source.priveasy.org "Gitea instance"), [Cryptpad instance](https://cryptpad.priveasy.org/ "Cryptpad instance"), and more. If you are interested in contributing to any of our projects and would like to request access to our self-hosted development resources, feel free to email the Priveasy Admin. You are also welcome to contribute to our [GitHub](https://github.com/P5vc), where we mirror all of our repositories. Please be mindful that all the development work for Priveasy is done by volunteers who also have other jobs and/or commitments. Therefore, you may not receive an instant response to pull requests, issues, or messages.

## Core Repositories

Priveasy is made-up of three, core repositories. These are the repositories responsible for powering all of Priveasy's main services.

### [Server Configurations](https://source.priveasy.org/Priveasy/server-configurations "server-configurations")

The **server-configurations** repository is exactly what it sounds like: an operations repository that contains the code used by Fetch Apply to set up, configure, and maintain all of our servers. If you are interested in server management or security, this is the repository for you!

### [Priveasy Backend](https://source.priveasy.org/Priveasy/priveasy-backend "priveasy-backend")

The **priveasy-backend** repository contains our web application backend. Unlike *server-configurations*, which aims to configure and maintain the servers themselves, *priveasy-backend* focuses specifically on processing the web requests made to Priveasy's website, and then communicating with our database and other necessary entities in order to return a proper response. If you enjoy webserver backends, dynamic web design, or Django, you'll definitely want to check this repository out!

### [Priveasy Web Design](https://source.priveasy.org/Priveasy/priveasy-web-design "priveasy-web-design")

The **priveasy-web-design** repository is used to model our web pages in a static format, before converting them to Django templates and adding them to *priveasy-backend*. This repository is useful for quickly testing changes in popular editors, and then easily serving those changes locally, for instant review. Because our official web pages are dynamic and optimized, there may be additional files or code for modeling various views, higher-quality resources, and plenty of filler text in this repository. If you're someone who loves web design (HTML, CSS, JS, Bootstrap, etc.), and you want to make changes to the website's design, then this will be your best resource!

## Extensions

Extensions are projects created or supported by Priveasy, but that do not make up any of Priveasy's core services. These projects may be a collaborative effort with other organizations, and therefore may have various licenses and/or contribution requirements that differ from the rest of Priveasy's repositories. Note that some of the code for these projects may cross over into other Priveasy repositories not found in this section.

### [Bad Apple Backend](https://source.priveasy.org/Priveasy/bad-apple-backend "bad-apple-backend")

The **bad-apple-backend** repository contains the web application backend for Bad Apple. Bad Apple is a collaborative project which provides valuable tools and resources to the public for free, with the aim of holding law enforcement accountable and putting an end to police misconduct.

## Base Repositories

Priveasy has two base repositories. These repositories are special-purpose repositories which support Priveasy indirectly, providing documentation and other resources necessary or useful for development, without strictly containing code.

### [Resources](https://source.priveasy.org/Priveasy/resources "Resources")

The **resources** repository is used to store all of the miscellaneous resources and documentation for Priveasy that doesn't quite fit into any of our other repositories. In here, you may find technical information, roadmaps, press releases, historical data, logos, media, and more.

### [Priveasy](https://source.priveasy.org/Priveasy/Priveasy "Priveasy")

**Priveasy** is our profile repository. Its unique purpose is to provide you with this overview information about Priveasy's development.

## Community Contributions

Community Contributions are repositories that contain code that was developed by Priveasy for use in our services at one point or another, but that we have purposely kept separate from our core repositories. All of these projects contain code that we see as being useful to a wider audience with a variety of different needs, and for that reason we purposely develop them as independent modules (without Priveasy-specific code) that can be easily implemented by anyone. All of these repositories are released under an MIT license.

### [Fetch Apply](https://source.priveasy.org/Priveasy/fetch-apply "fetch-apply")

The **fetch-apply** repository contains a lightweight system configuration and management tool designed for maximum transparency, security, efficiency, and auditability. To uphold our commitments to transparency, privacy, and security, we use Fetch Apply on all of our servers, without exception.

### [Bot Block](https://source.priveasy.org/Priveasy/bot-block "bot-block")

The **bot-block** repository contains a modern, self-hosted, privacy-respecting, completely automated, public Turing test, to tell computers and humans apart. This python-based CAPTCHA backend allows for the simple, efficient, and secure generation and verification of CAPTCHAs for your website. We use this tool within our services to provide an extra layer of protection to our infrastructure during unusually high levels of traffic or spam.

### [Zecwallet-Python](https://github.com/P5vc/Zecwallet-Python "Zecwallet-Python")

The **Zecwallet-Python** repository contains a simple wrapper around the Zecwallet Command Line LightClient written in Python, making it easier for Python programs and backends to easily interact with a fully-capable, lightweight Zcash wallet.

## Retired Repositories

Retired repositories contain projects that are no longer actively supported by us or code that is no longer in use in our production environments, yet that still serve an important role in the community. This role may be to inspire a developer to pick up where we left off, to maintain reference material, to document the history of Priveasy, etc.

### [(Old) Server Configurations](https://source.priveasy.org/Priveasy/ServerConfigurations "ServerConfigurations")

**ServerConfigurations** is the old operations repository used to configure, set up, and maintain Priveasy's servers from 2020-2022. Starting in 2023, to coincide with the complete redesign and rebuild of our backends and services, we switched to a new operations repository.

### [VPN Server Backend](https://source.priveasy.org/Priveasy/VPNServerBackend "VPNServerBackend")

The **VPNServerBackend** repository contains the "maintenance" code that was run on our VPN servers daily, back in 2020, to create and remove VPN profiles.

### [(Old) Webserver Backend](https://source.priveasy.org/Priveasy/WebserverBackend "WebserverBackend")

The **WebserverBackend** repository contains an old iteration of our web application backend that was retired at the end of 2020.
