# hello world
```javascript
var a = "hello"
```

## -php数据库连接
```php
$conn = @mysqli_connect("localhost","root","","html5-7");
if (!$conn) {
	die("连接失败！");
}

$conn->query("set names utf8");
$sql = "insert into user(name,pwd) values('c1','ccc'),('c2','ccc'),('c3','ccc')";
$conn->query($sql);
if(mysqli_affected_rows($conn)>0){
    echo "添加成功".mysqli_insert_id($conn);
}else{
    echo "添加失败";
}
