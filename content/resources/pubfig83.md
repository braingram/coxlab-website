---
title:      PubFig83 Face Identification Data Set
short_name:     pubfig83
type:       dataset
url:        http://coxlab.org/resources/pubfig83_first_draft.tar.gz
related_publications:   ["2011_pinto_cvpr", "2011_pinto_fg", "2009_pinto_cvpr"]
banner:                 'probe_banner.jpg'
highlight_picture:      neuron_220x160.jpg
order:                  0
---

<% content_for :summary do %>
Blah
<% end %>

**PubFig83** is a curated subset of the [PubFig face dataset](http://www.cs.columbia.edu/CAVE/databases/pubfig/) from Columbia University (originally descirbed in [Kumar et al., ICCV 2009](http://www.cs.columbia.edu/CAVE/projects/faceverification/).  PubFig83 was created by Zak Stone, and is described in [Pinto et al., CVPRW 2011](http://www.coxlab.org/publications/2011_pinto_cvpr_ws/).

While PubFig was originally designed to support "verification-mode" face recognition experiments (i.e. "are these two face images of the same person?"), there are sufficient images in the larger set to construct a smaller "identification-mode" test set.  In this scenario, rather than asking whether two faces are the same or different, we ask the face recognition system to identify which of a set of 83 previously-seen faces a new example face is.  Up to 100 previously labelled examples are available for each of the 83 individuals included in the set.  Such identification-mode tests are particularly interesting in the age of Facebook, where large quantities of collaboratively labeled face images are routinely available.

The **PubFig83** provides 100 images each of 83 celebrities. Effort has been made to remove near duplicates (the original PubFig set, by its large-scale nature contains quite a few), and the images have been curated to avoid dead links.  That said, the set does contain a small number of labeling errors, where individuals have been labeled with the incorrect name or where the OpenCV detection process resulted in an erroneous crop of the face.  For consistency with previous literature, these images have been left in, though known error are included in the readme.txt file.