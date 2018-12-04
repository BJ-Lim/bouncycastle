# Bouncy Castle
## 개요
bouncy castle은 암호 작성에 사용되는 API들의 모음입니다.

### Download
[link](http://www.bouncycastle.org/java.html)

## 지원 언어
- java
- c#

## 역사
```
Bouncy Castle은 두 명의 동료가 서버 측 Java SE에서 작업하는 작업을 변경할 때마다 일련의 암호화 라이브러리를
다시 작성해야하는 것에 지쳐 있었기 때문에 시작되었습니다. 개발자 중 한 명이 자바 ME (당시 J2ME) 개발에서
취미로 활동했으며 설계 고려 사항은 J2ME의 Java VM을 포함하여 라이브러리에 가장 많은 범위의 Java VM을 포함시키는
것이 었습니다. 이 디자인 고려 사항은 Bouncy Castle에 존재하는 아키텍처를 이끌어 냈습니다.

이 프로젝트는 2000 년 5 월에 설립되었습니다. 원래는 자바였습니다. C # API는 2004 년에 추가되었습니다.

원래 Java API는 테스트 코드 및 J2ME, JCE / JCA 공급자 및 기본 X.509 인증서 생성에 대한 지원을 포함하여
약 27,000 줄의 코드로 구성되었습니다. 이에 비해 1.53 릴리스는 테스트 코드를 포함하여 390,640 줄의 코드로
구성됩니다. PKCS # 10, PKCS # 12, CMS, S / MIME, OpenPGP, DTLS, TLS, OCSP, TSP, CMP, CRMF, DVCS, 
DANE, EST와 같은 많은 기능을 갖춘 원본 릴리스와 동일한 기능을 지원합니다.
C # API는 약 145,000 줄의 코드이며 Java API의 대부분을 지원합니다.

프로젝트의 주요 속성은 다음과 같습니다.
표준 준수 및 적응성에 중점을 둡니다.
공개 지원 시설에는 문제 추적기, dev 메일 링리스트 및 위키가 모두 웹 사이트에서 제공됩니다.
Bouncy Castle 웹 사이트에 나열된 관련 API에 대한 자료로 상업적 지원을 제공합니다.

2013 년 10 월 18 일 비영리 단체 인 Bouncy Castle Inc.의 군단 (Legion of Bouncy Castle Inc.)은 호주
빅토리아주의 핵심 개발자 및 다른 사람들이 프로젝트 소유권을 획득하고 현재 진행중인 아피스 협회는
교육 진흥의 목적과 2013 년 11 월 7 일에 호주 자선 단체 및 비영리 단체위원회에 의해 지역 사회에 도움이되는 
목적으로 호주 자선 단체로 인정되었습니다. 협회는 2013 년 11 월 29 일 
빅토리아 소비자 보호국 (Consumer Affairs Victoria)에서 그 목적을 지원하기 위해 기금 모금을 할 권한이있었습니다.
```

## references
- [bouncy castle](http://www.bouncycastle.org/java.html)
- [wikipedia](https://en.wikipedia.org/wiki/Bouncy_Castle_(cryptography))
- [google translation](https://www.google.com/search?ei=Kk8GXP78FIL-8QXYqL24Aw&q=%EB%B2%88%EC%97%AD%EA%B8%B0&oq=%EB%B2%88%EC%97%AD%EA%B8%B0&gs_l=psy-ab.12...0.0..266970...0.0..0.0.0.......0......gws-wiz.XgI5Z0Og5Sw)


# JAVA provider framework
## 개요
- Java에서 암호화 기술을 사용하기 위한 기본 기능은 JCA (Java Cryptography Architecture)와 그 형제인 Java Cryptography Extension (JCE)에서 제공합니다.
- JCA 아키텍처는 provider 기반 아키텍처입니다.
- Java 응용 프로그램과 암호화 공급자 사이의 중간 계층 (인터페이스)으로 정의되었습니다.
```
즉, 자바는 provider를 추가해서 추가 기능을 사용할 수 있도록 인터페이스를 정의해 놓았습니다.
```

## 제공하는 클래스와 인터페이스
- java.security
- javax.crypto
- javax.crypto.spec
- javax.crypto.interfaces

## reference
- 강의 교안

