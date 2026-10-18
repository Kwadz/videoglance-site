# VideoGlance

Public website and future distribution files for VideoGlance, a free macOS
Quick Look application for MKV, WebM and other video formats.

**The application is in preparation. No public installer or Homebrew cask is
available yet.** The website describes the tested configuration and known limits;
it does not claim full compatibility with Apple's previews.

This repository contains the generated French and English website, its images
and this introduction. It does not contain the application's source code.

Open the website to choose French or English. A custom domain may be added later.
Verified installers, checksums and release notes will be published through
GitHub Releases when ready. There are currently no release assets to download.

## Publishing

GitHub Pages serves the root of the `main` branch. The `.nojekyll` file preserves
the static HTML output without Jekyll processing. Only reviewed website exports
are pushed here; a push to the private application repository does not deploy
this site. A push to this public repository updates the website.

The preparation site keeps `noindex` metadata. This does not make it private:
the repository and website are public. Before the app's first public release,
the download links, installation instructions, release notes and search metadata
will be completed and verified.
