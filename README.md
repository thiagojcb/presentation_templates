# Presentation Beamer Templates
## Installation
This is a beamer template with Sussex and DUNE logo.

To install this, you can either:
- Copy all the .sty and .png file next to your presentations (ugly)
- Copy all the .sty and .png file in your latex directory, and you will get the theme available for all your Beamer presentations.
The way to do that:
1. Figure out where your TeX home directory is:
```kpsewhich -var-value=TEXMFHOME```
2. Create the following folders in them:
`/tex/latex/sussex`
3. Copy all the .sty and .png file in there.
https://tex.stackexchange.com/questions/1137/where-do-i-place-my-own-sty-or-cls-files-to-make-them-available-to-all-my-te
If that doesn't work... I don't know, you're on your own, goodluck.


## Usage
The only thing you need to do is:
```\usetheme{sussex}``` before the `\begin{document}`
