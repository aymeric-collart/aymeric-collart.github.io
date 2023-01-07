---
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---


<iframe src="/files/CV_AymericCollart_October2022.pdf" width="100%" height="500" frameborder="no" border="0" marginwidth="0" marginheight="0"></iframe>
The PDF copy of my CV can be downloaded [here](/files/CV_AymericCollart_October2022.pdf).



-
	var timeline = [
	{
		title: "Title A",
		detail: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi."
	}, {
		title: "Title B",
		detail: " Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi."
	}, {
		title: "Title C",
		detail: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi."
	}, {
		title: "Title D",
		detail: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi."
	}, {
		title: "Title D",
		detail: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi."
	}
	];
	
mixin timeline(entry)
	dl.timeline--entry
		dt.timeline--entry__title= entry.title
		dd.timeline--entry__detail= entry.detail

.wrapper
	h1 Timeline Created With CSS Grid

	.timeline
		for entry in timeline
			+timeline(entry)