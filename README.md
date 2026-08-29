# Overclocks releases

This public repository is the distribution and signed-control channel for Overclocks. The application source remains in a private repository.

- Download the current Windows build from Releases.
- update-policy.json is verified with Ed25519 before the application uses it.
- Release archives are pinned by version, filename, and SHA-256 inside that signed policy.
- Publish generated policies only through the signing script in the source repository.