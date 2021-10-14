# Container Orchestration

### 정의
오케스트레이션은 컴퓨터 시스템과 애플리케이션, 서비스의 자동화된 설정, 관리, 조정을 의미하며 그 중에서 컨테이너를 배포 관리하는 것을 Container Orchestration라 고 함.

### 목적
여러 컨테이너의 배포 프로세스를 최적화

### 기능
* 프로비저닝 및 배포
* 설정 및 스케줄링
* 리소스 할당
* 컨테이너 가용성
* 인프라 전반의 워크로드 밸런싱을 기반으로 컨테이너 스케일링 또는 제거
* 로드 밸런싱 및 트래픽 라우팅
* 컨테이너 상태 모니터링
* 실행될 컨테이너를 기반으로 애플리케이션 설정
* 컨테이너 간 상호 작용의 보안 유지

### Benefit
#### containers and their benefits
* Portability(이식성): One of the biggest benefits of containers is that they’re built to run in any environment(different cloud platforms). 
  * Boosts developer productivity, since they can write code in a consistent manner without worrying about its execution when deployed to different environments—from a local machine to an on-premises server to a public cloud.
* Application development: Containers can speed up application development and deployments, including changes or updates over time. This is particularly true with containerized microservices. This is an approach to software architecture that entails breaking up a larger solution into smaller parts. Those discrete components (or microservices) can then be deployed, updated or retired independently, without having to update and redeploy the entire application.
* Resource utilization and optimization: Containers are lightweight and ephemeral, so they consume fewer resources. You can run many containers on a single machine, for example.

#### benefits of container orchestration
Container orchestration is key to working with containers, and it allows organizations to unlock their full benefits. It also offers its own benefits for a containerized environment, including:

* Simplified operations: This is the most important benefit of container orchestration and the main reason for its adoption. Containers introduce a large amount of complexity that can quickly get out of control without container orchestration to manage it.
* Resilience: Container orchestration tools can automatically restart or scale a container or cluster, boosting resilience.
* Added security: Container orchestration’s automated approach helps keep containerized applications secure by reducing or eliminating the chance of human error.


### Tools
컨테이너 오케스트레이션 도구 중 Docker기반 오케스트레이션 도구가 있습니다. 이 중 가장 많이 알려진 도구에 대해 알아보겠습니다.

* [Kubernetes](https://kubernetes.io/)
구글에서 개발하였고 가장 기능이 풍부하고
널리 사용되는 오케스트레이션 프레임워크
베어 메탈, VM환경, 퍼블릿 클라우드 등의
다양한 환경에서 작동하도록 설계되어 있음.
컨테이너의 롤링 업그레이드 지원

* [Docker Swarm](https://docs.docker.com/engine/swarm/swarm-tutorial/)
여러 개의 Docker 호스트를 함께
클러스터링하여 단일 가상 Docker 호스트를 생성
호스트 OS에 Agent만 설치하면
간단하게 작동하고 설정이 쉬움
Docker명령어와 Compose를 그대로 사용가능

* [Apache Mesos](http://mesos.apache.org/documentation/latest/)
수만 대의 물리적 시스템으로
확장 할 수 있도록 설계되어 있음.
Hadoop, MPI, Hypertable, Spark같은
응용프로그램을 동적클러스터 환경에서
리소스 공유와 분리를 통해 자원 최적화가 가능
Docker 컨테이너를 적극적으로 지원함
