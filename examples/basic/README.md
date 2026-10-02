# Config example

This example uses the library in this repository. It combines typed defaults, TOML, environment entries and explicit
CLI overrides, validates typed settings, queries field provenance, and checks
that saved snapshots survive a live reload.

Run `(cd ../../../verification && just ecosystem-test config)` from this example directory. The example also runs through `goml test`
and `goml run --example basic` using the verifier's isolated registry home.

This example shares the library root manifest and development dependencies. Run `goml verify --example basic` to build and test it as an independent downstream module.
