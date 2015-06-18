Here I am going to see to what degree I can identify differential splicing events that occur upon acute heat stress with the ultimate goal of determing if there is a relationship with differentiall splicing and DMLs.  [As the Tophat suite was used for RNA-seq](http://onsnetwork.org/halfshell/2015/01/08/rna-seq-tophat-via-iplant/), I will start exploring the `cuffdiff` output.  Note all output from `cuffdiff` can be [found here](http://owl.fish.washington.edu/halfshell/index.php?dir=BS-heat%2FCuffdiff2_heat-b-2014-12-20-22-27-15.4%2F). 

---

Based on the very nice documentation at <http://cole-trapnell-lab.github.io/cufflinks/cuffdiff/> the first place I would look would be `splicing.diff`.  

<img src="http://eagle.fish.washington.edu/cnidarian/skitch/Cufflinks_1AD2D9F7.png" alt="Cufflinks_1AD2D9F7.png"/>

Having a gander at this file, there are in fact some features that appear to be significant. To make myself feel better about what I am looking at I will visualize in IGV. 

<img src="http://eagle.fish.washington.edu/cnidarian/skitch/Screenshot_4_6_15__8_15_AM_1AD2DAAA.png" alt="Screenshot_4_6_15__8_15_AM_1AD2DAAA.png"/>

----
If my notebook holds up I should be able to refer to [this post](http://onsnetwork.org/halfshell/2015/02/26/heating-up-the-beds/) (found via IGV tag) to recreate...

<img src="http://eagle.fish.washington.edu/cnidarian/skitch/igv___half-shell_1AD2DBDC.png" alt="igv___half-shell_1AD2DBDC.png"/>

Once IGV is open I hope to simply paste locus field (ie `scaffold1391:350297-393525` into search bar. Actually there is some [fancy formulas that would allow me to directly linkout from Excel](https://www.broadinstitute.org/software/igv/ControlIGV).

----

<img src="http://eagle.fish.washington.edu/cnidarian/skitch/splicing_diff_1AD2DFE8.png" alt="splicing_diff_1AD2DFE8.png"/>

---

<img src="http://eagle.fish.washington.edu/cnidarian/skitch/splicing_diff_and_IGV_and_Fibrocystin-L_-_Google_Search_and_splicing_diff_1AD2E02E.png" alt="splicing_diff_and_IGV_and_Fibrocystin-L_-_Google_Search_and_splicing_diff_1AD2E02E.png"/>

---

<img src="http://eagle.fish.washington.edu/cnidarian/skitch/splicing_diff_and_IGV_and_Fibrocystin-L_-_Google_Search_and_splicing_diff_1AD2E085.png" alt="splicing_diff_and_IGV_and_Fibrocystin-L_-_Google_Search_and_splicing_diff_1AD2E085.png"/>

---

<img src="http://eagle.fish.washington.edu/cnidarian/skitch/IGV_1AD2E0F6.png" alt="IGV_1AD2E0F6.png"/>

---

<img src="http://eagle.fish.washington.edu/cnidarian/skitch/IGV_1AD2E13E.png" alt="IGV_1AD2E13E.png"/>

---

<img src="http://eagle.fish.washington.edu/cnidarian/skitch/IGV_1AD2E1AC.png" alt="IGV_1AD2E1AC.png"/>

---

<img src="http://eagle.fish.washington.edu/cnidarian/skitch/IGV_1AD2E1F6.png" alt="IGV_1AD2E1F6.png"/>

----

<img src="http://eagle.fish.washington.edu/cnidarian/skitch/IGV_1AD2E22E.png" alt="IGV_1AD2E22E.png"/>

---

<img src="http://eagle.fish.washington.edu/cnidarian/skitch/IGV_1AD2E26F.png" alt="IGV_1AD2E26F.png"/>

---

<img src="http://eagle.fish.washington.edu/cnidarian/skitch/IGV_1AD2E358.png" alt="IGV_1AD2E358.png"/>

---

<img src="http://eagle.fish.washington.edu/cnidarian/skitch/IGV_1AD2E527.png" alt="IGV_1AD2E527.png"/>

---

So there was a good chunk and cut and pastes, some things to ponder, look at, and certainly come back to. 

Some closing help. 
That IGV session file is @ `/Users/sr320/data-genomic/tentacle/igv_session_041615.xml`
and 
Those significant splice locales

```
scaffold1391:350297-393525
```
