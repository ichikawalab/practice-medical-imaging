# practice-medical-imaging

「医療画像処理工学演習」の教材です．

## 内容

| ファイル | 内容 |
| --- | --- |
| [imgproc/09_3d_ai.ipynb](imgproc/09_3d_ai.ipynb) | 第9回 3次元画像処理とAIによる医用画像処理：TotalSegmentatorによる臓器の自動抽出（Google Colab用） |
| [imgproc/data/LIDC-IDRI-0265_CT.zip](imgproc/data/LIDC-IDRI-0265_CT.zip) | 第9回で使用する胸部CT画像（DICOM，133枚） |

第9回のノートブックは，次のリンクからGoogle Colabで開けます．

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ichikawalab/practice-medical-imaging/blob/main/imgproc/09_3d_ai.ipynb)

## 使用している画像とソフトウェア

### 画像：LIDC-IDRI（The Cancer Imaging Archive）

`imgproc/data/LIDC-IDRI-0265_CT.zip` は，The Cancer Imaging Archive（TCIA）で公開されている LIDC-IDRI の症例 LIDC-IDRI-0265 の胸部CT画像です．
TCIAにより匿名化されたデータを，変更せずに収録しています．
ライセンスは [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/) です．利用条件は zip 内の `LICENSE` を参照してください．

- Armato SG III, McLennan G, Bidaut L, et al. Data From LIDC-IDRI [Data set]. The Cancer Imaging Archive. 2015. https://doi.org/10.7937/K9/TCIA.2015.LO9QL9SX
- Armato SG III, McLennan G, Bidaut L, et al. The Lung Image Database Consortium (LIDC) and Image Database Resource Initiative (IDRI): a completed reference database of lung nodules on CT scans. Medical Physics. 2011;38(2):915–931. https://doi.org/10.1118/1.3528204
- Clark K, Vendt B, Smith K, et al. The Cancer Imaging Archive (TCIA): maintaining and operating a public information repository. Journal of Digital Imaging. 2013;26(6):1045–1057. https://doi.org/10.1007/s10278-013-9622-7

### ソフトウェア：TotalSegmentator

- Wasserthal J, Breit HC, Meyer MT, et al. TotalSegmentator: robust segmentation of 104 anatomic structures in CT images. Radiology: Artificial Intelligence. 2023;5(5):e230024. https://doi.org/10.1148/ryai.230024
- https://github.com/wasserth/TotalSegmentator

TotalSegmentatorは研究用のソフトウェアであり，医療機器ではありません．
