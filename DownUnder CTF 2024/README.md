## DownUnder CTF 2024년 7월 13일 Write up
## Forensics - Baby's First Forensics

해당 문제에는 pcap 파일 하나가 들어있었다.

프로토콜은 DNS, TCP, HTTP 프로토콜만을 이용한 패킷들이 보였고, TCP 프로토콜을 이용한 패킷들은 처음에 3 way handshaking을 주고받는 모습들이 보였다.

![initial](https://github.com/user-attachments/assets/99bf3309-df1c-4d02-b12c-18d8c42bcccf)

근데 문제에서는 패킷을 주고받는 데 사용한 툴과 버전을 알아내라고 했으니, HTTP 프로토콜을 자세히 살펴보도록 하겠다.

