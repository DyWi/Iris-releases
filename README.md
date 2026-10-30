<p align="center"><img src=".github/icon.png" width="128" height="128" alt="Iris icon"></p>

# Iris

Iris is a web browser for the Mac, built on WebKit by Dylan Willis for his own
use. It is privacy-first by construction: the browser contacts only the hosts
you type, click or configure. There is no telemetry, no update check, no
crash reporter, no suggestion service and no safe-browsing lookup. The one
thing that leaves the Mac is what you ask for.

## What it is

- A WebKit browser: address bar, tabs, bookmarks, history, downloads, find on
  page, reader-style New Tab page with favourites, the weather for a town you
  name, and news read directly from each publisher's own feed.
- A content blocker built in, from EasyList and EasyPrivacy, with per-site
  control.
- A password and card vault sealed by the Mac's Secure Enclave; Touch ID
  opens one item for one fill. Passwords, bookmarks and cards can be
  imported from Safari's export and from Apple's Passwords app.
- Registers the `http` and `https` schemes and can be set as the default
  browser. Opens to an address field and a page of bookmarks; navigates
  directly to the address given and renders the page exactly as served,
  with no redirection, no injected content and no native sign-in of its own.

Bundle identifier: `com.dylanwillis.iris`. Team: 3G9K26YFA3.

## Download

The current build is attached to the latest release on this page as a zip.
It is signed with a Developer ID certificate and notarized by Apple: unzip
it, move Iris to Applications, and open it. No account or sign-in is
needed.

## Passkeys

Iris uses WebKit's WebAuthn implementation. Passkey sign-ins on pages are
pending Apple's web-browser public-key-credential entitlement; once granted,
sign-ins use the passkeys in iCloud Keychain, as in Safari.
