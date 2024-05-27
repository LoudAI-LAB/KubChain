# KubChain
##### 나만의 Flowise를 로컬 서버에서 쉽고 빠르게 build 하기 위해 배포한 것입니다.


## KubChain Build
~~~sh
# Container 생성
docker build -t <tag name:version> .

# Container 실행
docker run --name [container_name] -d -p [local_port]:[container_port] [image_name]:[tag]
~~~
