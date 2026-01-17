---
title: "Media Embed Guide"
date: 2026-01-16
publish: false
tags:
  - guide
  - media
---

# Media embed guide

Use this as a copy/paste reference for posts. Paths below are **relative to this file**.

## Images

### Local image

![Sample image placeholder with a frame and label](media/sample-image.svg)

### Image with caption

<figure>
  <img src="media/sample-image.svg" alt="Sample image placeholder with a frame and label">
  <figcaption>Caption text for the image.</figcaption>
</figure>

### Link to the image file

[Download the full-resolution image](media/sample-image.svg)

## Links to media files

You can link to any file you include alongside your post:

- [Lab report PDF](media/sample-report.pdf)
- [Dataset ZIP](media/sample-data.zip)

## Video (mkdocs-video plugin)

Use the image syntax with a `type:video` marker:

```markdown
![type:video](media/sample-video.mp4)
```

You can also embed a hosted player:

```markdown
![type:video](https://www.youtube.com/embed/LXb3EKWsInQ)
```

## Video (HTML embed)

```html
<video controls width="640">
  <source src="media/sample-video.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```

## Audio (HTML embed)

```html
<audio controls>
  <source src="media/sample-audio.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>
```

## Tips

- Keep file sizes small; large files slow the site.
- Use clear, descriptive alt text for images.
- Images open in a lightbox if the site enables `mkdocs-glightbox`.
- Put media files in a `media/` folder next to your post and link them like `media/filename.ext`.
