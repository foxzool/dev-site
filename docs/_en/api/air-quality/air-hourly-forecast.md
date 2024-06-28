---
title: Air Quality Hourly Forecast (new)
tag: [guide, api, aq-v1, hourly-v1]
ref: 1-api-air-hourly-v1
---

Air quality (AQI) dailay forecasts, pollutants, and health advice based on local standards for the next 1-72 hours.

> **Hint:** It is recommended to read the [Air Quality Info](/en/docs/resource/air-info/) for details on index types, pollutants, supported countries, etc.

## Request URL

{% include api-url.html apidata="air-hourly-v1-coor" dev=true %}

## Path Parameters

{% include params.html p="p-lat p-lon" %}

## Query Parameters

{% include params.html p="key aq-hour lang-def" %}

## Request Example

{% include api-url-example.html apidata="air-hourly-v1-coor" %}

## Response

{% include api-snippet.html %}

{% include api-response.html group="air" type="hourly-v1" prefix="hourly" fxlink="0" refer="0" update="0" statusCode="0" metadata="tag"   %}