<div id="top"></div>




<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## Contributors
[@sfpacman](https://github.com/sfpacman)

## About The Project
This repository contains the R code used to generate a gif animation for a fundraising presentation for ovarian cancer research. The purpose of the animation is to captivate audiences with the remarkable capabilities of genomics sequencing technology. The animation is crafted using [gganimate](https://gganimate.com/) and comprises a series of ggplots. The tissue image and projections are derived from 10X Visium spatial transcriptome data obtained from an actual endometrium sample, which serves as the basis for the animation


<img src="https://raw.githubusercontent.com/sfpacman/show_off/main/data/animation.gif">

<!-- About -->
## The meaning of the animation
This animation represents a high-level overview of the workflow for 10X Visium. It commences with extracting an endometrium sample from the uterus, progresses through RNA sequencing, and incorporates a sequence analysis depicted through the PCA and t-SNE projection animation. Subsequently, the insights gained from this analysis are visually represented by colored dots on the t-SNE plot. These dots are then remapped to the tissue and the uterus, creating a dynamic and informative representation of the genomic journey.

<!-- GETTING STARTED -->
## How to run it
If you wish to make a simiar gif, you can [use ```renv.lock```file ](https://rstudio.github.io/renv/articles/renv.html#collaboration) to install the required R packages and the code is located at `notebook/demo_visium.Rmd`.
