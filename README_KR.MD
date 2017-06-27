# things-auth
## 1. 설명
이는 로그인, 로그아웃 비밀번호 재설정, 활성화 요청, 신규등록 요청을 위한 컴포넌트이다.

### 로그인 화면

Example:
```html
<things-login data-route="login"
              route ="{{route}}"
              title="Things Label Management"
              login-path="login"
              content-type="application/x-www-form-urlencoded"
              success-route="list"
              username-input-label="ID"
              password-input-label="Password"
              submit-label ="Submit"
              Reset-label = "Reset">
  <img avatar src="https://maps.gstatic.com/tactile/pane/default_geocode-1x.png"/>
</things-login>
```

## 2. 개발
### 2.1 Polymer-CLI 설치

먼저 [Polymer CLI](https://www.npmjs.com/package/polymer-cli)가 설치되어 있는지 확인한다. 다음, `polymer serve`를 실행하여 로컬에서 응용 프로그램을 제공한다.

### 2.2 Application 실행

```
$ polymer serve
```

### 2.3 Application 빌드

```
$ polymer build
```

아래 명령어로 `build/bundled`나 `build/unbundled`에서 서버를 띄울 수 있다.

```
$ polymer serve build/bundled
```

### 2.4 Test 실행

```
$ polymer test
```

[web-component-tester](https://github.com/Polymer/web-component-tester)에서 설명한 대로, 테스트 설정은 이미 완료되어 있다.
아래 명령어로 테스트를 실행할 수 있다.
```
$ polymer test
```
