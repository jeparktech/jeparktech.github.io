---
title: "Flutter 2.X Null Safety"
excerpt: "Learn about flutter null safety"

categories:
    - Flutter

tags:
    - Flutter
    - Dart
    - NullSafety

last_modified_at: 2021-07-09
---

Flutter가 2.x 로 업데이트 하면서 Null safety가 추가되었다.

Null safety가 추가되며 no reference 버그를 수정할 수 있었고,  
코드의 신뢰도를 향상시켰으며, 불필요한 연산을 제거함으로써   
컴파일러를 최적화하였다.

기존 Dart 문법의 variable는 null 값을 가질 수 없게 되었고  
새롭게 nullable variable type이 추가되었다.  

이로 인해 Null safety가 적용된 코드와 적용되지 않은 코드가
공존할수 있다.


