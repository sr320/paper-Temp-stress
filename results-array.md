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


In order to examine regions that were differentially methylated across all three oysters, features were identified where there were at least 3 adjacent probes with significantly differentially methylated. A total of 111 features were identified as hypomethylated and 54 features as hypermethylated when differentially methylated probe with 100bp were merged.  



  