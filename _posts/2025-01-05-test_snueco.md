---
layout: single
title:  "[3] 개발환경 구축 (flutter 사용) "
toc: true
toc_sticky: true
toc_label: "페이지 주요 목차"
---

본 어플은 Android와 iOS 동시 개발이 가능한 Flutter 프레임워크를 사용하여 제작하였으며, dart 언어를 활용함.

[코드팩토리 1시간 강의 Youtube](https://www.youtube.com/watch?v=3Ck42C2ZCb8)
영상을 참고하면 dart 언어 사용법을 익힐 수 있음.


#  Flutter 개발 환경 구축
### Test
### Test22


  # first
  ### sero

## forf
### gjdsgn

# sdflsknf
## dffspof
### sdfsfs

# slkfn

# slfksf
# flsdkfnslf
  * Flutter가 지원하는 환경은 아래와 같음

| OS     | window, Mac OS, Linux             |
|--------|-----------------------------------|
| Target | Android, iOS, Web, Desktop        |
| Editor | Android Studio, IntelliJ, VS Code |

개발 시에는 VS Code를 이용하여 수정하였으나, 개발자의 취향에 따라 안드로이드 스튜디오를 
사용해도 무관함(VS Code에서는 오류가 나는 코드가 안드로이드 스튜디오에서는 
잘 작동하기도 함). 다만, VS Code 편집기가 더 용이하므로 이를 기준으로 후술하겠음

이때, 결국 iOS 빌드를 위해서는 Mac OS 환경이 필요하므로 참고

개발환경 구축을 위해 크게 아래와 같은 작업 필요

(1) Flutter 플러그인 설치
([Flutter 플러그인 설치 링크](https://docs.flutter.dev/get-started/install))

(2) Android Studio 설치 
([Android Studio 설치 링크](https://developer.android.com/studio?hl=ko))

(3) VS Code 연결
([VS Code 설치 링크](https://code.visualstudio.com/download))

*참고: VS Code를 활용하더라도 Android Studio를 설치해야 함. 
설치하지 않는 방법도 있으나, 대부분의 개발자가 설치하고 사용하므로 
디버깅을 위해 설치하는 것을 권장함

[이 링크](https://breath-codedive.tistory.com/entry/Flutter-%ED%94%8C%EB%9F%AC%ED%84%B0-VS-Code-%EA%B0%9C%EB%B0%9C%ED%99%98%EA%B2%BD-%EC%84%B8%ED%8C%85-Windows)를 
참고하여 환경 변수 설정 등의 과정을 거치면 됨


### Flutter Flow
디자인 작업 효율 증진을 위해 Flutter Flow를 활용하여 어플 디자인 작업을 수행함.
[Flutter Flow 페이지](https://www.flutterflow.io/?gad_source=1&gclid=CjwKCAiA-Oi7BhA1EiwA2rIu22edVvXSfD3m57aOS50M3Y2XbOddbz3jf1js3QYbcW1tJOCcM6QyYhoCnAwQAvD_BwE
)에 접속하여 가입한 후, Flutter Flow 프로젝트에 Co-worker에 추가하는 방식으로 협업 가능

![Flutter Flow](https://github.com/rhn5121/rhn5121.github.io/blob/master/_posts/images/Flutter%20Flow.png?raw=true)

디자인 수정시, 코드 자체를 수정하면 바로 확인이 어려워서 FF 상에서 수정하고, 수정된 코드를 복사하여 VS Code와 같은 편집기 상의 코드를 수정하면 용이함.

FF 자체에서는 빌드 가능한 것이 로컬 상에서는 빌드가 되지 않아 오류가 나는 경우가 많으므로, 코드를 조금씩 가져다가 사용하는 방식으로 이용하기를 권장 (디자인 작업만 수행하는 것이 가장 안전함)






<p align="center"><img src="https://github.com/rhn5121/rhn5121.github.io/blob/master/_posts/images/beacon_mechanism.png?raw=true" width="80%" height="80%"/></p>


