# SPARC project page

Project page for **SPARC: Scene-Guided Photon Acquisition and Sparse Representation for SP-LiDAR Compression**
(Hashan K. Weerasooriya, Weijian Zhang, Stanley H. Chan, WACV 2027).

Live at: https://hashan-kavinga.github.io/SPARC/

## Publish (first time)

1. On GitHub, create a new **public** repository named exactly `SPARC` under `Hashan-Kavinga`. Don't add a README.
2. In this folder, run:

   ```
   git init
   git add .
   git commit -m "SPARC project page (WACV 2027)"
   git branch -M main
   git remote add origin https://github.com/Hashan-Kavinga/SPARC.git
   git push -u origin main
   ```

3. On GitHub, go to the repo's **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and click Save.
   After a minute or two the page is live at the URL above.

## Later updates

When the paper, supplement or code is available, replace the matching "coming soon" button in `index.html`
(search for `is-coming-soon`) with a normal link, e.g.

```html
<a href="https://..." class="external-link button is-normal is-rounded is-dark">
```

Then run `git add . && git commit -m "update links" && git push`.

Built with the [Nerfies](https://github.com/nerfies/nerfies.github.io) and [MagicTime](https://pku-yuangroup.github.io/MagicTime/) templates.
