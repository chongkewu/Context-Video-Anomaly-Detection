# Context-Video-Anomaly-Detection

The demo code of the paper ***Video anomaly detection using pre-trained deep convolutional neural nets and context mining***

paper link:
https://arxiv.org/ftp/arxiv/papers/2010/2010.02406.pdf

## Download related resource
https://drive.google.com/file/d/1vKzs6lmvH-qP6DubCHHxLPW0_RjDy7xt/view?usp=sharing

Note:
The Ped1_Train.csv, Ped1_Test.csv is the result generated from pretrained CNN model. If you want to integrated different CNN algorithm, you need to genereate your .CSV file.

The CNN algorithm we use for feature generation:

Object tracking: https://github.com/Zhongdao/Towards-Realtime-MOT

Object detection and background segmentation: https://github.com/chongkewu/detectron2

## Run the demo
The details in jupyter notebook is self-explained.
use Python 3.7.

## Citation
```
@article{wu2020video,
  title={Video anomaly detection using pre-trained deep convolutional neural nets and context mining},
  author={Wu, Chongke and Shao, Sicong and Tunc, Cihan and Hariri, Salim},
  journal={arXiv preprint arXiv:2010.02406},
  year={2020}
}
```
