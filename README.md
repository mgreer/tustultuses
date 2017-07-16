# tustultuses
Graphing the influence of real journalism

Phase 1: Real or Fake Provider
==========
* Curate a list of 100 real journalists
* Build an API to query against their name for real/unknown

Phase 2: Real or Fake Headlines
==========
* Build a tool to crawl top news headlines (on Twitter? Google News?) and mark them real/unknown
  * Glue headlines together about the same subject (using Google News API?)
  * Search for bylines in all, rank headline based on presence of solid/fake reporters
* Extend API to answer queries against headlines

Phase 3: Real or Fake Rumors
==========
* Extend crawl to blogs, Twitter, and other news distribution channels
* Rank distributors of news based on their real/fake ratio of shared headlines
* Extend API to answer queries on these sources

Phase 4: Realish or Fakish
==========
* Rework core ranking of journalists to a scale, using expert panel scoring them on professional reputation
* Build feedback loop to re-score news creators based on their success at providing truth
  * Hard to do, but first thought is to see who else reported the same news in our list and let that news cohort weigt them up/down 
* Extend list of journalists/news creators
