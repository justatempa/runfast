---
title: "Hello Hugo"
date: 2023-04-27T17:26:28+08:00
draft: true
tags: ["教程", "开发"]
---



hello hugo

<!--more-->

# 启动



# 页面

## 标签tags

tags: ["教程", "开发"]

## 标题

默认是文件名

## 摘要

`<!--more-->`后面的是正文

## 代码高亮

```java
    /**
     * 驼峰转下划线
     * @param str
     * @return
     */
    public static String humpToLine(String str) {
        Matcher matcher = humpPattern.matcher(str);
        StringBuffer sb = new StringBuffer();
        while (matcher.find()) {
            matcher.appendReplacement(sb, "_" + matcher.group(0).toUpperCase());
        }
        matcher.appendTail(sb);
        return sb.toString().toUpperCase();
    }
```



## 图片



## 页内标题



# about