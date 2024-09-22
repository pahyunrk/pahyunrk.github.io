---
title: "[Swift] leading과trailing"
description: 
author: pahyunrk
date: 2024-09-22
categories: [Swift]
tags: [Swift, alignment ,AppleWatch]
pin: false
math: true
mermaid: true
image:
  path: /thumbnail/swift-logo.png
  lqip: 
  alt: 
---

Swfit에서는 정렬을 할때 left,right대신 leading과trailing을 사용한다.
오늘은 그 이유와 사용법에 대해 알아보도록 하자.

<br>


## leading과 trailing을 사용하는 이유
우리나라는 글을 읽고 쓸때 왼쪽에서 오른쪽방향으로 좌횡서를 사용한다. 하지만 다른나라도 무조건 그러진 않을 것이다. 우리나라와 반대로 오른쪽부터 시작하여 왼쪽으로 읽고 쓰는 우횡서 문화를 가진 나라도 존재한다. 

만약 left와 right를 사용하여 앱을 만들면 우횡서문화를 가진 나라의 사람들은 앱을 이용할때 많은 불편함을 가질것이다. 그래서 나온 정렬방법이
leading과 trailing이다.

leading은 텍스트의 시작방향, trailing은 텍스트의 종료방향이다.

정리하자면 사용사의 불편함을 줄이기 위해 Right To Left, Left To Right를 원할하게 지원하기 위해서 사용된다.



![좌횡서](/assets/img/postImg/20240922/좌횡서.png)


![우횡서](/assets/img/postImg/20240922/우횡서.png)




## 사용법
만들어진 이유를 알았으니 사용법을 알아보자.

### leading
텍스트의 시작방향
![leading](/assets/img/postImg/20240922/leading.png)


### trailing
텍스트의 끝방향
![trailing](/assets/img/postImg/20240922/trailing.png)

----

이글은 Swift 공식문서를 참고하여 작성하였습니다.