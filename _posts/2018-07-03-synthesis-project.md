---
layout: post
title:  Geomatics students impress with projects on Sky View Factor and building reconstruction from images
categories: news
date: 2018-07-03 11:00
---

During Q4 of the first year of the MSc Geomatics we as a group were pleased to supervise 2 of the 5 groups of the Synthesis project. Within the synthesis project the students gain 10ECTS by performing a project in the way it works on the job. All subjects have a client from practice with a real-world problem they want to see solved. During a kick-off meeting the students see presentations from all clients and they choose themselves a preferred project. At the beginning of the project the groups translate the problem statement into a project proposal which they discuss with the client. After realigning the proposal to the discussion points of the client they go and start their research. The research is looking at state-of-the-art and based on this they start developing. In the end all groups present the end product to experts in the field during the Geomatics day [article in GIM International](https://gim-international.com/content/news/tu-delft-geomatics-day-provides-insight-into-future-careers).


Project Sky View Calculation

One of the projects supervised by our group is the sky view factor. Proposal of the client, Municipality of The Hague, is to create a web portal for calculating the sky view factor for any given location inside the municipality borders of The Hague. The sky view factor is the amount of visible sky from a location on the earth’s surface. One of the conditions was full open-source development.

<table border="0">
  <tr>
    <td><img class="img-responsive" src="/img/2018/SkyView-dome.png"></td>
    <td><img class="img-responsive" src="/img/2018/SkyView-3dpc.png"></td>
  </tr>
  <tr>
    <td>Source: Urban Horizon</td>
    <td>Source: An et al. (2014)</td>
  </tr>
</table>
<br />

What started as a group became a team during this project. They approached the project by divide and conquer and split the work into multiple disciplines. The portal development had to be learned from scratch since none had any experience with web development. This portal contains HTML, CSS and JavaScript to make all the components work. During earlier stages of the project calculation of the sky view factor in Python for a single location was taking around 50 seconds and after a lot of fine tuning the results came down to sub-second performance per point. This made it possible to do all calculations on-the-fly and drop pre calculations, database storage and caching mechanisms. The JavaScript portal and Python backend are communicating using only a few lines of PHP. Also they implemented options for uploading and downloading csv’s with locations and results as well as adding and removing buildings from the point cloud.
The web portal proofs to be scalable to country level and performs well for multiuser scenario’s. Finally this group delivered the project results the Municipality of The Hague. The report and all code are available within the web portal under Documentation. We as a group have enjoyed supervising this project and are proud to present you with their results.


<img class="img-responsive" src="/img/2018/SkyViewPortal.png">

The resulting web portal at [skyview.bk.tudelft.nl](http://skyview.bk.tudelft.nl)


Project Building reconstruction from images

The second group worked with with the [Floriade 2022 project](https://floriade.com) and built a complete C++ software that is able to automatically reconstruct building meshes from a set images acquired by drone or by handheld camera. Have a look at their [poster]({{"/pdfs/synthesis-floriade-poster.pdf" | prepend: site.baseurl}}) or their [github repository](https://github.com/Natasja1992/3d_floriade) if you want to know more.

We were impressed by the hard work of all students and hope to see them back for a graduation project.

<br />
<img class="img-responsive" src="/img/2018/synthesis-3drecon.png">