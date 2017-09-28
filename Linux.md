- 자유 소프트웨어가 만들어지면서 C 컴파일러, 편집기, 디버거, 빌드 도구 등 프로그래밍과 컴퓨터 운영에 필요한 다양한 도구를 개발하면서 진행되다가 실질적인 결실은 리누스 토발즈의 리눅스 커널과의 결합에 의해 완성되었다.

- 리눅스는 PC에서 사용할 수 있는 운영체제 중 가장 폭넓게 이식된 운영체제이다. 리눅스에서 작동하는 프로그램을 작성하면 그 프로그램이 가장 폭넓은 하드웨어에 대해 한번 작성하여 모든곳에서 실행하는것이 가능하다. 리눅스는 유닉스와 비슷한 운영체제지만 유닉스 버전은 아니다. 리눅스는 유닉스와 호환되는 인터페이스를 제공하는 것을 목표로 하고 있으나, 커널은 유닉스 소스 코드를 참고하지 않고 처음부터 새롭게 작성되었다. 따라서 리눅스 자체는 유닉스 포트 중 하나가 아니라 새로운 운영체제이다.


- 자유 소프트웨어의 확산은 오픈소스의 탄생을 부르는 초석이 되었다. 1991년 리누스 토발즈는 대학에서 교수가 학생들을 상대로 개발한 미닉스를 사용하던 중, 유닉스와 호환되는 공개된 운영체제의 개발 계획을 미닉스 사용자 모임에 발표하였다. 그리고 그는 공개 운영체제에 대해 토론하는 뉴스그룹 ‘comp.os.minix’에 글을 남기면서 오픈소스 시대의 막이 올랐다. 그는 초반에 이 운영체제를 만들면서 거대하고 전문적인 것은 바라지 않고 단지 취미로 만들기 시작했다. 뉴스그룹의 구성원들은 그의 프로젝트에 흥미를 느꼈고 새 운영체제를 만드는 데 힘을 보태기 시작했다. 1991넌 10월 초, 리눅스의 첫 결실인 리눅스 0.02버전이 만들어 졌고 리눅스는 그렇게 인터넷을 통해 확산되면서 전세계 개발자들의 손을 거쳐 유닉스 호환 운영체제로 발전하게 됐다. 리눅스 커널을 만들기 시작했을때, 최대의 관건은 어떻게 이식성이 뛰어난 시스템을 만들 수 있는가 였다. 여기에 대해 인정받던 학파가 있었는데 그들의 주장은 마이크로커널 스타일의 아키택처를 사용해야 한다는 것이다. 마이크로커널은 기존 커널보다 훨씬 적은 연산을 좀 더 제한적인 형태로 수행한다. 상호 프로세스 통신 제한된 프로세스 관리, 스케줄링, 그리고 몇가지 저수준 입출력이 이에 속한다.1992년 3월 리눅스는 0.95로 버전업 되었고 그래픽 사용자 인터페이스가 추가되었다. 그누 커널로 개발중이던 Hurd의 개발이 순조롭지 않았던 스톨먼과 FSF는 유닉스 커널과 호환 가능한 커널인 리눅스를 그누 시스템의 커널로 채택하였고, 리눅스는 그로 인해 강력한 그누 C 컴파일러인 gcc로 컴파일된 많은 응용 프로그램들을 가지게 되었다. 둘의 결합으로 그누 시스템은 완전한 구조를 갖추게 되었다. 리눅스의 커널 부분은 리누스 주도 하에 계속 개발되었는데, 리누스는 최대한 확장 가능한, 즉 사용자에게 제어권이 있으며 어떠한 인터페이스에도 종속되지 않도록 개발을 이끌고자 하는 의지가 있었따. 따라서 리누스는 그의 글을 통해 리눅스의 성공의 원인을 훌륭한 설꼐 원칙과 좋은 개발 모델 때문이라고 말하고 있다. 리눅스는 폭넓게 이식하고 사용할 수 있도록 만들고자 했던 원래의 목표 때문이 아 니라 훌륭한 설계 원칙과 좋은 개발 모델 기반 때문에 성공할 수 있었다. 이 튼튼한 기반이 이식성과 유용성을 쉽게 달성할 수 있도록 해준 것이다. 

- 1994년 1년 6개월 만에 리눅스 버전 1.0이 발표되었고, 이 전에는 네트워킹 기능이 추가되어 있었다. 이 운영체제는 자유로이 수정될 수 있고 매우 유용한 운영체제를 만들기 위해 FSF 산문과 다른 컴포넌트들과 병합되었다. 리눅스 공동체에서 여러 조직들은 사용할 수 있는 컴포넌트들을 다르게 조합하였는데 각 조합은 '배포판'으로 부르며 배포판들을 개발한 조직들을 '배포업자'라고 부른다. 일반적으로 널리 알려진 배포판으로는 레드햇, 맨드레이크, 수제, 칼데라, 코렐, 데비안 등이 있다. 다양한 배포판들간에는 차이점들이 있지만 모든 배포판들은 동일한 기바인 리눅스 커널 및 그누 라이브러리들에 기초하고 있다. 두가지 모두는 카피라이트 스타일의 라이센스로 다뤄지기 때문에 이러한 기반에 대한 변경은 일반적으로 모든 사람이 사용할 수 있어야 한다. 이는 AT&T 에서 파생된 유닉스 시스템간에는 존재하지 않는 리눅스만의 기반에서 리눅스 배포판들을 통합시키는 힘이 원천이다. 이 책은 리눅스 배포판에 고유한 것은 아니며 리눅스를 논의할 때 이 책은 본질적으로 모든 현재 주요 리눅스 배포판들에 대해 유효한 가정인 리눅스 커널 버전 2.2 이상과 C라이브러리 glibc 2.1 이상을 가정한다. 

-  이 즈음 자유소프트웨어라는 용어에서 오픈소프트웨어로 용어가 변경되는데, 자유란 용어 때문에 일반인들이 무료라고 인식하고 있다는 점, GPL 조항의 엄격성 때문에 소프트웨어 개발이 용이하지 않다는 점을 탈피하기 위해서 였다. 리눅스가 성공을 거두자 에릭 레이먼드는 1997년 상용 소프트웨어의 개발 방식을 성당에, 그누와 리눅스의 소프트웨어 개발 방식을 시장에 비유해 '성당과 시장'이라는 글을 쓴다.중세에 몇몇 건축가들에 의해 만들어지는 성당의 작업방식을 개발자 몇몇이 폐쇄적으로 개발하는 상용 소프트웨어의 개발 방식으로, 사람들이 북적이는 시장은 리눅스처럼 인터넷을 통해 누구나 개발에 참여할 수있는 개발 방식으로 본 것이다. 같은 해 에릭 레이먼드와 브루스 패런스는 OSI(Open Source Initiative)를 설립한다. 

- OSI는 오픈소스 문화를 활성화 해 기업들의 참여를 이끌려는 목적이었다. 오픈소스는 개작에 대한 동일 이용허락을 강제하지 않는 점을 빼고는 GPL과 비슷했다. 리처드 스톨만은 '자유 소프트웨어와 오픈소스는 대체로 같은 범주의 소프트웨어를 가리키는 말'이라며 소프트웨어 자체와 가치 중에서 무엇을 더 중요하게 생각하는가 라고 밝힌 바 있다.