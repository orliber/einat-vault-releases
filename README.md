# Diagnostic Vault – installers

Signed Windows installers only. No source code and no data of any kind live here.
Every release carries `latest.json` and `latest.json.sig` (Ed25519); the program installs a
new version only if the signature matches the key built into it and the installer's SHA-256
matches the signed notice.
