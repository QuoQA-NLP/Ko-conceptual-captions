# Korean Conceptual Captions Dataset

### Introduction

- [Google's Conceptual Captions Dataset](https://github.com/google-research-datasets/conceptual-captions)'s captions translated into Korean captions.
- English to Korean Machine Translation with [Finetuned Seq2Seq model of QuoQA-NLP/KE-T5-En2Ko-Base](https://github.com/QuoQA-NLP/T5_Translation)

|                       Original Dataset                       | Machine Translated Dataset | Gold-label Translation Dataset |
| :----------------------------------------------------------: | :------------------------: | :----------------------------: |
| [CC3M](https://huggingface.co/datasets/conceptual_captions)  | [KoCC3M](QuoQA-NLP/KoCC3M) |               -                |
|   [CC12M](https://huggingface.co/datasets/conceptual_12m)    |             -              |               -                |
| [YFCC100M](https://multimediacommons.wordpress.com/yfcc100m-core-dataset/) |             -              |               -                |

### CC3M Example

|                          image_url                           |                       english_caption                        |                        korean_caption                        |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![img4](http://l7.alamy.com/zooms/e47031473a3e4379abc95116186b3f2d/3d-digital-render-of-a-beautiful-asian-female-ballet-dancer-isolated-eby7yk.jpg) | 3d digital render of a beautiful female ballet dancer isolated on white background | 흰색 바탕에 고립된 아름다운 여성 발레 무용수의 3d 디지털 렌더링입니다. |
| ![img1](https://media.istockphoto.com/photos/bougainvillea-with-pink-flowers-on-a-white-background-picture-id146724993?k=6&m=146724993&s=612x612&w=0&h=g5LEZzsIszKDLpL4S56FohuVz4ySmxesPE4tQSG_yeI=) |   a bougainvillea with pink flowers on a white background    |         흰 바탕에 분홍색 꽃들이 그려진 보가인빌라다.         |
| ![img4](https://media.gettyimages.com/photos/malik-rosier-of-the-miami-hurricanes-warms-up-during-a-game-against-picture-id841875570) | person warms up during a game against american football team. |      아메리칸 축구팀과의 경기 중 사람이 몸을 풀고 있다.      |
| ![img](http://l7.alamy.com/zooms/9819df2053414fb29d11f790f34c9151/red-telephone-box-in-the-small-village-of-pott-shrigley-cheshire-england-j48m52.jpg) |            red telephone box in the small village            |             작은 마을에 빨간 전화기가 걸려 있다.             |


### Goal

Creating machine translated caption of vision-image dataset to further create human supervised gold label translation captions.

### References

- For specifics regarding for CC3M vision-image dataset, [please refer to description provided by Google Research](https://github.com/google-research-datasets/conceptual-captions#dataset-description).

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
