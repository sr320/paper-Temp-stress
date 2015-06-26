Side track with tracks

Today working on our paper looking at [heat stress and DNA methylation](https://www.authorea.com/users/3858/articles/18000/_show_article) I dived deeper into the array data in the search for what should be called a DMR. 

As a refresher we have tracks from the core that have 1.8+ fold difference (_sig_) and complementary tracks where there are three adjacents (_3plusAdjacent_). I made tracks where I merged the latter into a single feature when [within 100bp of each other](http://onsnetwork.org/halfshell/2015/02/20/differential-methylation-in-the-kitchen/). 

In order to see if there is any consistency across oysters..  

```
#concatenated tracks
!cat \
/Volumes/web/halfshell/2015-05-comgenbro/2M_3plusmerge_Hypo.bed \
/Volumes/web/halfshell/2015-05-comgenbro/4M_3plusmerge_Hypo.bed \
/Volumes/web/halfshell/2015-05-comgenbro/6M_3plusmerge_Hypo.bed \
> /Users/sr320/git-repos/paper-Temp-stress/ipynb/analyses/mergHYPOcat.bed
```

![](http://eagle.fish.washington.edu/cnidarian/skitch/IGV_-_Session___Volumes_web_halfshell_2015-05-comgenbro_igv_session_xml_and_Array-multi-ind-features_1B3DA9BE.png)

```
#then using bedtools merge features (though first had to sort)
!bedtools sort -i /Users/sr320/git-repos/paper-Temp-stress/ipynb/analyses/mergHYPOcat.bed \
> /Users/sr320/git-repos/paper-Temp-stress/ipynb/analyses/mergHYPOcatsort.bed
!bedtools merge -c 2 -o count \
-i /Users/sr320/git-repos/paper-Temp-stress/ipynb/analyses/mergHYPOcatsort.bed | sort -nrk4

```

and so on for the hypermethylated region. 

end of the AM, left with a new track



```
scaffold481	576986	578532	-3
scaffold247	141885	142442	-3
scaffold1518	212680	213736	-3
scaffold853	46186	46496	-2
scaffold406	419330	419384	-2
scaffold406	419005	419060	-2
scaffold406	418360	418767	-2
scaffold394	555813	556224	-2
scaffold247	144031	144583	-2
scaffold242	75918	76344	-2
scaffold142	656144	656735	-2
scaffold12	243960	244376	-2
scaffold257	1235165	1235481	+2
```

Jupter Notebook




