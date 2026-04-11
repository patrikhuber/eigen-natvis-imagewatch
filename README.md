# ImageWatch visualisers for Eigen

This repository contains a .natvis file to visualise Eigen matrices and vectors with the ImageWatch plugin for Visual Studio.

Note: Microsoft open-sourced Image Watch in April 2026. I've created a fork https://github.com/patrikhuber/image-watch and a Marketplace release https://marketplace.visualstudio.com/items?itemName=PatrikHuber.ImageWatch.

I fixed the col-major issue and the Eigen .natvis visualisers are now **bundled** with the above updated extension.

The .natvis file is initially taken from https://gist.github.com/willyd/3ffd39a1b11fa4c09938.

## Old Notes/Todos:

RowMajor matrices are displayed correctly. However, ColMajor matrices are displayed transposed. It would be nice to fix that. Image Watch supports row and col strides but I couldn't get it to work.

Support making Image Watch open-source: https://developercommunity.visualstudio.com/t/open-source-image-watch-plugin/351613

Post & details about the strides issue on MS Developer Community: https://developercommunity.visualstudio.com/content/problem/181317/image-watch-and-eigen-support-custom-rowcol-stride.html

## Other related links

Other potentially useful natvis visualisers: https://github.com/aleksey-nikolaev/natvis-collection
