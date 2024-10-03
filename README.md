<picture>
  <img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExdG10MDh5Y2g2YzZnaHh4NW80YXc2aDZvcGpjaDdsMHo5ajNjdGkwOCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/zD6sbCUC4gaBnDUxOE/giphy.webp">
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
