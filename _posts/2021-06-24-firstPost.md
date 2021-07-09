---
title:  "github.io 블로그 시작하기"
excerpt: "GitHub Blog 서비스인 github.io 블로그 시작하기로 했다."

categories:
  - Blog
tags:
  - Blog
last_modified_at: 2019-04-13T08:06:00-05:00
---

GitHub Blog 서비스인 github.io 블로그 시작하기로 했다.
GitHub Blog 서비스의 이름은 Pages이다.

Pages가 다른 블로그 플랫폼 보다 편한 것 같아서 마음에 든다.
다른 사람들도 같이 많이 사용했으면 좋겠다는 생각이 든다.

YFM에서 정의한 제목을 이중 괄호 구문으로 본문에 추가할 수 있다.
이 글의 제목은 {{ page.title }}이고
마지막으로 수정된 시간은 {{ page.last_modified_at }}이다.

기본적인 텍스트 표기 방식이다.
마크다운은 줄바꿈을 인식하지 않는다.

줄바꿈을 하기 위해서는 라인 끝에 스페이스를 2번  
표기해야 한다.  


### Example of using Java
```java
public static void main(String[] args) {
  System.out.println("Hello World!");
}
```