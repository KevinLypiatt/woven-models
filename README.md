# woven-models

Model files downloaded by the Woven iOS app. Nothing else lives here; the app's
source is in a separate, private repository.

## bioclip-2-int8

[BioCLIP 2](https://imageomics.github.io/bioclip-2/) (Imageomics Institute,
The Ohio State University), image tower only, converted to Core ML and quantised
to int8 for on-device species identification. BioCLIP 2 is released under the
MIT licence; this conversion carries the same licence. Please cite the BioCLIP 2
authors if you use it.

The release assets are the Core ML package split into 40 MB parts, plus a label
table (`labels.bin` / `labels.json`) of species embeddings, and a manifest the
app reads to reassemble and verify them.
