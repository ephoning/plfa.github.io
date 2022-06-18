---
title     : Table of Contents
permalink : /
next      : /Dedication/
---

This book is an introduction to programming language theory using the proof
assistant Agda.

Comments on all matters---organisation, material to add, material to remove,
parts that require better explanation, good exercises, errors, and typos---are
welcome.  The book repository is on [GitHub]. Pull requests are encouraged.
There is a private repository of answers to selected questions on github. Please
contact one of the authors if you would like to access it.


$for(toc.part)$
## $toc.part.title$
$for(toc.part.chapter)$
$if(toc.part.chapter.titlerunning)$
  * [$toc.part.chapter.titlerunning$]($toc.part.chapter.url$): $toc.part.chapter.subtitle$
$else$
  * [$toc.part.chapter.title$]($toc.part.chapter.url$)
$endif$
$endfor$
$endfor$

## Related


<!-- NOTE: The Mailing Lists are Deprecated -->
<!--
### Mailing lists
  * [plfa-interest@inf.ed.ac.uk](https://lists.inf.ed.ac.uk/mailman/listinfo/plfa-interest): <br />
    A mailing list for users of the book. <br />
    This is the place to ask and answer questions, or comment on the content of the book.
  * [plfa-dev@inf.ed.ac.uk](https://lists.inf.ed.ac.uk/mailman/listinfo/plfa-dev): <br />
    A mailing list for contributors. <br />
    This is the place to discuss changes and new additions to the book in excruciating detail.
-->

### Courses taught from the textbook

#### 2022
  * [Andrej Bauer, University of Ljubljana][UL-2022]
  * [Peter Thiemann, Albert-Ludwigs University][Freiburg-2022]

#### 2021
  * Favonia, University of Minnesota
    <!-- The course website is not public. -->

#### 2020
  * [William Cook, University of Texas][UT-2020]
  * [Jeremy Siek, Indiana University][IU-2020]
  * [Maria Emilia Maietti and Ingo Blechschmidt, Università di Padova][Padova-2020]
  * [John Maraist, University of Wisconsin-La Crosse][UWL-2020]
  * [Ugo de'Liguoro, Università di Torino][Torino-2020]

#### 2019
  * [Dan Ghica, University of Birmingham][BHAM-2019]
  * [Adrian King, San Francisco Types, Theorems, and Programming Languages Meetup][SFPL-Meetup-2020]
  * [Prabhakar Ragde, University of Waterloo][UW-2019]
  * [Philip Wadler, University of Edinburgh][TSPL-2019]
  * [Philip Wadler, Pontifícia Universidade Católica do Rio de Janeiro][PUC-2019]

#### 2018
  * [Philip Wadler, University of Edinburgh][TSPL-2018]
  * [David Darais, University of Vermont][UVM-2018]
  * John Leo, Google Seattle

Please tell us of others!

[GitHub]: https://github.com/plfa/plfa.github.io/
[SBMF]: https://homepages.inf.ed.ac.uk/wadler/topics/agda.html#sbmf
[SCP]: https://homepages.inf.ed.ac.uk/wadler/topics/agda.html#scf
[NextJournal]: https://nextjournal.com/plfa/ToC
[EUSA-2020]: https://www.eusa.ed.ac.uk/representation/campaigns/teachingawards2020/
[TSPL-2018]: https://plfa.github.io/19.08/TSPL/2018/
[UVM-2018]: https://web.archive.org/web/20190324115921/https://david.darais.com/courses/fa2018-cs295A/
[PUC-2019]: https://plfa.github.io/20.07/PUC/2019/
[TSPL-2019]: https://plfa.github.io/20.07/TSPL/2019/
[IU-2020]: https://jsiek.github.io/B522-PL-Foundations/
[SFPL-Meetup-2020]: https://meet.meetup.com/wf/click?upn=ZDzXt-2B-2BZmzYir6Bq5X7vEQ2iNYdgjN9-2FU9nWKp99AU8rZjrncUsSYODqOGn6kV-2BqW71oirCo-2Bk8O1q2FtDFhYZR-2B737CPhNWBjt58LuSRC-2BWTj61VZCHquysW8z7dVtQWxB5Sorl3chjZLDptP70L7aBZL14FTERnKJcRQdrMtc-3D_IqHN4t3hH47BvE1Cz0BakIxV4odHudhr6IVs-2Fzslmv-2FBuORsh-2FwQmOxMBdyMHsSBndQDQmt47hobqsLp-2Bm04Y9LwgV66MGyucsd0I9EgDEUB-2FjzdtSgRv-2Fxng8Pgsa3AZIEYILOhLpQ5ige5VFYTEHVN1pEqnujCHovmTxJkqAK9H-2BIL15-2FPxx97RfHcz7M30YNyqp6TOYfgTxyUHc6lufYKFA75Y7MV6MeDJMxw9-2FYUxR6CEjdoagQBmaGkBVzN
[UW-2019]: https://cs.uwaterloo.ca/~plragde/842/
[UT-2020]: https://www.cs.utexas.edu/~wcook/Courses/386L/Sp2020-GradPL.pdf
[BHAM-2019]: https://www.cs.bham.ac.uk/internal/modules/2019/06-26943/
[UWL-2020]: https://github.com/jphmrst/PLC/tree/fall2020
[Torino-2020]: https://laurea.educ.di.unito.it/index.php/offerta-formativa/insegnamenti/elenco-completo/elenco-completo/scheda-insegnamento?cod=MFN0633&codA=&year=2020&orienta=NSE
[Padova-2020]: https://www.math.unipd.it/~maietti/typ21.html
[UL-2022]: https://www.andrej.com/zapiski/ISRM-LOGRAC-2022/00-introduction.html
[Freiburg-2022]: https://proglang.informatik.uni-freiburg.de/teaching/proglang/2022ss/