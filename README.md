# Outpost for Mac

A static landing page for Outpost’s macOS network monitor and a home for its public releases.

## Preview locally

Run `python3 -m http.server 8000` from the repository root and open [the local preview](http://localhost:8000).

## GitHub Pages

Publish the root of the `main` branch from the repository’s **Settings → Pages**. The page has no build step.

The release buttons link to [GitHub Releases](https://github.com/chunyang-wen/Outpost.app/releases). Sparkle reads the signed `appcast.xml` from the root of `main` when it is published.
