# BigBigtree
### Members
邱顯安 110753110

### Demo 
Install Nextflow

	curl -s https://get.nextflow.io | bash

Install perl:bio 
https://www.biostars.org/p/103949/

```
	./nextflow run main.nf --aa 'example/Or_aa.fasta' --nn 'example/Or_nn_v2.fasta' --speciesTree 'example/speciesTree.ph' --msa_mode 'mafft' --tree_mode 'phyml' --logfile '$baseDir/nextflow.log'
```

## Folder organization and its related information

### docs
1092_bioinformatics_FP_< 110753110 >pptx, by **06.26**


### data

INSR (ENSG00000171105)
INSR is in a tree of 411 genes that corresponds to 
PTHR24416:SF140 in Panther, but
there are 80 trees (18,392 genes) in total in the family PTHR24416 .

For each tree there are six files
- all the unaligned CDS sequences in Fasta
- all the unaligned protein sequences in Fasta
- all the aligned CDS sequences in Fasta
- all the aligned protein sequences in Fasta
- the tree in newick
- mapping between protein stable_ids


### code
The original code is from jmchanglab/bigbigtree
You have to install Nextflow and perl:bio before runnung the code

### results
I try to run the original program from bigbigtree
But there is a problem when running hcluster
![](./results.result.png)

After fixing these problems, I will put the data in to execute

## References
https://github.com/jmchanglab/bigbigtree

