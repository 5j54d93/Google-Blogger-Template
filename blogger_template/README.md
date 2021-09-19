# Custom your own Blogger theme（template）

There are many html code（include Google AdSense code）you need to change to fit your blog！

## Blogger Template｜Overview

1. [Title](https://github.com/5j54d93/Google-Blogger-Template/tree/main/blogger_template#blogger-templatetitle)
2. [Navigation Bar](https://github.com/5j54d93/Google-Blogger-Template/tree/main/blogger_template#blogger-templatenavigation-bar)
   - [Home](https://github.com/5j54d93/Google-Blogger-Template/tree/main/blogger_template#home)
   - [Pages](https://github.com/5j54d93/Google-Blogger-Template/tree/main/blogger_template#pages)
   - [Social Media Links](https://github.com/5j54d93/Google-Blogger-Template/tree/main/blogger_template#social-media-links)
3. [Body](https://github.com/5j54d93/Google-Blogger-Template/tree/main/blogger_template#blogger-templatebody)
   - [Selected feature article](https://github.com/5j54d93/Google-Blogger-Template/tree/main/blogger_template#selected-feature-article)
   - [5 latest articles](https://github.com/5j54d93/Google-Blogger-Template/tree/main/blogger_template#5-latest-articles)
   - [10 most popular articles](https://github.com/5j54d93/Google-Blogger-Template/tree/main/blogger_template#10-most-popular-articles)
4. [Side Bar](https://github.com/5j54d93/Google-Blogger-Template/tree/main/blogger_template#blogger-templateside-bar)
   - [About & Share Buttons](https://github.com/5j54d93/Google-Blogger-Template/tree/main/blogger_template#about--share-buttons)
   - [Views](https://github.com/5j54d93/Google-Blogger-Template/tree/main/blogger_template#views)
   - [Followers](https://github.com/5j54d93/Google-Blogger-Template/tree/main/blogger_template#followers)
5. [Footer](https://github.com/5j54d93/Google-Blogger-Template/tree/main/blogger_template#blogger-templatefooter)
- [License](https://github.com/5j54d93/Google-Blogger-Template/tree/main/blogger_template#blogger-templatelicense-2021-看我所見-all-rights-reserved)

## Blogger Template｜Title

- [Line 11](https://github.com/5j54d93/Google-Blogger-Template/blob/5749cb31e611e13696b17134fe850bfa8ff873c9/blogger_template/theme.html#L11)：Change `看我所見` to your blog's name.

```html
<title>看我所見&#65372;<data:view.title.escaped/></title>
```

## Blogger Template｜Navigation Bar

<img src="https://github.com/5j54d93/Google-Blogger-Template/blob/main/blogger_template/photo/Navigation%20Bar：Pages.png" width='100%' height='100%'/>

### Home

- [Line 80](https://github.com/5j54d93/Google-Blogger-Template/blob/4db6ef7e27f00875297414f256b635e39fd3db29/blogger_template/theme.html#L80)：Change `看我所見` to your blog's name.

```html
<a class='navbar-brand fs-4 fw-bold text-white' href='/'>看我所見</a>
```

### Pages

- [Line 84](https://github.com/5j54d93/Google-Blogger-Template/blob/4db6ef7e27f00875297414f256b635e39fd3db29/blogger_template/theme.html#L84)：`首頁` means HOME, you could translate into your language.

```html
<li><a class='nav-link me-3' href='/'>首頁</a></li>
```

- [Line 85](https://github.com/5j54d93/Google-Blogger-Template/blob/4db6ef7e27f00875297414f256b635e39fd3db29/blogger_template/theme.html#L85)：`發燒文章` means Popular Article, you could translate into your language.  

```html
<li><a class='nav-link text-white me-3' href='#PopularPosts1'>發燒文章</a></li>
```

- [Line 86](https://github.com/5j54d93/Google-Blogger-Template/blob/4db6ef7e27f00875297414f256b635e39fd3db29/blogger_template/theme.html#L86)：`搜尋` means Search, you could translate into your language and you need to change the link in `href=''` to your search page's link.  

```html
<li><a class='nav-link text-white me-3' href='https://sharing-life-in-tw.blogspot.com/p/search.html' target='_blank'>搜尋</a></li>
```

- [Line 87](https://github.com/5j54d93/Google-Blogger-Template/blob/4db6ef7e27f00875297414f256b635e39fd3db29/blogger_template/theme.html#L87)：`社群` means Social Media, you could translate into your language and you need to change the link in `href=''` to your link like [linktree](https://linktr.ee).  

```html
<li><a class='nav-link text-danger me-3' href='https://linktr.ee/5j_54d93' target='_blank'>社群</a></li>
```

- [Line 88](https://github.com/5j54d93/Google-Blogger-Template/blob/4db6ef7e27f00875297414f256b635e39fd3db29/blogger_template/theme.html#L88)：`贊助` means Donate, you could translate into your language and you need to change the link in `href=''` to your donate page's link.

```html
<li><a class='nav-link text-info me-3' href='https://sharing-life-in-tw.blogspot.com/p/donate.html' target='_blank'>贊助</a></li>
```

### Social Media Links

<img src="https://github.com/5j54d93/Google-Blogger-Template/blob/main/blogger_template/photo/Navigation%20Bar：Social%20Media%20Links.png" width='100%' height='100%'/>

- From [Line 91](https://github.com/5j54d93/Google-Blogger-Template/blob/842d47e501f94b02cb60291e2dd77d65834cc48f/blogger_template/theme.html#L91) to [Line 104](https://github.com/5j54d93/Google-Blogger-Template/blob/842d47e501f94b02cb60291e2dd77d65834cc48f/blogger_template/theme.html#L104)：All you need to do is change the link in `href=''` to your social media's link.

```html
<!--YT-->
<li><a class='btn btn-outline-danger yt-red me-1' data-bs-placement='bottom' data-bs-toggle='tooltip' href='https://www.youtube.com/channel/UC71TBGWnlb26oMC9uS2xnuw' role='button' target='_blank' title='YouTube'><svg class='bi bi-youtube' fill='currentColor' height='16' viewBox='0 0 16 16' width='16' xmlns='http://www.w3.org/2000/svg'><path d='M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.007 2.007 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.007 2.007 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31.4 31.4 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.007 2.007 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A99.788 99.788 0 0 1 7.858 2h.193zM6.4 5.209v4.818l4.157-2.408L6.4 5.209z'/></svg></a></li>
<!--IG-->
<li><a class='btn btn-outline-danger day-orange me-1' data-bs-placement='bottom' data-bs-toggle='tooltip' href='https://www.instagram.com/5j_54d93/' role='button' target='_blank' title='Instagram'><svg class='bi bi-instagram' fill='currentColor' height='16' viewBox='0 0 16 16' width='16' xmlns='http://www.w3.org/2000/svg'><path d='M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.917 3.917 0 0 0-1.417.923A3.927 3.927 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.916 3.916 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.926 3.926 0 0 0-.923-1.417A3.911 3.911 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0h.003zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599.28.28.453.546.598.92.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.47 2.47 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.478 2.478 0 0 1-.92-.598 2.48 2.48 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233 0-2.136.008-2.388.046-3.231.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92.28-.28.546-.453.92-.598.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045v.002zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92zm-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217zm0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334z'/></svg></a></li>
<!--Clubhouse-->
<li><a class='btn btn-outline-warning clubhouse-yellow me-1' data-bs-placement='bottom' data-bs-toggle='tooltip' href='https://www.joinclubhouse.com/@5j_54d93' role='button' target='_blank' title='Clubhouse'><span class='material-icons' style='font-size: 16px; vertical-align: middle;'>waving_hand</span></a></li>
<!--Google Maps-->
<li><a class='btn btn-outline-success map-green me-1' data-bs-placement='bottom' data-bs-toggle='tooltip' href='https://maps.app.goo.gl/UZGou7XvCptory3v9?ltclid' role='button' target='_blank' title='Google Local Guides'><svg class='bi bi-geo-alt-fill' fill='currentColor' height='16' viewBox='0 0 16 16' width='16' xmlns='http://www.w3.org/2000/svg'><path d='M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10zm0-7a3 3 0 1 1 0-6 3 3 0 0 1 0 6z'/></svg></a></li>
<!--Twitter-->
<li><a class='btn btn-outline-primary day-twitter-blue me-1' data-bs-placement='bottom' data-bs-toggle='tooltip' href='https://twitter.com/5j_54d93' role='button' target='_blank' title='Twitter'><svg class='bi bi-twitter' fill='currentColor' height='16' viewBox='0 0 16 16' width='16' xmlns='http://www.w3.org/2000/svg'><path d='M5.026 15c6.038 0 9.341-5.003 9.341-9.334 0-.14 0-.282-.006-.422A6.685 6.685 0 0 0 16 3.542a6.658 6.658 0 0 1-1.889.518 3.301 3.301 0 0 0 1.447-1.817 6.533 6.533 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.325 9.325 0 0 1-6.767-3.429 3.289 3.289 0 0 0 1.018 4.382A3.323 3.323 0 0 1 .64 6.575v.045a3.288 3.288 0 0 0 2.632 3.218 3.203 3.203 0 0 1-.865.115 3.23 3.23 0 0 1-.614-.057 3.283 3.283 0 0 0 3.067 2.277A6.588 6.588 0 0 1 .78 13.58a6.32 6.32 0 0 1-.78-.045A9.344 9.344 0 0 0 5.026 15z'/></svg></a></li>
<!--Facebook-->
<li><a class='btn btn-outline-primary day-facebook-blue me-1' data-bs-placement='bottom' data-bs-toggle='tooltip' href='https://www.facebook.com/5j54d93/' role='button' target='_blank' title='Facebook'><svg class='bi bi-facebook' fill='currentColor' height='16' viewBox='0 0 16 16' width='16' xmlns='http://www.w3.org/2000/svg'><path d='M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951z'/></svg></a></li>
<!--Twitch-->
<li><a class='btn btn-outline-primary day-purple' data-bs-placement='bottom' data-bs-toggle='tooltip' href='https://www.twitch.tv/5j_54d93' role='button' target='_blank' title='Twitch'><svg class='bi bi-twitch' fill='currentColor' height='16' viewBox='0 0 16 16' width='16' xmlns='http://www.w3.org/2000/svg'><path d='M3.857 0 1 2.857v10.286h3.429V16l2.857-2.857H9.57L14.714 8V0H3.857zm9.714 7.429-2.285 2.285H9l-2 2v-2H4.429V1.143h9.142v6.286z'/><path d='M11.857 3.143h-1.143V6.57h1.143V3.143zm-3.143 0H7.571V6.57h1.143V3.143z'/></svg></a></li>
```

## Blogger Template｜Body

### Selected feature article

<img src="https://github.com/5j54d93/Google-Blogger-Template/blob/main/blogger_template/photo/Body：Selected%20feature%20article.png" width='100%' height='100%'/>

- [Line 113](https://github.com/5j54d93/Google-Blogger-Template/blob/951e2ff55caf4b06ba18ca5160f86bceb8eaa419/blogger_template/theme.html#L113)：this selected feature article will only show on Home page

```html
<b:if cond='data:blog.url == data:blog.homepageUrl'>
```

- [Line 117](https://github.com/5j54d93/Google-Blogger-Template/blob/951e2ff55caf4b06ba18ca5160f86bceb8eaa419/blogger_template/theme.html#L117)：
  - `發燒文章` means Trending article, you could translate into your language.
  - `瀏覽次數` means Views, you could translate into your language and edit the view number correctly afterward.
  - `發布日期` means Post day, you could translate into your language and edit the date correctly afterward.

```html
<strong class='d-inline-block mb-4' style='border-color: #03C755; color: #03C755;'>發燒文章 #1<span class='day-text night'>&#12539;瀏覽次數&#65306;7.46 萬次&#12539;發布日期&#65306;2019 年 8 月 12 日</span></strong>
```

- [Line 118](https://github.com/5j54d93/Google-Blogger-Template/blob/951e2ff55caf4b06ba18ca5160f86bceb8eaa419/blogger_template/theme.html#L118)：All you need to do is change `高中&#65306;一&#12289;二&#12289;三類組怎麼選&#65311;三類經驗分享&#65281;` to your selected article's title.

```html
<h1 class='card-title mb-4 fw-bold fst-italic'>高中&#65306;一&#12289;二&#12289;三類組怎麼選&#65311;三類經驗分享&#65281;</h1>
```

- [Line 119](https://github.com/5j54d93/Google-Blogger-Template/blob/951e2ff55caf4b06ba18ca5160f86bceb8eaa419/blogger_template/theme.html#L119)：All you need to do is change `文章重點預覽&#65306;高中類組&#65306;文章前言 一&#12289;二&#12289;三類組各別適合的學群 高中面臨選擇&#65306;&#12300;理組&#12301;還是&#12300;文組&#12301;&#65311; 高中二類&#12289;三類的差別&#65311;&#65281; 高中不確定想走&#12300;理工&#12301;還是&#12300;生物醫學&#12301;&#65311; 未來想走理工&#65292;但覺得三類能多學&#12300;生物&#12301;一科對自己也有幫助&#65281;` to your selected article's preview.

```html
<p class='card-text'>文章重點預覽&#65306;高中類組&#65306;文章前言 一&#12289;二&#12289;三類組各別適合的學群 高中面臨選擇&#65306;&#12300;理組&#12301;還是&#12300;文組&#12301;&#65311; 高中二類&#12289;三類的差別&#65311;&#65281; 高中不確定想走&#12300;理工&#12301;還是&#12300;生物醫學&#12301;&#65311; 未來想走理工&#65292;但覺得三類能多學&#12300;生物&#12301;一科對自己也有幫助&#65281;</p>
```

_You could put a Google Ad after this selected feature article！_

### 5 latest articles

<img src="https://github.com/5j54d93/Google-Blogger-Template/blob/main/blogger_template/photo/Body：5%20latest%20articles.png" width='100%' height='100%'/>

- [Line 176](https://github.com/5j54d93/Google-Blogger-Template/blob/ecd7b7d6c533fd91d72f15d9e78a942c3ff0d3a9/blogger_template/theme.html#L176)：`閱讀最新文章` means Read Newest Article, you could translate into your language.

```html
<a class='stretched-link btn btn-outline-primary day-blue night mt-3' expr:href='data:post.url'>閱讀最新文章</a>
```

_You could put a Google Ad after this 5 latest articles！_

### 10 most popular articles

<img src="https://github.com/5j54d93/Google-Blogger-Template/blob/main/blogger_template/photo/Body：10%20trending%20articles.png" width='100%' height='100%'/>

- [Line 1018](https://github.com/5j54d93/Google-Blogger-Template/blob/ec2cdc9f9fc2fcd2e30220d0c3b0fc3a9890b444/blogger_template/theme.html#L1018)：`閱讀本月熱門文章` means Read trending articles this month, you could translate into your language.

```html
<a class='stretched-link btn btn-outline-primary day-blue night mt-3' expr:href='data:post.href'>閱讀本月熱門文章</a>
```

_You could put a Google Ad after this 10 most popular articles！_

## Blogger Template｜Side Bar

### About & Share Buttons

<img src="https://github.com/5j54d93/Google-Blogger-Template/blob/main/blogger_template/photo/Side%20Bar：About%20%26%20Share%20Buttons.png" width='100%' height='100%'/>

- [Line 1034](https://github.com/5j54d93/Google-Blogger-Template/blob/1775ce3b1f5a021f576ffb433b8290fe0a27afb5/blogger_template/theme.html#L1034)：`關於` means About, you could translate into your language.

```html
<h4 class='fw-bold' id='about'>關於</h4>
```

- [Line 1035](https://github.com/5j54d93/Google-Blogger-Template/blob/1775ce3b1f5a021f576ffb433b8290fe0a27afb5/blogger_template/theme.html#L1035)：All you need to do is change `本網站成立於 2019 年 7 月 17 日&#65292;分享筆者的生活經歷與特殊經驗&#65281;科技&#12289;旅遊&#12289;學習&#12289;娛樂&#8943;&#8943;` to your blog's short description.

```html
<p class='mb-2'>本網站成立於 2019 年 7 月 17 日&#65292;分享筆者的生活經歷與特殊經驗&#65281;科技&#12289;旅遊&#12289;學習&#12289;娛樂&#8943;&#8943;</p>
```

- [Line 1036](https://github.com/5j54d93/Google-Blogger-Template/blob/1775ce3b1f5a021f576ffb433b8290fe0a27afb5/blogger_template/theme.html#L1036)：Go to [LINE Social Plugins](https://social-plugins.line.me/zh_TW/how_to_install#lineitbutton) to customize your LINE Share Button and replace Line 1036.

```html
<div class='line-it-button' data-color='default' data-count='false' data-lang='zh_Hant' data-size='small' data-type='share-a' data-url='https://sharing-life-in-tw.blogspot.com' data-ver='3' style='display: none;'/><script async='async' defer='defer' src='https://www.line-website.com/social-plugins/js/thirdparty/loader.min.js'/>
```

- [Line 1037](https://github.com/5j54d93/Google-Blogger-Template/blob/1775ce3b1f5a021f576ffb433b8290fe0a27afb5/blogger_template/theme.html#L1037)：Go to [Twitter Publish](https://publish.twitter.com/#) to customize your Twitter Share Button and replace Line 1037.

```html
<a class='twitter-share-button' data-show-count='false' href='https://twitter.com/share?ref_src=twsrc%5Etfw'>Tweet</a><script async='async' charset='utf-8' src='https://platform.twitter.com/widgets.js'/>
```

- [Line 1038](https://github.com/5j54d93/Google-Blogger-Template/blob/1775ce3b1f5a021f576ffb433b8290fe0a27afb5/blogger_template/theme.html#L1038)：Go to [FACEBOOK for Developers](https://developers.facebook.com/docs/plugins/share-button) to customize your Facebook Share Button and replace Line 1038.

```html
<div class='fb-share-button' data-href='https://sharing-life-in-tw.blogspot.com' data-layout='button_count' data-size='small' style='vertical-align: super; margin-left: 0.1rem !important;'><a class='fb-xfbml-parse-ignore' href='https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Fsharing-life-in-tw.blogspot.com%2F&amp;src=sdkpreparse' target='_blank'>分享</a></div>
```

### Views

<img src="https://github.com/5j54d93/Google-Blogger-Template/blob/main/blogger_template/photo/Side%20Bar：Views.png" width='100%' height='100%'/>

- [Line 1042](https://github.com/5j54d93/Google-Blogger-Template/blob/c1b8e07a8e598d623d44bd3466a19ad19c93e077/blogger_template/theme.html#L1042)：`總瀏覽次數` means Total Views, you could translate into your language.

```html
<b:widget id='Stats1' locked='false' title='總瀏覽次數' type='Stats' version='1'>
```

### Followers

<img src="https://github.com/5j54d93/Google-Blogger-Template/blob/main/blogger_template/photo/Side%20Bar：Followers.png" width='100%' height='100%'/>

- [Line 1065](https://github.com/5j54d93/Google-Blogger-Template/blob/c1b8e07a8e598d623d44bd3466a19ad19c93e077/blogger_template/theme.html#L1065)：`歡迎追蹤` means Welcome to Follow, you could translate into your language.

```html
<b:widget id='Text1' locked='false' title='歡迎追蹤！' type='Text' version='1'>
```

## Blogger Template｜Footer

<img src="https://github.com/5j54d93/Google-Blogger-Template/blob/main/blogger_template/photo/Footer.png" width='100%' height='100%'/>

- [Line 1118](https://github.com/5j54d93/Google-Blogger-Template/blob/c1b8e07a8e598d623d44bd3466a19ad19c93e077/blogger_template/theme.html#L1118)：All you need to do is change `看我所見` to your blog's name.

```html
<p class='mb-1'>&#169; 2021 看我所見. All rights reserved.</p>
```

- [Line 1119](https://github.com/5j54d93/Google-Blogger-Template/blob/c1b8e07a8e598d623d44bd3466a19ad19c93e077/blogger_template/theme.html#L1119)：You could replace `本網站內容為作者&#12300;Ricky Chuang&#12301;所有&#65292;未經許可請勿轉載&#65281;` with author and copyright strike.

```html
<p class='mb-0'>本網站內容為作者&#12300;Ricky Chuang&#12301;所有&#65292;未經許可請勿轉載&#65281;</p>
```

## Blogger Template｜License：© 2021 看我所見. All rights reserved.

This package is licensed under MIT license. See [LICENSE](https://github.com/5j54d93/Google-Blogger-Template/blob/main/LICENSE) for details.
