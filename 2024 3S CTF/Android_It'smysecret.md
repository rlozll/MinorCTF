![initial](https://github.com/user-attachments/assets/ad9c812e-2f23-4c39-8261-ed4e90f13d56)

우선 apk 파일을 apktool을 통해 디컴파일 해주었다.

(https://ndb796.tistory.com/448 참고)

![initial](https://github.com/user-attachments/assets/a0916c6a-2e1e-4cd7-aee9-9ac804454059)

이렇게 위와 같이 파일들이 나왔다.

이를 jadx로 열어주었다.

아마 nox 사용하라고 하신 거 보면여기서 어떤 파일을 열어야 힌트를 얻을 수 있는지 확인하는 것 같은데,

나는 nox 앱플레이어가 오류가 나서... 설치가 잘 되지 않는 바람에 일단 이것저것 뒤져보았다.

근데 파일을 그냥 찾던 도중, SecretActivity 파일이 (누가봐도) 수상해보여 들어갔더니, 플래그가 떴다.

오래 걸리지는 않았다.

![initial](https://github.com/user-attachments/assets/e1d6b288-70f4-46b7-aa9d-792a503a3d61)

### FLAG: 3S{It's_your_first_step_toward_Android_hacking} 
