# 基因组组装调研测试材料

## 这是对git分支练习添加的信息
## test
## test again

## _de novo DNA assembly(short and long reads)_
1. Unicycler: https://github.com/rrwick/Unicycler

unicycler作者最推荐的是三代+二代的测序数据输入组装，但同时unicycler也支持纯三代数据或者纯二代数据的输入。

2. Canu: https://canu.readthedocs.io/en/latest/quick-start.html

canu组装只针对单独的pacbio或者nanopore测序数据。支持使用亲本短读长测序数据与组装结果进行校正合并，更多是使用到二倍体基因组组装上。

3. Flye: https://github.com/fenderglass/Flye

flye组装只针对单独的pacbio或者nanopore测序数据。Flye is a de novo assembler for single-molecule sequencing reads, such as those produced by PacBio and Oxford Nanopore Technologies

4. Raven: https://github.com/lbcb-sci/raven

Raven组装针对长读长测序数据。Raven is a de novo genome assembler for long uncorrected reads.

5. wtdbg2: https://github.com/ruanjue/wtdbg2

wtdbg2组装只针对长读长测序数据。Wtdbg2 is a de novo sequence assembler for long noisy reads produced by PacBio or Oxford Nanopore Technologies (ONT).

6. Miniasm: https://github.com/lh3/miniasm

miniasm组装只针对长读长测序数据。Miniasm is a very fast OLC-based de novo assembler for noisy long reads

7. SPAdes: https://github.com/ablab/spades

spades支持三代+二代数据的组装、支持单独的二代数组装。

8. Falcon: https://github.com/PacificBiosciences/falcon

falcon中文操作：https://www.jianshu.com/p/3c7ebccb70a1

9. Wengan: https://github.com/adigenova/wengan
10. NextDenovo：https://github.com/Nextomics/NextDenovo

nextdenovo组装只针对单独的pacbio或者nanopore测序数据。NextDenovo is a string graph-based de novo assembler for long reads (CLR, HiFi and ONT)

11. Shasta: https://github.com/chanzuckerberg/shasta

针对nanopore测序数据。The goal of the Shasta long read assembler is to rapidly produce accurate assembled sequence using DNA reads generated by Oxford Nanopore flow cells as input.

12. hifiasm: https://github.com/chhylp123/hifiasm

hifiasm针对pacbio三代测序数据，也可以加上二代数据同时组装。Hifiasm is a fast haplotype-resolved de novo assembler for PacBio HiFi reads. 

## _polishing, error-correction, consensus，reassemble_
1. Racon: https://github.com/isovic/racon
2. Trycycler: https://github.com/rrwick/Trycycler
3. abyss: https://github.com/bcgsc/abyss

## _illumina paired-end short reads assembly_
1. SKESA：https://github.com/ncbi/SKESA

SKESA is a de novo assembler for microbial genomes based on DeBruijn graphs.是Read Assembly and Annotation Pipeline Tool (RAPT) (https://github.com/ncbi/rapt)中的组装模块。

2. Shovill: https://github.com/tseemann/shovill
3. SAGE2: https://github.com/lucian-ilie/SAGE2

SAGE2 accepts FASTA and FASTQ input files. Paired-end reads should be placed one after another (interlaced) in the input file. SAGE2 does not use single end reads.

### using reference (or draft assembly)
1. kermit: https://github.com/rikuu/kermit
