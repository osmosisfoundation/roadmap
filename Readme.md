### OsMoSiS Development Roadmap

This is the first cut at the maintenance and development roadmap for various open source tools in M&S

The roadmap is only intended to provide a higher level picture of the upcoming activities and potential target timelines.

For more details on each package's tooling and features visit the package repository's issues/milestones.

Please contribute to this roadmap by providing feedback via the issues page of this repository, or alternatively submit a pull-request

___This topics below provide an overall picture of the initial goals. This is not the final roadmap___

#### New Projects

* Non-compartmental analysis (NCA) toolset

There are many existing r-packages and a plethora of r-scripts floating around the community to perform NCA.
This project will aim to bring together the various stakeholders interested in contributing to the development of
a fast and flexible package to facilitate NCA analysis both via the command line and via a GUI.

* ggplot version of Xpose(4)

Xpose is the one the most popular post-processing tool for population modeling that utilizes the lattice package for plotting.
It has been community tested for many years and has excellent documentation. In recent times, with the increasing popularity of
ggplot, there has been a push to use this a plotting tool as it provides a lot of flexibility and is easy to learn. This project
requires a significant re-write of the plotting functions, and perhaps the data object generated.

#### Maintenance Projects

There are many existing open source packages that require maintenance. Most authors are responsible for their packages, but
osmosis can provide community support for maintenance/improvement of the existing packages

#### Documentation Projects

Many of the open source packages require good documentation. Lack of such documentation has become a barrier to entry for new
comers and experienced users. Osmosis will identify the packages that are popular in the community but require better documentation.
Guidelines on documentation practices will be developed as a part of the initial efforts that authors can use..

#### Educational Projects
This will be one of the major projects of osmosis going forward. Develop/improve/maintain educational material for the community, by the community
