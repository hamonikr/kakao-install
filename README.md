# kakao-install

하모니카 리눅스에서 윈도용 카카오톡을 설치해 주는 프로그램

## 주요기능

 * 윈도우용 kakaotalk 을 하모니카에서 사용하기 위해 필요한 프로그램의 자동 설치


## 데비안 패키지 빌드

다운로드 받은 디렉토리 안에서 아래와 같이 빌드하면 release 폴더 안에 설치 가능한 데비안 파일 생성

```
./build
```

## 프로그램 설치

```
sudo dpkg -i release/kakao-install*_amd64.deb
```

## 프로그램 삭제

```
sudo apt purge kakao-install
```

## 버그 또는 이슈 제출

사용 중 발견한 버그나 이슈는 help@hamonikr.org 로 메일을 보내주세요
