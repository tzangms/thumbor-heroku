Thumbor on heroku
=====================

[thumbor](https://github.com/thumbor/thumbor) 是一個動態縮圖服務, 也是[小海嚴選](http://curator.im/)背後採用的縮圖機制。

簡單來說, 可以及即時直接讀取原圖然後輸出你要的縮圖, 可以自定大小。


這個 repo 就是為了簡化所有流程而做的, 你只需要遵照以下幾個步驟, 就可以在五分鐘內開始擁有你自己的動態縮圖服務。


安裝流程
----------

```
$ git clone https://github.com/tzangms/thumbor-heroku.git
$ heroku create
$ git push heroku master
```

等它安裝完, 接著就可以打開屬於你自己的 thumbor

```
$ heroku open
```

接著然後輸入你要的縮圖圖片網址, 便可以動態產生縮圖, 這裡以寬高 300x300 為例子。

```
http://<your-herokuapp.com>/unsafe/300x300/media.curator.im/images/164483516927300/556890257686622_945544_556890257686622_1062581386_n.jpg
```


這裡便是我要的 300x300 的縮圖

![](https://raw.githubusercontent.com/tzangms/thumbor-heroku/master/docs/screenshot.png)

沒錯, 不到五分鐘! 要是超過 5 分鐘, 一定是你網路太慢, 或是 heroku 太慢, 絕對不是我的問題

更多詳細功能請見 [thumbor](https://github.com/thumbor/thumbor)
