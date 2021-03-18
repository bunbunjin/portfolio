---
title: "Line Alarm"
date: 2021-03-18T10:19:32+09:00
draft: false
---

警報が出たらLINEで通知してくれるやつ
===

##概要
高校在学中の僕は、とにかく学校に行きたくなくてかなりの頻度で「岡山　警報」とググっていた。
正直だるくなったので気象庁HPをスクレイピングしてLINEに通知させるようにした。
##使ったやつ
> - Python3
> - BeautifulSoup
> - LINE Nofity
##対象地域
> - 岡山市
> - 美作市

##コードについて
[実際のコード](https://github.com/bunbunjin/line_closed_school/blob/master/okayama_weather.py)
を見ればわかるが、dictを多用しているから可読性は低い

##思ったこと
- 今回は手動で市町村を入力したが、今後もし似たようなものを作るときはここを自動化したい
