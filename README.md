# Note:

This is a fork with small adjustments. Used as a replacement for the @pokusew/pcsclite as a peer dependency of nfc-pcsc.
Hence the name of the package must stay as is, or nfc-pcsc must be forked aswell.

Changes implemented:

-   [Make the module Context aware](https://github.com/santigimeno/node-pcsclite/commit/64952fb868feae7b93c0895a96e84aad0a7945f9)
-   [Updates nan to v2.19.0 to fix updated signature ObjectTemplate::SetAccessor on v8 12+ (Electron 28+)](https://github.com/santigimeno/node-pcsclite/pull/102)
