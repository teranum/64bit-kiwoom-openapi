# 64bit-kiwoom-openapi-ocx

* 국내용 ProgID: KHOPENAPI64.KHOpenAPICtrl.1
* 해외용 ProgID: KFOPENAPI64.KFOpenAPICtrl.1

# 설치방법
1. 최신판 vcredist x64 버젼 [link](https://docs.microsoft.com/ko-kr/cpp/windows/latest-supported-vc-redist?view=msvc-170) 설치
2. zip압축 해제후 파일들을 키움증권 OpenApi폴더로 이동 (C:\OpenApi), 해외선물용은 OpenApiG폴더로 이동(C:\OpenApiG)
3. <설치 관리자권한으로.bat> 파일을 관리자 권한으로 실행

# 참고
* 작동원리: 메모리 IPC통신을 이용하여 키움증권의 32비트 모듈과 데이터를 연결합니다.
* 32비트와 64비트 사이 데이터 통신이 진행되므로, 요청/응답 사이 추가적인 시간비용이 발생합니다.
* 32비트, 64비트 테스트 프로그램에서 요청과 응답의 딜레이를 밀리초 단위로 확인 할 수 있습니다.



