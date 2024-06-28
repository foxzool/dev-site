---
title: 逐小时空气质量预报(new)
tag: [guide, api, aq-v1, hourly-v1]
ref: 1-api-air-hourly-v1
---

全球空气质量逐小时预报，提供未来1-72小时基于当地标准的空气质量（AQI）预报、污染物和健康建议。

> **提示：**推荐阅读[空气质量信息文档](/docs/resource/air-info/)，以便了解指数类型、污染物、支持的国家等信息。

## 请求URL

{% include api-url.html apidata="air-hourly-v1-coor" dev=true %}

## 路径参数

{% include params.html p="p-lat p-lon" %}

## 查询参数

{% include params.html p="key aq-hour lang-def" %}

## 请求示例

{% include api-url-example.html apidata="air-hourly-v1-coor" %}

## 返回数据

{% include api-snippet.html %}

{% include api-response.html group="air" type="hourly-v1" prefix="hourly" fxlink="0" refer="0" update="0" statusCode="0" metadata="tag"   %}
