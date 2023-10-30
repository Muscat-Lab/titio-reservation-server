# titio-reservation-server

## 구성

 ### spring webflux 
 적은 수의 자원으로 높은 동시성을 갖출 수 있는 spring webflux를 사용해 WAS를 구현한다. 
 
 ### redission 
 redis에 구현되어 있는 distributed lock을 이용해 데이터의 결함 없이 공유 자원을 관리한다. 
 
 ### k8s 
 k8s를 이용해 어플리케이션을 배포하여 변화하는 트래픽에 유연하게 대응할 수 있는 클러스터를 구축해본다.
