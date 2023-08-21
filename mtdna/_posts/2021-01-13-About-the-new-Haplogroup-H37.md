---
layout: post
title: "About the new Haplogroup H37"
author: Hank de Wit
published: true
category: dna
yfullm: https://www.yfull.com/mtree/H37/
yfull: https://www.yfull.com/orderm/
FTDNA: https://www.familytreedna.com/products/mt-dna
FTDNAm: https://www.familytreedna.com/public/mt-dna-haplotree/H
phylotree: https://www.phylotree.org/
YSEQmtComplete: https://www.yseq.net/product_info.php?cPath=28&products_id=38291&osCsid=46f722a4ee1facc677c4c4839f0131bb
twentythreeandme: https://customercare.23andme.com/hc/en-us/articles/212880257-Maternal-Haplogroups-mtDNA
---

Back in 2018 I obtained a full-sequence mtDNA test with [FTDNA]( {{ FTDNAm }} ). I was a little disappointed that FTDNA just assigned me to the Haplogroup **H**. I was naively expecting a few sub-branches, something complicated looking like **X5a1b7**. But no, it was just **H**.

However, under the Extra Mutations section the report displayed, 

    309.1C, 315.1C, T319C, 522.1A, 522.2C, A3505G, A13748G, C16222T

What did this mean? I was determined to find out. 

I contacted as many of my matches as I could and obtained their list of Extra Mutations as well. In addition a few of my matches assisted by providing me with matches that they had and which I didn't. This was necessary as FTDNA only provide you with matches which have up to three genetic differences, which is rather meagre. I ended up with some thirty samples to compare. I also trawled through the [Genbank](https://www.ncbi.nlm.nih.gov/genbank/) looking for samples assigned to **H** but who also shared these mutations.

Collating all the mutations I was able to determine which mutations were common to all, and thus the oldest mutations, and also some common groupings for the later mutations. I was able to construct a branching pattern for the mutations.

When determining the branching I ignored the mutations **309.1C**, **315.1C**, **522.1A**, **522.2C**. These are insertions in the hypervariable part of the chromosome and can change frequently in either direction (that is inserions and deletions). The remaining useful mutations are then, 

    T319C, A3505G, A13748G, C16222T

The mutation C16222T is also quite common, and needs to be considered carefully. The most basic branching I came up with was as follows:

* A3505G
  * A13748G (C16222T)
     * T319C

Of course more mutations amongst my matches showed the full extent of branching which I will get to. 

However in this basic structure we see that **A3505G** was common to all in my list and had to be the oldest mutation. The next two mutations were actually common to all my FTDNA matches, but some Genbank matches did not have them. The **C16222T** mutation is in brackets, because sometimes it was missing, even in those with the youngest mutation **T319C**. 

I eventually uploaded my [FASTA](https://en.wikipedia.org/wiki/FASTA_format) file to YFull and they also identified the same mutations as the start of a new branch under **H**. They named it **H37** and that is the name I shall use from now on. The mutation **A3505G** is the mutation that defines **H37**. My particular sample is placed under the sub-clade **H37b1**, defined by **T319C**. This Haplogroup is obviously not yet in the current [Phylotree]( {{ page.phylotree }} ).

The YFull version of **H37** is [ {{page.yfullm}} ]( {{ page.yfullm }} )

I translated my version of the tree to a YFull like format. It contains all the samples available to me, which is far greater than YFull.

My version of **H37** is [ {{site.url}}/h37/h37_complex.html](/h37/h37_complex.html)

Our trees are remarkably similar, though we differ a little in the definition of the branch **H37a**.

There are some difficulties in assigning mtDNA branches particularly if they are based on only a single mutation. The entire **H37** tree is based on just the one mutation **A3505G**. It has two branches, **H37a** and **H37b**. There is no guarantee that the **A3505G** in **H37a** was the same **A3505G** in **H37b**. The same mutation may have occurred independently on two separate lines of **H**. The modern samples of **H37a** are Armenian, while those in **H37b** are from many regions in Europe. Are they separate origins or do they hint at an ancient connection. At this stage I'm preferring the simpler, common origin, theory and see where that takes us.

In a later post I'll discuss some of the features identified in the branches.