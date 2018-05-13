# design_fonts
A submodule of the [design_id](https://github.com/foss-ag/design_id) repository, `design_fonts` stores the font files needed to create graphics assets in line with the *corporate identity* of the FOSS-AG.

The font files here are stored, rather directly and vulgarly, in `ttf` and/or `otf` formats. This is data-intensive compared to an install script that fetches fonts from somewhere else, and may not comply entirely with the ideal Git model of a repository — but it allows for easy version lock-ins, manual updates and quick installations across various systems.

## Why this repository?
Digital fonts have become a complex and highly integrated aspect of modern graphic design. It is not uncommon for font packages — commercial or free — to recieve numerous updates after their first supposed stable release, improving anything from character support to kerning to glyph design.

Graphic design is a careful craft, however. Any sudden changes to these parameters may alter the desired effect of an image, logo or other crucial element.

This repository locks the primary fonts used for FOSS-AG designs into a single version that can be controlled and managed *from above* by our designers. It also specifies which handful of fonts make the cut as canonical and integral parts of the FOSS-AG brand identity in the first place.

## The Fonts
#### The Big Boy: Clear Sans
Intel's [Clear Sans](https://01.org/clear-sans/) is the font used to render the typographic part of the main FOSS-AG logo and all its derivatives.

It is thus the branding font of the FOSS-AG; the first and *generic* choice when beginning a new FOSS-AG design project. Clear Sans can be used for anything from *headers* to *body-copy*.

For now, it is also the *only* officially specified FOSS-AG font. In future, there will be style guidelines and recommendations with more fonts for specific purposes (like *body-copy*, or *code/typewriter*, etcetera).
