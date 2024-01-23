---
layout: default
title: Home
order: 1
---

<link rel="stylesheet" href="gallery/css/blueimp-gallery.min.css">

#### Our lab's mission is to understand immune defense quantitatively using theory and computation.

We are a Quantitative Immunology research group in the [Division of Infection and Immunity](https://www.ucl.ac.uk/infection-immunity/) at UCL. Our research is embedded within the collaborative environment of the [Innate2Adaptive lab group](https://www.ucl.ac.uk/infection-immunity/research/research-department-infection/lab-research-groups/innate2adaptive) and we have strong links with experimental and theory groups at UCL and beyond.

Our approach to quantitative immunology is rooted in the tradition of biological physics and we are part of UCL's [Institute for the Physics of Living Systems](https://www.ucl.ac.uk/physics-living-systems/).

### News

- On March 14th 2024 we are organizing the [2nd London Quantitative Immunology Day](https://qimmuno.com/ldnday/). Come join us!
- The London Quantitative Immunology Network now has a mailing list: Sign up instructions [here](https://qimmuno.com/ldnqimmuno/).
- December 2023: Silver and Bronze for the QImmuno lab in the [IMMREP23](https://www.kaggle.com/competitions/tcr-specificity-prediction-challenge/leaderboard) TCR Specificity Prediction Challenge!!
- On March 9th 2023 we are organizing a [London Quantitative Immunology Day](https://qimmuno.com/ldnday2023/). Come join us!
- Sept 30 2022: The workshop "Statistical physics and adaptive immunity" co-organized by Andreas is now open for [registration](https://aspenphys.org/physicists/summer/program/currentworkshops.html). The workshop will be held at the Aspen Center for Physics August 6 - 27, 2023.
- July 25 2022: First paper from lab out on [bioRxiv](https://doi.org/10.1101/2022.07.25.501373)! Our first foray into deciphering TCR specificity quantitatively. 
- Apr 7 2022: The lab opens its doors at UCL!
- Mar 15 2022: Andreas gave an invited talk at the APS march meeting in the [Sensing chemical spaces](https://meetings.aps.org/Meeting/MAR22/Session/F14) session.
- Mar 5 2020: Andreas gave an invited (virtual) talk at the APS march meeting in the [Population dynamics in time-varying environments](http://meetings.aps.org/Meeting/MAR20/Session/U27) session.
- December 11-13 2019: We have organized a conference at PCTS on [Sensing chemical spaces](https://pcts.princeton.edu/events/2019/sensing-chemical-spaces). Video recordings of the lectures are available [here](http://www.kaltura.com/tiny/opthb).
{:.horn}

### Selected Publications

A Mayer, C Callan **Measures of epitope binding degeneracy from T cell receptor repertoires**, PNAS, 2023. [<i class="ai ai-doi"></i>](https://doi.org/10.1073/pnas.2213264120)

H Chen, A Mayer, V Balasubramanian **A scaling law in CRISPR repertoire sizes arises from avoidance of autoimmunity**, Current Biology, 2022. [<i class="ai ai-doi"></i>](https://doi.org/10.1016/j.cub.2022.05.021)

MG Gaimann, M Nguyen, J Desponds, A Mayer, **Early life imprints the hierarchy of T cell clone sizes**, eLife, 2020. [<i class="ai ai-doi"></i>](https://doi.org/10.7554/eLife.61639)

A Mayer, Y Zhang, AS Perelson, NS Wingreen, **Regulation of T cell expansion by antigen presentation dynamics**, PNAS, 2019. [<i class="ai ai-doi"></i>](https://doi.org/10.1073/pnas.1812800116)

A Mayer, O Rivoire, T Mora, and AM Walczak, **Diversity of immune strategies explained by adaptation to pathogen statistics**, PNAS, 2016. [<i class="ai ai-doi"></i>](http://dx.doi.org/10.1073/pnas.1600663113)

### Image Gallery
<div id="links" style="background-color:#2d314d;padding:0.5em">
    <a href="images/pears.jpg" title="The Institute of Immunity and Transplantation">
        <img src="images/thumbnails/pears.jpg" alt="Pears Building">
    </a>
    <a href="images/crispr.jpg" title="What trade-offs shape prokaryotic immunity? (Current Biology 2022)">
        <img src="images/thumbnails/crispr.jpg" alt="CRISPR graphical abstract">
    </a>
    <a href="images/tcellexpansion.jpg" title="How is T cell expansion regulated? (PNAS 2019)">
        <img src="images/thumbnails/tcellexpansion.jpg" alt="T cell expansion">
    </a>
    <a href="images/ldnqimmuno_audience_23.jpg" title="The lively audience of the London QImmunoDay 2023">
        <img src="images/thumbnails/ldnqimmuno_audience_23.jpg" alt="London QImmuno Day">
    </a>
</div>

<div id="blueimp-gallery" class="blueimp-gallery blueimp-gallery-controls">
    <div class="slides"></div>
    <h3 class="title"></h3>
    <a class="prev">‹</a>
    <a class="next">›</a>
    <a class="close">×</a>
    <a class="play-pause"></a>
    <ol class="indicator"></ol>
</div>

<script>
document.getElementById('links').onclick = function (event) {
    event = event || window.event;
    var target = event.target || event.srcElement,
        link = target.src ? target.parentNode : target,
        options = {index: link, event: event},
        links = this.getElementsByTagName('a');
    blueimp.Gallery(links, options);
};
</script>

<script src="gallery/js/blueimp-gallery.min.js"></script>


