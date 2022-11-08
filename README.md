# 计算基因组学论文阅读

## 论文阅读记录
| 日期 | 标题 | 作者 | 期刊/会议 | 源码|
| --: | -- | -- | --: | -- |
|2022/10/31|[Fast and accurate short read alignment with Burrows-Wheeler transform](https://academic.oup.com/bioinformatics/article/25/14/1754/225615)|Li H. and Durbin R|Bioinformatics| [https://github.com/lh3/bwa](https://github.com/lh3/bwa)|
|2022/11/07|[Aligning sequence reads, clone sequences and assembly contigs with BWA-MEM](https://arxiv.org/pdf/1303.3997.pdf)|Li Heng|Bioinformatics| [https://github.com/lh3/bwa](https://github.com/lh3/bwa)|
|2022/11/14|[High Throughput Short Read Alignment via Bi-directional BWT](https://hub.hku.hk/bitstream/10722/129577/1/Content.pdf)|T.W. Lam∗, Ruiqiang Li†, Alan Tam∗, Simon Wong∗, Edward Wu∗, S.M. Yiu∗|Bioinformatics| [https://github.com/lh3/bwa](https://github.com/lh3/bwa)|
## 论文主题
### 短序列（读长）比对算法（Short read alignment）

1. DNA短序列（读长）比对（DNA short-read alignment）


|<div style="width:30px">已读</div> | <div style="width:30px">年份</div> | <div style="width:80px">名字 </div>| <div style="width:150px">题目 </div>| <div style="width:100px">简介</div> | <div style="width:50px">引用 </div>|
| ---- | ---- | ------ | ------------ | --- | -------------- |
|⬜| 2008 |MAQ| [ Mapping short DNA sequencing reads and calling variants using mapping quality scores ](http://genome.cshlp.org/content/18/11/1851.full.pdf) | 基于hash-table的DNA短读长比对算法               |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fbc103d96366ec97e0dd620894bbb04c8849eb772%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Mapping-short-DNA-sequencing-reads-and-calling-Li-Ruan/bc103d96366ec97e0dd620894bbb04c8849eb772)|
|✅| 2009 |BWA| [ Fast and accurate short read alignment with Burrows-Wheeler transform](https://academic.oup.com/bioinformatics/article-pdf/25/14/1754/605544/btp324.pdf) | 基于BWT的DNA短读长比对算法               |[![citation](https://img.shields.io/badge/citation-111-blue)](https://www.semanticscholar.org/paper/Fast-and-accurate-short-read-alignment-with-Li-Durbin/b6de563c03eedf95d7e880a2aeb5688936ea1d26#citing-papers)|
|⬜| 2009 |Bowtie| [ Ultrafast and memory-efficient alignment of short DNA sequences to the human genome](https://doi.org/10.1186/gb-2009-10-3-r25) | 基于BWT的DNA短读长比对算法               |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Febe875cf08dd398e0ed25f518502301c984a9afe%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Ultrafast-and-memory-efficient-alignment-of-short-Langmead-Trapnell/ebe875cf08dd398e0ed25f518502301c984a9afe)|
|✅| 2009 |SMEMs| [ High Throughput Short Read Alignment via Bi-directional BWT](https://hub.hku.hk/bitstream/10722/129577/1/Content.pdf) | 基于双向BWT的高通量短读长比对算法               |[![citation](https://img.shields.io/badge/citation-1515-blue)](https://www.semanticscholar.org/paper/High-Throughput-Short-Read-Alignment-via-BWT-Lam-Li/2eed549f8878f84d9e83ad365517227f12cb0b5d)|
|⬜| 2012 |SeqAlto| [Fast and accurate read alignment for resequencing ](https://academic.oup.com/bioinformatics/article-pdf/28/18/2366/16910927/bts450.pdf) | 基于hash-table的DNA短读长比对算法               |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F0d8bd3991b021e48d8ab654a83f767dacf897a80%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Fast-and-accurate-read-alignment-for-resequencing-Mu-Jiang/0d8bd3991b021e48d8ab654a83f767dacf897a80)|
|⬜| 2012 |GEM| [ The GEM mapper: fast, accurate and versatile alignment by filtration](http://www.tcoffee.org/Courses/Exercises/bologna_ma_2013/biblio/4.4.paper.gem.pdf) | 基于hash-table的DNA短读长比对算法               |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F71150718ec7affbc4f9130f55f925af0dd956651%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/The-GEM-mapper%3A-fast%2C-accurate-and-versatile-by-Marco-Sola-Sammeth/71150718ec7affbc4f9130f55f925af0dd956651)|
|✅| 2013 |BWA-MEM| [ Aligning sequence reads, clone sequences and assembly contigs with BWA-MEM](https://arxiv.org/pdf/1303.3997.pdf) | 基于BWT的DNA短读长比对算法               |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F74574ee09030e8aadb48fa349eb9b054e2f95ceb%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Aligning-sequence-reads%2C-clone-sequences-and-with-Li/74574ee09030e8aadb48fa349eb9b054e2f95ceb#citing-papers)|
|⬜| 2013 |Bowtie2| [ Fast gapped-read alignment with Bowtie 2](https://www.nature.com/articles/nmeth.1923) | 基于BWT的DNA短读长比对算法               |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6fca260e9a3c37e246cc15e7639d1a5fa2aed465%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Fast-gapped-read-alignment-with-Bowtie-2-Langmead-Salzberg/6fca260e9a3c37e246cc15e7639d1a5fa2aed465)|

