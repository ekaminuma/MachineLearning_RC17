# Machine Learning ReadingCircle
Hands-on形式の初心者向け深層学習輪読会のログ 

```
初心者向け深層学習輪読演習を行います(NIG遺伝研大量遺伝　神沼)

    ＊ノートパソコン必携
    ＊演習形式
    ＊月一回月曜日11:00-12:00 NIG-W403
　   ＊python with jupyter notebook (anaconda installed). 
    ＊2017年1月よりスタート

==== 0. Book for Machine Learning ReadingCircle  ===========================

BOOK TITLE: "Hands-On Machine Learning with Scikit-Learn and TensorFlow"
AUTHOR : Aurélien Géron
Publisher: O'Reilly Media
Release Date: March 2017

==== 1. Book Information  ==================================================
```
＊Book title: 「[Hands-On Machine Learning with Scikit-Learn and TensorFlow](http://shop.oreilly.com/product/0636920052289.do)」　
```
Table of Contents
Chapter 1 The Machine Learning landscape
Chapter 2 End-to-end Machine Learning Project
Chapter 3 Classification
Chapter 4 Training Linear Models
Chapter 5 Support Vector Machines
Chapter 6 Decision Trees and Random Forests
Chapter 7 Ensemble Methods
Chapter 8 Dimensionality Reduction
Chapter 9 Up and Running with TensorFlow
Chapter 10 Introduction to Artificial Neural Networks
Chapter 11 Training Deep Neural Nets
Chapter 12 Distributing TensorFlow across Devices and Servers
Chapter 13 Convolutional Neural Networks
Chapter 14 Recurrent Neural Networks
Chapter 15 Autoencoders
Chapter 16 Reinforcement Learning

＊Download a pdf from the following Google drive
https://drive.google.com/file/d/0BxjNviDTeO_Lem9wcEVOdC1zeGs/view?usp=sharing


==== 2. How to Install Tensorflow  ==================================================
＜実行環境の準備(windows)＞

Iでの準備
(1) anaconda install in windows
(2) メニュからanaconda prompt起動
(2) $ jupyter notebook
(3) web access to http://localhost:8888/ (web browser上でjupyter notebookが起動される)
(4) web browserでプログラムを書いたら.ipynbで保存。ファイルをgithub.comにアップロードすると実行結果が視覚化される。
---------------------------------------------
IIでの準備
(5) anaconda prompt上で $ pip install tensorflow (ローカルインストール用。スパコンGPU環境での利用方法は後述)

==== 3. Author Original Exercise Codes  ==================================================
＜著者コード＞
```
[https://github.com/ageron/handson-ml/](https://github.com/ageron/handson-ml)

```

==== 4. Reading Circle Schedule  ==================================================
開催日
```
|    | 日時  | md,ipynb |　章  |ページ |　内容  | 
|---|---|---|---|---|---| 
|1回目  | [2017/1/30](170130_p1.md)  11:00-12:00 |[p1.md](170130_p1.md)| 1 | 1-19　| What is Machine learning?  |
|2回目  | [2017/2/13](170213_p19.md)  11:00-12:00 |[p19.md](170213_p19.md)| 1 | 19-26　| Types of Machine Learning systems   |
|3回目  | [2017/3/13](170313_p26.md)  11:00-12:00 |[p26.md](170313_p26.md)| 1 | 26-36　| Main challenges of machine Learning |
|4回目  | [2017/4/10](170410_p37.md)  11:00-12:00 |[p37.md](170410_p37.md)| 1 | 37-44　| End-to-end Machine Learning project  |
|5回目  | [2017/5/8](170508_p49.md)  11:00-12:00 |[p49.ipynb](170508_p49.ipynb), [p53.ipynb](170508_p53.ipynb) | 2  | 49-57　| Get the data  |
|6回目  | [2017/6/5](170605.md)  11:00-12:00 |[p57.ipynb](170605_p57.ipynb)| 2  | 57-67 | Visualizing geographical data |
|7回目  | [2017/7/3](170703.md)  11:00-12:00 |[p67.ipynb](170703_p67.ipynb)| 2 | 67-69　| Handling text and categorical attributes  |
|8回目  | [2017/7/25](170725.md)(火)  11:00-12:00 || 2 | 69-81　| Custom transformers  |
|9回目  | [2017/9/4](170904.md)  11:00-12:00 |[p83.ipynb](170904_p83.ipynb)| 3 | 83-91　| Classification, MNIST  |
|10回目  | [2017/10/2](171002.md)  11:00-12:00 |[p91.ipynb](171002_p91.ipynb)| 3 | 91-110　| Precision/Recall tradeoff  |
|11回目  | [2017/11/20](171120.md)  11:00-12:00 |[p241.ipynb](171106_p241.ipynb)| 9 | 241-253　| Tensorflow  |
|12回目  | [2017/12/7](171207.md)  11:00-12:00 || 9 | 254-　| Tensorboard  |
