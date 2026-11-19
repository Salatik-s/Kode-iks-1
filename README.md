# Kode-iks · distribution mirror 1

Signed server installation packages for Kod Dela. The application sends a small verified bootstrap over SSH; the selected server downloads a release archive from this repository and verifies the offline signature, expiry, version, size and SHA-256 before extraction.

This is the first distribution mirror. No passwords, VPN subscription links, device secrets or user messages belong in this repository.

Source code: https://github.com/Salatik-s/kod-dela

The verification key is public (`release-key.pem`). Signing keys stay off the hosting server and GitHub. A GitHub account alone is insufficient to create a trusted installer. Transport licenses and exact upstream source references are included in each archive.

This mirrors installation packages, not network traffic. Another repository may help with a repository-specific outage, but does not bypass a block of all GitHub infrastructure.
