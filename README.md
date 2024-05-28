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
