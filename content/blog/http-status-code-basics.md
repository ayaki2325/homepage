---
title: '要点だけ学ぶHTTPステータスコード基礎'
date: '2025-11-14T00:00:00+09:00'
draft: false
authors:
  - name: あやき
    link: https://x.com/ayaki2325
    image: https://pbs.twimg.com/profile_images/1958533086771314689/lutI-pc-_400x400.jpg
tags:
  - ネットワーク
  - HTTP
  - 要点だけ学ぶシリーズ
---

## はじめに

HTTPステータスコード[^1]の基礎知識を端的にまとめます。

対象読者は、**一度でもステータスコードを学んだことがある人**です。  
以下のような要望に応えられる記事です。

- 短時間で復習したい
- 技術面接の対策がしたい
- 忘れた頃にさくっと見返せる情報源が欲しい

初心者向けの資料はすでに世の中にたくさんあるので、それらとは棲み分けています。  
個人的なおすすめは『[Webを支える技術](https://gihyo.jp/book/2010/978-4-7741-4204-3)』です。  

[^1]: 以降、見出しを除き「ステータスコード」と表記します。

## HTTPステータスコードとは

| 分類 | 説明                                                     |
| :--- | :------------------------------------------------------- |
| 1xx  |                                            |
| 2xx  |  |
| 3xx  |                    |
| 4xx  |                                    |
| 5xx  |                                            |

## 1xx

### 100 Continue

### 101 Switching Protocols

## 2xx

### 200 OK

### 201 Created

### 202 Accepted

### 203 Non-Authoritative Information

### 204 No Content

### 205 Reset Content

### 206 Partial Content

## 3xx

### 300 Multiple Choices

### 301 Moved Permanently

### 302 Found

### 303 See Other

### 304 Not Modified

### 307 Temporary Redirect

### 307 Temporary Redirect

## 4xx

### 400 Bad Request

### 401 Unauthorized

### 403 Forbidden

### 404 Not Found

---

### 405 Method Not Allowed

### 406 Not Acceptable

### 407 Proxy Authentication Required

### 408 Request Timeout

### 409 Conflict

### 410 Gone

### 411 Length Required

### 412 Precondition Failed

### 413 Content Too Large

### 414 URI Too Long

### 415 Unsupported Media Type

### 416 Range Not Satisfiable

### 417 Expectation Failed

### 421 Misdirected Request

### 425 Too Early 

### 426 Upgrade Required

### 428 Precondition Required

### 429 Too Many Requests

### 431 Request Header Fields Too Large

### 451 Unavailable For Legal Reasons

---

## 5xx

### 500 Internal Server Error

### 501 Not Implemented

### 502 Bad Gateway

### 503 Service Unavailable

### 504 Gateway Timeout

### 505 HTTP Version Not Supported

### 506 Variant Also Negotiates

### 510 Not Extended

### 511 Network Authentication Required

## さいごに

ステータスコードの要点をざっとおさらいしました。  
基礎知識が曖昧になったときなどにまた読み直してみてください。

## 参考文献

- [Webを支える技術](https://gihyo.jp/book/2010/978-4-7741-4204-3)
- [HTTPの教科書](https://www.shoeisha.co.jp/book/detail/9784798126258)
- [HTTP レスポンスステータスコード - HTTP | MDN](https://developer.mozilla.org/ja/docs/Web/HTTP/Reference/Status)
