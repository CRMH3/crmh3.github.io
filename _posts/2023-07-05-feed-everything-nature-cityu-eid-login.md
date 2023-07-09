---
layout: post
title: feed-everything-nature-cityu-eid-login
tag: rss
---



## Step 1. Specify source page

```
https://www.nature.com/search?journal=nrd&order=date_desc
```

## Step 2. Define extraction rules

```
<h3{*}>{*}<a href="https://www.nature.com/{%}"{*}">{%}</a>{*}</h3>{*}<span class="c-meta__type">{%}</span>
```

## Step 3. Define output format

| Item                | Content                                                     |
| ------------------- | ----------------------------------------------------------- |
| Feed title          | Nature Reviews Drug Discovery                               |
| Feed link           | `https://www.nature.com/search?journal=nrd&order=date_desc` |
| Item Title Template | `「{%3}」{%2} `                                          |
| Item Link Template  | `https://www-nature-com.ezproxy.cityu.edu.hk/{%1}`          |

