---
layout: page
title: TeraScaleFixup - A Lilu plugin for exotic AMD TeraScale GPUs
description: 2023-Present
img: assets/img/KEXT.png
importance: 2
category: Modern macOS
related_publications: false
---

<h3>
    <a href="https://github.com/Jazzzny/iFR">View on GitHub</a>
</h3>
<br>

TeraScaleFixup is a Lilu plugin that provides support for exotic AMD TeraScale GPUs in macOS. It uses the Lilu Patching Engine to inject necessary patches for unsupported TeraScale GPUs relying on the ATIRadeonX2000 driver family, which explicitly lacks support for these GPUs.


## Screenshots

<div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/terascalefixup/elcap.png" title="TeraScaleFixup on 10.11 El Capitan" class="img-fluid rounded z-depth-1" %}
</div>