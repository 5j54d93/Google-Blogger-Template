# Customize Your Google Blogger Template

Customize [this XML code](https://github.com/5j54d93/Google-Blogger-Template/blob/main/BloggerTemplate/BloggerTemplate.xhtml) with this README.md file！

## Tag：`<html>`

- [LINE 3](https://github.com/5j54d93/Google-Blogger-Template/blob/e8952e14d92cbbcfeb4b5ab6eef608db19608c15/BloggerTemplate/BloggerTemplate.xhtml#L3)：change `lang='zh-TW'` to fit your blogger language, if yours is English, change to `lang='en'`

```xml
<html lang='zh-TW' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'> 
```

## Navbar

<img src="https://github.com/5j54d93/Google-Blogger-Template/blob/main/BloggerTemplate/.github/assets/Navbar.png" width='100%' height='100%'/>

- [LINE 223](https://github.com/5j54d93/Google-Blogger-Template/blob/1dff835b2763b0f5e5182e392efd31b14a9b93d9/BloggerTemplate/BloggerTemplate.xhtml#L223)：change `看我所見` to yuor blog title

```xml
<a class='navbar-brand fs-4 fw-bold text-white' href='/'>看我所見</a>
```

- [LINE 228 ～ LINE 247](https://github.com/5j54d93/Google-Blogger-Template/blob/1dff835b2763b0f5e5182e392efd31b14a9b93d9/BloggerTemplate/BloggerTemplate.xhtml#L228-L247)：change `贊助`、`所有文章`、`社群連結` to yuor blog page, and change `發燒文章`、`使用說明`、`隱私政策` to links you want to show in `dropdown` list
  - `一般` means general：translate it to your language
  - `說明與法規` means help & legal：translate it to your language

```xml
<div class='navbar-nav flex-row'>
  <a class='nav-link me-2' href='/p/support-us.html' style='color:orange;' target='_blank'>贊助</a>
  <a class='nav-link me-2 active' href='/p/all-posts.html' target='_blank'>所有文章</a>
  <a class='nav-link me-2 active' href='https://linktr.ee/5j_54d93' target='_blank'>社群連結</a>
  <div class='navbar-nav nav-item dropdown'>
    <a aria-expanded='false' class='nav-link dropdown active' data-bs-toggle='dropdown' href='#' id='navbarDropdown' role='button' style='display:block; border-radius:13%;'>
      <svg class='bi bi-three-dots-vertical' fill='currentColor' height='22' viewBox='0 0 18 18' width='22' xmlns='http://www.w3.org/2000/svg'>
        <path d='M9.5 13a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0zm0-5a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0zm0-5a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0z'/>
      </svg>
    </a>
    <div aria-labelledby='navbarDropdown' class='dropdown-menu dropdown-menu-end dropdown-menu-sm-start' style='position:absolute !important;'>
      <p class='dropdown-header fs-6'>一般</p>
      <a class='dropdown-item' href='#PopularPosts1'>發燒文章</a>
      <hr class='dropdown-divider' style='color:rgb(205,217,229);'/>
      <p class='dropdown-header fs-6'>說明與法規</p>
      <a class='dropdown-item' href='/' target='_blank'>使用說明</a>
      <a class='dropdown-item' href='/p/privacy-policy.html' target='_blank'>隱私政策</a>
    </div>
  </div>
</div>
```

<img src="https://github.com/5j54d93/Google-Blogger-Template/blob/main/BloggerTemplate/.github/assets/Navbar：social%20media%20links.png" width='100%' height='100%'/>

- [LINE 260 ～ LINE 302](https://github.com/5j54d93/Google-Blogger-Template/blob/a522867eef459f7971b3977a82a48d8fd821b61b/BloggerTemplate/BloggerTemplate.xhtml#L260-L302)：change `href` in each tag `<a>` to your social media link

```xml
<div class='navbar-nav flex-row flex-wrap ms-md-auto'>
  <!--YT-->
  <a class='btn btn-outline-danger yt-red me-1 my-1' data-bs-placement='bottom' data-bs-toggle='tooltip' href='https://www.youtube.com/channel/UC71TBGWnlb26oMC9uS2xnuw' role='button' target='_blank' title='YouTube'>
    <svg class='bi bi-youtube' fill='currentColor' height='16' viewBox='0 0 16 16' width='16' xmlns='http://www.w3.org/2000/svg'>
      <path d='M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.007 2.007 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.007 2.007 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31.4 31.4 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.007 2.007 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A99.788 99.788 0 0 1 7.858 2h.193zM6.4 5.209v4.818l4.157-2.408L6.4 5.209z'/>
    </svg>
  </a>
  <!--IG-->
  <a class='btn btn-outline-danger ig-orange me-1 my-1' data-bs-placement='bottom' data-bs-toggle='tooltip' href='https://www.instagram.com/5j_54d93/' role='button' target='_blank' title='Instagram'>
    <svg class='bi bi-instagram' fill='currentColor' height='16' viewBox='0 0 16 16' width='16' xmlns='http://www.w3.org/2000/svg'><path d='M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.917 3.917 0 0 0-1.417.923A3.927 3.927 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.916 3.916 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.926 3.926 0 0 0-.923-1.417A3.911 3.911 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0h.003zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599.28.28.453.546.598.92.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.47 2.47 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.478 2.478 0 0 1-.92-.598 2.48 2.48 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233 0-2.136.008-2.388.046-3.231.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92.28-.28.546-.453.92-.598.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045v.002zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92zm-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217zm0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334z'/>
    </svg>
  </a>
  <!--Google Maps-->
  <a class='btn btn-outline-success line-green me-1 my-1' data-bs-placement='bottom' data-bs-toggle='tooltip' href='https://maps.app.goo.gl/UZGou7XvCptory3v9?ltclid' role='button' target='_blank' title='Google Local Guide'>
    <svg class='bi bi-geo-alt-fill' fill='currentColor' height='16' viewBox='0 0 16 16' width='16' xmlns='http://www.w3.org/2000/svg'>
      <path d='M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10zm0-7a3 3 0 1 1 0-6 3 3 0 0 1 0 6z'/>
    </svg>
  </a>
  <!--Twitter-->
  <a class='btn btn-outline-secondary twitter-blue me-1 my-1' data-bs-placement='bottom' data-bs-toggle='tooltip' href='https://twitter.com/5j_54d93' role='button' target='_blank' title='Twitter'>
    <svg class='bi bi-twitter' fill='currentColor' height='16' viewBox='0 0 16 16' width='16' xmlns='http://www.w3.org/2000/svg'>
      <path d='M5.026 15c6.038 0 9.341-5.003 9.341-9.334 0-.14 0-.282-.006-.422A6.685 6.685 0 0 0 16 3.542a6.658 6.658 0 0 1-1.889.518 3.301 3.301 0 0 0 1.447-1.817 6.533 6.533 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.325 9.325 0 0 1-6.767-3.429 3.289 3.289 0 0 0 1.018 4.382A3.323 3.323 0 0 1 .64 6.575v.045a3.288 3.288 0 0 0 2.632 3.218 3.203 3.203 0 0 1-.865.115 3.23 3.23 0 0 1-.614-.057 3.283 3.283 0 0 0 3.067 2.277A6.588 6.588 0 0 1 .78 13.58a6.32 6.32 0 0 1-.78-.045A9.344 9.344 0 0 0 5.026 15z'/>
    </svg>
  </a>
  <!--Facebook-->
  <a class='btn btn-outline-secondary facebook-blue me-1 my-1' data-bs-placement='bottom' data-bs-toggle='tooltip' href='https://www.facebook.com/5j54d93/' role='button' target='_blank' title='Facebook'>
    <svg class='bi bi-facebook' fill='currentColor' height='16' viewBox='0 0 16 16' width='16' xmlns='http://www.w3.org/2000/svg'><path d='M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951z'/>
    </svg>
  </a>
  <!--Twitch-->
  <a class='btn btn-outline-secondary purple me-1 my-1' data-bs-placement='bottom' data-bs-toggle='tooltip' href='https://www.twitch.tv/5j_54d93' role='button' target='_blank' title='Twitch'>
    <svg class='bi bi-twitch' fill='currentColor' height='16' viewBox='0 0 16 16' width='16' xmlns='http://www.w3.org/2000/svg'>
      <path d='M3.857 0 1 2.857v10.286h3.429V16l2.857-2.857H9.57L14.714 8V0H3.857zm9.714 7.429-2.285 2.285H9l-2 2v-2H4.429V1.143h9.142v6.286z'/>
      <path d='M11.857 3.143h-1.143V6.57h1.143V3.143zm-3.143 0H7.571V6.57h1.143V3.143z'/>
    </svg>
  </a>
  <!--GitHub-->
  <a class='btn btn-outline-dark GitHub-white me-1 my-1' data-bs-placement='bottom' data-bs-toggle='tooltip' href='https://github.com/5j54d93' role='button' target='_blank' title='GitHub'>
    <svg class='bi bi-github' fill='currentColor' height='16' viewBox='0 0 16 16' width='16' xmlns='http://www.w3.org/2000/svg'>
      <path d='M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.012 8.012 0 0 0 16 8c0-4.42-3.58-8-8-8z'/>
    </svg>
  </a>
</div>
```

## Main

<img src="https://github.com/5j54d93/Google-Blogger-Template/blob/main/BloggerTemplate/.github/assets/Most%20popular%20post.png" width='100%' height='100%'/>

- [LINE 320 ～ LINE 327](https://github.com/5j54d93/Google-Blogger-Template/blob/9e39c18ed49af59993ff495ccfce373bb067d215/BloggerTemplate/BloggerTemplate.xhtml#L320-L327)：code here will automatically show the most popular post, all you need to do is：
  - `發燒文章` means popular article：translate it to your language
  - `瀏覽次數` means views count：translate it to your language
  - `10.2 萬次` means number of views count：because there's no API to get the number of views count, you need to edit it by hand
  - `發布日期&#65306;2019 年 8 月 12 日` means post date：translate it to your language, there's no API to get the post date too
  - `閱讀發燒文章` means read popular article：translate it to your language

```xml
<div class='alert alert-success mt-4' role='alert'>
  <h6><span class='line-green'>發燒文章 #1</span><span class='text-muted'>&#12539;瀏覽次數&#65306;10.2 萬次&#12539;發布日期&#65306;2019 年 8 月 12 日</span></h6>
  <header><h1 class='alert-heading fst-italic mb-3'><data:post.title/></h1></header>
  <div style='text-align:justify;'><data:post.snippet/></div>
  <div class='d-flex justify-content-end'>
    <a class='btn btn-outline-success line-green stretched-link mt-3' expr:href='data:post.href'>閱讀發燒文章</a>
  </div>
</div>
```

<img src="https://github.com/5j54d93/Google-Blogger-Template/blob/main/BloggerTemplate/.github/assets/Archive%20Tag.png" width='100%' height='100%'/>

<img src="https://github.com/5j54d93/Google-Blogger-Template/blob/main/BloggerTemplate/.github/assets/404%20Tag.png" width='100%' height='100%'/>

<img src="https://github.com/5j54d93/Google-Blogger-Template/blob/main/BloggerTemplate/.github/assets/Search%20None.png" width='50%' height='100%'/><img src="https://github.com/5j54d93/Google-Blogger-Template/blob/main/BloggerTemplate/.github/assets/Search.png" width='50%' height='100%'/>

<img src="https://github.com/5j54d93/Google-Blogger-Template/blob/main/BloggerTemplate/.github/assets/Search%20Date.png" width='100%' height='100%'/>

- [LINE 369 ～ LINE 388](https://github.com/5j54d93/Google-Blogger-Template/blob/78b95010566af0cb434b3c655420fe79927f297d/BloggerTemplate/BloggerTemplate.xhtml#L369-L388)：different tag between different blog page type

```xml
<h4 class='alert alert-warning text-center' role='alert'>
  <b:switch var='data:blog.pageType'>
    <b:case value='archive'/>
there are <data:posts.length/> posts about&#12300;<data:blog.pageName/>&#12301;
    <b:case value='error_page'/>
      404
    <b:case value='index'/>
      <b:if cond='data:blog.searchQuery'>
        <b:if cond='data:posts.length == 0'>
          there aren't any post about&#12300;<data:blog.searchQuery/>&#12301;😢
        <b:else/>
          there are <data:posts.length/> posts about&#12300;<data:blog.searchQuery/>&#12301;
        </b:if>
      </b:if>
      <b:if cond='data:blog.searchLabel'>
        there are <data:posts.length/> posts about&#12300;<data:blog.searchLabel/>&#12301;
      </b:if>
    <b:default/>
  </b:switch>
</h4>
```

## License：MIT

This package is [MIT licensed](https://github.com/5j54d93/Google-Blogger-Template/blob/main/LICENSE).
