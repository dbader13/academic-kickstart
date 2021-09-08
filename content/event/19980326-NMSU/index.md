---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "NMSU Seminar: Designing High Performance Algorithms for Clusters of SMPs"
event: "Deparmtnet of Computer Science, New Mexico State University"
event_url:
location:
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "With the cost of commercial off-the-shelf (COTS) high performance interconnects falling and the respective performance of microprocessors increasing, workstation clusters have become an attractive computing platform offering potentially a superior cost effective performance. In recent years, we have seen the maturing of Symmetric Multiprocessors (SMPs) technology, and the heavy reliance upon SMPs as the work-intensive servers for client/server applications. There are already several examples of clusters of SMPs, such as clusters of DEC AlphaServer, SGI Origin, Sun Ultra HPC machines, and the IBM SP system with SMP 'High' nodes; moreover, the Department of Energy's Accelerated Strategic Computing Initiative (ASCI) program relies on the success of computational clusters such as Option White, a 512-node IBM SP-2 with 16-way SMP nodes. With the acceptance of message passing standards such as MPI, it has become easier to design portable parallel algorithms making use of these primitives. However, the focus of MPI is a standard for communicating between shared-nothing processors, and although MPI programs run on clusters of SMPs, this is not necessarily the optimal methodology for these platforms.

In this talk, we will describe a hybrid methodology for programming clusters of SMP nodes which aids in the design and implementation of efficient high performance parallel algorithms. We call this approach SIMPLE, referring to the joining of SMP and MPI-like message passing paradisms and the _simple_ programming approach. Our complexity model captures the performance of shared memory access on SMP nodes combined with message passing between the nodes. We illustrate the power of our methodology by presenting experimental results for sorting integers, two-dimensional fast Fourier transforms (FFT) and constraint-satisfied searching."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 1998-03-26T10:30:00-06:00
date_end: 1998-03-26T11:30:00-06:00
all_day: false

# Schedule page publish date (NOT event date).
publishDate: 2021-09-07T10:50:19-04:00

authors: []
tags: []

# Is this a featured event? (true/false)
featured: false

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

# Optional filename of your slides within your event's folder or a URL.
url_slides:

url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this event with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

{{<figure src="flyer.jpg">}}

## Biography ##

**David A. Bader** holds a Ph.D. in Electrical Engineering from the University of Maryland, College Park. He is currently an Assistant Professor in the Electrical & Computer Engineering Department at the University of New Mexico, Albuquerque. David completed his B.S. (with high honors) in computer engineering and M.S.E.E. degrees from Lehigh University, Bethlehem, PA, in 1990 and 1991, respectively. In support of his doctoral research, David received the presitigous NASA Graduate Student Researcher Fellowship from Goddard Space Flight Center. As an NSF CISE Research Associate in Experimental Computer Science with the Institute for Advanced Computer Studies at the University of Maryland (UMIACS) from 1996-1997, David worked closely with Earth scientists at NASA/GSFC and University of Marylands's Geography Department to develop a high performance system for on-demand queries of terascale remotely-sensed Earth science data, such as 4km AVHRR global coverage, used for monitoring long-term, global studies of the Earth.

David has published numerous peer-reviewed journal articles in *Journal of Parallel & Distributed Computing*, *ACM Journal of Experimental Algorithmics*, *IEEE Transactions on Image Processing*, and *Journal of Supercomputing*, as well as high performance computing conference papers in the International Parallel Processing Symposium (IPPS) and the Symposium for Praallel Algorithms and Architectures (SPAA). His research interests are in the general area of high performance computing wiht particular emphasis on clustered systems interconnected by high-speed networks, experimental parallel algorithms for data communication, combinatorial and image processing applications, and programming methodologies for clusters of SMP workstations. In addition to the on-demand, remotely-sensed Earth science query system, David has developed other portable high performance applications for image segmentation and classification, and software tools for programming clusters of SMP workstations.

He is a member of Sigma Xi, Eta Kappa Nu, Tau Beta Pi, Omicron Delta Kappa, IEEE and ACM.
