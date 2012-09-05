common-library-proposal
=======================

This repository is a basis for discussion concerning a shared repository among different biodiversity organizations. 
Many organizations need to develop approximately the same kind of software. The idea behind this repository is to maximize our efforts to allow us to 
benefit form each other's works, and a lot have already been done by some organizations, including GBIF. Let's
discuss how we can centralized all this work to ease the reuse of the current and future code.

The initial proposal is to create a library for the processing and the validation of raw data for an Occurrence Portal.

* This library will not have any link to a specific implementation
and/or structure.
* This library will offer a way to be extended.

Initial target:
* [Date](https://github.com/cgendreau/common-library-proposal/issues/2) (including partial date and date range)
* [Country](https://github.com/cgendreau/common-library-proposal/issues/3) 
* [Province and State](https://github.com/cgendreau/common-library-proposal/issues/4)
* [Continent](https://github.com/cgendreau/common-library-proposal/issues/5)
* [Scientific Name](https://github.com/cgendreau/common-library-proposal/issues/6)
* [Coordinates](https://github.com/cgendreau/common-library-proposal/issues/7)
* [Altitude](https://github.com/cgendreau/common-library-proposal/issues/8)

There is a lot of (existing) ways to process those data, but we need to discuss how we can make them available to all of our projects.
Again, this is only a proposal, so feel free to share and comment via the GitHub Issue system.
If you are interested to use or to contribute to this library, please contact @cgendreau.