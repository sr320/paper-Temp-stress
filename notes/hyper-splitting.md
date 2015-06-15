With a good two weeks hands-off of the the array data it took a bit of time to get back on target.  Following up from last time (per my instruction) I began to delve into how the hypomethylated versus hypermethylated DMLs played out with respect to genomic features. Still not convinced I am convoluting the analysis I went [through the motions](http://nbviewer.ipython.org/github/sr320/paper-Temp-stress/blob/master/ipynb/Array-feature-overlap-05.ipynb).     ~[bu-html](http://goo.gl/EuCIIN).  ~[excel](https://github.com/sr320/paper-Temp-stress/blob/master/ipynb/analyses/hypo-hyper-overlap.xlsx) :(

---

As a reminder most of the DMLs are Hypos. The first thing I did was split the `*.sig.bedgraph` files to `hypo` and `hyper`. These live in `tenacle` ie `/Users/sr320/data-genomic/tentacle/2014.07.02.2M_sig.hypo.bedGraph`.  

---

Looking at DEGs, there really did not seem to be a pattern (confirm with stats). 

I considered the overlap based on total number of DMLs  (hypo and hyper separately).

<img src="http://eagle.fish.washington.edu/cnidarian/skitch/Screenshot_4_3_15__8_52_AM_1ACEEED5.png" alt="Screenshot_4_3_15__8_52_AM_1ACEEED5.png"/>

<img src="http://eagle.fish.washington.edu/cnidarian/skitch/Array-feature-overlap-05_1ACEEE8E.png" alt="Array-feature-overlap-05_1ACEEE8E.png"/> 

---

Interesting and maybe not unexpected? was that there is a clear pattern based on gene function. 
<img src="http://eagle.fish.washington.edu/cnidarian/skitch/Screenshot_4_3_15__8_54_AM_1ACEEF2F.png" alt="Screenshot_4_3_15__8_54_AM_1ACEEF2F.png"/>

When splitting DMLs, a housekeeping genes were hyper more? hypermethylated, whereas environmental response genes were (on percentage basis) more likely to be hypomethylated.  That being said it seems that the fact that both were more hypomethyated when you just look at the #s (recalling that overall there was more DMLs that were hypo v hyper. 

--

Slow story short... this is becoming a descriptive paper with clean RNA-seq data but a loss to how the array data relates.  Hindsigting there are serval hypotheses.

* Stress demethylates response genes to allow for spuriousness
* Stress regulates gene expression via promoter methylation
* Stress randomly alters methylation - to add noise
* Methylation status is not impacted directly by stress but rather a side effect of gene activity. 

One place I could go next is to identify gene products that significantly altered the number of isoforms post stress? This would be interesting regardless, though not readily evident how it would work .


