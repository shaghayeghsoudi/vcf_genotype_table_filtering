# vcf and genotype table filtering
This repository contains scripts that 1) perform vcf file post-filtering (such as DP, GQ, etc) and converts vcfs into genotype table and 2) perform extra filtering steps on genotype tables filtering such as MAF 


to run vcf2vertical.pl type:
```
cat PTH/TO/VCS/test.vcf | vcf2vertical.pl > test.converted.genotype.tab
```

to run snp_coverage.pl:
```
perl snp_coverage.pl test.converted.genotype.tab
```

It will produce 2 output files; genotype table (test.converted.genotype.tab.table)
and summary table (test.converted.genotype.tab.table.summary)
