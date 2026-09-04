# kellnr-dist

Vendored prebuilt kellnr releases for the scala VPS fleet: byte-identical upstream
binaries plus cargo-binstall delivery manifests. Nothing here is ever compiled;
`deploy_rust` consumes the release via `cargo binstall --manifest-path` with
compile strategies disabled. Binary provenance and digests are recorded in each
release's notes.
