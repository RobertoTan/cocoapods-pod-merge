# Change Log

## [0.0.4](https://github.com/grab/cocoapods-pod-merge/releases/tag/0.0.4)

Released on 2019-11-09.

- Automatically adds the `MergeFile` to your generated Pods project (just like your `Podfile`)
- Adds support for fixing Swift modular imports (`import xxxx`) when the `has_dependencies!` flag is specified [#10](https://github.com/grab/cocoapods-pod-merge/issues/10)
- Adds a group using `swift_version!` & `has_dependencies!` flags in the [example project](https://github.com/grab/cocoapods-pod-merge/tree/master/PodMergeExample)

## [0.0.3](https://github.com/grab/cocoapods-pod-merge/releases/tag/0.0.3)

Released on 2019-11-06.

- Adds a new flag `swift_version!` to manually set the Swift version of a merge group [#5](https://github.com/grab/cocoapods-pod-merge/issues/5)
- Fixes an issue with the `.modulemap` unable to compile when a pod contains `+` in it's name [#8](https://github.com/grab/cocoapods-pod-merge/issues/8)

## [0.0.2](https://github.com/grab/cocoapods-pod-merge/releases/tag/0.0.2)
Released on 2019-10-28.

- Fixes an issue when the `resource` property in a Podspec is a `String`

## [0.0.1](https://github.com/grab/cocoapods-pod-merge/releases/tag/0.0.1)
Released on 2019-10-12.

- Initial release 🎉