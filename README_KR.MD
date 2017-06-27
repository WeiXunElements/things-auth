# things-auth
## 1. 설명
로그인, 로그아웃 페스워드 재설정, 활성화요청, 신규등록 요청을 위한 컴포넌트

ko-KR
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

##

en-US
## A things login form asking for login and password.

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

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

### 2.2 Application 수행

```
$ polymer serve
```

### 2.3 Application 빌드

```
$ polymer build
```

아래 명령어로 ` build/bundled`나 ` build/unbundled`에서 서버를 띄울수 있다.

```
$ polymer serve build/bundled
```

### 2.3 Running Tests

```
$ polymer test
```

테스트는 [web-component-tester](https://github.com/Polymer/web-component-tester)에서 설명한데로 설정완료됨.
아래 명령어로 테스트를 수행할 수 있다.
```
$ polymer test
```
