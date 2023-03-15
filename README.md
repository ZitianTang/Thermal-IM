# Thermal-IM Dataset
**What Happened 3 Seconds Ago? Inferring the Past with Thermal Imaging, CVPR 2023**

Zitian Tang, Wenjie Ye, Wei-Chiu Ma, Hang Zhao

<br>

This repository introduces our Thermal Indoor Motion dataset (Thermal-IM), which contains synchronized RGB-Thermal and RGB-Depth videos about indoor human motion. This dataset covers various human-object interactions in living room and office room. Many of these human activities can leave thermal imprints on the objects. This dataset also provides annotated human action time and estimated 2D and 3D human poses.

## Download

You can download Thermal-IM dataset from here.

## Dataset Contents

Each folder in the dataset contains a clip described by the following files:

+ **Videos**:
  + RGB channel of the RGB-Thermal camera: `RGBT_RGB.mp4`
  + Thermal channel of the RGB-Thermal camera: `RGBT_T.mp4`
  + RGB channel of the RGB-Depth camera: `RGBD_RGB.mp4`
+ **Depth point cloud** of the RGB-Depth camera: `RGBD_D/*.npy`
+ **Action annotation**: `annotation.json`
+ **Extrinsic parameters** and **estimated human poses**: `info.npz` 

#### Joint Types

We use openpose25 ...

## Citation

We will be happy if you find this dataset useful. Please cite our work if you use it.

```
@inproceedings{ThermalIM2023,
      title = {What Happened 3 Seconds Ago? Inferring the Past with Thermal Imaging}, 
      author = {Zitian Tang and
      	Wenjie Ye and
      	Wei-Chiu Ma and
      	Hang Zhao},
      booktitle = {CVPR},
      year = {2023}
}
```



## LICENSE

Thermal-IM Dataset is released under blabla...

### 