# Korean Conceptual Captions Dataset

### Introduction

- [Google's Conceptual Captions Dataset](https://github.com/google-research-datasets/conceptual-captions)'s captions translated into Korean captions.
- English to Korean Machine Translation with [Finetuned Seq2Seq model of QuoQA-NLP/KE-T5-En2Ko-Base](https://github.com/QuoQA-NLP/T5_Translation)



|                       Original Dataset                       | Machine Translated Dataset | Gold-label Translation Dataset |
| :----------------------------------------------------------: | :------------------------: | :----------------------------: |
| [CC3M](https://huggingface.co/datasets/conceptual_captions)  | [KoCC3M](QuoQA-NLP/KoCC3M) |               -                |
|   [CC12M](https://huggingface.co/datasets/conceptual_12m)    |             -              |               -                |
| [YFCC100M](https://multimediacommons.wordpress.com/yfcc100m-core-dataset/) |             -              |               -                |



### Goal

Creating machine translated caption of vision-image dataset to further create human supervised gold label translation captions.



### References

For specifics regarding for CC3M vision-image dataset, [please refer to description provided by Google Research](https://github.com/google-research-datasets/conceptual-captions#dataset-description).

```
@inproceedings{sharma2018conceptual,
  title = {Conceptual Captions: A Cleaned, Hypernymed, Image Alt-text Dataset For Automatic Image Captioning},
  author = {Sharma, Piyush and Ding, Nan and Goodman, Sebastian and Soricut, Radu},
  booktitle = {Proceedings of ACL},
  year = {2018},
}

@article{ng2020understanding,
  title={Understanding Guided Image Captioning Performance across Domains},
  author={Edwin G. Ng and Bo Pang and Piyush Sharma and Radu Soricut},
  journal={arXiv preprint arXiv:2012.02339},
  year={2020}
}
@inproceedings{changpinyo2021cc12m,
  title = {{Conceptual 12M}: Pushing Web-Scale Image-Text Pre-Training To Recognize Long-Tail Visual Concepts},
  author = {Changpinyo, Soravit and Sharma, Piyush and Ding, Nan and Soricut, Radu},
  booktitle = {CVPR},
  year = {2021},
}

```
