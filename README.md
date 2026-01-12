## About
This blog uses blowfish and Hugo

## Versions
### Node
version: v25.2.1
### Hugo
hugo v0.154.1-e2fd6764be86d0cde988a7de6334fda0f43de871+extended+withdeploy linux/amd64 BuildDate=2026-01-01T17:32:20Z VendorInfo=gohugoio

## Dev Notes

### Running
When creating a page via blowfish-tools, it will be a draft.
To see draft pages use `hugo server -D`.

To see the site without drafts, use `hugo server`.

### Images
hugo / blowfish may not respect EXIF orientation when processing images for the
feature view.
to fix orientation you can use the `imagemagick` tool

use: `mogrify -auto-orient <image-name>`

to fix the orientation
