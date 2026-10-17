# 三星堆·掘

在线体验：https://cyzcyz669.github.io/sanxingdui/

原型 v0，还在改。你是考古队员：1986 年草棚夜里的抢救发掘，2020 年方舱里的多学科考古，用手指一层一层挖。本仓库只放网页发布文件。画面与声音的来源、授权、哪些是示意，写在页面内「来源」里（点页面底栏）。

## 图片授权

器物照片均为博物馆中**修复后**的样子，来自维基共享资源；坑里的器物是这些照片的抠图（`assets/cut_*.webp`）；两版都玩完后可看「展品轮播」（`assets/ex_*.jpg` 等）。铜罍照片的坑号为摄影者题注。坑、土、灯、象牙、方舱等为示意绘制，声音为合成。

| 文件 | 原图 | 作者 | 授权 |
|---|---|---|---|
| jinzhang.jpg、cut_jinzhang.webp | [Sanxingdui Gold Scepter (9950984395).jpg](https://commons.wikimedia.org/wiki/File:Sanxingdui_Gold_Scepter_(9950984395).jpg) | Gary Todd | CC0 |
| zongmu.jpg、cut_zongmu.webp | [Ancient Bronze Mask from Sanxingdui with Protruding Eyes & Ears a.jpg](https://commons.wikimedia.org/wiki/File:Ancient_Bronze_Mask_from_Sanxingdui_with_Protruding_Eyes_%26_Ears_a.jpg) | Gary Todd | CC0 |
| cut_dali.webp、cut_hand.webp | [Bronze Colossal Standing Figure, Sanxingdui a.jpg](https://commons.wikimedia.org/wiki/File:Bronze_Colossal_Standing_Figure,_Sanxingdui_a.jpg) | Gary Todd | CC0 |
| niutou.jpg、cut_niutou.webp | [三星堆-青铜扭头跪坐人像 sanxingdui.jpg](https://commons.wikimedia.org/wiki/File:三星堆-青铜扭头跪坐人像_sanxingdui.jpg) | Wxmarshall | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |
| dali.jpg | [Bronze Colossal Standing Figure, Sanxingdui a.jpg](https://commons.wikimedia.org/wiki/File:Bronze_Colossal_Standing_Figure,_Sanxingdui_a.jpg) | Gary Todd | CC0 |
| ivory.jpg | [Sanxingdui Ivory Tusk (9951099014).jpg](https://commons.wikimedia.org/wiki/File:Sanxingdui_Ivory_Tusk_(9951099014).jpg) | Gary Todd | CC0 |
| ex_shenshu.jpg | [Sanxingdui Bronze Tree (9950507156).jpg](https://commons.wikimedia.org/wiki/File:Sanxingdui_Bronze_Tree_(9950507156).jpg) | Gary Todd | CC0 |
| ex_taiyang.jpg | [Sanxingdui Bronze Sun Wheel (9950554625).jpg](https://commons.wikimedia.org/wiki/File:Sanxingdui_Bronze_Sun_Wheel_(9950554625).jpg) | Gary Todd | CC0 |
| ex_niaojiao.jpg | [Bronze Bird-man Figure, Sanxingdui a.jpg](https://commons.wikimedia.org/wiki/File:Bronze_Bird-man_Figure,_Sanxingdui_a.jpg) | Gary Todd | CC0 |
| ex_niaotou.jpg | [Bronze Bird Head from Larger Artifact, Sanxingdui 1.jpg](https://commons.wikimedia.org/wiki/File:Bronze_Bird_Head_from_Larger_Artifact,_Sanxingdui_1.jpg) | Gary Todd | CC0 |
| ex_daiguan.jpg | [Ancient Bronze Mask from Sanxingdui- Flanged, with Protruding Pupils a.jpg](https://commons.wikimedia.org/wiki/File:Ancient_Bronze_Mask_from_Sanxingdui-_Flanged,_with_Protruding_Pupils_a.jpg) | Gary Todd | CC0 |
| ex_gongji.jpg（已裁切） | [Sanxingdui Bronze Rooster (9951533324).jpg](https://commons.wikimedia.org/wiki/File:Sanxingdui_Bronze_Rooster_(9951533324).jpg) | Gary Todd | CC0 |
| ex_lei.jpg | [Sanxingdui Bronze Lei from Pit 2 (9951021206).jpg](https://commons.wikimedia.org/wiki/File:Sanxingdui_Bronze_Lei_from_Pit_2_(9951021206).jpg) | Gary Todd | CC0 |

`niutou.jpg` 与其抠图 `cut_niutou.webp`（裁剪、去背景）按 CC BY-SA 4.0 以相同许可提供。

### 发掘现场照片（经授权）

`sckg_k1_1986.jpg`（1986 年 1 号坑）、`sckg_k2_1986.jpg`（1986 年 2 号坑）、`sckg_dali_1986.jpg`（铜大立人像、铜大面具出土）、`sckg_k4_2021.jpg`（2021 年 2 月 26 日 4 号坑）：© 四川省文物考古研究院，出自其官网 [《广汉三星堆遗址》](https://www.sckg.com/shangzhou/1575.html)，**经研究院授权在本作品中使用，不适用任何开放许可，请勿另行转载**。仅缩小尺寸，未裁切、未去水印。

## 第二章“看”试做：纵目面具 3D 示意模型

`look.html`：青铜纵目面具的 3D **示意**模型，照着 Gary Todd 拍的 4 张照片（Wikimedia Commons “Ancient Bronze Mask from Sanxingdui with Protruding Eyes & Ears a/c/d/e”，**CC0**）和展牌尺寸（宽 138、高 66 厘米）手工搭建，**不是扫描**；另参考了两段展厅视频的截图，只用来量形状：侧面轮廓（下巴前探、鼻子下面的嘴凹）照截图量，整体形状再用开源 COLMAP 从其中 15 张截图重建的稀疏点云核对、微调（约 1000 个点到模型表面的距离中位约 1 厘米）；截图和点云本身不在本仓库、也不用作贴图；眼柱长短、厚度、背后和顶上等是估的。`m3d_a/c/d/e.webp` 是这 4 张照片缩小并压平展厅灯光后的贴图。

© dai vu。设计、代码与文案保留所有权利；未经许可，请勿复制、改编或再发布（上表所列第三方图片按其各自授权）。
