# 泰拉记事社-阅读书源
**介绍**
本项目为适用于[阅读](https://github.com/gedoor/legado)https://github.com/gedoor/legado 的漫画源，爬取地址为鹰角的漫画项目[泰拉记事社](https://terra-historicus.hypergryph.com/)https://terra-historicus.hypergryph.com/

**贡献**

如有问题或者功能欢迎提issue和pr。

**泰拉记事社API**

- 全部漫画：`/api/comic`

  ```json
  {
    "code": 0,
    "msg": "",
    "data": [
      {
        "cid": "5033",
        "type": 1,
        "cover": "https://web.hycdn.cn/comic/pic/20250124/b4e3198727905c5408dac43000fd79f2_p_20.jpg",
        "title": "暮岁闲谈：来拍电影吗",
        "subtitle": "",
        "authors": [
          "鹰角网络"
        ]
      },
      {
        "cid": "0695",
        "type": 1,
        "cover": "https://web.hycdn.cn/comic/pic/20241023/2fd2a92b325f27b9cada1dd7e1af6394_p_20.jpg",
        "title": "序言组曲：旧创",
        "subtitle": "",
        "authors": [
          "鹰角网络"
        ]
      },
      {
        "cid": "8908",
        "type": 1,
        "cover": "https://web.hycdn.cn/comic/pic/20240708/af5fc38d8c2ce29aec861646896f59d3_p_20.jpg",
        "title": "塞茜莉亚的安魂寻旅",
        "subtitle": "",
        "authors": [
          "鹰角网络"
        ]
      },
      {
        "cid": "6252",
        "type": 1,
        "cover": "https://web.hycdn.cn/comic/pic/20240301/5af12cedd4bc2fd9fb3a443fc668b472_p_20.jpg",
        "title": "一起吃个饭吧",
        "subtitle": "",
        "authors": [
          "鹰角网络"
        ]
      },
      {
        "cid": "7747",
        "type": 1,
        "cover": "https://web.hycdn.cn/comic/pic/20231127/d207cc1a73dc4b2673025e41636d75c9_p_20.jpg",
        "title": "序言组曲：利锏银锋",
        "subtitle": "",
        "authors": [
          "鹰角网络"
        ]
      },
      {
        "cid": "1420",
        "type": 1,
        "cover": "https://web.hycdn.cn/comic/pic/20231027/4cf87f3c0a6fcd6d99af7df055400323_p_20.jpg",
        "title": "序言组曲：无拘奏音",
        "subtitle": "",
        "authors": [
          "鹰角网络"
        ]
      },
      {
        "cid": "2864",
        "type": 1,
        "cover": "https://web.hycdn.cn/comic/pic/20230427/06d80836fe024d8fe70579c754103f0b_p_20.jpg",
        "title": "信使安洁莉娜漫游手记",
        "subtitle": "",
        "authors": [
          "鹰角网络"
        ]
      },
      {
        "cid": "1421",
        "type": 1,
        "cover": "https://web.hycdn.cn/comic/pic/20220614/b1b0f7c6da3fb225c8cf4cca13a70969_p_20.jpg",
        "title": "罗德岛源石记事——莱茵生命",
        "subtitle": "RHODES ISLAND’S RECORDS OF ORIGINIUM - RHINE LAB",
        "authors": [
          "鹰角网络"
        ]
      },
      {
        "cid": "8909",
        "type": 1,
        "cover": "https://web.hycdn.cn/comic/pic/20220513/89b6ea9526a60c92bccdd15d007f643d_p_20.jpg",
        "title": "罗德厨房——回甘",
        "subtitle": "",
        "authors": [
          "鹰角网络",
          "馬かのこ"
        ]
      },
      {
        "cid": "0696",
        "type": 1,
        "cover": "https://web.hycdn.cn/comic/pic/20230202/bf6e5dc78c9c3fa840ababbcda078ef1_p_20.jpg",
        "title": "A1行动预备组",
        "subtitle": "",
        "authors": [
          "鹰角网络"
        ]
      },
      {
        "cid": "6253",
        "type": 3,
        "cover": "https://web.hycdn.cn/comic/pic/20250114/5cdf49a97a36f441a80e9f6ff1626af4_p_20.jpg",
        "title": "123罗德岛！？",
        "subtitle": "你可能不知道的罗德岛小剧场！",
        "authors": [
          "鹰角网络"
        ]
      },
      {
        "cid": "9382",
        "type": 1,
        "cover": "https://web.hycdn.cn/comic/pic/20220424/dde462eb8bce6c9885eb2eb5b970afcd_p_20.jpg",
        "title": "罗德岛源石记事——黑钢",
        "subtitle": "RHODES ISLAND’S RECORDS OF ORIGINIUM - BLACK STEEL",
        "authors": [
          "鹰角网络"
        ]
      },
      {
        "cid": "7748",
        "type": 3,
        "cover": "https://web.hycdn.cn/comic/pic/20210506/6b85f1b2990d83a04916d90abdce7581_p_20.jpg",
        "title": "罗德岛闲逛部",
        "subtitle": "大家一起来闲逛吧！",
        "authors": [
          "鹰角网络"
        ]
      },
      {
        "cid": "2865",
        "type": 2,
        "cover": "https://web.hycdn.cn/comic/pic/20210511/ce52a2d283fd1c4c754288fe871bd03d_p_20.jpg",
        "title": "罗德岛相簿",
        "subtitle": "留下罗德岛干员生活的每一个瞬间！",
        "authors": [
          "鹰角网络"
        ]
      }
    ]
  }
  ```

- 漫画信息：`/api/comic/{comicId}`

  ```json
  {
    "code": 0,
    "msg": "",
    "data": {
      "cid": "5033",
      "type": 1,
      "cover": "https://web.hycdn.cn/comic/pic/20250124/b4e3198727905c5408dac43000fd79f2.jpg",
      "title": "暮岁闲谈：来拍电影吗",
      "subtitle": "",
      "authors": [
        "鹰角网络"
      ],
      "keywords": [
        "轻松",
        "日常",
        "岁"
      ],
      "introduction": "这是否是比记忆更牢固的东西。",
      "direction": "left",
      "readConfig": null,
      "episodes": [
        {
          "cid": "8639",
          "type": 1,
          "shortTitle": "01",
          "title": "来拍电影吗",
          "displayTime": 1737993600
        }
      ],
      "updateTime": 1737993600
    }
  }
  ```

- 章节信息：`/api/comic/{comicId}/episode/{episodeId}`

  ```json
  {
    "code": 0,
    "msg": "",
    "data": {
      "title": "来拍电影吗",
      "shortTitle": "01",
      "type": 1,
      "likes": 2311,
      "pageInfos": [
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        },
        {
          "width": 1194,
          "height": 1663,
          "doublePage": false
        }
      ]
    }
  }
  ```

- 单页信息：`/api/comic/{comicId}/episode/{episodeId}/page?pageNum={pageNum}`

  ```json
  {
    "code": 0,
    "msg": "",
    "data": {
      "pageNum": 1,
      "url": "https://res01.hycdn.cn/3eafa12d13d654f09e0afab1eb8310a4/67A0ABAA/comic/pic/20250125/bc5959f6aa1d248b152bba6506cce84a.jpg"
    }
  }
  ```

  