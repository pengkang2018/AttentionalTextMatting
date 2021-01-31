# AttentionalTextMaating

This github repo is for the paper
```
@inproceedings{kang2021atm,
  title={ATM: Attentional Text Matting},
  author={Kang, Peng and Zhang, Jianping and Ma, Chen and Sun, Guiling},
  booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
  pages={3902--3911},
  year={2021}
}
```
Please cite our paper if you find it useful. Thank you!

This repo is for generating the dataset used in the paper. You can make your own text-matting dataset following the recipes in this repo.

## 0. check the requirements

```
pip install requirements.txt
```

## 1. Prepare the ingredients:

Put the background images in the **background** folder, the fonts in the **font** folder, the texture images in **texture** folder, and update **words.py** file to add your words and characters.

## 2. Cooking:

Following **gen_font_image.ipynb**, generate **data\bg**, **data\fg**, **data\mask**, **data\images**, and the image list.

## 3. Dessert:

Generate **data\trimap** following **trimap.ipynb** 

If you want to get a portion of our dataset, please drop us an email pengkang2022@u.northwestern.edu with your intention. Thank you!
