# 包 UserInfo 中函数的返回值说明

## getCodeQuantity
返回值为 int 类型，表示用户代码量，单位为「个字符」。

## getNewRepository
返回 List 字典：
```js
{
  "cnt": 2,
  "repoList": [
    "https://api.github.com/repos/Luoky76/GCat",
    "https://api.github.com/repos/ShakingSH/bobing"
  ]
}
```

## getNewCollaborator
返回 List 字典：
```js
{
  "cnt": 3,
  "userID": [
    "Luoky76",
    "ShakingSH",
    "ShakingSH"
  ],
  "repoList": [
    "https://api.github.com/repos/Luoky76/GCat",
    "https://api.github.com/repos/Luoky76/GCat",
    "https://api.github.com/repos/ShakingSH/bobing"
  ],
  "time": [
    "2021/11/3 22:41",
    "2021/11/3 10:41",
    "2021/11/2 05:30"
  ]
}
```

## getAllBrowseList
返回 List 字典：
```js
{
  "cnt": 2,
  "repoList": [
    "https://api.github.com/repos/Luoky76/GCat",
    "https://api.github.com/repos/ShakingSH/bobing"
  ],
  "time": [
    "2021/11/3 22:41",
    "2021/11/2 05:30"
  ]
}
```

## getBrowseList
返回 List 字典：
```js
{
  "C++": {
    "cnt": 2,
    "repoList": [
      "https://api.github.com/repos/Luoky76/GCat",
      "https://api.github.com/repos/ShakingSH/bobing"
    ]
    "time": [
      "2021/11/3 22:41",
      "2021/11/2 05:30"
    ]
  },
  "Python": {
    "cnt": 2,
    "repoList": [
      "https://api.github.com/repos/fireflylxx/learning1",
      "https://api.github.com/repos/fireflylxx/login-test"
    ]
    "time": [
      "2021/9/20 21:23",
      "2021/11/14 23:21"
    ]
  }
}
```

## getAllAction
返回 List 字典：
```js
{
  "cnt": 3,
  "action": [
    "push",
    "commit",
    "merge"
  ],
  "repoList": [
    "https://api.github.com/repos/Luoky76/GCat",
    "https://api.github.com/repos/Luoky76/GCat",
    "https://api.github.com/repos/ShakingSH/bobing"
  ],
  "time": [
    "2021/10/10 12:20",
    "2021/10/10 12:20",
    "2021/10/10 13:07"
  ]
}
```

## getAction
返回 List 字典：
```js
{
  "push": {
    "cnt": 1,
    "repoList": [
      "https://api.github.com/repos/Luoky76/GCat"
    ]
    "time": [
      "2021/10/10 12:20"
    ]
  },
  "commit": {
    "cnt": 2,
    "repoList": [
      "https://api.github.com/repos/fireflylxx/learning1",
      "https://api.github.com/repos/fireflylxx/login-test"
    ]
    "time": [
      "2021/11/10 15:47",
      "2021/11/7 14:31"
    ]
  },
  "merge": {
    "cnt": 2,
    "repoList": [
      "https://api.github.com/repos/fireflylxx/learning1",
      "https://api.github.com/repos/fireflylxx/login-test"
    ]
    "time": [
      "2021/11/11 15:57",
      "2021/11/6 11:34"
    ]
  }
}
```