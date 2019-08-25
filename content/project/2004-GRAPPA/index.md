---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "GRAPPA: Genome Rearrangements Analysis under Parsimony and other Phylogenetic Algorithms"
summary: ""
authors: []
tags: []
categories: []
date: 2004-12-31T09:47:53-04:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Copyright (C) 2000-2004, The University of New Mexico and The University of Texas at Austin

This program is free software; you can redistribute it and/or modify it under the terms of the [GNU General Public License](http://www.gnu.org/copyleft/gpl.html) as published by the Free Software Foundation -- using version 2 (June 1991) of the License or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of or a link to the GNU General Public License along with this program; you can also write to the Free Software Foundation, Inc., 59 Temple Place - Suite 330, Boston, MA 02111-1307, USA.


GRAPPA is available as a gzipped tar file containing all source files needed to compile an executable version. Documentation for this early release is minimal (there is a README file and some online help). GRAPPA changes quickly, so be sure to grab the latest release.

GRAPPA was featured in Access, the magazine of the NCSA/Alliance in [Vol. 14 (1)](http://www.ncsa.uiuc.edu/News/Access/Stories/phylogeny/) (Spring 2001). It is discussed at some length in

* Moret, B.M.E., Wyman, S., Bader, D.A., Warnow, T., and Yan, M., "A new implementation and detailed study of breakpoint analysis," *Proc. 6th Pacific Symp. on Biocomputing (PSB 2001)*, Hawaii, World Scientific Pub. (2001), 583-594. [PS](psb1.ps)

Its linear-time computation of inversion distance is presented in

* Bader, D.A., Moret, B.M.E., and Yan, M., ``A linear-time algorithm for computing inversion distances between signed permutations with an experimental study,'' *Proc. 7th Workshop on Algorithms and Data Structures (WADS 01)*, Providence (2001), Lecture Notes in Computer Science **2125**, 365-376, Springer Verlag. Journal version appears in *J. Comput. Biol.* **8**, 5 (2001), 483-491. [PDF](jcb01.pdf)

The improvements due to better bounding and new search ordering (the layered method) are discussed in

* Moret, B.M.E., Tang, J., Wang, L.S., and Warnow, T., "Steps toward accurate reconstruction of phylogenies from gene-order data," to appear in *J. Comput. Syst. Sci.* (invited, special issue on computational biology), 2002. [PS](jcss.ps)

while the improvements achieved through the use of true inversion medians are documented in

* Moret, B.M.E., Siepel, A.C., Tang, J., and Liu, T., "Inversion medians outperform breakpoint medians in phylogeny reconstruction from gene-order data," *Proc. 2nd Int'l Workshop on Algorithms in Bioinformatics (WABI'02)*, Rome (2002), to appear in *Lecture Notes in Computer Science* **2452**, 2002. [PS](wabi02a.ps)

which also contains references to the works of A. Caprara and of A. Siepel, whose codes for the computation of true inversion medians are included in this release.
The latest release is

[GRAPPA-2.0](GRAPPA20.tar.gz)

from October 1, 2004.
Previous releases (1.6 and 1.03) are obsolete.

You may want to look at some [test data](testsets.tar.gz). 

<pre>
Authors (original):

    David A. Bader
    Electrical and Computer Engineering Department
    University of New Mexico
    Albuquerque, NM 87131
    +1.505.277.6724
    dbader@eece.unm.edu
    www.eece.unm.edu/~dbader

    Bernard M.E. Moret
    Department of Computer Science
    University of New Mexico
    Albuquerque, NM 87131
    +1.505.277.5699
    moret@cs.unm.edu
    www.cs.unm.edu/~moret

    Tandy Warnow
    Department of Computer Sciences
    University of Texas, Austin
    Austin, TX 78712
    +1.512.471.9724 
    tandy@cs.utexas.edu
    www.cs.utexas.edu/users/tandy/
     
    Stacia K Wyman
    Department of Computer Sciences
    University of Texas, Austin
    Austin, TX 78712
    +1.512.232.7432
    stacia@cs.utexas.edu
    www.cs.utexas.edu/users/stacia

    Mi Yan
    Electrical and Computer Engineering Department
    University of New Mexico
    Albuquerque, NM 87131
    +1.505.277.6185
    miyan@unm.edu
    www.ahpcc.unm.edu/~miyan/

Main contributors to version 1.6:

    Jijun Tang
    Department of Computer Science
    University of New Mexico
    Albuquerque, NM 87131
    jtang@cs.unm.edu

    Adam C. Siepel
    Department of Computer Science and Engineering
    University of California at Santa Cruz
    Santa Cruz, CA
    acs@cse.ucsc.edu

    Alberto Caprara
    DEIS
    Universitá di Bologna
    40136 Bologna, Italy
    acaprara@deis.unibo.it

Main contributor to version 2.0:

    Jijun Tang
    Department of Computer Science and Engineering
    University of South Carolina
    jtang@cs.unm.edu


Maintainers:

    Bernard M.E. Moret moret@cs.unm.edu and Jijun Tang jtang@cs.unm.edu
</pre>


https://www.cs.unm.edu/~moret/GRAPPA/
