---
title: Current Air Quality (new)
tag: [guide, api, aq-v1, now-v1]
ref: 1-api-air-now-v1
---

Real-time air quality data supports current AQI, pollutant concentration, sub-indexes and health advice, based on the local standard and monitoring station.

> **Hint:** It is recommended to read the [Air Quality Info](/en/docs/resource/air-info/) for details on index types, pollutants, supported countries, etc.

## Request URL

{% include api-url.html apidata="air-now-v1" dev=true %}

## Path Parameters

{% include params.html p="p-location-id" %}

## Query Parameters

{% include params.html p="key lang-def aq-pollutant aq-sta" %}

## Request Example

{% include api-url-example.html apidata="air-now-v1" %}

## Response

{% include api-snippet.html %}

{% include api-response.html group="air" type="now-v1" prefix="nil" fxlink="0" refer="0"  %}