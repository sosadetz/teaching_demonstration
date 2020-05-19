## Teaching Demonstration Materials - Stephen Osadetz
## John Cabot University - May 21, 2020

This repository contains a few examples of the materials I use to teach students how to code. To start the workshop, simply click on the "Launch Binder" button below. This will open your own Jupyter Notebook, that you can use to study ngrams across I number of corpora.

<b>CLICK HERE:</b>

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sosadetz/teaching_demonstration/master)

*(NOTE: The file itself is called teaching_demonstration.ipynb. If you click on that file in the git, you'll pull up an image of the file itself, and it won't be interactive!)*

You can imagine that this lesson would fall somewhere in the middle of a course on the digital humanities for students from across your university. This lesson, which addresses the use of ngrams, would occur on the third day of a unit on simple counting techniques. In general, you'll find that although the Jupyter Notebook I've provided is interactive, it's somewhat less intensely interactive than the problem sets that I would give students, and which would also be offered through Jupyter Notebooks. I'm only using these Binder-generated notebooks for this remote teaching demonstration. Normally, I would ask students to run Jupyter Lab directly from their own devices.

During the teaching demonstration, it will be helpful to have a browser tab open with the main Jupyter Notebook, as well as a second tab open to https://books.google.com/ngrams. Keep the Microsoft Teams application open, and if you run into technical difficulty, you can follow along with my screenshare of the teaching demonstration. I strongly recommend you use a laptop or desktop machine for this demonstration, and that you do not try to follow along on a mobile device.

I'll keep this git repo available for a few days after my demonstration, along with the associated Binder version of the Jupyter Notebook. This will allow you to come back, reopen the notebook, and tinker with the code yourself. Please don't hesitate to send me an e-mail if you have any questions. I can be reached at osadetz@fas.harvard.edu.

This lesson's code uses Python 3.7 with the nltk, matplotlib, os, glob, and collections modules. I'll also make use of Jupyter Lab, Binder, Tableau Public, and of course Google's Ngram Viewer.

At the beginning of the lesson, I'll make reference to the excellent article <a href='https://litlab.stanford.edu/LiteraryLabPamphlet11.pdf'>"Canon/Archive: Large-scale Dynamtics in the Literary Field"</a> by Mark Algee-Hewitt et al. Refer to page 6 for his discussion of the graph that inspired this lesson, but note that, rather than ngram variance, he calls the crucial measure "redundancy," and as a result, his graph is flipped.

The main graph we will discuss can be found here: https://public.tableau.com/profile/stephen8554#!/vizhome/collected_corpora_simple_counting_results/Sheet1?publish=yes. I recommend you use the button in the bottom-right corner of the visualization to make it full-screen, as this will help to distinguish among the data points.
