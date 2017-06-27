# things-auth
## 1. Explanation
This is a component for resetting login, logout password and requesting activation and new registration.

### Login Form

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

## 2. Development
### 2.1 Install Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

### 2.2 Run Application

```
$ polymer serve
```

### 2.3 Build Application

```
$ polymer build
```

You can launch the server from `build/bundled` or `build/unbundled` with the following command:

```
$ polymer serve build/bundled
```

### 2.3 Run Tests

```
$ polymer test
```

The test has been set up as described in [web-component-tester](https://github.com/Polymer/web-component-tester).
You can run the test with the following command.
```
$ polymer test
```
