---
layout: post
title:  Effect of acquisition error and LOD on accuracy of spatial analyses
categories: news
date: 2017-01-27 09:24
---

We published a new paper:

<div class="filteredelement"><strong>The effect of acquisition error and level of detail on the accuracy of spatial analyses</strong>. Filip Biljecki, Gerard Heuvelink, Hugo Ledoux, and Jantien Stoter. <em>Cartography and Geographic Information Science</em>, 45(2): 156-176, 2018. <br /> <a href="http://filip.biljecki.com/publications/2018_cagis_lod_error_propagation.pdf"><i class="fas fa-file-pdf"></i> PDF</a> <a href="http://dx.doi.org/10.1080/15230406.2017.1279986"><i class="fas fa-external-link-alt"></i> DOI</a> <a href="#bib2018_cagis_lod_error_propagation" data-toggle="collapse"><i class="fas fa-caret-square-down"></i> BibTeX</a><div id="bib2018_cagis_lod_error_propagation" class="collapse" tabindex="-1"><pre class="bibtex">@article{2018_cagis_lod_error_propagation,
    author = {Biljecki, Filip and Heuvelink, Gerard B M and Ledoux, Hugo and Stoter, Jantien},
    title = {The effect of acquisition error and level of detail on the accuracy of spatial analyses},
    journal = {Cartography and Geographic Information Science},
    year = {2018},
    volume = {45},
    number = {2},
    pages = {156--176},
    doi = {10.1080/15230406.2017.1279986}
}</pre></div></div>

<br/>

There has been a great deal of research about errors in geographic information and how they affect spatial analyses. A typical GIS process introduces various types of errors at different stages, and such errors usually propagate into errors in the result of a spatial analysis. However, most studies consider only a single error type thus preventing the understanding of the interaction and relative contributions of different types of errors. We focus on the level of detail (LOD) and positional error, and perform a multiple error propagation analysis combining both types of error. We experiment with three spatial analyses (computing gross volume, envelope area, and solar irradiation of buildings) performed with procedurally generated 3D city models to decouple and demonstrate the magnitude of the two types of error, and to show how they individually and jointly propagate to the output of the employed spatial analysis. The most notable result is that in the considered spatial analyses the positional error has a much higher impact than the LOD. As a consequence, we suggest that it is pointless to acquire geoinformation of a fine LOD if the acquisition method is not accurate, and instead we advise focusing on the accuracy of the data.<br/><br/>

<a href="http://dx.doi.org/10.1080/15230406.2017.1279986"><img src="{{ site.baseurl }}/img/2017/cagis-1.png"/></a><br/><br/>

The paper is freely available at the <a href="http://dx.doi.org/10.1080/15230406.2017.1279986">journal</a> (open access).<br/><br/><br/>

<img src="{{ site.baseurl }}/img/2017/cagis-2.png"/><br/><br/>
<img src="{{ site.baseurl }}/img/2017/cagis-3.png"/><br/><br/>
