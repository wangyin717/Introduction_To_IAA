# 美学课题入门学习资料

## 计算机视觉入门

### A. python数据挖掘 && 机器学习入门
代码和理论学习（跟着视频配置环境，写代码，需要全部看完）：
* "*4天快速入门Python数据挖掘* " 哔哩哔哩 [[link]](https://www.bilibili.com/video/BV1xt411v7z9/?spm_id_from=333.999.0.0&vd_source=0e48243c36ada68108535fbdbf51eb68)
* "*3天快速入门python机器学习* " 哔哩哔哩 [[link]](https://www.bilibili.com/video/BV1nt411r7tj/?spm_id_from=333.999.0.0&vd_source=0e48243c36ada68108535fbdbf51eb68)

### B. 机器学习基础
理论学习（看视频，同时在配套笔记的基础上可以简单做一些笔记，加深记忆。不需要全部看完，大概看到`第八周`即可，包括第八周）
* "*吴恩达机器学习系列课程* " 哔哩哔哩 [[link]](https://www.bilibili.com/video/BV164411b7dx/?spm_id_from=333.999.0.0&vd_source=0e48243c36ada68108535fbdbf51eb68)
* 配套笔记："*黄海广博士的机器学习个人笔记* " [[pdf]](https://github.com/wangyin717/Introduction_To_IAA/blob/main/Material/notes.pdf)

### C. 深度学习基础
代码学习（跟着视频配置环境，写代码，训练模型）：
* "*霹雳吧啦Wz-深度学习-图像分类篇章* " 哔哩哔哩 [[link]](https://space.bilibili.com/18161609/channel/collectiondetail?sid=48290) （不需要全部看完，前面的几个经典模型都要看，后面的可以根据需要挑着看）

理论学习（有了前面的基础看这个视频应该可以很快理解）：
* "*李宏毅2021/2022春机器学习课程* " 哔哩哔哩 [[link]](https://space.bilibili.com/18161609/channel/collectiondetail?sid=48290) （同样不需要都看，可以只看计算机视觉相关的，比如`CNN`、`Self-Attention`、`Transformer`、`GAN`）

## 美学课题入门
### 课题组现有成员
目前在读学生为18人，构成比例为3本科生 + 15研究生 + 4老师

### A. 入门文章
* "NIMA: Neural Image Assessment" `NIMA` [[pdf]](https://github.com/wangyin717/Introduction_To_IAA/blob/main/Material/NIMA.pdf) [[code]](https://github.com/yunxiaoshi/Neural-IMage-Assessment)

* "Image Composition Assessment with Saliency-augmented Multi-pattern Pooling" `构图评价` [[pdf]](https://github.com/wangyin717/Introduction_To_IAA/blob/main/Material/Image%20Composition%20Assessment%20with%20Saliency-augmen.pdf) [[code]](https://github.com/bcmi/Image-Composition-Assessment-Dataset-CADB)

* "Rethinking Image Aesthetics Assessment: Models, Datasets and Benchmarks" `TANet多主题` [[pdf]](https://github.com/wangyin717/Introduction_To_IAA/blob/main/Material/TANet.pdf) [[code]](https://github.com/woshidandan/TANet)

* "Towards Artistic Image Aesthetics Assessment: a Large-scale Dataset and a New Method" `BAID艺术图像数据集` [[pdf]](https://github.com/wangyin717/Introduction_To_IAA/blob/main/Material/BAID.pdf) [[code]](https://github.com/Dreemurr-T/BAID)

### B. 课题相关数据集
各类美学数据集 [点击链接](https://grappaproject.eu/databases/image_datasets/)

| 数据集名称  | 数据集描述  | 数据集规模    |   作用   | 链接|
| :-----------: | :--------: | :--------: | :--------: | :--------: |
| AVA★★★★★     |     人类对于图片进行1-10分的打分      |      255,500张图像    |      训练基础的美学模型     |     [链接](https://github.com/mtobeiyf/ava_downloader?spm=a2c6h.12873639.0.0.7707199420mLYv)     |
| AADB★★★ | 包含11种摄影属性,5个人的平均评分 | 10000张图像 ,  8500 张训练，500 验证，1000 测试 | 评价美学维度 | [链接](https://drive.google.com/open?id=1Viswtzb77vqqaaICAQz9iuZ8OEYCu6-_) |
| BAID★★★ | 艺术图像数据集 | 60337张图像 ,  50737 张训练，3200 验证，6400 测试 | 训练基础的美学模型 | [链接 提取码: 9y91](https://pan.baidu.com/share/init?surl=9pxr19neJ6Pmd0B6A_u55Q) |
| DPChallenge.com     |     人类对于图片进行1-10分的打分      |      16,509张图像    |      训练基础的美学模型     |      [链接](https://ritendra.weebly.com/aesthetics-datasets.html?spm=a2c6h.12873639.0.0.7707199420mLYv)     |
| photo.net     |     人类对于图片进行1-10分的打分      |      20,278张图像    |      训练基础的美学模型     |      [链接](https://ritendra.weebly.com/aesthetics-datasets.html?spm=a2c6h.12873639.0.0.7707199420mLYv)     |
| TID2013★★★★★     |     人类对于多种处理后的失真图片进行1-10打分      |      25×24张照片，25张参考图像，24个失真类型    |      美学因素，图像质量客观评价因素     |      [链接 提取码: 9oc4](https://pan.baidu.com/s/1oj7tRDppmHV8DeCEuJNcJg)     |
| LIVE 提取码: g2sh  解压密码为：livedatabase2005  |     人类对于多种处理后的失真图片进行1-10打分      |      29×5张照片，29张参考图像，5个失真类型    |      美学因素，图像质量客观评价因素     |      [链接](https://pan.baidu.com/s/1gVcaWpIX9m8zER4XeWow9g)     |
| MLIVE     |     人类对于多种处理后的失真图片进行1-10打分      |      15×15张照片，15张参考图像，15个失真类型    |      美学因素，图像质量客观评价因素     |      [链接](http://live.ece.utexas.edu/research/quality/live_multidistortedimage.html?spm=a2c6h.12873639.0.0.7707199420mLYv)     |
| WATERLOO     |     人类对于多种处理后的失真图片进行1-10打分      |      4744张参考图像, 20个失真类型    |      美学因素，图像质量客观评价因素     |      [链接](https://ece.uwaterloo.ca/~k29ma/exploration/?spm=a2c6h.12873639.0.0.7707199420mLYv)     |
| flickr★★★★★     |     很多摄像师拍的照片，还附有相机参数和一些关键字评论      |      无数张？可以自己爬下来    |      美学因素，图像质量客观评价因素     |      [链接](https://www.flickr.com/)     |
| PCCD | 有人对图像的评论和7个维度的评分 | 4,235张照片，29,645评论 | 评价美学维度、美学因素 | [链接](https://drive.google.com/file/d/12Xk-GVM4XA-Gy096nbzxQQNNXB_X7bJ4/view) |
| KonIQ-10k★★★ | 包含总分、Brightness、Colorfulness、Contrast、Sharpness | 10,073张图像 | 评价美学维度 | [链接](http://database.mmsp-kn.de/koniq-10k-database.html) |
| CUHKPQ | 只包含好照片和不好照片，但是细分为动物，建筑等很多类 | 28,410张图像 | 评价美学维度 | [链接](http://mmlab.ie.cuhk.edu.hk/archive/CUHKPQ/Dataset.htm) |
| TAD66K | 按主题标注，分为47个主题 | 66,000张左右的图像 | 整体美学评分 | [链接](https://drive.google.com/drive/folders/1b2D9LeeG5XZzhEa8ldnIZjGh0IHadHhU) |
