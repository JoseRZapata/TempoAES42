# AES 42 Audio Tempo Evaluation Data

This repo contains the code in a [jupyter notebook](http://nbviewer.jupyter.org/github/JoseRZapata/TempoAES42/blob/master/TempoEvaluationAES42.ipynb) to reproduce all of the analyses from the audio tempo evaluation paper:

Zapata, Jose R.; Gómez, Emilia.
**"Comparative Evaluation and Combination of Audio Tempo Estimation Approaches"**,
AES 42nd International Conference: Semantic Audio, Ilmenau, Germany. pp. 198 - 207, Jul 2011.

- http://www.aes.org/e-lib/browse.cfm?elib=15964

- [Download paper](http://mtg.upf.edu/system/files/publications/Audio_tempo_comparison_Zapata_Gomez.pdf)
- [Jupyter Notebook ->TempoEvaluationAES42.ipynb](http://nbviewer.jupyter.org/github/JoseRZapata/TempoAES42/blob/master/TempoEvaluationAES42.ipynb) (Use this link to nbviewer to watch the interactive plots)

##

## ABSTRACT
The automatic analysis of musical tempo from audio is still an open research task in the Music Information Retrieval
(MIR) community. The goal of this paper is to provide an updated comparative evaluation of different methods for
audio tempo estimation. We overview, following the same block diagram, 23 documented methods. We then analyze
their accuracy, error distribution and statistical differences, and we discuss which strategies can provide better
performance for different input material. We then take advantage of their complementarity to improve the results by
combining different methods, and we finally analyze the limitations of current approaches and give some ideas for
future work on the task.

## DATASET
The ISMIR 2004 tempo induction contest uses three different data sets http://mtg.upf.edu//ismir2004/contest/tempoContest/node3.html

In this web page only evaluates the tempo algorithms in the Song Excerpt data set http://mtg.upf.edu//ismir2004/contest/tempoContest/node6.html

can be download: http://www.iua.upf.edu/mtg/ismir2004/contest/tempoContest/data3.tar.gz

Info extracted from the original web page

Song excerpts Data set

A professional musician placed beat marks on several song excerpts. The ground-truth tempo was computed as the median of the inter-beat intervals.
- Total number of instances: 465
- Duration: 20 s
- Total duration: 9300 s
