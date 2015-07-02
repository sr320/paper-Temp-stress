#results-array

In direct comparison of methylation for an individual oyster prior to and following heat shock approximately 10k differentially methylated features were identified as defined by >/= 1.8 fold difference.  For all oysters a majority of the features (individual probe regions) were hypomethylated. Specifically, for oysters #2, #4, and #6 the number of hypomethylated features was 7224, 6560, and 7645, respectively.  Genome feature tracks (bedGraph) for each oysters are available:  _genome-feature-tracks/2014.07.02.2M_sig.bedGraph, genome-feature-tracks/2014.07.02.4M_sig.bedGraph, genome-feature-tracks/2014.07.02.6M_sig.bedGraph_.   

![](./figures/igv-dmr-1.png)

![](https://www.authorea.com/users/3858/articles/18000/master/file/figures/igv-dmr-1.png)

**Figure** - Screenshot of genome feature tracks showing differential methylation at individual probe level.


When only features were considered where at least 3 adjacent probes were also differentially methylated in the same direction the number of features (adjacent probe region merged when within 100bp) for oysters #2, #4, and #6 was 112, 58, and 62, respectively.  A majority of these features were hypomethylated (108, 48, and 53, respectively). Genome feature tracks (bedGraph) for each oysters are available in _genome-feature-tracks_ directory: 
```  
2M_3plusmerge_Hyper.bed2M_3plusmerge_Hypo.bed4M_3plusmerge_Hyper.bed4M_3plusmerge_Hypo.bed6M_3plusmerge_Hyper.bed6M_3plusmerge_Hypo.bed
```

![](./figures/igv-dmr-2.png)
![](https://www.authorea.com/users/3858/articles/18000/master/file/figures/igv-dmr-2.png)

**Figure 2** Screenshot from IGV showing deaeration of merge tracks

**Table** - Number of features

Oyster | Hypo-probes | Hyper-probes | Hypo-3plus-merged | Hyper-3plus-merged
--- | --- | --- | --- | ---
2 | 7224 | 2803 | 108 | 4
4 | 6560 | 3587 | 48 | 10
6 | 7645 | 4044 | 53 | 9


In order to examine regions that were differentially methylated multiple oysters, feature were identified where there was at least three adjacent features that were present in at least two individuals. The specific locations are

```
scaffold481 576986  578532  -3
scaffold247 141885  142442  -3
scaffold1518    212680  213736  -3
scaffold853 46186   46496   -2
scaffold406 419330  419384  -2
scaffold406 419005  419060  -2
scaffold406 418360  418767  -2
scaffold394 555813  556224  -2
scaffold247 144031  144583  -2
scaffold242 75918   76344   -2
scaffold142 656144  656735  -2
scaffold12  243960  244376  -2
scaffold257 1235165 1235481 +2
```

With twelve features hypomethylated and one feature hypermethylated.

Going down the list, _scaffold418_576986_ is a feature that overlaps gene EKC36328, [_Bromodomain-containing protein 8_](http://www.uniprot.org/uniprot/K1QRE8). Specifically the location is in the intron between exon 18 and 19 (total of 20 exons). This gene is differentially expressed, that is expressed at an elevated level following heat shock.

"The precise function of the domain is unclear, but it may be involved in protein-protein interactions and may play a role in assembly or activity of multi-component complexes involved in transcriptional activation [PMID: 7580139]."


![scaffold418_576986](./figures/scaffold481_576986.png)

---
Another DMR that is consistent across oysters is located within the intron of [_Homeobox protein LOX2_](http://www.uniprot.org/uniprot/K1RXD0). Homeobox are transcription factors often associated with developmental processes.


![scaffold247_141885](./figures/scaffold247_141885.png)

---

Significant hypomethylation is also present within the intron of [Tenascin](http://www.uniprot.org/uniprot/K1PZ30), a glycoprotein expressed in the extracellular matrix during stress.

![scaffold1518_212680](./figures/scaffold1518_212680.png)  