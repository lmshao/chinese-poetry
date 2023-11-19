# Chinese Poetry

收集整理、重新校正中国古诗词。旨在收集全部古诗词数据。

## 数据格式

字段|说明|示例
:---:|:---:|---
author|作者|李白、苏轼
dynasty|朝代|唐、宋
type|文体|诗、词、曲
rhythmic|曲调|乐府诗类型：横吹曲辞；词牌：蝶恋花；曲牌：天净沙
title|题目|蜀道难、静夜思
preface|序言|丙辰中秋，欢饮达旦，大醉，作此篇，兼怀子由。
paragraphs|正文|...
notes|注释|...
id|ID|统计用标记

**示例**

```json
{
    "author": "李白",
    "dynasty": "唐",
    "type": "诗",
    "rhythmic": "横吹曲辞",
    "title": " 洛阳陌",
    "preface": "",
    "paragraphs": [
        "白玉谁家郎，回车渡天津。",
        "看花东陌上，惊动洛阳人。"
    ],
    "notes": "",
    "id": "8606b532c21e6a626639593d43a771d9"
}
```

## 数据来源

[chinese-poetry/chinese-poetry](https://github.com/chinese-poetry/chinese-poetry)
