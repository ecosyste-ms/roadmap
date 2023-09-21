# Ecosyste.ms: Roadmap
Planning and roadmap for future Ecosyste.ms development

[Ecosyste.ms](http://Ecosyste.ms) presents open datasets and APIs that perform dependency mapping (i.e. identifying key software systems where open source software is critical) of the OSS ecosystem to determine which projects are most critical and most in need of support. 

The project builds on the ideas of an earlier tool [libraries.io](http://libraries.io/), but focuses more on expanding available data and APIs to take it to the next level. This tool provides a foundational basis for researchers to better analyze OSS and for funders to better prioritize which projects most need to be funded.

## Goals

- A comprehensive set of APIs for parsing and querying open source package manager metadata from across many software ecosystems
- Up-to-date, easily accessible open data for each software ecosystem
- Individual open source services that can be deployed or consumed for a variety of use cases related to the sustainability of open source software.

## Services

The core of the project is made up of lots of small services, these can be used independently 
or combined together to form more powerful pipelines and datasets.

### [Packages](https://github.com/ecosyste-ms/packages)

Package, version and dependency metadata of many open source software ecosystems and registries.

### [Timeline](https://github.com/ecosyste-ms/timeline)

The timeline of over 6 Billion events for every public repo on GitHub, all the way back to 2015.

### [Parser](https://github.com/ecosyste-ms/parser)

Parse dependency metadata from many open source software ecosystems manifest files.

### [Archives](https://github.com/ecosyste-ms/archives)

Inspecting package archives and files from many open source software ecosystems.

### [Digest](https://github.com/ecosyste-ms/digest)

Digests of packages from many open source software ecosystems.

### [Diff](https://github.com/ecosyste-ms/diff)

Generate diffs between package releases for many open source software ecosystems.

### [Licenses](https://github.com/ecosyste-ms/licenses)

Parse license metadata from many open source software ecosystems.

### [Repos](https://github.com/ecosyste-ms/repos)

Repository metadata for many open source software ecosystems.

### [Resolve](https://github.com/ecosyste-ms/resolve)

Resolve full dependency trees for many open source software ecosystems.

### [Advisories](https://github.com/ecosyste-ms/advisories)

Security vulnerability metadata for many open source software ecosystems.

### [Commits](https://github.com/ecosyste-ms/commits)

Commit metadata for open source projects.

## Planned services

### Readmes

Discovering and rendering README files for open source projects.

### System Package Managers

Support for system package managers like apt, yum, dpkg and pacman in [Packages](https://github.com/ecosyste-ms/packages).

### Package Building Service

Test the reproducability of packages by automatically rebuilding from source and comparing.

## Contribute

Please do! The source code is hosted at [GitHub](https://github.com/ecosyste-ms/roadmap). If you want something, [open an issue](https://github.com/ecosyste-ms/roadmap/issues/new) or a pull request.

If you need want to contribute but don't know where to start, take a look at the issues tagged as ["Help Wanted"](https://github.com/ecosyste-ms/roadmap/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22).

You can also help triage issues. This can include reproducing bug reports, or asking for vital information such as version numbers or reproduction instructions. 

Finally, this is an open source project. If you would like to become a maintainer, we will consider adding you if you contribute frequently to the project. Feel free to ask.

For other updates, follow the project on Twitter: [@ecosyste_ms](https://twitter.com/ecosyste_ms).

### Note on Patches/Pull Requests

 * Fork the project.
 * Make your feature addition or bug fix.
 * Send a pull request. Bonus points for topic branches.

### Vulnerability disclosure

We support and encourage security research on Ecosyste.ms under the terms of our [vulnerability disclosure policy](https://github.com/ecosyste-ms/roadmap/security/policy).

### Code of Conduct

Please note that this project is released with a [Contributor Code of Conduct](https://github.com/ecosyste-ms/.github/blob/main/CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

## Copyright

[GNU Affero License](LICENSE) © 2022 [Andrew Nesbitt](https://github.com/andrew).
