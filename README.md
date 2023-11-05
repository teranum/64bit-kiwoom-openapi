# 64bit-kiwoom-openapi-ocx

* 국내용 ProgID: KHOPENAPI.KHOpenAPICtrl.1
* 해외용 ProgID: KFOPENAPI.KFOpenAPICtrl.1
* *32비트/64비트 ProgID, GUID 동일, 소스수정 없이 빌드환경만 64비트로 바꾸어주면 됨.(2023/11/05 업데이트)
* *nuget KHOpenApi.NET 이용 할 경우 버젼 1.4.0 이상 설치

# 설치방법
1. 최신판 vcredist x64 버젼 [link](https://docs.microsoft.com/ko-kr/cpp/windows/latest-supported-vc-redist?view=msvc-170) 설치
2. zip압축 해제후 파일들을 키움증권 OpenApi폴더로 이동 (C:\OpenApi), 해외선물용은 OpenApiG폴더로 이동(C:\OpenApiG)
3. <설치 관리자권한으로.bat> 파일을 관리자 권한으로 실행

# 참고
* 메모리 IPC통신을 이용하여 키움증권의 32비트 모듈과 데이터 통신진행.
* 64비트와 32비트 사이 데이터 통신이 진행되며, 요청/응답 사이 추가적인 시간비용 발생.
* 64비트/32비트 테스트 프로그램으로 요청과 응답의 딜레이를 밀리초 단위로 확인가능.



