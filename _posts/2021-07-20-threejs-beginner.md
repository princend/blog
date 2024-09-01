---
title: 初探threejs
categories:
- Tech
feature_image: "https://picsum.photos/2560/600?image=2"  
excerpt: |
 Three.js 是一套基於 WebGL 開發出的 Javascript 函式庫  
 它提供了比 WebGL 更簡單的 Javascript API，讓開發者能夠輕易在瀏覽器做 3D 繪圖  
---



### Intro

> Three.js 是一套基於 WebGL 開發出的 Javascript 函式庫，它提供了比 WebGL 更簡單的 Javascript API，讓開發者能夠輕易在瀏覽器做 3D 繪圖

> 而 Three.js 最大的優點就是它對 WebGL 進行了良好的封裝，大大的降低了前端工程師們的學習成本，可以說 Three.js 蠻像 3D 網頁中的 jQuery。

#### Scene

場景:供其他元素設置的空間。

#### Camera

相機:在場景中建立觀察點，並確定觀察方向、角度。

正交相機 : 三隻羊一樣大

![OrthographicCamera](/assets/blog/2021-07-20-threejs-begginner/20190918231213655.png)

透視相機:三隻羊不一樣大

![Perspective Camera](/assets/blog/2021-07-20-threejs-begginner/20190918231348619.png)

#### Object

物體:在場景中添加被觀察的物體。

mesh 網格

![https://d1dwq032kyr03c.cloudfront.net/upload/images/20181014/20107572TbrTvCtxq4.png](https://d1dwq032kyr03c.cloudfront.net/upload/images/20181014/20107572TbrTvCtxq4.png)

Points :粒子

![https://d1dwq032kyr03c.cloudfront.net/upload/images/20181014/201075725EchwpExRk.png](https://d1dwq032kyr03c.cloudfront.net/upload/images/20181014/201075725EchwpExRk.png)

Geometry:形狀

![canvas-three-js%20%E5%88%9D%E6%8E%A2%2001813be646c1477b94507c2c4a905c06/20107572TSjeNFaprl.png](/assets/blog/2021-07-20-threejs-begginner/20107572TSjeNFaprl.png)

Material:材質

![canvas-three-js%20%E5%88%9D%E6%8E%A2%2001813be646c1477b94507c2c4a905c06/material.png](/assets/blog/2021-07-20-threejs-begginner/material.png)

#### Light

光源:在場景中用來照亮物體的光。環境光（AmbientLight）、點光源（PointLight）、聚光燈（SpotLight）、平行光（DirectionalLight）

![canvas-three-js%20%E5%88%9D%E6%8E%A2%2001813be646c1477b94507c2c4a905c06/light.png](/assets/blog/2021-07-20-threejs-begginner/light.png)

#### Renderer

渲染器:將所要呈現的場景渲染到畫面上。

#### 成品
<br>

##### 星星環繞
<br>

{% include iframe.html  url="https://princend.github.io/starfield/" title="starfield"%}
