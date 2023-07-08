---
title: "My Linux Dotfiles"
image: neofetch.png
description: "Skills: Linux"
---

[Github](https://github.com/paarthtandon/dotfiles)

{{< figure src="/images/neofetch.png" title="" >}}

Hello, these are my Linux dotfiles. I run a Wayland setup on Arch, and use Sway (similar to i3wm) for my window manager.

I personally do not advise anyone to run Wayland unless they enjoy tinkering in Linux. However, it does come with certain advantages. This includes a longer battery life, plug and play external monitors, no screen tearing, and automatic scaling. However, there any still many broken features. Some issues I have personally experienced are: Zoom always crashes, and Discord screenshare does not work. Besides these issues, it works very smoothly. In my experiences much smoother than X.

Setup:

* Dell XPS 13 9380
* Arch
* Wayland
* Sway
    * automatic alternating layout when opening new tiles
* Waybar

`.bashrc` contains some helpful aliases:

```
# easy sleep command
alias sleep='systemctl suspend'

# micro is a more modern version of nano
alias e='micro'

# screenshots on Wayland are weird
alias ss='grim -g "$(slurp)" screenshot.png'
```
