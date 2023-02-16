# Digital Human Heads Quality Assessment Database

We are excited to present our latest research paper proposing a large-scale quality assessment database for digital human heads (DHHs). Our database includes a total of 1,540 DHH models, including 55 high-quality reference stimuli and their corresponding manually degraded versions with 7 types of distortions.

## Experiment Design

We invited 255 human subjects to participate in the DHH scanning experiment. The reference DHH models, which cover both male and female, young and old subjects, are in the format of textured meshes. We carefully selected 55 high-quality generated DHH models as reference stimuli.

The 7 types of distortions we used to degrade the reference DHHs include surface simplification, position compression, UV compression, texture sub-sampling, texture compression, color noise, and geometry noise. We obtained a total of 1,540 distorted DHHs.

A well-controlled subjective experiment was conducted to collect mean opinion scores (MOS) for the distorted DHHs. We obtained the largest subject-rate quality assessment database for digital human heads (DHHQA).

## Metrics and Results

We validated several mainstream quality assessment metrics for the benchmark. Furthermore, we designed a deep neural network (DNN) based full-reference (FR) quality assessment method to boost the performance on DHH quality evaluation.

The experimental results show that the proposed method has a better correlation with the subjective ratings and achieves better performance than other quality assessment metrics.

We believe that our DHHQA database and proposed FR quality assessment method will facilitate the development of more accurate and effective digital human head modeling and rendering techniques.

Thank you for your attention.

## Citation
If you find our paper useful, please cite our work as:
```
@inproceedings{zhang2023perceptual,
  title={Perceptual Quality Assessment for Digital Human Heads},
  author={Zhang, Zicheng and Zhou, Yingjie and Sun, Wei and Min, Xiongkuo and Wu, Yuzhe and Zhai, Guangtao},
  booktitle={IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  year={2023},
  organization={IEEE}
}
```
