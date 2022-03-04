---
layout: page
title: Creative Revision Release
permalink: /creativerevision/
---
## [0.106.1](https://github.com/Shuttlerock/creative-revision/compare/v0.106.0...v0.106.1) (2022-03-04)


### Bug Fixes

* deliverable duration was saved in the wrong unit ([792187c](https://github.com/Shuttlerock/creative-revision/commit/792187c1005fa044104c8bf05fb843325b521a51))
* migrate duration in database to correct unit ([d35114c](https://github.com/Shuttlerock/creative-revision/commit/d35114c858056df1ff5f88d570f056360c10d418))
* support duration=0 for statics for compatibility with creative-order ([0742380](https://github.com/Shuttlerock/creative-revision/commit/0742380112da95970dce5c8e1cab58f1b43aec67))
* use nanoseconds and uint64 in graphql schema inputs and outputs ([f3846e1](https://github.com/Shuttlerock/creative-revision/commit/f3846e197bb59b348d7b6de3c0c34ec1d89ac23e))

# [0.106.0](https://github.com/Shuttlerock/creative-revision/compare/v0.105.0...v0.106.0) (2022-03-03)


### Features

* MCC-553 Display warning text when viewing an old version ([#253](https://github.com/Shuttlerock/creative-revision/issues/253)) ([5d31605](https://github.com/Shuttlerock/creative-revision/commit/5d316053b5b1519b9cf6a032668f3e2d49ac9934))

# [0.105.0](https://github.com/Shuttlerock/creative-revision/compare/v0.104.0...v0.105.0) (2022-03-03)


### Features

* MCC-555 Show minor versions only to internal Shuttlerock staff  ([#243](https://github.com/Shuttlerock/creative-revision/issues/243)) ([4b36ba5](https://github.com/Shuttlerock/creative-revision/commit/4b36ba57b152029ad648875812c196a7e33f7123))

# [0.104.0](https://github.com/Shuttlerock/creative-revision/compare/v0.103.0...v0.104.0) (2022-03-03)


### Bug Fixes

* api build error ([64bc882](https://github.com/Shuttlerock/creative-revision/commit/64bc8820561b8a34fa6ae9417c08723ba9ce94a4))
* MCC-740 fix linting ([5456a3d](https://github.com/Shuttlerock/creative-revision/commit/5456a3dacd1122370aacde0668f564007ec599dc))
* MCC-740 small changes and tidy code ([91d03f2](https://github.com/Shuttlerock/creative-revision/commit/91d03f228df2cab8a6789dcdeedbe3cb6062724f))


### Features

* MCC-740 Call ent count() rather than len() ([0db1574](https://github.com/Shuttlerock/creative-revision/commit/0db1574ae05aead36b75636c5cc5a011ec873db4))
* MCC-740 Update version toggle component ([c4d4e6a](https://github.com/Shuttlerock/creative-revision/commit/c4d4e6aa0962a3c7d90140fb80cf8cbb64e230b9))

# [0.103.0](https://github.com/Shuttlerock/creative-revision/compare/v0.102.6...v0.103.0) (2022-03-03)


### Features

* Add versioning feature toggling to API. ([a286c9c](https://github.com/Shuttlerock/creative-revision/commit/a286c9c5f27ea7b2b1734e44903cb5e9ca96795b))

## [0.102.6](https://github.com/Shuttlerock/creative-revision/compare/v0.102.5...v0.102.6) (2022-03-02)


### Bug Fixes

* preview environments failed because cloud state version was outdated ([7ad46d4](https://github.com/Shuttlerock/creative-revision/commit/7ad46d45076db1c54ade679a7c6576a6a5e96afd))

## [0.102.5](https://github.com/Shuttlerock/creative-revision/compare/v0.102.4...v0.102.5) (2022-03-02)


### Bug Fixes

* Fix ordering of dispatcher when sending multiple events. ([c56783a](https://github.com/Shuttlerock/creative-revision/commit/c56783a2beb73c4beb5324ce2ffc897c5061cb7c))
