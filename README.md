# MultiMap3D
- Unbuntu version：Ubuntu 20.04
- ROS：Noetic
- OpenCV：4.2.0
- Pangolin：0.5



Notion Link : https://www.notion.so/zxytql/3D-1d39be3154784919a8cf9e99b27ae82d

Before using this repo, you have to move to your ros workspace and get the code as a rospackage.

```
cd /${your_workspace}/src
git clone https://github.com/zxytql/MultiMap3D.git
```



## Test & Verify ORB_SLAM2

有TUM、KITTI、EuRoC三种数据集，本实验使用TUM数据集，从http://vision.in.tum.de/data/datasets/rgbd-dataset/download下载序列并解压缩。

```
cd /${your_workspace}/src/MultiMap3D/ORB-SLAM2
./bin/mono_tum Vocabulary/ORBvoc.txt Examples/Monocular/TUMX.yaml PATH_TO_SEQUENCE_FOLDER
```

