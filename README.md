# Dogs vs Cats
##   使用说明
-   此项目在Google Cloud Platform上面开发执行, 具体实例配置为:
12 Core CPUs
60G RAM
100G SSD DISK
Tesla P100

-   操作系统及内核版本:
Distributor ID:	Ubuntu
Description:	Ubuntu 16.04.4 LTS
Release:	    16.04
Codename:	    xenial
Uname:          4.13.0-1015-gcp

-   开发软件环境如下:
Python                  3.5.2
h5py                    2.7.1
image                   1.5.20
ipykernel               4.8.2
ipython                 6.3.1
ipython-genutils        0.2.0
ipywidgets              7.2.1
jupyter                 1.0.0
jupyter-client          5.2.3
jupyter-console         5.2.0
jupyter-core            4.4.0
kaggle                  1.3.6
Keras                   2.1.6
Markdown                2.6.11
matplotlib              2.2.2
notebook                5.4.1
numpy                   1.14.3
opencv-python           3.4.0.12
pandas                  0.22.0
pip                     10.0.1
scikit-image            0.13.1
scikit-learn            0.19.1
scipy                   1.1.0
sklearn                 0.0
tensorboard             1.8.0
tensorflow-gpu          1.8.0

##   关于运行时长
-   在项目一开始, 直接使用CNN进行数据拟合的过程, 耗费将近10分钟.
-   使用Xception对特征向量导出, 此处过程耗费近5分钟.
-   使用Xception导出的特征向量对数据进行拟合, 此处将耗费近0.5分钟.

##   关于运行状态截图
-   已导出所有执行过程与结果, 详见附件Dogs_vs_Cats.html
