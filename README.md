## About
This blog uses blowfish and Hugo

## Versions
### Node
version: v25.2.1
### Hugo
hugo v0.154.1-e2fd6764be86d0cde988a7de6334fda0f43de871+extended+withdeploy linux/amd64 BuildDate=2026-01-01T17:32:20Z VendorInfo=gohugoio

[link](https://github.com/gohugoio/hugo/releases/tag/v0.154.1)

## Dev Notes

### Running

#### Setup
To begin, you need to download the listed versions of node and Hugo.

Pull the repo, and run `git submodule update --init` to initialize the
blowfish submodule.

use `npx blowfish-tools` or edit the existing files to make the desired
changes

#### Adding Pages
When creating a new page via blowfish-tools, it will be a draft.
To view / generate draft pages use `hugo server -D` to run the server.

To see the site without drafts, use `hugo server`.

### Images
Hugo / blowfish may not respect EXIF orientation when processing images for the
feature view.
to fix orientation you can use the `imagemagick` tool

use: `mogrify -auto-orient <image-name>`

to fix the orientation
