# redis-clone

This is a clone of https://mliezun.github.io/2023/04/08/redis-clone.html

### How to run
go run main.go

### How to test
$ telnet 127.0.0.1 6380
GET a
$-1
set a "test \"quotes\" are working"
+OK
get a
$25
test "quotes" are working