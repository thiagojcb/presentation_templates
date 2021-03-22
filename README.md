# Presentation Beamer Templates
## Installation
This is a beamer template with Sussex and DUNE logo.

To install this, you can either:
- Copy all the .sty and .png file next to your presentations (ugly)
- Copy all the .sty and .png file in your latex directory, and you will get the theme available for all your Beamer presentations.

The way to do that:

1. Figure out where your TeX home directory is:

```TXHOME=$(kpsewhich -var-value=TEXMFHOME)```

2. Create the following folders in the TeX home directory:

`mkdir -p ${TXHOME}/tex/latex/sussex`

3. Copy all the .sty and .png file in there.

Reference: https://tex.stackexchange.com/questions/1137/where-do-i-place-my-own-sty-or-cls-files-to-make-them-available-to-all-my-te

If that doesn't work... I don't know, you're on your own, goodluck.


## Usage
The only thing you need to do is:

```\usetheme{sussex}```

before the `\begin{document}`.

## Example
There is an example in `example`.

## Wait I want to use it for NOvA/some other experiment!
Around line 11 of `beamerinnerthemesussex.sty` is where the choice for the logo is made. You can uncomment the logo you need there...

## Contribute
You can contribute if you want, probably the best would be to create a branch and commit your modifications on there before we include them in the main branch.

TODO:
- Modify the `beamerinnerthemesussex.sty` to allow toggling between DUNE/NOvA
- Make the logo a variable such that somebody can use a different logo (SNO+ or anything else)
