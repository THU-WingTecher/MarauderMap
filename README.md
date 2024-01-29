# MarauderMap
**Note: These samples were collected for research purposes only!**

## Introduction
**MarauderMap** contains 7,796 active and unique ransomware samples from 95 families.

In terms of the distribution of ransomware families, the top ten are as follows:
LockBit (29.32%), Conti (12.87%), REvil (7.93%), Cerber (3.83%), WannaCry (1.64%), BlackCat (1.33%), GandCrab (1.22%), Hive (0.89%), Maze (0.73%), and Jigsaw (0.64%).

To the best of our knowledge, this sample analysis size is an order of magnitude more than previous studies.
We would also like to point out that our dataset contains a variety of very new ransomware families, such as Tellyouthepass, Bianlian, and Nevada.

These samples were collected over a period ranging from November 2022 to March 2023.
Regarding the first-seen timestamp distribution of the samples:
66 samples (0.85%) were detected before 2021, while the remaining 7,730 samples (99.15%) were first identified between 2021 and 2023.

They are all Win32 EXE file types; we tested them in the Win10 environment.
We identify and organize them by their SHA-256 values.

If you want to know more about dataset construction, please refer to the paper ***An Empirical Study of Data Disruption by Ransomware Attacks*** published in ICSE'24.


## Extraction
The password to unzip these samples is *maraudermap*.
Please be careful; they are active and can be executed once clicked.

To extract each sample:
```
unzip -P maraudermap <sample-sha256.zip>
```


## Full Access
Due to the space limit of the GitHub repository, the ransomware samples are not fully uploaded (only 108 here).
Please access the full dataset via Google Drive: [link](https://drive.google.com/drive/folders/1lpQdZ-G2TMG1GYOiv70ZF8Fe9yWfgthY?usp=sharing)


## Citation
If you would like to use these samples, please cite us:

```
@inproceedings{hou2024maraudermap,
  title = {An Empirical Study of Data Disruption by Ransomware Attacks},
  author = {Hou, Yiwei and Guo, Lihua and Zhou, Chijin and Xu, Yiwen and Yin, Zijing and Li, Shanshan and Sun, Chengnian and Jiang, Yu},
  booktitle = {Proceedings of the 46th IEEE/ACM International Conference on Software Engineering (ICSE'24)},
  year = {2024},
  location = {Lisbon, Portugal},
  organization = {IEEE}
}
```
