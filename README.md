# study-webdev
web 开发相关

## 获取当前时间戳
```javascript
const getTs = ()=>{
    var time = Date.parse( new Date() ).toString();//获取到毫秒的时间戳，精确到毫秒
    return time.substr(0,10);//精确到秒
}
```
## 随机整数[30,50]
```
const RandNum = ()=>  parseInt(Math.random()*20)+30
```
