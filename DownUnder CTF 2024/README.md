## DownUnder CTF 2024년 7월 13일 Write up
## Forensics - Baby's First Forensics

해당 문제에는 pcap 파일 하나가 들어있었다.

프로토콜은 DNS, TCP, HTTP 프로토콜만을 이용한 패킷들이 보였고, TCP 프로토콜을 이용한 패킷들은 처음에 3 way handshaking을 주고받는 모습들이 보였다.

![initial](https://github.com/user-attachments/assets/99bf3309-df1c-4d02-b12c-18d8c42bcccf)

근데 문제에서는 패킷을 주고받는 데 사용한 툴과 버전을 알아내라고 했으니, HTTP 프로토콜을 자세히 살펴보도록 하겠다.

![initial](https://github.com/user-attachments/assets/3c14fb26-3331-45f2-ba13-e3f5ccb6428c)

HTTP 프로토콜을 사용한 패킷들 중에서도 404라든지 이런 오류가 뜨는 것이 아닌 뭔가 주고 받은 흔적들이 보이는 패킷을 하나 골라 자세히 살펴주었다.

그 중 Hypertext Transfer Protocol section을 확장하여 User-Agent 필드를 확인해주었다.

