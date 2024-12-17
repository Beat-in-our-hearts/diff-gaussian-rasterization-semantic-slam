# Differential Gaussian Rasterization

Used as the rasterization engine for the paper "3D Gaussian Splatting for Real-Time Rendering of Radiance Fields". If you can make use of it in your own research, please be so kind to cite us.

# Render Depth image and feature map

a depth image buffer and a feature buffer were created just like the RGB image.

# Gradient for camera pos and rot $T_{Cw}$

for camera pos: 

# Gradient for Depth image and feature map


# Semantic Render Flag

| 渲染性能 | DIM | 0 | 8 | 32 | 64 | 128 | 256 |
|----------|-----|---|---|----|----|-----|-----|
| 追踪渲染 | 1794 | 1758 | 1750 | 1731 | 1722 | 1634 |
| 建图渲染 | 1786 | 1475 | 846 | 457 | 149 | |



<section class="section" id="BibTeX">
  <div class="container is-max-desktop content">
    <h2 class="title">BibTeX</h2>
    <pre><code>@Article{kerbl3Dgaussians,
      author       = {Kerbl, Bernhard and Kopanas, Georgios and Leimk{\"u}hler, Thomas and Drettakis, George},
      title        = {3D Gaussian Splatting for Real-Time Radiance Field Rendering},
      journal      = {ACM Transactions on Graphics},
      number       = {4},
      volume       = {42},
      month        = {July},
      year         = {2023},
      url          = {https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/}
}</code></pre>
  </div>
</section>

