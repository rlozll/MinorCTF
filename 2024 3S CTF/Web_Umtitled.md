## Untitled

index.php 파일의 내용은 아래와 같다.

![initial](https://github.com/user-attachments/assets/a5a53757-00a4-440c-a640-59b029e92980)

flag.php 파일의 내용은 아래와 같다.

![initial](https://github.com/user-attachments/assets/d4637ee5-86eb-488f-9f8d-149996613fe6)

index.php 파일의 preg_match를 보면 flag, etc, test,.... 등 여러 개가 써있다.

그리고 test를 요청하는 것 같은데, 그렇다면 쿼리문을 작성해보면

(앞의 url 주소~..)?test=flag

이런식으로 해봤는데 되지 않는다.

include 부분에 공백이 있는 걸 봐서 공백을 추가해야 하는 것 같다.

여러가지를 시도해보다가, ?test=fla%20%20g를 입력하니까 되었다.

![initial](https://github.com/user-attachments/assets/02c2b381-eb75-457d-9d46-156f47d18577)

### FLAG: 3S{re_re_re_r3_Re_re_RE_re_re_GEx}
