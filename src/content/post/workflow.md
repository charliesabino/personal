---
title: "My Blazingly Fast Mac Workflow"
description: "My Mac workflow featuring Neovim, Yabai, Raycast, and more."
publishDate: "29 August 2023"
tags: ["workflow", "tools", "tech"]
---

Ever since my discovery of efficient software and tools such as Alfred and Vim,
I have sought to develop the most BLAZINGLY FAST Mac workflow possible.

In this article, I will share that workflow—its constituent parts and my individual configuration of tools.

![](https://i.imgur.com/bjA8kYs.jpg)

## Neovim

My first (and favorite) tool that I use daily is [Neovim](https://neovim.io/). Neovim is a hyperextensible
Vim-based text editor.

For those who don't know what Vim is, it's essentially a text editor that can be controlled entirely with the keyboard. Neovim is a vastly superior fork of Vim, extensible in Lua and featuring a vast selection of plugins. You can read more about it [here](https://opensource.com/resources/what-vim).

When I first started using Neovim, I developed and maintained my own configuration. However, this was frustrating and resulted in countless hours of wasted debugging.

To remedy this complaint with an otherwise fantastic tool, I've switched to [AstroNvim](https://github.com/AstroNvim/AstroNvim), a Neovim configuration maintained by others. AstroNvim deals with all of the annoying parts of Neovim, provides sensible defaults, and still allows for the hyperextensibility key to Neovim's identity. My configuration can be found [here](https://github.com/charliesabino).

I use and love many plugins; however, some of my favorites are Telescope, Leap, Comment, Packer, Whick-Key, Mason, and ToggleTerm.

Learning Vim is a grind, but having done it, I can say with certainty that it is well worth it—I can't imagine going back to using a mouse. Additionally, learning the ways of Vim allows for greater efficiency in the parts of a workflow outside of programming, evidenced by the later parts of this article.

## Raycast

As a long-time Alfred user and devotee, I can say with confidence that [Raycast](https://www.raycast.com/) is superior in almost every way.

For those of you who are unaware, Alfred and Raycast are spotlight extension tools. They allow you to perform many tasks—unit conversions, quitting and opening apps, controlling Spotify, viewing clipboard history, defining words, etc.—by simply activating spotlight (command + space).

I recently switched from Alfred to Raycast due to the latter's superior plugin library; however, both are great choices. They are much easier tools to pick up than Vim and arguably facilitate greater improvements in efficiency as well.

Some of my favorite Raycast plugins include [Kill Process](https://www.raycast.com/rolandleth/kill-process), [Spotify Player](https://www.raycast.com/mattisssa/spotify-player), [Bitwarden](https://www.raycast.com/pomdtr/bitwarden), [YouTube Search](https://www.raycast.com/pomdtr/bitwarden), and [DevDocs](https://www.raycast.com/pomdtr/devdocs).

## Yabai + SKHD

<img src="https://media.giphy.com/media/ytjdWXIBB1WifvJidY/giphy.gif" width="100%" height="0" />

[Yabai](https://github.com/koekeishiya/yabai) and [SKHD](https://github.com/koekeishiya/skhd) are two separate tools that, when combined, provide by far the best windows management on Mac. I have configured the two such that I can resize, maximize/minimize, and switch between windows and desktops using Vim mappings.

Both my Yabai and SKHD configs can be found in [my dotfiles](https://github.com/charliesabino/dotfiles/tree/main/dot_config).

## BetterTouchTool

I don't use [BetterTouchTool](https://folivora.ai/) for much, but it is convenient for navigating to an application whose desktop number I'm unaware of or opening an instance of an app if it isn't already.

For example, I use option + b to navigate to my browser, option + i to navigate to my terminal, and option + s to navigate to my email.

## Superhuman

Although ridiculously expensive, [Superhuman](https://superhuman.com/) is an email client that can be controlled entirely with the keyboard using Vim-like mappings. Not sure if that justifies the price tag, but they do offer a student discount.

## Chrome Extensions

[Vimium](https://vimium.github.io/) is a Chrome extension that, once again, as the name implies, allows for browser navigation solely through the keyboard using Vim mappings. It has improved my browser traversal efficiency by several factors, and I can't imagine living without it.

[Video Speed Controller](https://chrome.google.com/webstore/detail/video-speed-controller/nffaoalbilbmmfgbnbgppjihopabppdk?hl=en) is a Chrome Extension that allows you to speed videos found anywhere on the internet up to the speed of your choosing. I tend to watch videos at 2x speed, but sometimes push them up to 3.5x if I'm bored or find the content easy to grasp. The inability to speed up videos without distorting audio in WebKit-based browsers is the sole thing that keeps me using Chromium-based ones.

## Conclusion

I hope you enj
