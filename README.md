# Machine Learning ReadingCircle
Hands-on形式の初心者向け深層学習輪読会のログ 

＊Book site: 「[Hands-On Machine Learning with Scikit-Learn and TensorFlow](http://shop.oreilly.com/product/0636920052289.do)」　

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

==== 2. Book Information  ==================================================
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
実行環境の準備(windows)

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
著者オリジナルコード
```
[https://github.com/ageron/handson-ml/](https://github.com/ageron/handson-ml)

```
※本に掲載されていないコードが多数掲載されています

==== 4. Reading Circle Schedule  ==================================================
開催日
月一回で開催しています。
```
2018年1月31日分から、補助本を使います。
日本語補助本(ゼロから作るディープラーニング)
 - [https://github.com/oreilly-japan/deep-learning-from-scratch](https://github.com/oreilly-japan/deep-learning-from-scratch)


|    | 日時  | md,ipynb |　章  |ページ |　内容  | 
|---|---|---|---|---|---| 
|1回目  | [2017/1/30](170130_p1.md)  11:00-12:00 |[p1.md](170130_p1.md)| 1 | 1-19　| What is Machine learning?  |
|2回目  | [2017/2/13](170213_p19.md)  11:00-12:00 |[p19.md](170213_p19.md)| 1 | 19-26　| Types of Machine Learning systems   |
|3回目  | [2017/3/13](170313_p26.md)  11:00-12:00 |[p26.md](170313_p26.md)| 1 | 26-36　| Main challenges of machine Learning |
|4回目  | [2017/4/10](170410_p37.md)  11:00-12:00 |[p37.md](170410_p37.md)| 1 | 37-44　| End-to-end Machine Learning project  |
|5回目  | [2017/5/8](170508_p49.md)  11:00-12:00 |[p49.ipynb](170508_p49.ipynb), [p53.ipynb](170508_p53.ipynb) | 2  | 49-57　| Get the data  |
|6回目  | [2017/6/5](170605_p57.md)  11:00-12:00 |[p57.ipynb](170605_p57.ipynb)| 2  | 57-67 | Visualizing geographical data |
|7回目  | [2017/7/3](170703_p67.md)  11:00-12:00 |[p67.md](170703_p67.md)| 2 | 67-69　| Handling text and categorical attributes  |
|8回目  | [2017/7/25](170725_p73.md)(火)  11:00-12:00 |[p73.md](170725_p73.md)| 2 | 69-81　| Custom transformers  |
|9回目  | [2017/9/4](170904_p83.md)  11:00-12:00 |[p83.ipynb](170904_p83.ipynb)| 3 | 83-91　| Classification, MNIST  |
|10回目  | [2017/10/2](171002_p91.ipynb)  11:00-12:00 |[p91.ipynb](171002_p91.ipynb)| 3 | 91-110　| Precision/Recall tradeoff  |
|11回目  | [2017/11/6](171106_p241.md)  11:00-12:00 |[p241.ipynb](171106_p241.ipynb)| 9 | 241-253　| Tensorflow  |
|12回目  | [2017/12/22](171222_p254.ipynb)  11:00-12:00 |[p254.ipynb](171222_p254.ipynb)| 9 | 254-　| Tensorboard  |
|13回目  | [2018/1/31](180131_AUX_CH3.ipynb)  11:00-12:00 |[180131_AUX_CH3.ipynb](180131_AUX_CH3.ipynb)| Aux.3 | 39-82　| ニューラルネットワーク |
|14回目  | [2018/2/13](180213_AUX_CH4.ipynb)  11:00-12:00 |[180213_AUX_CH4.ipynb](180213_AUX_CH4.ipynb)| Aux.4 | 83-122　| ニューラルネットワークの学習 |
|16回目  | [2018/2/26](180226_AUX_CH5.ipynb)  11:00-12:00 |[180226_AUX_CH5.ipynb](180226_AUX_CH5.ipynb)| Aux.5 | 123-164　| 誤差逆伝播法 |
|17回目  | [2018/3/19](180319_AUX_CH6a.ipynb)  11:00-12:00 |[180319_AUX_CH6a.ipynb](180319_AUX_CH6a.ipynb)| Aux.6 | 　| 学習のテクニック |
|18回目  | [2018/4/12](180319_AUX_CH6b.ipynb)  11:00-12:00 |[180412_AUX_CH6b.ipynb](180412_AUX_CH6b.ipynb)| Aux.6 | 　| 学習のテクニック |
