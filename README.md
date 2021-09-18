# deploy_with_docker
Deploy Flask Web Server using docker in AWS EC2


1. [7/59] 클라우드 서비스 구축 - AWS EC2 서버 접속
  1) aws에서 발급한 pem key를 통해 aws에 ssh 접속하는 방법
      chmod 400 key.pem
      ssh -i key.pem ubuntu@[할당한 IP 주소]
      * IP 주소 할당 방법은 AWS에서 인스턴스 생성 후, 탄력적 IP 생성 후에, 해당 인스턴스와 연결 --> 탄력적 IP 탭에서 "할당된 IPv4 주소" 컬럼의 값이 [할당한 IP 주소] 값이다.