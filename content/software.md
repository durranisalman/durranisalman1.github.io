---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Mathematica and Matlab Software for Computing Distance Distributions"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2023-10-01T18:35:04+11:00
lastmod: 2023-10-01T18:35:04+11:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

During the course of my research, I have written a number of software libraries in collaboration with my students. One of them is now available publicly here and others will be made available in the future.

If you use the software in your research, please reference our relevant publication (see details below).

If you have any suggestions for improving the software, please email me and we can incorporate this in the software.

- #### **Computing distance distributions between two random points, each uniformly randomly distributed in arbitrary (concave or convex) polygons with or without holes [Released: Jan. 2021]**
    - Mathematica Notebooks:
        - [Example 1](../files/software/Example1.nb): Abritrary polygons without holes. Requires Mathematica 11 or higher version.
        - [Example 2](../files/software/Example2.nb): Abritrary polygons with holes. Requires Mathematica 12.
    - Our [paper](https://arxiv.org/abs/1903.07757) is currently under review in Mathematical Methods in Applied Sciences journal (revised: 24 Jan. 2021)
    - Screenshot: ![fig1](/fig1.jpg)

- #### **Computing distance distributions in arbitrary (convex or concave) polygon regions with holes and arbitrary reference point [Released: coming soon!]**
	In K-tier heterogeneous networks, the coverage regions are modelled using a multiplicatively weighted Voronoi diagram. This software computes: (i) the exact closed-form probability density function and (ii) the exact closed-form cumulative density function of the distance between a randomly located node and any arbitrary reference point inside or outside an arbitrarily shaped multiplicatively weighted Voronoi cell.
    - Matlab code (zipped): Developed and tested [Nov. 2014].
    - Mathematica code
    - **Our paper is still in draft form and I am hoping to write it up in the second half of this year.**
    - Screenshot: ![fig2](/fig2.jpg)

- #### **Computing exact closed-form distance distributions in arbitrary (convex or concave) polygon regions without holes and arbitrary reference point [Released: June 2015]**
	This software computes: (i) the exact closed-form probability density function and (ii) the exact closed-form cumulative density function of the distance between a randomly located node and any arbitrary reference point inside an arbitrary L-sided convex polygon.
    - [Mathematica Notebook](http://www.mathematica-journal.com/2015/06/computing-exact-closed-form-distance-distributions-in-arbitrarily-shaped-polygons-with-arbitrary-reference-point/)
    - Screenshot: ![fig3](/fig3.jpg)

- #### **Computing exact closed-form distance distributions in arbitrary convex polygon regions with interior reference point**
	This software computes: (i) the exact closed-form probability density function and (ii) the exact closed-form cumulative density function of the distance between a randomly located node and any arbitrary reference point inside an arbitrary L-sided convex polygon.
    - [Our relevant IEEE TCOM paper (see Appendix A)](../files/software/2014_ieeetcom.pdf)
    - Mathematica Notebook: This will no longer be posted. See our [Mathematica Notebook](http://www.mathematica-journal.com/2015/06/computing-exact-closed-form-distance-distributions-in-arbitrarily-shaped-polygons-with-arbitrary-reference-point/), which can handle both concave and convex polygons.

- #### **Computing exact closed-form distance distributions in regular polygon regions with interior reference point [Released: May 2013]**
	This software computes: (i) the exact closed-form probability density function and (ii) the exact closed-form cumulative density function of the distance between a randomly located node and any arbitrary reference point inside a regular L-sided polygon. These results can be used to obtain the closed-form probability density function of the Euclidean distance between any arbitrary reference point and its nth neighbor node when N nodes are uniformly and independently distributed (i.e. according to a uniform Binomial Point Process) inside a regular L-sided polygon. These distance distributions have many applications in wireless networks. This code is available in both Mathematica and Matlab.
    - [PDF of Mathematica Notebook](../files/software/Compute_DistanceDistributions_Polygon_v1_Mathematica.pdf)
    - [Mathematica Notebook (zipped)](../files/software/Compute_DistanceDistributions_Polygon_v1_Mathematica.zip)
    - [Matlab Code (zipped)](files/software/Compute_DistanceDistributions_Polygon_v1_Matlab.zip)
    - [Our relevant IEEE TVT paper](../files/software/journals/2013_ieeetvt.pdf)
    - Applications: [IEEE TCOM paper](../files/software/2014_ieeetcom.pdf) and [IEEE TVT paper](../files/software/journals/2014_ieeetvt.pdf)
    - [Slides for AusCTW 2013 (invited talk)](../files/software/Durrani_ausCTW2013.pdf)
    - Screenshot: ![fig4](/fig4.jpg)