### webStorage
  一个将localStorage和sesionStorage封装到一起的包.

  ![](https://img.shields.io/badge/rollup-v1.7.3-green.svg)       ![](https://img.shields.io/badge/npm-6.4.1-green.svg)       ![](https://img.shields.io/badge/loaclStorage-webStorage-blue.svg) ![](https://img.shields.io/badge/sessionStorage-webStorage-blue.svg) 

  * [x] localStorage
  * [x] sessionStorage
#### 安装

 ```js
  npm install xieyezi-storage
 ```
 #### 用法

```js
import xieyeziStorage form 'xieyezi-storage';
```

localStorage设置storage:
```js
 storage.set(key,val);
```
sessionStorage设置storage:
```js
storage.session.set(key, val);
```

localStorage获取storage:
```js
 storage.get(key,val) ;
```
sessionStorage获取storage:
```js
storage.session.get(key, val);
```

#### API

set(key,value):

get(key,def);

remove(key);

has(key);

clear();

getAll();

forEach(callback);





  

