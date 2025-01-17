# hse_hw3_chromhmm
Colab - https://colab.research.google.com/drive/1LStC4SA6CQNxmcV8cBgMIfwl9_ufEu4x?usp=sharing  
## Гистоновые метки  
| histoneName | fileName |
| --- | --- |
| H3k27ac | H3k27acAlnRep1.bam |
| H3k79me2 | H3k79me2AlnRep1.bam |
| H3k27me3 | H3k27me3AlnRep1.bam | 
| H2az | H2azAlnRep1.bam |
| H3k09me3 | H3k09me3AlnRep1.bam | 
| H4k20me1 | H4k20me1AlnRep1.bam |
| H3k04me2 | H3k04me2AlnRep1.bam |
| H3k09ac | H3k09acAlnRep1.bam |
| H3k04me1 | H3k04me1AlnRep1.bam |
| H3k36me3 | H3k36me3AlnRep1.bam |  
## cellmarkfiletable.txt  
![image](https://github.com/vityavasilev/hse_hw3_chromhmm/assets/147335727/2fe886a7-bb3b-43a8-b3e8-7f2301a91c2b)  
## chromHMM  
| Emission |
| --- |
| ![emissions_12](https://github.com/vityavasilev/hse_hw3_chromhmm/assets/147335727/71133041-8a97-4b63-94de-e71bc5255856) |
| Transitions |
| ![transitions_12](https://github.com/vityavasilev/hse_hw3_chromhmm/assets/147335727/e1e8eac4-13cf-491f-9182-3dc6af77a91a) |  
| Overlap |
| ![image](https://github.com/vityavasilev/hse_hw3_chromhmm/assets/147335727/d87afde2-570f-4edf-a45f-d7c4a3b146cc) |
| TSS |
| ![image](https://github.com/vityavasilev/hse_hw3_chromhmm/assets/147335727/d3328178-2703-4182-8faa-ce3d29a3aad4) |
| TES |
| ![image](https://github.com/vityavasilev/hse_hw3_chromhmm/assets/147335727/1c6647fd-a67b-49ee-9e5a-c5f9874c5557) |  
![image](https://github.com/vityavasilev/hse_hw3_chromhmm/assets/147335727/31f9e3b0-91ec-45af-84dc-04f0c2528cfb)  
# Описание гипотетических функций
| № | Название | Описание |
| --- | --- | --- |
| 1 | Active Promoter | H3k04me проявляет сильно и H3k4me2 слабее + попадает на интрон и экзон |
| 2 | Weak Enhancer | Сильно выражают H3k04me, H3k4me2 и H3k27ac + находятся на интроне |
| 3 | Strong Enhancer | H3k9ac, H3k4me3, H3k4me2 и H3K27ac сильно выражают + находятся на интроне |
| 4 | Active Promoter | H3k4me2 сильно выражает + находится на интроне и экзоне |
| 5 | Active Promoter | H3k79me2 сильно и H3k4me2 слабо выражают + находятся на интроне и экзоне |
| 6 | Weak Enhancer | H3k79me2 средне выражает + находятся на интроне |
| 7 | Weak Enhancer | не хватает надежности данных для интерпретации |
| 8 | Weak Transcribed | не хватает надежности данных для интерпретации |
| 9 | Weak Transcribed | Ctcf средне выражает + интрон и экзон |
| 10 | Repressed | H3k09me средне выражает + не попадает на ген |
| 11 | Heterochromatin | Ezh средне выражает + не попадает на ген |
| 12 | Heterochromatin | H3k36me3 средне выражает + не попадает на ген |  
# Бонус
(в колабе)
![image](https://github.com/vityavasilev/hse_hw3_chromhmm/assets/147335727/e7976c07-e95b-449c-bb7b-6b5e00868220)
