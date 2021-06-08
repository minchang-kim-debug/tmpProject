how to Xing API downloading

1. 트레이딩 다운로드 홈페이지 접속 (eBest)
- https://www.ebestsec.co.kr/ 
- 계좌 개설 및 xing API 동의해야 함
2. 하단 API를 눌러 설치 및 이용동의하여 접속
3. DevCenter 실행
4. cmd를 통해 pywin32 설치
- pip install pywin32
5. 설치 후 동작 확인
- import win32com.client
- client = win32com.client.Dispatch("XA_Session.XASession")
- client.ConnectServer("demo.ebestsec.co.kr", 20001)
>> TRUE
TRUE return is success

- demo.ebestsec.co.kr << test url
