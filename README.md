# Printer Protector — downloads

Installers for **Printer Protector**, the printer monitoring tool used by
[toner.management](https://toner.management), toner-management.com and tonerconnect.io.

This repository exists **only to host the downloads**. There is no application source
here — the product lives in a private repository. Nothing in this repo needs to be
built or cloned; get the file for your platform from **Releases**, or from the
"Printer watcher" section of your workspace, which links to the same file.

## What the tool does

It runs on a computer that stays on and can reach your printers. It finds them, reads
the toner level where the printer will tell it, and reports back so replacement toner
can be ordered before you run out. It does not read documents, print jobs, or spool
files.

## Verifying a download

Every release lists a SHA-256 checksum. To confirm the file you downloaded is the file
we published:

    shasum -a 256 <file>      # macOS / Linux
    certutil -hashfile <file> SHA256   # Windows

## Signing

Builds are **not code-signed yet**. macOS will say the developer is unidentified and
Windows SmartScreen will warn on first run. That is a statement about the certificate,
not about the file — check the published checksum above. Signed builds will replace
these when a certificate is in place.

## Support

care@unitedundergod.org
