# Changelog

## v2.0.4, 2018-01-11
* Make refs optional. PR: [#166](https://github.com/arunoda/react-komposer/pull/166)

## v2.0.3, 2018-01-09
* README removed broken links

## v2.0.2, 2018-01-09
* use @ggallon/react-stubber

## v2.0.1, 2018-01-09
* Freeze the versions of the dependencies packages
* Fix typo on dataLoader features test
* support npm >= 3
* React peer dependencies, publish under @ggallon

## v2.0.0, 2016-11-08
* First release of v2.0.0

## v1.13.1, 2016-07-09
* Make mobx a dependency. Fix issue: [#103](https://github.com/kadirahq/react-komposer/issues/103)

## v1.13.0, 2016-07-08
* Add support for MobX. See: [PR101](https://github.com/kadirahq/react-komposer/pull/101)

## v1.12.0, 2016-07-04
* Added [withRef](https://github.com/kadirahq/react-komposer#ref-to-base-component) option to expose the underline component. See [PR88](https://github.com/kadirahq/react-komposer/pull/88).
* Remove disableMode from the docs since with the new stubbing functionality we don't need a disableMode.

## v1.11.0, 2016-06-23
* Add a way to set default loading and error components. See: [#8](https://github.com/kadirahq/react-komposer/issues/8).

## v1.10.0, 2016-06-23
* Updated compose to allow passing of context into the subscribe function. [PR46](https://github.com/kadirahq/react-komposer/pull/46)

## v1.9.0, 2016-06-22
* Add a way to provide a stubbed version of composer. See: [PR87](https://github.com/kadirahq/react-komposer/pull/87)
* Refactor the code base for simplyness.
* Pass props to the loading component. [PR47](https://github.com/kadirahq/react-komposer/pull/47)

## v1.8.0, 2016-04-09
* Add support to React 15.x.x

## v1.7.2, 2016-03-30
* Add disableMode support for composeAll.

## v1.7.1, 2016-03-30
* Remove react-native from peerDependencies.

## v1.7.0, 2016-03-30
* Remove default loading and error components in ReactNative. User always needs to provide them. 
* Earlier we conditionally require react-native and use it. But, it's not going to work with Webpack as it needs RN to be available inside the project.

## v1.6.0, 2016-03-30
* Add a way to disable the functionality of React Komposer. See [more](https://github.com/kadirahq/react-komposer#disable-functionality).

## v1.5.0, 2016-03-30
* Add loading components for ReactNative. See: [PR64](https://github.com/kadirahq/react-komposer/pull/64)

## v1.4.1, 2016-03-16
* Remove browser flag completely where it might give us errors in Meteor.

## v1.4.0, 2016-03-16
* Add support for React Native. See: [PR53](https://github.com/kadirahq/react-komposer/pull/53)

## v1.3.3, 2016-03-11
* Fix some issue with Meteor's Tracker integration. See [PR49](https://github.com/kadirahq/react-komposer/pull/49)

## v1.3.2, 2016-02-24
* Update _mounted internal state when unmounting. See: [PR39](https://github.com/kadirahq/react-komposer/pull/39)

## v1.3.1, 2016-02-10
* Fix a small typo. See: [#28](https://github.com/kadirahq/react-komposer/pull/28)

## v1.3.0, 2016-01-28
* Implement purity in containers. See: [#19](https://github.com/kadirahq/react-komposer/issues/19).

## v1.2.1, 2016-01-18
* Stop wrapping the UI component with a div. See: [#15](https://github.com/kadirahq/react-komposer/issues/15)

## v1.2.0, 2016-01-15
* Add custom loading and error components to all composers. See: [#12](https://github.com/kadirahq/react-komposer/pull/12)

## v1.1.0, 2016-12-31
* Add `composeAll` utility.
* Allow to pass custom error component and loading component as options. See: [#7](https://github.com/kadirahq/react-komposer/issues/7)
* Allow to return a cleanup function from the tracker composerFunction as well. See: [#8](https://github.com/kadirahq/react-komposer/issues/8)

## v1.0.0, 2015-12-31
* Initial Release
