cookie.js
=========

**一个极小但强大并容易使用的cookie.js**

**a tiny but powerfull and easy to use cookie.js**

**only 只有 472 Byte**


by wushufen
wusfun@foxmail.com
2014.01.05
update 2014.06.12



## Usage

### set
```javascript
cookie('name', 'value', {expires: ms, path: '', domain: '', secure: true}); //options
```
```javascript
cookie('name', 'value'); //set
```

### delete
```javascript
cookie('name', null);    //delete
```
```javascript
cookie(null);            //delete all
```

### get
```javascript
cookie();                //get all {}
```
```javascript
cookie().name            //get
```
```javascript
cookie()['name']         //get
```
```javascript
cookie('name');          //get
```