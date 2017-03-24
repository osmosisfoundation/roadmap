## OsMoSiS Development Roadmap

This roadmap is only intended to provide a higher level picture of the upcoming activities and potential target timelines.

For more details on each package's tooling and features visit the package repository's issues/milestones.

Please contribute to this roadmap by providing feedback via the issues page of this repository, or alternatively submit a pull-request

___The primary goal of OsMoSiS is to limit redundancy in tool development and lower the technical barrier to entry in pharm sciences___

### New Projects

#### _Non-compartmental analysis (NCA) toolset_

There are many existing r-packages and a plethora of r-scripts floating around the community to perform NCA.
This project will aim to bring together the various stakeholders interested in contributing to the development of a fast and flexible package to facilitate NCA analysis both via the command line and via a GUI. By collaborating with experts in the domains where NCA is most utilized, the toolset will be extend to perform other critical functions such as:

1. Linear mixed effect modeling for BE analysis
2. IVIVC approaches
3. ...

#### _ggplot version of Xpose(4)_

Xpose is the one the most popular post-processing tool for population modeling that utilizes the lattice package for plotting.
It has been community tested for many years and has excellent documentation. In recent times, with the increasing popularity of
ggplot, there has been a push to use this a plotting tool as it provides a lot of flexibility and is easy to learn. This project
requires a significant re-write of the plotting functions, and perhaps the data object generated.

#### _Open-Source Estimation Engine for Non-linear mixed effect modeling_

One of the biggest barriers to entry for newcomers to pharmacometrics and quantitative sciences in general is the lack of a open, community driven free software that is readily available to a larger community. OsMoSiS is teaming up with experts from around the world to develop a fast open source alternative to the commercial tools available in the market.

### Maintenance Projects

There are many existing open source packages that require maintenance. Most authors are responsible for their packages, but osmosis can provide community support for maintenance/improvement of the existing packages

### Documentation Projects

There is tremendous research debt in our community. Some of the open source tools available in our community are designed to perform cutting edge analysis, but they debt comes in the form of poor documentation/communication of methods and examples on how to use these tools. Lack of such documentation has become a barrier to entry for newcomers and experienced users. Osmosis will identify the packages that are popular in the community but require better documentation.
Guidelines on documentation practices will be developed as a part of the initial efforts that authors can use. Such guidelines will be provided via the [process repository wiki](https://github.com/osmosisfoundation/process).

### Educational Projects
This will be one of the major projects of osmosis going forward. Develop/improve/maintain educational material for the community, by the community.

#### _Clarity_

OsMoSis will design an e-learning platform that will facilitate community members to contribute their learning effectively via cutting edge interactive tools and videos. ***Clarity*** has three goals:

1. Provide a state-of-the-art hub for knowledge propagation in core areas of programming statistical concepts and clinical pharmacology
2. Provide tooling and support for creation and dissemination of video, blog, and interactive content
3. Provide a medium for discussion and interaction in the community directly tied to technical and conceptual content

#### _Code Incubator_

OsMoSiS will provide a home for people have developed code for their own work and think it might be useful out in the open, but the code needs some polish and they don't know how to build a package or otherwise get it into the community.
