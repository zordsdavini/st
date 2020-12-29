Patched version of Simple (Suckless) terminal ST by zordsdavini
===============================================================

**To read real Suckless readme read `README`**

Applied patches:
* **Xresources** - as I'm using `pywal` for teminal (Qtile, dmenu and other cool apps) theming, then `st` can read colours through
  `.Xresources`. To check how to enable see my dotfiles
* **spoiler** - invert colors then selecting. That avoids lost text if it is same colour as selection
* **newterm** - open new terminal with <C-return>

2020-05-19 - bump to 0.8.3 version
2020-06-19 - bump to 0.8.4 version
