# 수업 내용 필기

이 곳에는 수업 내용 필기를 위한 마크다운(MarkDown)을 작성하는 방법을 살펴보겠습니다.

## 랜덤(Random)

랜덤은 뭐가 나올지 예측이 불가능한 값을 말합니다.  
랜덤을 만드는 방법은 여러 가지가 있습니다.

1. Random이라는 도구를 생성하여 사용
2. Math.random() 명령을 사용
3. SecureRandom 도구를 생성하여 사용

여기서는 Random 도구를 생성합니다.
```java
Random r = new Random(); // 참조형 r 생성
r.setSeed(System.currentTimeMillis()); // 시드 값을 현재시간에 대한 값으로 설정.
```

이도구를 사용하기 위해서는 import가 필요합니다.
```java
import java.util.Random;
```

import는 직접 작성하지 않고 **단축키**인 `ctrl+shift+o`를 누릅니다.

## 랜덤 정수 추첨

생성한 도구를 이용해서 랜덤한 정수를 추첨할 수 있습니다.
단, 생성을 위해서는 범위를 정해야 합니다.

- 사람은 범위를 이야기할 때 `a`부터 `b`까지 라고 합니다.
- 자바는 범위를 이야기할 때 `a`부터 `b`개 라고 합니다.

| 항목 | 범위 |
| :---: | :--- |
| 주사위 | `1`부터 `6`까지 |
| 로또 | `1`부터 `45`개 |
| 두자리 정수 | `10`부터 `90`개 |

난수 생성의 원리가 궁금하시다면 [위키백과](https://ko.wikipedia.org/wiki/%EB%82%9C%EC%88%98)에서 확인할 수 있습니다.  

![img](https://i.namu.wiki/i/Tu93EDNTHxVfDsDjQEoYRQQnkNmZe1ySr70TpkyxU3kd0IoWS96oLBhl3kbl6EIKS-dXVCBkjLK4Ga1pLtZ92w.webp)  

오늘도 연봉이 10원 올랐습니다.
![좋아 역시 최고야!](./20190408111831_pfhdosqp.gif)
