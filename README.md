# 네이버 뉴스를 통한 주가 예측 프로그램
> 간략한 프로젝트 소개 문구를 작성합니다.

[![NPM Version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Downloads Stats][npm-downloads]][npm-url]

투자에 관심이 높아짐에 따라 예적금보다 상대적으로 위험도가 높은 주식 투자에도 개인의 관심도가 증가하고 있다. 

일반적으로 투자한 기업의 주가의 상승과 하락에 따라 자산이 증감하게 되는데, 따라서 주식투자를 통해 수익을 내기 위해선 기업의 주가를 예측할 수 있어야 한다. 

그 방법으로 여러 가지가 있지만, 이 프로젝트는 네이버 사이트를 통해 다양한 신문사의 뉴스 기사를 수집하고, 그 기사들이 주가에 어떤 영향을 주는지 분석하여 주가를 예측하고자 한다.



## 구현 방법

네이버 증권에서 삼성전자의 기사 제목, 1분마다의 주가, 그 때의 시간 데이터를 동적 웹 크롤링을 실행하고, 전처리를 시행하였다.
이 정보를 바탕으로 SQL을 활용해 DB화 하고, LSTM을 통해 모델을 학습시켰다. 






![](../header.png)

## 설치 방법

OS X & 리눅스:

```sh
npm install my-crazy-module --save
```

윈도우:

```sh
edit autoexec.bat
```

## 사용 예제

스크린 샷과 코드 예제를 통해 사용 방법을 자세히 설명합니다.

_더 많은 예제와 사용법은 [Wiki][wiki]를 참고하세요._

## 개발 환경 설정

파이썬과 mariadb, sqlite, pytorch 
```sh
make install
npm test
```

## 코드블럭 설명

```c
//```뒤에 자신이 원하는 언어 (생략 가능)
#include <stdio.h>
int main(void) {
  printf("Hello World!");
}
```


## 업데이트 내역

* 0.2.1
    * 수정: 문서 업데이트 (모듈 코드 동일)
* 0.2.0
    * 수정: `setDefaultXYZ()` 메서드 제거
    * 추가: `init()` 메서드 추가
* 0.1.1
    * 버그 수정: `baz()` 메서드 호출 시 부팅되지 않는 현상 (@컨트리뷰터 감사합니다!)
* 0.1.0
    * 첫 출시
    * 수정: `foo()` 메서드 네이밍을 `bar()`로 수정
* 0.0.1
    * 작업 진행 중

## 정보

이름 – [@트위터 주소](https://twitter.com/dbader_org) – 이메일주소@example.com

XYZ 라이센스를 준수하며 ``LICENSE``에서 자세한 정보를 확인할 수 있습니다.

[https://github.com/yourname/github-link](https://github.com/dbader/)

## README 

1. https://github.com/kyechan99/capsule-render
2. https://yermi.tistory.com/entry/%EA%BF%80%ED%8C%81-Github-Readme-%EC%98%88%EC%81%98%EA%B2%8C-%EA%BE%B8%EB%AF%B8%EA%B8%B0-Readme-Header-Badge-Widget-%EB%93%B1


## 그외의 팁

취소선
~~취소선~~


인용글
> 인용글 1
> > 인용글 2
> > > 인용글 3

기울임
*기울임 꼴*

_기울임 꼴_


굵은글씨

**굵은 글씨**

__굵은 글씨__

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki
