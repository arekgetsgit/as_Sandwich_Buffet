<picture>
  <div style="width:100%;height:0;padding-bottom:100%;position:relative;"><iframe src="https://giphy.com/embed/zD6sbCUC4gaBnDUxOE" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div><p><a href="https://giphy.com/gifs/pedro-pascal-nuke-compositing-zD6sbCUC4gaBnDUxOE">via GIPHY</a></p>
</picture>

Sandwich Buffet is a set of python scripts for The Foundry Nuke, creating popular node setups, applying a certain operation and inverting it back.

At the moment there are seven sandwich node cases:
- unpremult-premult
- reformat
- gamma
- grade
- lin2log
- colorspace
- OCIO colorspace

While unpremult-premult is very simple, other setups offer expression connections saving additional clicks and tweaks.

Please note, each setup has one node labeled “set values here”, that’s the one you want to play with.

Grade and Gamma sandwich is mostly popular for applying defocus, it’s applying preferable gamma value and inverting it back at the end.

Lin2Log sandwich converts linear color space to logarithmic and back and offers white, black, gamma sliders expression connection.

Colorspace allows you to change color space without needing to switch back in the second node.

Reformat with scale operation allows you to scale image and invert transformation back. This setup is also mirroring resize type and filter knobs.
