---
title: "A Faceted Prior for Scalable Wideband Imaging: Application to Radio Astronomy"
collection: publications
permalink: /publications/proceedings/camsap2019
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2019-12-15
end: 2019-12-18
venue: 'IEEE International Workshop on Computational Advances in Multi-Sensor Adaptive Processing (CAMSAP)'
paperurl: 'https://researchportal.hw.ac.uk/en/publications/a-faceted-prior-for-scalable-wideband-imaging-application-to-radi'
citation: 'Pierre-Antoine Thouvenin, Abdullah Abdulaziz, <b>Ming Jiang</b>, Audrey Repetti, and Yves Wiaux.
           A faceted prior for scalable wideband imaging: application to radio astronomy.
           In <em>2019 IEEE International Workshop on Computational Advances in Multi-Sensor Adaptive Processing (CAMSAP)</em>. 2019.'
show_citation: false
type: proceedings
---
## Abstract
Wideband radio-interferometric (RI) imaging consists in estimating images of the sky across a whole frequency band from incomplete Fourier data. Powerful prior information is needed to regularize the inverse imaging problem. At the extreme resolution and dynamic range of interest to modern telescopes, image cubes will far exceed Terabyte sizes, with data volumes orders of magnitude larger, making image estimation a very challenging task. The computational cost and memory requirements of corresponding iterative image recovery algorithms are extreme and call for high parallelism. A data-splitting strategy was recently introduced to parallelize computations over data blocks within an advanced primal-dual convex optimization algorithm. Building on the same algorithm, we propose an image faceting approach that consists in splitting the image cube into 3D overlapping facets with their own prior, reducing the computational bottleneck from full image to facet size. Simulation results suggest our prior provides similar if not superior reconstruction quality to the corresponding state-of-the-art non-faceted approach, with facet parallelization offering acceleration and therefore increased potential of scalability to large data and image sizes.

## Hightlights
![image-center](/images/proceedings/camsap2019.png){: .align-center}

Faceted (column 1 and 3) v.s. standard HyperSARA (column 2 and 4) on synthetic data for the channel 1 (first two columns) and 20 (last two columns). From top to bottom: the ground truth with the associated normalized uv-coverage, the reconstructed and residual images. Faceted HyperSARA gives an imaging quality similar to HyperSARA for high intensity emissions, and outperforms it for faint emissions as can be seen on the reconstructed images (zoomed region). The faceted approach yields better or comparable residual images of very small amplitude when compared to HyperSARA (last row).

[[Bibtex]]({% link _publications/proceedings/camsap2019-Bibtex.html %}) [[PDF]]({% link files/proceedings/camsap2019.pdf %})