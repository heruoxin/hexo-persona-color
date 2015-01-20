# Persona Color

Theme for [Hexo].

[Demo]

![4 color schemes](http://ww3.sinaimg.cn/large/66cab368gw1ed07yp2yjfj21400mi7a2.jpg)

You can edit the color schemes in `themes/persona-color/source/css/_base/variable.styl`

## Install

Execute the following command and modify `theme` in `_config.yml` to `persona-color`.

```
git clone git://github.com/heruoxin/hexo-persona-color.git themes/persona-color
```

## Update

Execute the following command to update Persona Color.

```
cd themes/persona-color
git pull
```

## Config

Default config:

``` 

photo: /icon.jpg

email: 
twitter: 
facebook: 
googleplus: 
github: 
pinterest: 
linkedin: 
instagram: 
zhihu: 
weibo: 
renren: 

addthis:
  enable: false
  pubid:
  facebook: true
  twitter: true
  google: true
  pinterest: true

fancybox: true
bighomepage: true
usecdn: true

google_analytics: 
rss: /atom.xml
```

- **photo** - Your Photo. The best size is 340x340.
- **twitter** - Your twitter username,will show on the sidebar (Desktop view) or the header (Mobile view).
- **facebook and etc.** - Same as twitter.
- **addthis** - Share buttons at the buttom of articles (Powered by [AddThis]).
  - **enable** - Enable share buttons (true/false).
  - **pubid** - Profile ID of [AddThis].
  - **facebook** - Enable Facebook button.
  - **twitter** - Enable Twitter button.
  - **google** - Enable Google+ button.
  - **pinterest** - Enable Pinterest button.
- **fancybox** - Enable [Fancybox]
- **bighomepage** - Using html5 history.pushState API to get better user experience. But may slow down the homepage.
- **usecdn** - Using CNDJS and some other CDN to improve a few loading speed. You can disable it if your web server is fast.
- **google_analytics** - Google Analytics ID(example: UA-xxxxxxxx-x)
- **rss** - RSS subscription link (change if using Feedburner)


[Hexo]: http://zespia.tw/hexo/
[Demo]: http://1ittlecup.com/
[AddThis]: https://www.addthis.com
[Fancybox]: http://fancyapps.com/fancybox/
