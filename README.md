# Chinese Landscape Painting Stylization
This repo contains source code for training a Pix2Pix model that synthesizes Chinese landscape paintings from human-drawn sketches. Contents of synthesized paintings include mountains, rocks, trees, and houses. The model can also be used for applying style transfer to photos. 

## Example Training Data
![](images/sample_chinese_paintings.png)
## Example Model Outputs
### Sketch to Painting 
![](images/Sketch2.jpg)
![](images/Sketch4.jpg)
![](images/Sketch16.jpg)
![](images/Sketch9.jpg)
![](images/Sketch10.jpg)
![](images/Sketch14.jpg)
![](images/Sketch12.jpg)
![](images/Sketch13.jpg)
<!-- ![](images/Sketch8.jpg) --> 

### Style Transfer
![](images/mountain.jpg)
![](images/mountain2.jpg)

## Overall Technical Workflow
![](images/architecture_diagram.png)

## Try it out on Colab
**Get your own paintings:**
[<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/github/Luxi-Zhao/chinese-landscape-painting-stylization/blob/master/src/pix2pixSketch2PaintPredict.ipynb)

**Train model:**
[<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/github/Luxi-Zhao/chinese-landscape-painting-stylization/blob/master/src/pix2pixSketch2Paint.ipynb)

## Acknowledgements
- This project is a continuation of a [course project](https://github.com/Luxi-Zhao/sketch-to-Chinese-landscape-painting) done in collaboration with [<img src="https://avatars3.githubusercontent.com/u/43994607?s=64&amp;v=4" width="32" height="32" alt="@Tony-Feng">](https://github.com/Tony-Feng).
- Training data: [Chinese Landscape Painting Dataset](https://github.com/alicex2020/Chinese-Landscape-Painting-Dataset).
- Procedure for obtaining sketch-like edge maps was inspired by [Holistically-Nested Edge Detection](https://arxiv.org/abs/1504.06375) and [SketchyGAN](https://arxiv.org/abs/1801.02753).
- Pix2Pix model training: [TensorFlow tutorial](https://www.tensorflow.org/tutorials/generative/pix2pix).