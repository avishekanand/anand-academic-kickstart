---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Information Retrieval"
summary: ""
authors: []
tags: []
categories: []
date: 2020-07-19T11:18:02+02:00

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
Web archives such as Internet Archive and Internet Memory have been involved in periodically archiving websites for over 17 years with collection sizes amounting to several Terabytes of data. Similarly, many news companies such as The New York Times, Wall Street Journal, The Times archive both their published digital content as well as digitize non-digital articles. In spite of the progresses in preservation, search capabilities over archives have been limited. A naive adaptation of the indexing infrastructure used for text retrieval is expensive and does not capture the temporal dimension inherent to such archives. To this end, we presented a novel index organization that process queries with almost zero increase in index size. We further proposed novel query optimization techniques and phrase indexing techniques to efficiently support a wider ranger of queries.


While searching for articles published over time, a key preference is to retrieve documents which cover the important aspects from important points in time which is different from standard search behavior. To support such a search strategy, we introduce the notion of a Historical Query Intent to explicitly model a historian's search task and define an aspect-time diversification problem over news archives. We present novel algorithms and build a search system called HistDiv over 20 years of New York Times, that explicitly models the aspects and important time windows based on a historian's information seeking behavior. 


[1] http://www.archive.org
[2] http://www.internetmemory.org
[3] http://www.l3s.de/~anand/histdiv/
[4]
