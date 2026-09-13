# RO Helper Profiles

Public, signed version profiles used by the RO Helper automatic updater.

- `manifest.json` is the signed index consumed by the application.
- `manifest.sig` is a Base64 RSA/SHA-256 signature of the exact manifest bytes.
- `profiles/` contains profiles that completed live validation and may be applied automatically.
- `candidates/` contains unverified research results. The application must never apply these automatically.

Every profile is selected by the SHA-256 of `Ragexe.exe`. Local machine paths and credentials are not published.
Signed public memory profile updates for RO Helper
