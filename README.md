# sys_lab4_repo
시스템 프로그래밍 lab4 실습





### Usage
< num 2 >
```
// POSIX thread 함수(pthread_create, pthread_join)를 사용하는 경우
// hellothreads.c, jointhread.c 해당
$ gcc filename.c -o filename -lpthread
$ ./filename
```

```
$ gcc filename.c -o filename
$ ./filename
```

< num 3 >
```
$ gcc boundedbuffer.c -o boundedbuffer
$ ./boundedbuffer
```

< num 4 >
```
$ gcc broadcast.c -o broadcast
$ ./broadcast
```

< num 5 >
터미널 1 (서버)
```
$ gcc socket_ex_s.c -o socket_ex_s
$ ./socket_ex_s
```

터미널 2 (클라이언트)
```
$ gcc socket_ex_c.c -o socket_ex_c
$ ./socket_ex_c
```

< num 6 >
터미널 1
```
$ gcc server.c -o server
$ ./server
```

터미널 2
```
$ gcc client.c -o client
$ ./client <IP> <name>
```

터미널 3
```
$ ./client <IP> <name>
```

< num 7 >
터미널 1
```
$ gcc tcp_web_server.c -o tcp_web_server
$ ./tcp_web_server
```

터미널 2
```
$ curl http://<IP>:<포트 번호>
```

_*curl 미설치 시 : sudo apt install curl_

< num 8 >
```
$ gcc -o filename filename.c $(pkg-config --cflags --libs gtk+-3.0)
$ ./filename
```

_*gtk 미설치 시 : sudo apt-get install libgtk-3-dev glade cmake build-essential_

9
컴파일
gcc -o calculator calculator.c $(pkg-config --cflags --libs gtk+-3.0)
실행
./calculator
