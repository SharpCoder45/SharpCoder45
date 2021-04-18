### Introduction
# Stately [![build passing](https://img.shields.io/badge/build-passing-<COLOR>.svg)](https://github.com/SharpCoder45/SharpCoder45) [![license gpu](https://img.shields.io/badge/license-gpu-<COLOR>.svg)](https://github.com/SharpCoder45/SharpCoder45/blob/main/LICENSE)
A global state and logic framework for JavaScript applications. With Stately by your side, front-end state management is a breeze.
### Documentation
```javascript
const App = new State();

App.setState('hello world');
```
**Why Stately?**
<br>
Stately is a powerful, lightweight alternative to state-management tools such as Redux, VueX and MobX.
<br>
**Value of State**
In the above snippet, the state of `App` is set to `'hello world'`. If we want to *view* the state, we can do so with a simple log to the console:
```javascript
console.log(App.state);
```
Output:
<br>
`'hello world'`
### Content Delivery Network (CDN)
Before you can begin using Stately, you need to integrate Stately into your web app by linking to our content delivery network or CDN. Don't worry, this is a simple process.
```html
<script src='https://github.com/SharpCoder45/SharpCoder45/blob/main/index.js'></script>
```
Now you're ready to start utilizing the power of Stately!
