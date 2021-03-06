# Eclipse plugin for [Bazel](http://bazel.io) (**Highly experimental**)

e4b is an Eclipse plugin for Bazel. It is really rudimentary.
It simply supports creating the classpath from a project and using
Bazel for incremental builds..

You can create a new Bazel project with New project > Import Bazel project
Then you can select the list of targets you want to build and the list
of directories you want to track.

It is highly experimental and support is minimal. However, we are happy
to accept contribution to make this support grows to a better shape.

## Installation

This plugin was tested with Eclipse Mars (4.5) but should also work with Eclipse Neon (4.6).

   * Start Eclipse
   * Select "Help" > "Install Software"
   * Add the update
site
[http://bazelbuild.github.io/e4b/p2updatesite](http://bazelbuild.github.io/e4b/p2updatesite).
   * Select "Uncategorized category" > "Eclipse 4 Bazel"

## Using the plugin

To import an existing Bazel project or start a new one, go to "New" > "Project..." > "Others".

## Missing features

Interesting feature to add is first to be able to launch test from
Eclipse, correctly adding the eclipse debugger to the JVM.

Second, better support for BUILD file would be interesting. Maybe
using Xtext.

Finally, the code is completely missing tests and improving the test
coverage would be great.
