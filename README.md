# Dogs vs Cats
##   使用说明
-   此项目在Google Cloud Platform上面开发执行, 具体实例配置为:<br>
12 Core CPUs<br>
60G RAM<br>
100G SSD DISK<br>
Tesla P100<br>
<br>
-   操作系统及内核版本:<br>
Distributor ID:	Ubuntu<br>
Description:	Ubuntu 16.04.4 LTS<br>
Release:	    16.04<br>
Codename:	    xenial<br>
Uname:          4.13.0-1015-gcp<br>
<br>
-   开发软件环境如下:<br>
Python                  3.5.2<br>
h5py                    2.7.1<br>
image                   1.5.20<br>
ipykernel               4.8.2<br>
ipython                 6.3.1<br>
ipython-genutils        0.2.0<br>
ipywidgets              7.2.1<br>
jupyter                 1.0.0<br>
jupyter-client          5.2.3<br>
jupyter-console         5.2.0<br>
jupyter-core            4.4.0<br>
kaggle                  1.3.6<br>
Keras                   2.1.6<br>
Markdown                2.6.11<br>
matplotlib              2.2.2<br>
notebook                5.4.1<br>
numpy                   1.14.3<br>
opencv-python           3.4.0.12<br>
pandas                  0.22.0<br>
pip                     10.0.1<br>
scikit-image            0.13.1<br>
scikit-learn            0.19.1<br>
scipy                   1.1.0<br>
sklearn                 0.0<br>
tensorboard             1.8.0<br>
tensorflow-gpu          1.8.0<br>
<br>
##   关于运行时长
-   在项目一开始, 直接使用CNN进行数据拟合的过程, 耗费将近10分钟.<br>
-   使用Xception对特征向量导出, 此处过程耗费近5分钟.<br>
-   使用Xception导出的特征向量对数据进行拟合, 此处将耗费近0.5分钟.<br>

##   关于运行状态截图
-   已导出所有执行过程与结果, 详见附件Dogs_vs_Cats.html<br>
