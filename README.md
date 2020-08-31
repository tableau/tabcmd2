# Tabcmd2

[![Tableau Supported](https://img.shields.io/badge/Support%20Level-Tableau%20Supported-53bd92.svg)](https://www.tableau.com/support-levels-it-and-developer-tools)

A Python based app that replicates the functionality of the existing [Tabcmd command line utility](https://help.tableau.com/current/server/en-us/tabcmd.htm).

**Important Note:** Tabcmd2 is a work in progress ("beta") which may be useful for test and development purposes, but is not yet recommended for production environments.

* [Why Tabcmd2\?](#whytabcmd2)
* [Demo](#demo)
* [Get started](#get-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Run](#run)
* [Contributions](#contributions)

## Why Tabcmd2?

* Run Tabcmd commands on MacOS (existing Tabcmd does not officially support MacOS)
* Authenticate using Personal Access Tokens (existing Tabcmd does not support Personal Access Token login)
* Easily use public endpoints available in Python based [Tableau Server Client](https://github.com/tableau/server-client-python/)
* Add more functionality and extend script for other automation tasks

## Demo/Samples

_coming soon_

## Get started

This section describes how to install and configure Tabcmd2.

### Prerequisites

To work with Tabcmd2, you need the following:

* MacOS / Windows
* Python 3.7+ installed

### Installation

To install Tabcmd2, follow these steps:

1. Clone the repo
2. Run `pip install .`

## Run

To run Tabcmd2, follow these steps:

1. To run a command:
    * `tabcmd2 [command_name] [--flags]`
    * Examples:
        * `tabcmd2 login --username [username] --password [password] --server
         [server_name] --site [site_name]`
        * `tabcmd2 createproject --name [project_name]`

### Available Commands

1. addusers (to group)
2. creategroup
3. createproject
4. createsite
5. createsiteusers
6. delete workbook-name or datasource-name
7. deletegroup
8. deleteproject
9. deletesite
10. deletesiteusers
11. editsite
12. export
13. listsites
14. login
15. logout
16. publish
17. publishsamples
18. removeusers

## Contributions

Code contributions and improvements by the community are welcomed!

See the LICENSE file for current open-source licensing and use information.

Before we can accept pull requests from contributors, we require a signed [Contributor License Agreement (CLA)](http://tableau.github.io/contributing.html).
