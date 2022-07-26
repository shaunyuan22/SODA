## Large-scale Benchmark for Small Object Detection: SODA
**SODA** is a large-scale benckmark for Small Object Detection, including SODA-D and SODA-A which concentrate on Driving and Aerial scenarios respectively.

### Update
 - [20220726] Our [Homepage](https://shaunyuan22.github.io/SODA/) for SODA benchmark opens!
 - [20220726] The paper of SODA dataset and a thorough review on Small Object Detection is submitted to [*arXiv*](https://arxiv.org).
 - [20220726] SODA Benchmark if officially available, please refer to the Dataset Download 
 - [20220726] [Codes](https://github.com/shaunyuan22/SODA) for training and evaluating of SODA-D and SODA-A dataset are released.
 - [20220726] Pretrained models for SODA-D and SODA-A are released, please refer to the Dataset Download 
 
### SODA-D
SODA-D contains 24704 well-chosen and high-quality images under driving scenarios, on which 274496 instances of 9 categories with horizontal bounding boxes were annotated. Some example images are shown below.
![image](imgs/sodad_vis.png)

### SODA-A
SODA-A comprises 2510 high-resolution images ofaerial scenes, which has 780203 instances annotated with oriented rectangle box annotations over 9 classes. An example image of SODA-A is shown next.
![image](imgs/sodaa_vis.png)

### Results
We exhibit the experiment resullts of several representative methods on SODA-D test-set (Top) and SODA-A test-set (Bottom) as follow.
<!--![image](imgs/sodad_res.PNG)-->
<!--![image](imgs/sodaa_res.PNG)-->

| **Method** | **Schedule** | $AP$ | $AP_{50}$ | $AP_{75}$ | $AP_T$ | $AP_{eT}$ | $AP_{rT}$ | $AP_{gT}$ | $AP_S$ |
| :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
| Faster RCNN | $1 \times$ | 32.9 | 64.5 | 29.4 | 28.9 | 19.3 | 30.1 | 35.8 | 43.2 |
| Cascade RCNN | $1 \times$ |35.7 | 64.6 | 33.8 | 31.2 | 20.4 | 32.5 | 39.0 | 46.9 |
| RetinaNet | $1 \times$ | 29.2 | 58.0 | 25.3 | 25.0 | 15.7 | 26.3 | 31.8 | 39.6 |
| FCOS | $1 \times$ | 28.7 | 55.1 | 26.0 | 23.9 | 11.9 | 25.6 | 32.8 | 40.9 |
| RepPoints | $1 \times$ | 32.9 | 60.8 | 30.9 | 28.0 | 16.2 | 29.6 | 36.8 | 45.3 |
| ATSS | $1 \times$ | 30.1 | 59.5 | 26.3 | 26.1 | 17.0 | 27.4 | 32.8 | 40.5 |
| Deformable-DETR | $1 \times$ | 23.4 | 50.6 | 18.8 | 19.2 | 10.1 | 20.0 | 26.5 | 34.2 |
| Sparse RCNN | $1 \times$ | 28.3 | 55.8 | 25.5 | 24.2 | 14.1 | 25.5 | 31.7 | 39.4 |


### Download
We provide the downloading of our paper, datasets and pretrained models.
 - Paper: [Towards Large-Scale Small Object Detection: Survey and Benchmarks](https://arxiv.org)
 - Datasets:
  - SODA-D: [OneDrvie](https://www.microsoft.com/onedrive); [BdiduNetDisk](https://pan.baidu.com)
  - SODA-A: [OneDrvie](https://www.microsoft.com/onedrive); [BdiduNetDisk](https://pan.baidu.com)
 - Pretrained Models: Models trained on trsin-set are available at: [OneDrvie](https://www.microsoft.com/onedrive); [BdiduNetDisk](https://pan.baidu.com)


You can use the [editor on GitHub](https://github.com/shaunyuan22/SODA/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/shaunyuan22/SODA/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
