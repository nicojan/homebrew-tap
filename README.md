# nicojan/tap

Homebrew cask for [Chorus](https://github.com/nicojan/Chorus), a native macOS app
that puts your web services in one window, each with its own isolated session.

```sh
brew install --cask nicojan/tap/chorus
```

The cask installs the signed, notarized DMG from the Chorus releases page. Chorus
then updates itself through Sparkle, so `brew upgrade` leaves it alone unless you
pass `--greedy`.
