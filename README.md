
## Nepali Panchang Json DB
 This is simple and small JSON database of Nepali panchange which gives info on events,festivals,tithe,..etc in different year.
## API Reference


#### Get item

```http
  GET https://raw.githubusercontent.com/prolaxu/nepali-panchang-json-db/main/${year}/${month}/${day}.json
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `year`      | `int` | **Required**. Year from calender to fetch |
| `month`      | `int` | **Required**. Month from calender to fetch |
| `month`      | `int` | **Required**. Day from calender to fetch |

#### Example response

```
[
{
"title": "वि.सं",
"value": "२०७८ बैशाख १ बुधवार"
},
{
"title": "ईसवी",
"value": "2021 Apr 14, Wednesday"
},
{
"title": "नेपाल संवत",
"value": "1141 चौलाथ्व द्वितीया-2"
},
{
"title": "सूर्य",
"value": "5:42☀️, 18:28🌤"
},
{
"title": "चन्द्र",
"value": "7:03☽, 20:32☾"
},
{
"title": "तिथि",
"value": "द्वितीया upto 13:4:56, उपरान्त: तृतीया"
},
{
"title": "पक्ष",
"value": "चैत्र शुक्ल पक्ष 🌒"
},
{
"title": "नक्षत्र",
"value": "भरणी upto 17:40:2, उपरान्त: कृत्तिका"
},
{
"title": "योग",
"value": "प्रीति upto 16:32:23, उपरान्त: आयुष्मान"
},
{
"title": "करण",
"value": "कौलव upto 13:4:56"
},
{
"title": "चन्द्र राशि",
"value": "मेष ♈ upto 24:26:58, उपरान्त: वृष ♉"
},
{
"title": "दिनमान",
"value": "31 घडी 55 पला - 12hr 46min"
},
{
"title": "ऋतु",
"value": "वसन्त-Spring"
},
{
"title": "आयान",
"value": "उत्तरायण"
}
]
```

