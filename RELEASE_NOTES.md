Announcing the immediate availability of passbolt's docker repository 4.2.0.

This release, the first based on Debian 13, adds:
- Openshift support for non-root images
- Pin Passbolt server key generation to RSA by default
- Bump `supercronic` to 0.2.39

Moreover, it also fixes:
- `mediaType` OCI mismatch between index and manifest
- JWT directory permission error

And brings miscellaneous testing improvements.
