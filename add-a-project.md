# Add your project

To transfer a project to `xarray-contrib` make sure it meets the requirements below then open a [new issue](https://github.com/xarray-contrib/xarray-contrib/issues/new/choose) in this repository to discuss transferring it to the xarray-contrib organization.

```{warning}
Projects included in xarray-contrib organization are not supported by the Xarray Core Developer Team. The organization provides visibilty to the project and a mechanism for people to volunteer to maintain abandoned projects.
```

## Requirements

There are three hard requirements for a project to be included in `xarray-contrib`

### 1. Open source license

The project must bee Licensed under an [OSI approved license](https://opensource.org/licenses)

### 2. Code of Conduct

The project must have a Code of Conduct, or adopt an existing one. For example the NUMFOCUS [code of conduct](https://numfocus.org/code-of-conduct)

### 3. Transfer Power to publish Releases and Documentation

#### Releases

To ensure that new maintainers can be added in the future if the original project authors stop responding any new projects must share the [keys to the castle](https://scientific-python.org/specs/spec-0006/). This ensures that `xarray-contrib` will be able to allow volunteer maintainers to revive projects and publish new releases and documentation.

**pypi**

The pypi project will be transferred to the xarray-contrib PyPi organization (TODO - create that and then link here).

**conda-forge**

If there is a conda-forge package then an xarray-contrib core team member must be added as an owner of the package (TODO: is there an easier way?)

**other package registries**
If the package is multi language you must provide a mechanism for the xarray-contrib maintainers to add a new volunteer in the future for the approriate package registry (e.g. `npm`, `cargo`, `cran`, ...)

#### Documentation

Any documentation hosting (e.g. `readthedocs`) must also be shared with `xarray-contrib`

## Guidelines

Projects in `xarray-contrib` should contain sufficient functionality and documentation to be useful and welcoming to new users. They should also follow software development best practices:

- Supports a recent version of Xarray
- Available on [PyPI](https://pypi.org/) and/or [conda-forge](https://conda-forge.org/)
- Documentation sufficient for new users to get started, which typically includes:
  - A user guide or tutorial
  - Usage examples
  - API reference
- Unit tests + continuous integration
- [PEP8](https://www.python.org/dev/peps/pep-0008/) compliant code style

If you have a project that meets these requirements, open a [new issue](https://github.com/xarray-contrib/xarray-contrib/issues/new/choose) in this repository to discuss transferring it to the xarray-contrib organization.
