# Leech Phylo


## 18.04.2023

```
for file in *.trinity.fa;do TransDecoder.LongOrfs -t $file; TransDecoder.Predict -t $file; rm -rf *.cmds; rm -rf *.transdecoder_dir; rm -rf *.__checkpoints; rm -rf *.__checkpoints_longorfs; mv *.bed bed; mv *.gff3 gff3; mv *.cds cds; mv *.pep pep;done 
```
