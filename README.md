# HausMorphoCode
Goal of this package is to improve the performance of the algorithm proposed by Rodrigues E. [1] in order to reduce execution timeof Hausdorff Distance calculation and implement average Hausdorff Distance for medical imagiing data.

Results show that current implementation is 10 times faster than this developed in [1] in order to conduct futher tests author is currently in process of integrating this repository with python pytorch.
In order to execute the code it is recommended to create a docker enviroment - dockerfile is presented in [2].

In order to execute the example one should execute mainExample.py file.
Script executes set of benchmarks that will compare current implementations with some popular alternatives
Hovewer in case one would try to execute it not in the Docker container, the paths to the CT-Org [3] dataset and path where the result csv should be stored needs to be adjusted in the script.


[1] Érick Oliveira Rodrigues,An efficient and locality-oriented Hausdorff distance algorithm: Proposal and analysis of paradigms and implementations, Pattern Recognition,Volume 117,2021
[2] https://github.com/jakubMitura14/Hausdorff_morphological
[3] https://wiki.cancerimagingarchive.net/display/Public/CT-ORG%3A+CT+volumes+with+multiple+organ+segmentations
