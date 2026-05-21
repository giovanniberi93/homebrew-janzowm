# homebrew-janzowm

Homebrew tap for [janzoWM](https://github.com/giovanniberi93/janzoWM) — a macOS tiling window manager that combines app focusing and window tiling into a single key-chord interaction. Vim-like keybindings supported.

## Installation

Install via [Homebrew](https://brew.sh):

```bash
brew install --cask giovanniberi93/janzowm/janzowm
```

> ***Why does macOS block janzoWM on first launch?***
>
> `janzoWM` is distributed unsigned (no $99/yr Apple Developer Program). The first launch hits Gatekeeper and the app refuses to open. Two ways past it:
>
> - **System Settings → Privacy & Security**, scroll to the "*janzoWM* was blocked..." notice and click **Open Anyway**, then confirm; or
> - remove the quarantine attribute from the bundle via command line:
>
> ```bash
> xattr -dr com.apple.quarantine /Applications/janzoWM.app
> ```

After launch, grant Accessibility permission when prompted: **System Settings → Privacy & Security → Accessibility**.
