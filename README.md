# cystic-index

An automated image analysis tool for measuring cystic index and the percentage of cystic collecting duct organoids.

**[rjayasin.github.io/cystic-index](https://rjayasin.github.io/cystic-index/)**

Upload a bright-field image of collecting duct organoids to quantify cyst formation. The tool estimates the cystic index for each organoid (cyst area as a percentage of total organoid area) and the percentage of organoids classified as cystic (cystic organoids divided by all organoids). Review and adjust the segmentation as needed.

Everything runs in the browser from a single `index.html` with no dependencies or build step; images are never uploaded anywhere. To run it locally, serve the folder with any static file server, e.g. `python3 -m http.server`.
