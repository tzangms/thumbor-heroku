thumbor-heroku
==============

[thumbor](https://github.com/thumbor/thumbor) is a smart imaging service. It enables on-demand crop, resizing and flipping of images.

It let you generate thumbnail on the fly.

You can clone this repo and deploy to heroku, then you'll get your own `thumbor` in 5 minutes.


```
$ git clone https://github.com/tzangms/thumbor-heroku.git
$ heroku create
$ git push heroku master
```

Wait for a moment to get your packages to install on heroku. After you console is stopped.

```
$ heroku open
```

then you can access something like this below

```
http://<your-herokuapp.com>/unsafe/300x300/media.curator.im/images/164483516927300/556890257686622_945544_556890257686622_1062581386_n.jpg
```


Here is the screenshot

![](https://raw.githubusercontent.com/tzangms/thumbor-heroku/master/docs/screenshot.png)
