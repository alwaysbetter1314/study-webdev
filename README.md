# study-webdev
web 开发相关

## 获取当前时间戳
```
const getTs = ()=>{
    var time = Date.parse( new Date() ).toString();//获取到毫秒的时间戳，精确到毫秒
    return time.substr(0,10);//精确到秒
}
```
