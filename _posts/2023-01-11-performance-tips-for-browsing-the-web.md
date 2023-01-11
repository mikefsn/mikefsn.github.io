---
title: "Performance tips for browsing the web"
---

## Block ads + cookie prompts

[uBlock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm) not only lets you block ads, but also cookie prompts. To enable blocking of cookie prompts, go to the extension's options > Filter lists and tick these boxes under Annoyances:

\- EasyList Cookie  
\- uBlock filters - Annoyances

## Auto discard tabs opened in the background

[Auto Tab Discard](https://chrome.google.com/webstore/detail/auto-tab-discard/jhnleheckmknfcgijgkadoemagpecfol) lets you automatically discard tabs opened in the background. To enable this, go to the extension's options and tick the box called:

\- Discard all newly opened inactive tabs after they get loaded

## Use lightweight alternatives of Reddit, Twitter, YouTube and the homepage

[Redirector](https://chrome.google.com/webstore/detail/redirector/ocgpenflpmgnfapjedencafcfakcekcd) lets you redirect requests from:

reddit.com -> old.reddit.com  
youtube.com -> yewtu.be  
twitter.com -> nitter.net

To set up these redirects, go to the extension's options and import these settings:

[Redirector.json](https://gist.githubusercontent.com/mikefsn/e28c1a6f910dcaf6bceada4e414a16ed/raw/122578be478309fb3cba023c37173b62abf97f3e/Redirector.json)

(Note I'm writing this from the point of view of someone who visits YouTube and Twitter as a guest. For content creators the original websites will be better.)

For New Tab Page, you can use a minimalistic extension like this one:

https://github.com/mikefsn/new-tab-page

## Keep Chrome running as a background process (on Windows)

[Lightning Reopen](https://chrome.google.com/webstore/detail/lightning-reopen/ahphokgmcecbjeipkfkamcdmemghkaph) lets Chrome run as a background process on Windows. This makes the browser launch instantaneously.

## Disable animation when opening Chrome windows (on MacOS)

In order to disable the animation when opening Chrome windows on MacOS, you can run this command:

```
defaults write NSGlobalDomain NSAutomaticWindowAnimationsEnabled -bool NO
```

To enable it again, run this command:

```
defaults write NSGlobalDomain NSAutomaticWindowAnimationsEnabled -bool YES
```

[_Previous post_](https://mikefsn.github.io/2022/10/22/how-the-zig-team-pushes-a-narrative.html)
