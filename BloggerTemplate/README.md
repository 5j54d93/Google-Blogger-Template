# Customize Google Blogger Template

## Tag：`<html>`

- [LINE 3](https://github.com/5j54d93/Google-Blogger-Template/blob/e8952e14d92cbbcfeb4b5ab6eef608db19608c15/BloggerTemplate/BloggerTemplate.xhtml#L3)：change `lang='zh-TW'` to fit your blogger language, if yours is English, change to `lang='en'`

```xml
<html lang='zh-TW' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'> 
```

## Tag：`<head>`

- [LINE 6 ～ LINE 30](https://github.com/5j54d93/Google-Blogger-Template/blob/e8952e14d92cbbcfeb4b5ab6eef608db19608c15/BloggerTemplate/BloggerTemplate.xhtml#L6)：You don't need that `<script>`, but it's fun！

```js
<script>
/**
                                                       __----~~~~~~~~~~~------___
                                      .  .   ~~//====......          __--~ ~~
                      -.            \_|//     |||\\  ~~~~~~::::... /~
                   ___-==_       _-~o~  \/    |||  \\            _/~~-
           __---~~~.==~||\=_    -_--~/_-~|-   |\\   \\        _/~
       _-~~     .=~    |  \\-_    &#39;-~7  /-   /  ||    \      /
     .~       .~       |   \\ -_    /  /-   /   ||      \   /
    /  ____  /         |     \\ ~-_/  /|- _/   .||       \ /
    |~~    ~~|--~~~~--_ \     ~==-/   | \~--===~~        .\
             &#39;         ~-|      /|    |-~\~~       __--~~
                         |-~~-_/ |    |   ~\_   _-~            /\
                              /  \     \__   \/~                \__
                          _--~ _/ | .-~~____--~-/                  ~~==.
                         ((-&gt;/~   &#39;.|||&#39; -_|    ~~-/ ,              . _||
                                    -_     ~\      ~~---l__i__i__i--~~_/
                                    _-~-__   ~)  \--______________--~~
                                  //.-~~~-~_--~- |-------~~~~~~~~
                                         //.-~~~--\
                                  神獸保佑 程式碼沒 Bug

*/
console.log(&#39;社群連結 https://linktr.ee/5j_54d93&#39;);
</script>
```

- [LINE 32](https://github.com/5j54d93/Google-Blogger-Template/blob/e8952e14d92cbbcfeb4b5ab6eef608db19608c15/BloggerTemplate/BloggerTemplate.xhtml#L32)：refresh page on every 360 second, you could change 360 to any number you want or delete this line if you don't want your blog to refresh at all

```xml
<meta content='360' http-equiv='refresh'/>
```

- [LINE 33](https://github.com/5j54d93/Google-Blogger-Template/blob/e8952e14d92cbbcfeb4b5ab6eef608db19608c15/BloggerTemplate/BloggerTemplate.xhtml#L33)：set a theme color of your website or delete this line, because this is not required

```xml
<meta content='#25292f' name='theme-color'/>
```
