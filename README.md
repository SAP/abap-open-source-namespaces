[![REUSE status](https://api.reuse.software/badge/github.com/SAP/abap-open-source-namespaces)](https://api.reuse.software/info/github.com/SAP/abap-open-source-namespaces)

# ABAP Open Source Namespaces

## About this project

SAP provides dedicated [ABAP Open Source Namespaces](https://me.sap.com/namespaces/opensource) exclusively for open source projects. This repository lists all existing namespaces, including development and repair keys for DEMOSYSTEM installations such as the [ABAP Cloud Developer Trial](https://community.sap.com/t5/technology-blog-posts-by-sap/abap-cloud-developer-trial-2025-available-now/ba-p/14376009) (formerly known as miniSAP).

## How to Get a Namespace

The right path for getting an ABAP namespace depends on what you are building. Consider which of the following cases applies to you:

**Commercial development**
The ABAP Developer Trial is licensed for non-productive use only and cannot serve as the basis for software you sell or deliver to customers. If you are building commercial software, you need a standard SAP commercial license. Request a namespace through the [Development Namespace Application](https://me.sap.com/namespaces) as outlined [in the documentation](https://support.sap.com/content/dam/support/en_us/library/ssp/my-support/keys/new-request-namespace.pdf).

**Personal learning**
If you are exploring ABAP for your own education and do not plan to share code with others, no namespace registration is required. If you are running a local ABAP system (miniSAP / ABAP Developer Edition), you will need a miniSAP license key — find out how to obtain one [here](https://caldocs.cfapps.eu01.hana.ondemand.com/caldocs/help/Minisap_License_Keys.pdf).

**Open source project**
If you are publishing your ABAP code as open source (e.g., via abapGit on GitHub), you can request a dedicated ABAP Open Source Namespace through this project. We prefer requests that already have existing code or a credible public project behind them — pure ideation requests may be deferred.

When choosing your namespace, keep the following in mind:
- Format: `/YOURNS/` — 3 to 8 uppercase letters, enclosed in slashes
- Must relate to your project or organization name
- Must not conflict with existing trademarks or well-known names (e.g., namespaces starting with `SAP`, `ABAP`, `AWS` will not be approved)
- If you have an S-User, please check whether your desired namespace is already taken in the [Development Namespace Application](https://me.sap.com/namespaces) before requesting. All existing open source namespaces are also listed [below](#existing-abap-open-source-namespaces).

To request a namespace, [send us an e-mail](mailto:ospo@sap.com?subject=ABAP%20Open%20Source%20Namespace%20Request&body=Dear%20SAP%20Open%20Source%20Program%20Office%2C%0A%0AI%20would%20like%20to%20request%20an%20ABAP%20Open%20Source%20Namespace%20for%20my%20project.%20Please%20find%20the%20details%20below%3A%0A%0AProject%20name%3A%20%0ARequested%20namespace%3A%20%0AProject%20description%3A%20%0AProject%20URL%3A%20%0AProject%20License%3A%20%0A%0ABest%20regards%2C%0A%5BYour%20name%5D) with the following details:

```
Project name:
Requested namespace:
Project description:
Project URL:          (e.g. link to GitHub repo or organization)
Project License:
```

## Existing ABAP Open Source Namespaces

**Note:** The development keys listed below are exclusively for ABAP Cloud Developer Trial systems (or any others with 'DEMOSYSTEM' as installation ID). For all other systems, please use the [Development Namespace Application](https://me.sap.com/namespaces/opensource). The given repair keys should work on any system.

| Namespace | Description | Project URL | DEMOSYSTEM development key | Repair key |
| --------- | ----------- | ----------- | -------------------------- | --------------------- |
| /ABAPGIT/ | Git client for ABAP | https://github.com/abapGit | 23994246593733623882 | 40091955262536808301 |
| /AGNFRW/ | Agent Integration Processing Framework | https://github.com/IlyaPrusakou/aipf | 42827589023469285687 | 18345328440571757595 |
| /APMG/ | Package Manager for ABAP | https://github.com/abapPM | 19377473852358672491 | 41813564412598342476 |
| /ATRM/ | Transport Request Manager | https://github.com/RegestaItalia/trm-docs | 18531191373370851361 | 00211665563784583720 |
| /AWSEX/ | AWS Example Code Library | https://github.com/awsdocs/aws-doc-sdk-examples | 14651386910339465450 | 38127449234049228390 |
| /AWSLABS/ | AWS Labs | https://github.com/awslabs | 08687220553514260293 | 06678115934145756969 |
| /AWSSAMP/ | AWS Samples | https://github.com/aws-samples | 13391533940099332908 | 39944149741907428904 |
| /AWSSOL/ | AWS Solution Library | https://github.com/aws-solutions-library-samples | 08428002090177052957 | 06628540192866312031 |
| /C2A/ | cds2alv - Generate ALV List Reports for CDS Views | https://github.com/rku-it-GmbH/cds2alv | 03688288682419678361 | 37246368571464575750 |
| /CC4A/ | Code Pal for ABAP Cloud | https://github.com/SAP/code-pal-for-abap-cloud | 19443791570447289803 | 22229904900326563203 |
| /ORK/ | Open Core Kit | https://github.com/eplamsi | 14037021782659176457 | 25672835621882575754 |
| /OTCT/ | Open Tax Compliance Technologies | https://github.com/openTCT | 06491018313941499730 | 20057332490737420344 |
| /RBGRP/ | Rule-based Group | https://github.com/rulebased-group | 01116174434106589083 | 04764198110284863201 |
| /SGALM/ | Self-hosted Simple Application Lifecycle Manager | https://github.com/sergio-gracia/abap-SimpleALM | 19831896331475332905 | 38673778903560384071 |
| /SKYL/ | Skylint | https://github.com/furkancosgun/skylint | 01004226610577331698 | 32190681314202826278 |
| /XLWB/ | XLSX Workbench | https://github.com/igor-borodin/XLWB | 06882850232695308586 | 40644561731137480400 |

## Support, Feedback, Contributing

This project is open to feature requests/suggestions, bug reports etc. via [GitHub issues](https://github.com/SAP/abap-open-source-namespaces/issues). Contribution and feedback are encouraged and always welcome. For more information about how to contribute, the project structure, as well as additional contribution information, see our [Contribution Guidelines](CONTRIBUTING.md).

## Security / Disclosure

If you find any bug that may be a security problem, please follow our instructions [in our security policy](https://github.com/SAP/abap-open-source-namespaces/security/policy) on how to report it. Please do not create GitHub issues for security-related doubts or problems.

## Code of Conduct

We as members, contributors, and leaders pledge to make participation in our community a harassment-free experience for everyone. By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/SAP/.github/blob/main/CODE_OF_CONDUCT.md) at all times.

## Licensing

Copyright 2024 SAP SE or an SAP affiliate company and abap-open-source-namespaces contributors. Please see our [LICENSE](LICENSE) for copyright and license information. Detailed information including third-party components and their licensing/copyright information is available [via the REUSE tool](https://api.reuse.software/info/github.com/SAP/abap-open-source-namespaces).
