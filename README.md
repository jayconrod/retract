This repository is an example of retraction in Go modules. It provides the
following versions:

* v0.9.9 - the actual `@latest` version.
* v1.0.0 - an accidentally published version.
* v1.0.1 - retracts itself and v1.0.0. This is the `@latest` version before
  retractions are considered, so `retract` directives are loaded from here.
