# VideoGlance

Public website and distribution files for VideoGlance, a free macOS Quick Look
application for MKV, WebM and other video formats.

VideoGlance 1.1 is available from the
[Releases](https://github.com/Kwadz/videoglance-site/releases): a disk image
signed and notarized by Apple, its SHA-256 checksum, release notes and the
corresponding third-party sources. The Homebrew cask lives in
[Kwadz/homebrew-videoglance](https://github.com/Kwadz/homebrew-videoglance).
The website describes the tested configuration and known limits; it does not
claim full compatibility with Apple's previews.

This repository contains the generated French and English website, its images
and this introduction. It does not contain the application's source code.

The project's domain is [videoglance.app](https://videoglance.app/).
Open the website to choose French or English.

## Publishing

GitHub Pages serves the root of the `main` branch. The `.nojekyll` file preserves
the static HTML output without Jekyll processing. `CNAME` declares `videoglance.app`;
GitHub Pages settings, DNS and HTTPS must also be configured. Only reviewed website exports
are pushed here; a push to the private application repository does not deploy
this site. A push to this public repository updates the website.

Until the launch is approved, the website keeps `noindex` metadata. This does
not make it private: the repository, the website and the releases are public.

## Demonstration footage

Movie excerpts and stills: **Spring** — © Blender Foundation | cloud.blender.org/spring.
Licensed under [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/);
see the [movie's official reuse terms](https://studio.blender.org/projects/spring/pages/about/).
The source copy is available on [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Spring_-_Blender_Open_Movie.webm).
Two real Finder recordings show opening Quick Look with Space, hovering to reveal
its progress bar, and revealing
VideoGlance's circular control in Finder's Preview pane, with the file list visible.
The excerpts are silent and scaled; a Space key annotation is added to the first
recording: a spacebar symbol followed by Espace on the French page and Space
on the English page. Each page loads only its own language variant. The second
records the actual macOS pointer and a real seek operation.
The movie footage retains its CC BY 4.0 terms; no endorsement by Blender
Foundation is implied. This media credit does not publish or license the
application's source code.
