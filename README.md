# Deploying-Flask-To-OpenShift 
Deploying a Flask App To OpenShift Tutorial 📝 

* [Youtube Demo](https://youtu.be/PlomZkYcdYU)   

今天教大家如何佈署 Flask App 到 [OpenShift](https://www.openshift.com/) 

[OpenShift](https://www.openshift.com/) 免費版本

* 可以創造 3個 app。


更多說明請參考 [OpenShift](https://www.openshift.com/) 


## 教學

### 步驟一

先註冊 OpenShift 帳號，請到 [OpenShift](https://www.openshift.com/)  註冊

### 步驟二

<b>新增 SSH keys</b>

可參考 github 的 [generating-a-new-ssh-key](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/) 說明

或是

參考小弟之前拍的影片 [github基本教學 - 從無到有](https://www.youtube.com/watch?v=py3n6gF5Y00)

影片教學包含如何產生 <b>SSH key</b>

如下圖將自己的 <b>id_rsa.pub</b> 設定完畢即可

![alt tag](http://i.imgur.com/cM87Psl.jpg)

### 步驟三

開始建立 flask web app

![alt tag](http://i.imgur.com/GqBTCoA.jpg)

[OpenShift](https://www.openshift.com/) 支援非常多的程式語言，

找到 python ，然後點選 <b>see all</b> 就可以找到 Flask 了

![alt tag](http://i.imgur.com/cIHT8Cv.jpg)

![alt tag](http://i.imgur.com/wy5Ei5r.jpg)

接著輸入網址的名稱，如果輸入的不合法，他會提醒你

![alt tag](http://i.imgur.com/MVBsRUZ.jpg)

接著按 <b> Create Application </b>，然後就是等~~~~~

![alt tag](http://i.imgur.com/6CBMxAU.jpg)

等他跑完，就會跳到下面這個畫面

![alt tag](http://i.imgur.com/Kd7k1jJ.jpg)

基本上就是 git 的操作，如不清楚什麼是 [Git](https://git-scm.com/)

可以參考我之前寫的 [Git-Tutorials](https://github.com/twtrubiks/Git-Tutorials)

![alt tag](http://i.imgur.com/yrqEEAq.jpg)

clone 下來預設的資料夾底下會有這些東西

![alt tag](http://i.imgur.com/vEowCmI.jpg)

可以直接點紅色框起來的地方

![alt tag](http://i.imgur.com/8B6RKYb.jpg)

以下範例是我的

[http://deployingflasktutorials-twtrubikscode.rhcloud.com/](http://deployingflasktutorials-twtrubikscode.rhcloud.com/)

會直接跳到你的網站，預設 Flask app 版面如下

![alt tag](http://i.imgur.com/uoBDv0o.jpg)

如果你需要重新佈署，基本上就是 git 的操作

![alt tag](http://i.imgur.com/N8mOKAe.jpg)

我修改掉標題的部分

![alt tag](http://i.imgur.com/mCeSUxy.jpg)


以上就是 Deploying-Flask-To-OpenShift  的方法，更多資訊可以參考 

[Getting Started with the Flask Microframework](https://developers.openshift.com/languages/python/flask.html)


## Reference 
* [OpenShift](https://www.openshift.com/) 


## License
MIT license
