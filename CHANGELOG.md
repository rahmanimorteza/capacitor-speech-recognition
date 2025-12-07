# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## 8.0.0 (2025-12-07)


### ⚠ BREAKING CHANGES

* This plugin now only supports Capacitor 7.

Co-authored-by: Thomas Hammerl <thomas.hammerl@semanticlabs.at>
* Remove deprecated permission methods (#94)
* Update to Capacitor 6 (#86)
* use correct name on rollup (#93)
* Update to Capacitor 5 (#62)

### Features

* add `isListening` method and `listeningState` listener ([#83](https://github.com/capacitor-community/speech-recognition/issues/83)) ([5a9b532](https://github.com/capacitor-community/speech-recognition/commit/5a9b532f316df7585b94e65bff77b642df5eb32e))
* Add checkPermissions and requestPermissions ([#64](https://github.com/capacitor-community/speech-recognition/issues/64)) ([710e49a](https://github.com/capacitor-community/speech-recognition/commit/710e49ae6f4ed2889ab9d4416ddec7200cbb2b21))
* add partial result  ([09fe4c2](https://github.com/capacitor-community/speech-recognition/commit/09fe4c2bcd4fa11dc7325eb6c56362de4dee464f))
* Add removeAllListeners method ([#55](https://github.com/capacitor-community/speech-recognition/issues/55)) ([21447ac](https://github.com/capacitor-community/speech-recognition/commit/21447ac73acac634a4ccbdb233399d4d7487f1c8))
* migrate to capacitor 3 ([09b7f85](https://github.com/capacitor-community/speech-recognition/commit/09b7f8553373e9bb2758618778ac353887ab9f30))
* Remove deprecated permission methods ([#94](https://github.com/capacitor-community/speech-recognition/issues/94)) ([77d89b8](https://github.com/capacitor-community/speech-recognition/commit/77d89b86117a9e1adc88abfafc8c9327ea5fef8d))
* Update to Capacitor 5 ([#62](https://github.com/capacitor-community/speech-recognition/issues/62)) ([011a908](https://github.com/capacitor-community/speech-recognition/commit/011a908fe5782b7d5ecc8d28c6dda7f5e7ac55d3))
* Update to Capacitor 6 ([#86](https://github.com/capacitor-community/speech-recognition/issues/86)) ([8e2f62b](https://github.com/capacitor-community/speech-recognition/commit/8e2f62b5ed37fdb8acf33c31b4e7157d03a47739))
* update to Capacitor 7 ([#114](https://github.com/capacitor-community/speech-recognition/issues/114)) ([bb13bee](https://github.com/capacitor-community/speech-recognition/commit/bb13beec20410b6d3b2e4192cf9fa14cc55c3360))
* update to Capacitor v4 ([#35](https://github.com/capacitor-community/speech-recognition/issues/35)) ([9755bf5](https://github.com/capacitor-community/speech-recognition/commit/9755bf5058a6bfb903346882e1ab501612ca1e9b))


### Bug Fixes

* android res direcly after start if partial result ([66d1ac8](https://github.com/capacitor-community/speech-recognition/commit/66d1ac81561d98016dd7a7fef6ac2754913dc130))
* **android:** Add permission and queries to AndroidManifest.xml ([#53](https://github.com/capacitor-community/speech-recognition/issues/53)) ([32b56d3](https://github.com/capacitor-community/speech-recognition/commit/32b56d3e4784a4dd593674d36a5bbb4686af2553))
* **android:** call error on expetion ([7069c1e](https://github.com/capacitor-community/speech-recognition/commit/7069c1e2a15e74f47b5c6e90664cc7eecca2db95))
* **android:** convert correctly matches result ([b1a9ba7](https://github.com/capacitor-community/speech-recognition/commit/b1a9ba7e9f38118b9566ee4566db17da4114cdfb))
* **android:** Resolve Issue with popup not returning result ([#34](https://github.com/capacitor-community/speech-recognition/issues/34)) ([8e80c59](https://github.com/capacitor-community/speech-recognition/commit/8e80c59dc571d0286e272f2d3f762fe378945712))
* **android:** Send final result on partialResults listener ([#66](https://github.com/capacitor-community/speech-recognition/issues/66)) ([14db1b4](https://github.com/capacitor-community/speech-recognition/commit/14db1b49c50001d9ee363f73f900cb670763c0f6))
* **android:** use matches for partial results ([#56](https://github.com/capacitor-community/speech-recognition/issues/56)) ([95373b3](https://github.com/capacitor-community/speech-recognition/commit/95373b3c373b93309f8a7d873703c19de7229dfd))
* available ([214d61c](https://github.com/capacitor-community/speech-recognition/commit/214d61cdf21b377dafe273665fa16344282d6154))
* correct since for isListening and listeningState ([#92](https://github.com/capacitor-community/speech-recognition/issues/92)) ([8b9445c](https://github.com/capacitor-community/speech-recognition/commit/8b9445caf09093422d761c6b3f91ed330d273047))
* definition ([6d279e4](https://github.com/capacitor-community/speech-recognition/commit/6d279e41b944a0d4b39dd69e1c92fa3873525b0d))
* gracefully handle AVAudioSession conflict when mic is busy ([#116](https://github.com/capacitor-community/speech-recognition/issues/116)) ([36cc033](https://github.com/capacitor-community/speech-recognition/commit/36cc0333c69ab676eb057f81cec2e9be22398cc9))
* **ios:** add missing listeningState stopped cases ([#95](https://github.com/capacitor-community/speech-recognition/issues/95)) ([19f98d1](https://github.com/capacitor-community/speech-recognition/commit/19f98d13b6a9454373a7d1af57e83f49fa823174))
* **ios:** check for possible null values ([393367a](https://github.com/capacitor-community/speech-recognition/commit/393367a878abd8f6aa3f25a66fff5bc94fe6747b))
* **ios:** Don't force cast audio engine ([#65](https://github.com/capacitor-community/speech-recognition/issues/65)) ([3e43ac8](https://github.com/capacitor-community/speech-recognition/commit/3e43ac81e3f09938c6d75619a6735be57eb36fbe))
* **ios:** proper isListening return ([#103](https://github.com/capacitor-community/speech-recognition/issues/103)) ([daf40a7](https://github.com/capacitor-community/speech-recognition/commit/daf40a73fda9b1caa5e84df41bf15ff687617742))
* **ios:** register plugin method ([1927c46](https://github.com/capacitor-community/speech-recognition/commit/1927c4659a8e0a1bb3cb73e8fa4e7d1caa67159e))
* make properties optional ([d92d353](https://github.com/capacitor-community/speech-recognition/commit/d92d353b3cbbcc093b5bc6b4d27fb1de38f235ec))
* missin semi ([1e42872](https://github.com/capacitor-community/speech-recognition/commit/1e4287202534ecc34af3aa4451f76840fe7fd6d2))
* type issue ([473d8f1](https://github.com/capacitor-community/speech-recognition/commit/473d8f112740df2c774ad2be8e0abd7b5b15e48b))
* use correct name on rollup ([#93](https://github.com/capacitor-community/speech-recognition/issues/93)) ([d8fefbc](https://github.com/capacitor-community/speech-recognition/commit/d8fefbc13594c7949e3bc687355c7308d9f90d8d))

### [7.0.1](https://github.com/capacitor-community/speech-recognition/compare/v7.0.0...v7.0.1) (2025-06-09)


### Bug Fixes

* gracefully handle AVAudioSession conflict when mic is busy ([#116](https://github.com/capacitor-community/speech-recognition/issues/116)) ([36cc033](https://github.com/capacitor-community/speech-recognition/commit/36cc0333c69ab676eb057f81cec2e9be22398cc9))

## [7.0.0](https://github.com/capacitor-community/speech-recognition/compare/v6.0.1...v7.0.0) (2025-03-25)


### ⚠ BREAKING CHANGES

* This plugin now only supports Capacitor 7.

### Features

* update to Capacitor 7 ([#114](https://github.com/capacitor-community/speech-recognition/issues/114)) ([bb13bee](https://github.com/capacitor-community/speech-recognition/commit/bb13beec20410b6d3b2e4192cf9fa14cc55c3360))

### [6.0.1](https://github.com/capacitor-community/speech-recognition/compare/v6.0.0...v6.0.1) (2024-06-28)


### Bug Fixes

* **ios:** proper isListening return ([#103](https://github.com/capacitor-community/speech-recognition/issues/103)) ([daf40a7](https://github.com/capacitor-community/speech-recognition/commit/daf40a73fda9b1caa5e84df41bf15ff687617742))

## [6.0.0](https://github.com/capacitor-community/speech-recognition/compare/v5.1.0...v6.0.0) (2024-06-07)


### ⚠ BREAKING CHANGES

* Remove deprecated permission methods (#94)
* Update to Capacitor 6 (#86)
* use correct name on rollup (#93)

### Features

* Remove deprecated permission methods ([#94](https://github.com/capacitor-community/speech-recognition/issues/94)) ([77d89b8](https://github.com/capacitor-community/speech-recognition/commit/77d89b86117a9e1adc88abfafc8c9327ea5fef8d))
* Update to Capacitor 6 ([#86](https://github.com/capacitor-community/speech-recognition/issues/86)) ([8e2f62b](https://github.com/capacitor-community/speech-recognition/commit/8e2f62b5ed37fdb8acf33c31b4e7157d03a47739))


### Bug Fixes

* correct since for isListening and listeningState ([#92](https://github.com/capacitor-community/speech-recognition/issues/92)) ([8b9445c](https://github.com/capacitor-community/speech-recognition/commit/8b9445caf09093422d761c6b3f91ed330d273047))
* **ios:** add missing listeningState stopped cases ([#95](https://github.com/capacitor-community/speech-recognition/issues/95)) ([19f98d1](https://github.com/capacitor-community/speech-recognition/commit/19f98d13b6a9454373a7d1af57e83f49fa823174))
* use correct name on rollup ([#93](https://github.com/capacitor-community/speech-recognition/issues/93)) ([d8fefbc](https://github.com/capacitor-community/speech-recognition/commit/d8fefbc13594c7949e3bc687355c7308d9f90d8d))

## [5.1.0](https://github.com/capacitor-community/speech-recognition/compare/v5.0.0...v5.1.0) (2024-03-27)


### Features

* add `isListening` method and `listeningState` listener ([#83](https://github.com/capacitor-community/speech-recognition/issues/83)) ([5a9b532](https://github.com/capacitor-community/speech-recognition/commit/5a9b532f316df7585b94e65bff77b642df5eb32e))

# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.
