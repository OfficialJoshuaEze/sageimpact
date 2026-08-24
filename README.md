# Sage Impact Foundation — Visual Impact Platform Prototype

This version expands the redesign into a media-rich impact archive.

## What is included
- Brand system based on Sage Impact navy and orange
- Fully responsive desktop / tablet / mobile layouts
- Animated navigation and mobile menu
- Filterable Programs / Projects catalogue
- Project detail modal with impact metrics and photo gallery
- Photo-batch / lightbox experience
- Documentary and video-library section
- Video-preview modal with stock reference links
- Scroll reveal, hover, image zoom and color-transition interactions
- Impact statistics and journey timeline
- Partnership conversion section

## Placeholder media
The prototype intentionally mixes:
1. the Sage image already referenced by the current website; and
2. stock / external placeholder imagery used only to demonstrate art direction and media density.

Before production launch, replace all stock placeholders with Sage-owned photographs and videos, and confirm usage rights for every final asset.

## Easy media replacement
Most catalogue items are populated from the `projects`, `videoData`, and `batchImages` arrays near the bottom of `index.html`.

To replace an image, change its URL in those arrays. To add a project, duplicate one object in the `projects` array and update its title, category, image, summary, metrics and gallery.

For videos, replace the placeholder `url` with a Sage YouTube/Vimeo link or adapt the modal to embed locally hosted MP4/WebM files.

## Suggested production CMS collections
- Programs
- Projects / Interventions
- Impact Stories
- Photo Batches
- Videos / Documentaries
- Events
- Press
- Reports
- Partners
- Team

## Production notes
- Download and optimize final Sage images into WebP/AVIF.
- Host video on a proper streaming/CDN service rather than placing large files directly in the page bundle.
- Add meaningful alt text for every final photograph.
- Replace prototype impact figures with approved monitoring data.
- Connect partnership, donation and contact actions to real forms/workflows.
