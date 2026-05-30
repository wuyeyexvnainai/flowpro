# FlowPRO — Project Page

Static project page for the paper:

> **FlowPRO: Reward-Free Reinforced Fine-Tuning of Flow-Matching VLAs via Proximalized Preference Optimization**
> Yihao Wu, He Zhang, Junbo Tan, Xueqian Wang, Zhengyou Zhang
> Submitted to CoRL 2026.

🔗 Live site: <https://wuyeyexvnainai.github.io/flowpro/>

---

## Local preview

This is a pure static page (HTML / CSS / JS). To preview locally:

```bash
# Python 3
python -m http.server 8000
# then open http://localhost:8000/
```

## Deployment

Hosted on **GitHub Pages** from the `main` branch (root). Any commit to `main` is deployed automatically by GitHub.

## Replacing demo videos with YouTube embeds

In `index.html`, find any `<div class="video-placeholder">…</div>` block and replace it with:

```html
<div class="publication-video">
  <iframe width="560" height="315"
          src="https://www.youtube.com/embed/YOUR_VIDEO_ID"
          title="FlowPRO demo"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          allowfullscreen></iframe>
</div>
```

## Acknowledgements

Page template adapted from [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template), originally based on [Nerfies](https://nerfies.github.io/).
