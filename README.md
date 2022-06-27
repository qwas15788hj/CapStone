# CapStone


[문제정의]

분산된 정보를 한곳으로 통합하여 힙합 공연 정보를 제공하는 서비스를 개발하였습니다. 현재는 사이트마다 다른 정보를 제공하기 때문에 사용자가 자신이 원하는 정보를 찾으려고 할 때 시간을 많이 소비하기 하고 있는 실정입니다. 그리고 공연정보 시간에 맞춰서 사용자들에게 알람 서비스를 제공하도록 개발 하였습니다. 대부분의 공연정보 제공 어플들은 알람 서비스를 제공하지 않습니다.
공연정보를 제공하는 기업들은 각자의 시장을 가지고 거기에 맞는 공연정보만 제공하고 있습니다. 인터파크의 경우 규모가 큰 공연 정보만을 제공하고 있고 그 외 사이트들의 경우 소규모 공연정보들을 제공하고 있습니다.
그래서 저희는 사용자들에게 흩어진 공연 정보를 모아서 한 번에 볼 수 있는 더 나은 서비스를 제공할 것입니다.


[해결 시나리오/방법]

- 주 언어 : JAVA , Kotlin , Python
- 개발 환경: Android Studio, Visual Studio Code, Adobe
- 정보 습득처 : 티켓팅 사이트, 공공API, 크롤링, 수작업
- 서버 및 DB : Firebase



분산된 정보를 한곳으로 통합하여 힙합 공연 정보를 제공하는 서비스를 개발하였습니다.
현재는 사이트마다 다른 정보를 제공하기 때문에 사용자가 자신이 원하는 정보를 찾으려고 할 때 시간을 많이 소비하기 하고 있는 실정입니다.
이러한 문제점을 해결하기 위해 큐레이션을 통해 소비자는 자신이 보고 싶은 공연에 관한 정보를 얻고, 티켓팅, 공연시간에 맞춰 알람기능까지 받아 볼 수 있는 공연 스케줄 매니저 용도로 개발할 것입니다. 



[해결시 예상되는 문제들]
프로젝트시 문제가 될 요소들 
(기술적 문제 혹은 데이터셋 수집, 보안, 개인정보 관련 등)
- Firbase DB의 경우 NoSQL사용 , 달력 형식으로 저장하는 현 프로젝트에 적합한    DB인지 의문
- UX/UI
- 어플리케이션 이외에 데이터를 수집한 크롤링 프로그램, API사용에 대한 난이도
- 위에 해당되는 기능들을 통합했을 때 예상치 못한 오류 발생 가능성



[제안하고자 하는 방식의 요소 기술들]
-Selenium이나 beautifulsoup등을 통한 크롤링
-Firebase_admin을 이용하여 Firebase DB에 데이터 저장
-파이어베이스 클라우드 메시징을 통한 푸쉬알람 기능
-JAVA, Kotlin을 활용한 프로그래밍
[향후 일정]
 - 중간발표(중간고사 기간) 및 최종발표 일정을 고려한 타임라인
	03.08 ~ 03.21 코틀린 학습 및 앱 레이아웃 설계
	03.22 ~ 04.18 앱 프로그래밍(로그인, 로그아웃 기능 제작)
  
  
  
  
  
