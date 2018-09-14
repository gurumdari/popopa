# PoPoPa
PoPoPa는 공동 작업 프로젝트의 일정을 관리해주는 프로그램이다. Gantt 차트 형태로 일정을 한 눈에 볼 수 있게 제공하며, 보고 있는 Gantt 차트 화면에서 바로 일정을 추가, 편집할 수 있다. 일정마다 메모나 이슈 추가를 통한 리스크 관리 기능을 제공한다. Gantt 차트 형태로 관리되는 일정을 실시간으로 주간보고서나, 월간보고서로 취합하여 전환할 수 있으며, 주간보고서나 월간보고서에 팀원 전체를 포함하여 한꺼번에 보고서로 전환 가능하게 하는 기능도 제공한다.

![Alt Gantt 챠트 형태의 일정 관리](images/ko/gantt.png?raw=true "Gantt 챠트 형태의 일정 관리")
<p align="center">[Gantt 챠트 형태의 일정 관리]</p>

![Alt 실시간 보고서](images/ko/weekly.png?raw=true "실시간 보고서")
<p align="center">[실시간 보고서]</p>

![Alt MS Word 형식의 보고서](images/ko/docx.png?raw=true "MS Word 형식의 보고서")
<p align="center">[MS Word 형식의 보고서]</p>

> PoPoPa의 탄생 배경은 금요일에 최종 보고할 주간보고서를 월요일에 작성해야 하는 불합리한 상황을 좀더 현실에 맞게 작성할 수 있도록 개선하기 위해 개발되었다. 예를 들면, 한주간의 업무보고를 위해 금요일에 임원보고가 있다고 한다면, 목요일에 부서별 보고가 있고, 수요일에는 프로젝트별 보고가 있고, 화요일에는 팀원 보고가 있게 되어, 결국 개인별 보고서 작성은 월요일에 해야 하는 일이 발생한다. 최종 보고가 금요일인데 그 보고를 월요일에 작성한다는 것은 한마디로 앞으로 해야 할 일을 마치 수행한 업무인 양 작성하고, 2주후에 일어날 업무들을 차주 계획인 양 작성해야 한다.

> 문제는 앞으로 해야 할 업무를 마치 수행한 업무인 것처럼 작성을 하다보니, 월요일 작성때는 수행 가능할 것처럼 보여 수행했다고 보고한 업무에 이슈가 발생하여 처리를 못하게 되어도, 최종 금요일 보고에는 이슈가 없고 잘 진행중인 것으로 보고가 된다. 잘못된 보고는 다시 이를 바로 잡기 위해 무리한 일정으로 진행하게 되고 이로인해 업무에 부하가 걸려 점점 눈덩이처럼 쌓여 되돌릴 수 없는 상황에까지 이르게 되기도 한다.

> 한마디로, PoPoPa는 실시간으로 주간보고서나, 월간보고서로 취합하여 전환함으로써 예측으로 작성한 보고서로부터 생기는 문제를 개선해준다.

### 사용 가이드
PoPoPa의 자세한 사용법은 아래의 PoPoPa 공식 사이트를 참조하기 바란다.

[https://popopa.gurumdari.com](https://popopa.gurumdari.com)

### 사용 환경
PoPoPa는 JEE 기반의 Web Application으로써, Dynamic Web Module 3.1 이상을 지원하는 WAS를 사용가능한 모든 Server OS에 설치가 가능하다. Client PC 환경은 별도의 Client용 프로그램 설치가 필요없고, HTML5를 지원하는 Web Browser를 통해 언제 어디서나 PoPoPa가 설치된 Server에 접속하면 바로 사용이 가능하다. 단, Internet Explorer의 경우 10 이상의 버전만 지원한다.

<p align="center"><img src="images/html5.png?raw=true" width="352" height="339" /></p>

<p align="center"><img src="images/ie10_11.png?raw=true" width="352" height="77" /></p>

### 다국어 지원
PoPoPa는 Web Browser에 설정된 언어에 따른 언어로 자동 표시되도록 언어팩 기능을 제공한다. 현재, 한국어, 영어, 일본어를 자체 내장하고 있으며, 필요시 직접 언어 팩을 만들어 사용할 수도 있다. Web Browser에 설정된 언어와 상관없이 특정 언어로만 사용할 수 있는 기능을 시스템 설정 및 개인 설정으로 할 수 있게 제공한다.

<p align="center"><img src="images/languages.png?raw=true" width="399" height="310" /></p>

### 기부 Donate
PoPoPa는 Jnode Framework를 기반으로 만들어진 무료 소프트웨어이다! 만약 PoPoPa와 Jnode Framework을 사용하면서 유용하다고 생각했다면, 자발적인 기부를 부탁드린다. 금액에 상관없이 참여한 기부금에 대해 보다 나은 PoPoPa와 Jnode Framework 개발로 보답하겠다. 아울러 우리 나라에서도 공개 소프트웨어가 활성화되고, 기부문화도 활성화되는 계기가 되었으면 한다.

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=6YYMTECUZXM9S)

### 다른 언어로 읽기
[영어 (English)](https://github.com/gurumdari/popopa/blob/master/README.md)