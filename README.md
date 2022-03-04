# Google Blogger Template（Theme）

[![Jekyll site CI](https://github.com/5j54d93/Google-Blogger-Template/actions/workflows/jekyll.yml/badge.svg)](https://github.com/5j54d93/Google-Blogger-Template/actions/workflows/jekyll.yml)
![GitHub](https://img.shields.io/github/license/5j54d93/Blogger-Template)
[![GitHub stars](https://img.shields.io/github/stars/5j54d93/Blogger-Template)](https://github.com/5j54d93/Blogger-Template/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/5j54d93/Google-Blogger-Template)](https://github.com/5j54d93/Google-Blogger-Template/network)
![GitHub repo size](https://img.shields.io/github/repo-size/5j54d93/Blogger-Template)

[**Google Blogger**](https://www.blogger.com) theme（template）designed with [**Bootstrap**](https://bootstrap5.hexschool.com) and Blogger's special XML syntax.

- colorful social media links on right of navibar which could collapse into `navbar-toggler-icon`（hamburger）on small screen 
- the most view count post on top of HOME page
- 5 latest & 10 most popular articles on HOME page
- there are About、Views and Followers on the sidebar which would `sticky-top`
- links & license at bottom of all pages
- automatic switch between `light theme` & `dark theme`
- custom search bar、custom search page、custom archive page、custom topic page

<img src="https://github.com/5j54d93/Google-Blogger-Template/blob/main/.github/assets/Demo.png" width='100%' height='100%'/>

> Demo website：[**sharing-life-in-tw.blogspot.com**](https://sharing-life-in-tw.blogspot.com)

## Overview

1. [**How To Use**](https://github.com/5j54d93/Google-Blogger-Template#how-to-use)
2. [**Design on Your Own**](https://github.com/5j54d93/Google-Blogger-Template#design-on-your-own)
3. [**Learn More**](https://github.com/5j54d93/Google-Blogger-Template#learn-more)
4. [**License：MIT**](https://github.com/5j54d93/Google-Blogger-Template#licensemit)

## How To Use

0. You shoul have a [Google Blogger](https://www.blogger.com) account first！
1. Go to theme page
2. Click on the down triangle button beside "Custom"
3. Clink "Edit HTML"

<img src="https://github.com/5j54d93/Google-Blogger-Template/blob/main/.github/assets/Blogger：Theme%20Page.png" width='100%' height='100%'/>

4. Delete all code you see
5. Fork this repository and custom [this XHTML code](https://github.com/5j54d93/Google-Blogger-Template/blob/main/BloggerTemplate/BloggerTemplate.xhtml) through [this README.md file](https://github.com/5j54d93/Google-Blogger-Template/tree/main/BloggerTemplate) to fit your blog

## Design on Your Own

You could design your own blogger website start by using the simplest code below

```xml
<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
  
  <head>
    <b:skin><![CDATA[]]></b:skin>
  </head>

  <body>
    <b:section id='header'/>
  </body>
    
</html>
```

## Learn More

If you want to creat a page to list all posts on your Google Blogger by time, [view this repository](https://github.com/5j54d93/Blogger-All-Post-List).

<img src="https://github.com/5j54d93/Google-Blogger-Template/blob/main/.github/assets/Demo：All-Posts-List.gif" width='100%' height='100%'/>

## License：MIT

This package is [MIT licensed](https://github.com/5j54d93/Google-Blogger-Template/blob/main/LICENSE).
