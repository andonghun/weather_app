## React Native Basic

node, npm 필수

안드로이드 스튜디오나 Xcode를 설치해도 되지만, expo를 이용해 휴대폰에서 진행하도록 하겠다. 휴대폰에 expo를 다운받도록 한다.

그리고 아래와 같은 명령어를 이용해 실행시켜준다.

```bash
$ npm install -g expo-cli
$ expo init weather
```



***expo란?***
모바일 native files에 접근하고 관리할 수 있도록 해주는 react Framework



#### 특징

- Live Reload: 코드를 수정하면 프로젝트 전체를 새로고침하여 반영된다.
- Hot Reload: 코드를 수정하면 우리가 수정한 부분만을 인지하여 그 부분만 새롭게 불러온다.



### 모바일 앱을 만드는 방법

1. Native 방식
   1. Swift or objective-c For iOS
   2. Java or Kotlin For Android
2.  앱 기반 웹뷰
   1. Codova 등
   2. Phone Gap
3. RN
   1. 자바스크립를 이용해서 Native의 엔진을 조작(Using Bridge)



#### StyleSheet API

RN에서 제공하는 CSS API