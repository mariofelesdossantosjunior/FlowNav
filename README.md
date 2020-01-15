# FlowNav &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![](https://api.travis-ci.org/jeziellago/FlowNav.svg)

FlowNav is a mobile library for Android that helps and provider a better way to make multi-modules navigation.

The main purpose of this library is to help in cases where you have a project with multiple modules and need to navigate from one feature to another without adding dependency between them. For example, to navigate from module A to module B, you do not need to add module B as a dependency of module A.

There are other ways to solve the problem of module-to-module browsing such as using Intent-filter (which is error-prone and not supportive of fragments). FlowNav solves these problems, either using Activities, Native Fragments, or through the Navigation Component.

Check the [wiki](https://github.com/jeziellago/FlowNav/wiki).

>**FlowNav is an annotation processor and tool to make navigation simple**.

![](https://github.com/jeziellago/FlowNav/blob/master/sample/flownav.png)

## Current Stable Version

```gradle
// latest stable
flownav_version = '0.4'
```

## Start Now!
* [Import dependencies](https://github.com/jeziellago/FlowNav/wiki/Setup-Dependencies)
* [Init FlowNavApp on Application](https://github.com/jeziellago/FlowNav/wiki/Start-FlowNav)
* [Navigation on Activities](https://github.com/jeziellago/FlowNav/wiki/Navigation-on-Activities)
* [Navigation on Fragments](https://github.com/jeziellago/FlowNav/wiki/Navigation-on-Fragments)


## LICENSE

This project is available under Apache Public License version 2.0. See [LICENSE](LICENSE.md).
