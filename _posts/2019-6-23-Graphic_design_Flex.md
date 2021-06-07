---
layout: page
title: 如何让元素居中？
categories:
     - 平面设计
---

## 使用弹性布局实现元素的水平居中和垂直居中
>Flex是Flexible Box的缩写，意为”弹性布局”，用来为盒状模型提供最大的灵活性。

任何一个容器都可以指定为Flex布局。

HTML片段：
    
    <div class="box">
        <p>运用弹性布局实现元素居中</p>
    </div>
    
CSS3片段：
**水平居中**

    .box{
        display: flex;
        justify-content:center;
        }

**垂直居中**

    .box{
        display: flex;
        width: 300px;
        height: 10rem;
        align-items: center;
        }

**水平垂直居中**

    .box{
        display: flex;
        width: 300px;
        height: 10rem;
        align-items: center;
        justify-content:center;
        }