#공부하고 싶은 것들과 이유

##커널 프로그래밍

지난 2학년까지 공부를 하며 느낀점은 프로그래밍이라고 내가 생각했던 것들은 고급 언어를 위주로 만드는 사용자 앱에 불과했다.
프로그래밍에 처음 흥미를 느낀 계기는 스마트폰이 보편화되면서 정작 많이 사용하는 앱이 아닌, 스마트폰의 생명줄, 와이파이에 관심을 갖게 되었다.

정작 와이파이 없이는 사용할 수 없는 네트워크의 일종이지만, 와이파이에 대해서 공부할 수 있는 기회는 적었다.
그래서 혼자 찾아보며, 깃허브의 간단한 소스코드를 참고하며 네트워크 프로그래밍의 발을 조금씩 디뎠다.

2학년 2학기에는 학점 상관없이 최용훈 교수님의 <컴퓨터 네트워킹>을 수강했다.
수업이 로봇공학과 3학년 수업이라서 재수강하는 학생들이 많아서 주변에선 학점 자살행위라고 말했지만,
학점 챙기자고 고통받으면서 듣기 싫은 수업을 듣는것은 더더욱 싫었다.

아무튼 2학기 수업을 <컴퓨터 네트워킹 하향식 접근 7판>을 읽으면서 진도를 맞추기 위해서 빠르게 지난 부분들도 읽게 되면서 흥미를 유지했다.
보안은 다들 어렵다고 말만할 뿐 정작 제대로 다루지 않아서 오기 때문에 관심을 갖은 것 같기도 하다.

네트워크 수업을 떠나 이 모든게 결국 커널 프로그래밍인 것을 알고, 리눅스 커널에 대해서 공부를 하고 싶어졌다.

하드웨어 자원 관리, 네트워킹, 보안, DB, 컴퓨터에 대해서 공부하면 한번씩은 접하는 분야이지만,
'표면상으로 그러한 것이 존재한다'라며 넘어가기엔 너무 답답했다.

단순히 앱과 프로그램을 만드는 모듈화된 사람이 되고 싶진 않았고,
전반적인 시스템에 대해서 알기 위해서 커널 수준의 공부를 하고싶게 되었다.<br>

##C/C++

2019년 2월에 객체 지향언어를 처음 익힌 언어가 C++이다.
최호성의 <이것이 C++이다>로 생후 제일 적극적으로, 열정적으로 공부했었다.
C를 1학년 1년간 공부를 하고나서, 처음으로 객체라는 것을 접한후로 받은 충격은 상당했던것으로 기억난다.

객체라는 것을 이용해서 일단 게임을 만들기로 마음을 먹었지만, 계속되는 삽질 끝에 배운 것은 "프로그래밍의 흐름"을 짜는 방식이었다.

아직도 기억나는 <이것이 C++이다>의 문구는 "미래의 나는 다른 사람이다, 코드를 작성할 때 나를 손님으로 대하라"이다(맞나?).

처음 기획헀던 게임은 반복되는 요소가 많은 단순한 RPG로 5분 분량의 작은 게임이었다.
처음에는 스크립트가 2~3개로 짰다가 코드가 중복되고 얽혀서 포기하고, 점차 귀찮아져도 반복될 요소는 모두 클래스로 모듈화 해버리는 습관을 갖게되었다.

물론 나중에 파이썬을 하면서 규모가 커지면 일단 빠르게 구축하기 위해서 하나의 코드로 작성후 분리하는 작업을 거치게 되지만,
이때 많은 삽질 덕분에 객체 지향에 대해서 조금 깨닫게 되고, 어떤 부분을 객체화 모듈화를 할지 약간의 감을 얻게 되었다.

2019년 3월 학기가 시작되고, <A Tour Of C++> 번역본을 읽게 되었다.
책을 통해서 C++의 창시자인 비야네 스트로스룹의 의도를 알게되면서 더욱 흥미를 붙인걸로 기억이 난다.

이후에 C++를 활용하기 위해서 관련된 오픈소스 프로젝트를 찾아보고 다녀봤지만, 내 수준에서 소스코드를 읽어도 이해할 역량이 안되어 점차 C/C++를 손에서 놓게되었다.

최근(2019.9 ~ 2019.12) 네트워크를 공부하면서 커널수준의 프로그래밍을 알아보면서 다시 C/C++에 대해 다시 공부할 필요성을 느끼게 되었다.

내가 편리하게 썼던 파이썬의 낮은 수준에 대해서 알아보고 동시에 커널에 대해서 공부할 수 있는 기초배경 지식을 위해서 C/C++를 이번 기회에 공부를 하고싶게 되었다.<br>

##Python

파이썬은 내가 DeepCreamPy를 처음 접한 뒤로 주력으로 삼은 언어다.

파이썬이 가장 매력적으로 느낀 점은 타입추론(Type Inference)였다.
변수를 선언할 때 타입을 쓰지않고, 자유자재로 변수를 필요에 따라 의도/비의도적으로 내가 없애고 재활용 할 수 있다는 점이
빠른 프로그래밍에 도움이 되었다.

파이콘(PyCon Korea) 자원봉사에 참여한 만큼 많은 애정을 느낀 프로그래밍 언어였다.
시간을 내면서 자원봉사에 참여한 것은 파이콘이 처음이였다.

비록 파이썬을 깊게 배울 수 있는 서적(C++의 경우 <A Tour of C++>)이 없어서 구글링을 많이 한 고생이 있었지만,
래핑(wrapping)된 많은 파이썬 라이브러리 덕분에 많은 프로그래밍에 대해서 접할 수 있었다.

PySide2, PyQt5를 통해서 GUI를 직접 만들고, pywin32를 이용한 윈도우 시스템 제어, Django로 만든 웹호스팅 서버,
무엇보다 reqeusts 라이브러리를 통해서 웹 스크래핑, 등 많은 경험을 했다.

쉽게 배우고, 좋은 환경을 갖춘 만큼 다양한 프로젝트 또한 많아서 즐거웠다.

현재(2019.12) 파이썬은 3.8버전이 막 나온 상태다. 문법이나 언어의 특성이 격변한 것은 없지만,
역동적인 언어이며 오픈소스 언어이다보니 전역을 하면 파이썬 4.x 버전이 나올지도 모르겠다.

그래서 틈이 나면 앱을 파이썬의 새로운 문법도 종종 공부하며 감을 잃지 않는 것을 목표로 두고 있다.<br>


##일본어

1학년 때 일본어 교양수업을 들어놓고 귀찮아서 드랍을 했다.
일본 유학을 다니는 친구도 있고, 일본 여행을 갔을 때 언어 때문에 말을 못하는 답답한 경우가 많았다.

제2 외국어를 배우고 싶다.
