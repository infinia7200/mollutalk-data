# mollutalk-json

This is a translation file for the [MolluTalk site](https://mollutalk.com)

If there is a typo or correction, please make a full request.

twitter - [@Raun0129](https://twitter.com/Raun0129)

any typos in mollutalk-offical - [go this way](https://github.com/Raun0129/mollutalk-official)

----
## official_directory.json

There is information about the Blue Archive momotalk.

### Structure
```
[
  {
    "series_no": 189,                     // If you want to add a new official talk, it should be higher than the previous number.
    "series_idx": 3,                      // The order of the series, it should be higher than the previous number.
    "profile_no": 12,                     // Profile picture for this talk. Character number in mollutalk-json/character_directory.json
    "profile_idx": 3,                     // The order of the Profile. Profile number in mollutalk-json/character_directory.json
    "characters": [12],                   // The character number that appears in the talk [...character_no]
    "file_name": "official_189_3.json",   // Corresponding Talk Name, official_[series_no]_[series_idx].json
    "series_title": {
      "kr": "하루카의 인연스토리",
      "jp": "하루카의 인연스토리",
      "en": "하루카의 인연스토리",
      "zh_cn": "하루카의 인연스토리",
      "zh_tw": "하루카의 인연스토리"
    },
    "title": {
      "kr": "차가운 바람, 따듯한 햇볕(번역)",
      "jp": "차가운 바람, 따듯한 햇볕(번역)",
      "en": "차가운 바람, 따듯한 햇볕(번역)",
      "zh_cn": "차가운 바람, 따듯한 햇볕(번역)",
      "zh_tw": "차가운 바람, 따듯한 햇볕(번역)"
    },
    "writer": {                           // The nickname of the person who translated it [...nickname]
      "kr": ["Molru"],
      "jp": [""],
      "en": [""],
      "zh_cn": [""],
      "zh_tw": [""]
    }
  },
  ...
]
```
----
## character_directory.json

There is information about the Blue Archive character.

### Structure
```
[
  {
    "kr" : "아비도스",                      // school name
    "en" : "ABYDOS",
    "jp" : "アビドス",
    "zh_cn" : "阿比多斯",
    "zh_tw" : "阿比多斯",
    "club" : [
      {
        "kr" : "대책위원회",                 // club name
        "en" : "Countermeasures Council",
        "jp" : "対策委員会",
        "zh_cn" : "对策委员会",
        "zh_tw" : "對策委員會",
        "characters" : [
          {
            "no" : 1,                       // character Unique number
            "kr" : "스나오오카미 시로코",    // character name
            "en" : "Sunaookami Shiroko",   //  - Basically "[Last name] [First Name]" or "[First Name]"
            "jp" : "砂狼 シロコ",           //  - Word spacing is use '-' ex] "Tea-Party"
            "zh_cn" : "砂狼 白子",
            "zh_tw" : "砂狼 白子",
            "illust" : 0,                   // not used
            "profile" : [1,2],              // character profile no
            "momotalk" : true,              // MOMOTALK Existence status in Blue Archive
            "open" : true                   // Disclosure status in Blue Archive
          },
        ]
      }
    ]
  },
]
```
----
## translate.json

Collection of languages used within the site.

----
## translateHelp.json

Collection of languages used for help pages.

----
## translateTerms.json

Collection of languages used for term pages.

----
## updateLog.json

This is the MolluTalk site update log. (Default - kr)

