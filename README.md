# :clap: It is a great honor for this piece of work to have received an entrepreneurial collaboration invitation from a renowned university professor.
![image](https://github.com/shaoshuai6666/NILM-TTRNet/blob/main/QQ%E5%9B%BE%E7%89%8720230630131841.png)

# TTRNet
This is an approach to NILM for commercial loads, and my article is in press.This is my first paper, because of the lack of personal ability, inevitably there are omissions, welcome interested in the exchange of discussion together.

## Deep Learning-Based Non-Intrusive Commercial Load Monitoring
This repository provided python code for the paper "Deep Learning-Based Non-Intrusive Commercial Load Monitoring", which is based on the pytorch framework.Some academics have cited my paper in their GitHub repository "Awesome NILM", and others have emailed me invitations to speak, so thank you very much for your love and support.
```
MDPI and ACS Style
Zhou, M.; Shao, S.; Wang, X.; Zhu, Z.; Hu, F. Deep Learning-Based Non-Intrusive Commercial Load Monitoring. Sensors 2022, 22, 5250. https://doi.org/10.3390/s22145250
```
## This is the first work dedicated to non-invasive load monitoring for commercial loads using deep learning methods.
A new Tansformer-based deep learning network is provided. The paper discusses the characteristics and difficulties of commercial loads in NILM. We compare with the latest NILM methods and the results prove that our approach is better.

## If you find this work helpful please cite my paper.
```
@Article{s22145250,
AUTHOR = {Zhou, Mengran and Shao, Shuai and Wang, Xu and Zhu, Ziwei and Hu, Feng},
TITLE = {Deep Learning-Based Non-Intrusive Commercial Load Monitoring},
JOURNAL = {Sensors},
VOLUME = {22},
YEAR = {2022},
NUMBER = {14},
ARTICLE-NUMBER = {5250},
URL = {https://www.mdpi.com/1424-8220/22/14/5250},
PubMedID = {35890929},
ISSN = {1424-8220},
ABSTRACT = {Commercial load is an essential demand-side resource. Monitoring commercial loads helps not only commercial customers understand their energy usage to improve energy efficiency but also helps electric utilities develop demand-side management strategies to ensure stable operation of the power system. However, existing non-intrusive methods cannot monitor multiple commercial loads simultaneously and do not consider the high correlation and severe imbalance among commercial loads. Therefore, this paper proposes a deep learning-based non-intrusive commercial load monitoring method to solve these problems. The method takes the total power signal of the commercial building as input and directly determines the state and power consumption of several specific appliances. The key elements of the method are a new neural network structure called TTRNet and a new loss function called MLFL. TTRNet is a multi-label classification model that can autonomously learn correlation information through its unique network structure. MLFL is a loss function specifically designed for multi-label classification tasks, which solves the imbalance problem and improves the monitoring accuracy for challenging loads. To validate the proposed method, experiments are performed separately in seen and unseen scenarios using a public dataset. In the seen scenario, the method achieves an average F1 score of 0.957, which is 7.77% better than existing multi-label classification methods. In the unseen scenario, the average F1 score is 0.904, which is 1.92% better than existing methods. The experimental results show that the method proposed in this paper is both effective and practical.},
DOI = {10.3390/s22145250}
}
```

:disappointed_relieved:Today, I found that an article used the same parameter settings as my article in the evaluation section, but did not quote my article. I was too sad.
X. Cheng, M. Zhao, J. Zhang, J. Wang, X. Pan and X. Liu, "TransNILM: A Transformer-based Deep Learning Model for Non-intrusive Load Monitoring," 2022 International Conference on High Performance Big Data and Intelligent Systems (HDIS), Tianjin, China, 2022, pp. 13-20, doi: 10.1109/HDIS56859.2022.9991439.

