# timex
An ontology that extends the W3C "time" ontology (https://www.w3.org/2006/time) to integrate time intervals and time points.

Also see https://www.w3.org/TR/owl-time/

"timex" is based on the paper (see docs folder):
Alfred J. Reich.  "Intervals, Points, and Branching Time.  In S. D. Goodwin and H. J. Hamilton, editors, Proceedings of the TIME-94 International Workshop on Temporal Reasoning , pages 121–133, Regina, SK, Canada, 1994. University of Regina.
http://www2.cs.uregina.ca/~temporal/time94/time-94-papers.html

The format of the file, timex.ttl, is "turtle" as described here:
https://www.w3.org/TR/turtle/

In the docs folder, the file <b>"reich-ascii-tbls.txt"</b> includes four transitivity tables; one from the paper by J.F. Allen mentioned in the paper by A.J. Reich, and three from the paper by A.J. Reich:
* Interval Transitivity Table (Allen)  <b><-- W3C Time describes the 13 relations here</b>
* Interval & Point Transitivity Table (Reich)  <b><-- <i>timex.ttl</i> describes how this connects to W3C Time</b>
* Right Branching Interval & Point Transitivity Table (Reich)
* Left Branching Interval & Point Transitivity Table (Reich
