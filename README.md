# GitHub Composite Actions demo

This repository wants to demostrate what is possible with [recently introduced](https://github.com/actions/runner/issues/646#issuecomment-901336347) changes to Composite Actions:
* They now have `uses` steps to call other actions, such as regular marketplace actions, actions from other repositories, and local actions
* When calling other composite actions, there can be nesting up to a level of 9
* In addition to `run` steps, a "container" step using a `docker://` reference can execute arbitrary Docker images on the fly.

More information about this is yet do be released on the [GitHub Changelog](https://github.blog/changelog/).
