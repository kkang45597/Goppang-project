# gopang-microservice
현재 configserver/src/main/resource/bootstrap.yml 파일에는 깃허브 패스워드가 누락되어있습니다. <br>
```
  cloud:
    config:
      server:
        git:
          default-label: main
          uri: https://github.com/kkang45597/Gopang-config
          username: kkang45597
          password: 
          refresh-rate: 60
```
실행하기 위해선 Gopang-config 리포지토리를 생성하고 파일을 넣은 뒤, 자신의 깃허브 아이디와 패스워드 토큰을 사용해야 합니다.

## POSTMAN
<img src="./image/K-001.png" width=90% /><br>


## Zipkin
<img src="./image/K-002.png" width=90% /><br>

<img src="./image/K-003.png" width=90% /><br>


## Kibana
<img src="./image/K-004.png" width=90% /><br>

<img src="./image/K-005.png" width=90% /><br>

<img src="./image/K-006.png" width=90% /><br>

