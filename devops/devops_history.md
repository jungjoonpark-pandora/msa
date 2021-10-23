데브옵스(DevOps)는 소프트웨어의 개발(Development)과 운영(Operations)의 합성어로서, 소프트웨어 개발자와 정보기술 전문가 간의 소통, 협업 및 통합을 강조하는 개발 환경이나 문화를 말한다. 데브옵스는 소프트웨어 개발조직과 운영조직간의 상호 의존적 대응이며 조직이 소프트웨어 제품과 서비스를 빠른 시간에 개발 및 배포하는 것을 목적으로 한다.



The (Short) History of DevOps









2000년대 중반, IT 운영자와 개발자 사이에서 수많은 논쟁이 있었고 이 두 그룹의 관계는 평탄치 않았음.

각자 구체적인 목표를 달성해야 하는 상황에서 서로가 장애물로 느껴지는 경우가 많았기 때문.


하지만 점차 더 많은 IT 조직에서 더 흔하게 나타나게 된 핵심적인 문제에 중점을 두게 되었습니다.

'비즈니스를 위해 개발과 운영 사이의 격차를 해소하려면 어떻게 할 것인가?'가 그것이었습니다.

시작점: IT 종사자인 Patrick Dubois와 Andrew Shaffer가 Velocity Conference 2008에서 나눈 대화.
이 대화의 결과로 최초의 커뮤니티 중 하나인 Agile Systems Administration Group이 탄생.
이 커뮤니티에서 이어진 논의를 통해 Dubois는 첫 Velocity Conference를 열게 되었고 그는 이를 “DevOps Days”라고 명명.
이렇게 DevOps라는 이름과 운동이 시작된 것입니다. 


DevOps의 태동

2009년 오라일리(O’Reilly) 주최 벨로시티(Velocity) 컨퍼런스에서, Flickr(당시:루디코프社, 현:미국 Yahoo!社)의 엔지니어 2명이 10+ Deploys per Day

: Dev and Ops Cooperation at Flickr(하루에 10회를 초과하는 Deploy : Flickr에 있어서 개발과 운용의 협력)이라는 프레젠테이션.

​

​

첫 번째 슬라이드에는 다음과 같이 기술되어 있습니다.

Dev versus Ops 
전통적인 조직에서의 개발 부문과 운용 부문은 대립 관계에 있다고 언급.

개발 부문은 사업(Business)을 위해 서비스에 변화를 주려 하지만, 운용 부문은 변화를 싫어합니다.

운용 부문의 미션은 안정적 가동이기 때문에 손을 대고 싶지 않습니다. 



​

​

서비스에서 운용을 둘러싼 음 반복에 대하여 다음과 같이 기술되어 있습니다.

• Because the site breaks unexpectedly

• Because no one tells them anything

• Because They say NO all the time



​

알기 쉽게 반복되어 있지만, 막상 문서로 작성해 보면 이상한 구조가 되어 버리는 것을 볼 수 있습니다. 운용 부문의 미션 관련 생각에 대해 다음과 같이 언급하고 있습니다.

Ops’ job is NOT to keep the site stable and fast(운용 부문의 미션은 안정적 가동도 최적화도 아니다)
Ops’ job is to enable the business (this is dev’s job too)(운용 부문의 미션은 비즈니스를 유효하게 하는 것이다(개발 부문도 마찬가지다))
​

세상의 변화에 대응하기 위해 개발 부문이 비즈니스에 변화를 주고 싶어 하지만, 운용 부문은 안정을 위해 사업으로 인한 변화를 가하고 싶지 않아 합니다.

그러나 뒤돌아보면 양쪽의 목적은 일치합니다. 그렇다면 변화에 겁을 먹고 계속 피할 것인가, 그렇지 않다면 변화가 요구될 때마다 변화할 것인가에 대한 갈등이 생겨납니다. 슬라이드에는 후자를 위한 아래와 같은 내용이 담겨 있습니다.

​

Lowering risk of change through tools and culture(변화의 위험을 도구와 문화로 낮춘다)
도구와 문화와 관련하여 변화에 대응하기 위한 몇 가지 지표를 제시하고 있습니다.

​



​

[변화에 대응하기 위한 도구]​

• Automated infrastructure (인프라 자동화)

• Shared version control (버전 관리 공유)

• One step build and deploy (원 스텝 빌드와 deploy)

• Feature Flags (어플리케이션 기능의 유효/무효를 설정 파일로 관리하는 것)

• Shared metrics(metrics 공유)

• IRC and IM robots (IRC와 인스턴트 메신저 bot)



​

[변화에 대응하기 위한 문화]

• Respect (존중)

• Trust (신뢰)

• Healthy attitude about failure (실패에 대한 긍정적인 자세)

• Avoiding Blame (비난을 하지 않는 것)

​

​

Dev vs Ops → Supporting Business ("10+ Deploys per Day" 불가능) → DevOps
