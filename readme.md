# OCR 常用数据集合

该仓库包含了常用的文本检测和文本识别的数据集，并且提供了统一的数据集格式。
> support: lmdb, .txt, .csv ,.json

## 数据集

|序号|数据集名称|	文本类型|	标注格式|	数据来源|	下载地址|简介|
|--|---|---|---|---|---|--|
|1|ICDAR2019-LSVT|	中/英/数字|	json 文件|	[ICDAR2019](https://rrc.cvc.uab.es/?ch=16&com=tasks)	|[百度大脑](https://ai.baidu.com/broad/download?dataset=lsvt)|共45w中文街景图像，包含5w（2w测试+3w训练）全标注数据（文本坐标+文本内容），40w弱标注数据（仅文本内容）|
|2|ICDAR2017-RCTW-17|	中/英/数字|	<image_name>.txt |	[ICDAR2017](https://rctw.vlrlab.net/)	|[ICDAR2017](https://rctw.vlrlab.net/dataset.html)|共包含12,000+图像，大部分图片是通过手机摄像头在野外采集的。有些是截图。这些图片展示了各种各样的场景，包括街景、海报、菜单、室内场景和手机应用程序的截图。|
|3|中文街景文字识别|中/数字/英|	todo |	[ICDAR2019-LSVT](https://aistudio.baidu.com/aistudio/competition/detail/8)	|[百度大脑](https://aistudio.baidu.com/aistudio/datasetdetail/8429)|共包括29万张图片，其中21万张图片作为训练集（带标注），8万张作为测试集（无标注).图像都经过一些预处理，将文字区域放射变换高为48像素的图片|
|4|中文文档文字识别|中/英/数字/标点| train.list [w h image_name label] |	[chinese-ocr](https://github.com/YCG09/chinese_ocr)	|[百度云](https://pan.baidu.com/s/1QkI7kjah8SPHwOQ40rS1Pw) 密码：lu7m|364万张图片.按照99:1划分成训练集和验证集,图片分辨率统一为280x32|
|5|ICDAR2019-ArT|中|	todo |	[ICDAR2019](https://ai.baidu.com/broad/introduction?dataset=art)	|[百度大脑](https://ai.baidu.com/broad/download?dataset=art)|共包含10,166张图像，训练集5603图，测试集4563图。由Total-Text、SCUT-CTW1500、Baidu Curved Scene Text (ICDAR2019-LSVT部分弯曲数据) 三部分组成，包含水平、多方向和弯曲等多种形状的文本|
|6|手写中文数据集|中/英/数字/标点| todo	|	[中科院自动化研究所](http://www.nlpr.ia.ac.cn/databases/handwriting/Download.html)	|[中科院自动化研究所](http://www.nlpr.ia.ac.cn/databases/handwriting/Download.html)|包含在线和离线两类手写数据,HWDB1.0~1.2总共有3895135个手写单字样本,HWDB2.0~2.2总共有5091页图像，分割为52230个文本行和1349414个文字|
|7|NIST手写单字数据集|英| todo	|	[NIST](https://www.nist.gov/srd/nist-special-database-19)	|[NIST](https://www.nist.gov/srd/nist-special-database-19)|81万张字符图片|
|8|中国城市车牌数据集|中/英| todo	|	[Github](https://github.com/detectRecog/CCPD)	|[Google Driver](https://drive.google.com/file/d/1rdEsCUcIUaYOVRkx5IMTRNA7PcGMmSgc/view) [百度云](https://pan.baidu.com/s/1i5AOjAbtkwb17Zy-NQGqkw) 提取码:hm0U|25万张中国城市车牌图片及车牌检测、识别信息的标注|
|9|银行信用卡数据集|英| todo	|	[heywhale](https://www.kesci.com/home/dataset/5954cf1372ead054a5e25870)	|[百度云](https://pan.baidu.com/s/1lpM863fi_3PIY0TXN5Gd_w) 提取码: plaj|81万张字符图片|
|10|多语言数据集|多种语言| todo	|[ICDAR 2019](https://rrc.cvc.uab.es/?ch=15&com=downloads)	|[rrc](https://rrc.cvc.uab.es/?ch=15&com=downloads)|识别任务中，训练集包含111998个样本;检测任务中，训练集包含10000张图片，共有10种语言，每种语言包含1000张训练图片。测试集包含10000张图片|
|11|SynthText in the Wild dataset|多种语言| todo	|[SynthText](https://www.robots.ox.ac.uk/~vgg/data/scenetext/)	|[github](https://github.com/ankush-me/SynthText) 合成|个综合生成的数据集，其中单词实例放置在自然场景图像中，同时考虑场景布局。数据集由大约80万个合成词实例的800万个图像组成。每个文本实例都使用其文本字符串、字级和字符级边界框进行注释。|
|12|Google FSNS |法语| todo	|[ICDAR 2017](https://rrc.cvc.uab.es/?ch=6)|[ICDAR2017](https://rrc.cvc.uab.es/?ch=6)|Google FSNS数据集包含了100多万张从法国Google街景图片中截取的街道名称标志图片。每个图像包含同一街道名称标志的四个视图。路标上的文字最多可以跨越三行。每一个路标都有一个规范的抄本。|
|13|COCO-Text|多种语言| todo	|[COCO-Text](https://vision.cornell.edu/se3/coco-text-2/)	|[COCO-Text](https://vision.cornell.edu/se3/wp-content/uploads/2019/05/COCO_Text.zip)|63686个图像，145859个文本实例，3个细粒度文本属性|
|14|MSRA-TD500|多种语言| todo	|[MSRA-TD500](http://www.iapr-tc11.org/mediawiki/index.php/MSRA_Text_Detection_500_Database_%28MSRA-TD500%29)	|[MSRA-TD500](http://www.iapr-tc11.org/dataset/MSRA-TD500/MSRA-TD500.zip)|MSRA文本检测500数据库（MSRA-TD500）包含500幅自然图像|
|15|The Uber Text dataset|多种语言| todo	|[ubertext](hhttps://s3-us-west-2.amazonaws.com/uber-common-public/ubertext/index.html)	|[ubertext](https://s3-us-west-2.amazonaws.com/uber-common-public/ubertext/Uber-Text.zip)|街道图像及其文本区域多边形和相应的文本|
|16|Chinese Text in the Wild(CTW)|汉字| todo	|[CTW](hhttps://ctwdataset.github.io/)	|[CTW](https://ctwdataset.github.io/downloads.html)|主要包括3万多幅街景图像中注释的3850个独特的中文文本数据集，其中约有100万个汉字|
|17|The Chars74K dataset|数字/英文| todo	|[chars74k](http://www.ee.surrey.ac.uk/CVSSP/demos/chars74k/)	|[chars74k](http://www.ee.surrey.ac.uk/CVSSP/demos/chars74k/)|提供了超过74K个图像|
|18|MSRA-TD500|多种语言| todo	|[MSRA-TD500](http://www.iapr-tc11.org/mediawiki/index.php/MSRA_Text_Detection_500_Database_%28MSRA-TD500%29)	|[MSRA-TD500](http://www.iapr-tc11.org/dataset/MSRA-TD500/MSRA-TD500.zip)|MSRA文本检测500数据库（MSRA-TD500）包含500幅自然图像|
|19|MTWI-2018 网络图像的文本识别|中文，英文| [图像文件名].txt	|[MTWI 2018 挑战赛一](https://tianchi.aliyun.com/competition/entrance/231684/information)	|[MTWI 2018 挑战赛一](https://tianchi.aliyun.com/competition/entrance/231684/information)|20000张图像，要由合成图像，产品描述，网络广告构成|
|20|mjsynth|英文| [图像文件名].txt	|[Synthetic Word Dataset](https://github.com/clovaai/deep-text-recognition-benchmark) |[百度云](https://pan.baidu.com/s/1KSNLv4EY3zFWHpBYlpFCBQ) 提取码：rryk|训练：MJSynth和SynthText 验证：IIIT, SVT, IC03, IC13, IC15, SVTP, CUTE|
|21|Synthetic Chinese String Dataset|中文/英文/标点| todo	|[Characters Recognition](https://github.com/Sierkinhane/CRNN_Chinese_Characters_Rec) |[百度云](https://pan.baidu.com/s/1ufYbnZAZ1q0AlK7yZ08cvQ)|训练：MJSynth和SynthText 验证：IIIT, SVT, IC03, IC13, IC15, SVTP, CUTE|

## 参考

1. [PaddleOcr](https://github.com/PaddlePaddle/PaddleOCR/blob/release/2.3/doc/doc_ch/datasets.md) 【1～10】
2.  https://github.com/WenmuZhou/OCR_DataSet