# Yaseer WhatsApp Automation — releases

Signed builds of the Yaseer LIS WhatsApp sender. The source is private; this
repository holds the published builds only.

Installed copies update themselves from here. Each release carries
`manifest.json` (version, SHA-256 of every build) and `manifest.json.sig`, an
ed25519 signature made with the publisher's key; a copy installs a build only
when that signature verifies against the key compiled into it.

**First install on a lab PC:** download `yaseer-go-whatsapp-windows-amd64.exe` from the
latest release, rename it `yaseer-go-whatsapp.exe`, and put it where the old one was.
Every later version arrives by itself.
