# TheSaaSPeople media

Public images for scheduled social posts (Instagram and LinkedIn carousels). Buffer reads each image from its raw GitHub link when it publishes the post.

- One folder per post: `<platform>/<YYYY-MM-DD>-<slug>/slide-NN.jpg`, plus `alt.json` (image descriptions).
- Everything here is public, because it is about to be posted publicly. Never put drafts, client names, screenshots with real data, or anything private here.
- Slides are rendered from the approved post by `social-ops/tools/slides/render_carousel.py` (in the marketing folder) in the house style: 1080x1350, dark ground, teal and blue, Inter.
- Don't delete a folder until its post has gone live; Buffer fetches the images at publish time.
