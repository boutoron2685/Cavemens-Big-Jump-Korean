# Cavemen's Big Jump 한국어 패치
![메인](0.png)   
[다른 스크린샷 보기](screenshot.md)   
Cavemen's Big Jump 한국어 패치입니다. By 간케
   
개발자 트위터: [일본어](https://twitter.com/kyokz_jp) / [영어](https://twitter.com/kyokz_en)

__목차__  
[1.주의](#주의)  
[2.후기](#후기)  
[3.다운로드](#다운로드)  
[4.적용 방법](#적용-방법)  
[5.제보](#제보)  
[6.패치노트](#패치노트)  
[7.문제점](#문제점)  

## 주의
* 간혹 __신세계로!__ 와 __붙잡힌 원시인(쉬움)__ 을 난이도 차이라고 오해하시는데, 이는 단순 몹배치 빈도의 차이가 아니라 스테이지 구성 자체가 차이가 납니다. 이를 어떻게 본다면 __붙잡힌 원시인__ 은 프리퀄입니다. 본편은 __신세계로__ 가 맞습니다.
* 저는 이걸 깰 실력이 없어서, 꼼수로 강제로 컷신 불러와서 정상적으로 출력되는지 그 외의 환경은 테스트할 수가 없습니다.
* __나무위키__ 문서에 오역 제보 올리시면 제가 항상 주시하는게 아니라서 확인하기 힘듭니다!!

## 후기
모 스트리머 방송에서 실시간으로 하는걸 보게 되었습니다. 그 분께서 나만 당할 수는 없다는 정신에 감명이 깊어, 파일을 보니 암호화도 안되어있고 구조도 너무 간단하게 되어있고 이런 똥겜에 누가 자진해서 할 거 같아 보이진 않아서... __그냥 까짓거 해보죠 뭐__ 식으로 만들어지게 되었습니다. 그리 다국어에 능통한 편은 아닌지라 번역하며 애먹은게 한둘이 아닌거 같습니다. 그렇게 우여곡절 끝에 만들었지만, 몇 주가 지나도 아무도 한글패치의 존재를 몰랐다는것에 너무 슬펐습니다. 그래서 몇 일 동안은 다른 유튜버분들 하시는 영상에 덧글로 영업하다가 하다보니 뇌절치는거같고 저를 한글패치 제작자가 아닌 게임 제작자로 오해 하는 분들도 계셔서 그만뒀습니다. 만약 이 게임을 즐기시는 스트리머분들이 발견하신다면 여러분들이 저를 대신해 영업을 하셔서 고통받는 모습을 즐겨해주셨으면 좋겠습니다.

이런 게임을 보여주게 하신 [김도](https://www.twitch.tv/kimdoe)님과 한글패치 실시간 테스트 해주신 [여까](https://www.twitch.tv/yeokka)님에게 진심으로 감사드립니다.

## 다운로드
[Releases](https://github.com/boutoron2685/Cavemens-Big-Jump-Korean/releases)를 확인해주세요.

## 적용 방법
Cavemen's Big Jump 1.0이 필요합니다.
* 다운로드: [미국](https://kyokz.itch.io/cavemens-big-jump)/[일본](https://freegame-mugen.jp/action/game_6627.html)
* 이는 단순한 홈페이지 언어 차이입니다. 게임은 기본적으로 영어/일본어가 포함되어 있습니다.
받으신 뒤, 압축파일을 풀어서 덮어씌우면 됩니다.

## 제보
오역이나 패치 후 플레이에 문제가 생기셨다면, [New issue](https://github.com/boutoron2685/Cavemens-Big-Jump-Korean/issues/new)를 생성해주시기 바랍니다.

## 패치노트
* 1.1 
  * 한글깨짐으로 인한 수정
* 1.2
  * 챕터 엔화기호 출력으로 인한 수정
* 1.3
  * 원래 __新天地__ 의 번역을 __새로운 세상__ 으로 했으나 문장이 길어지는 관계로  __신세계__ 로 바꿨습니다. 
  * 일부 챕터명을 변경하였습니다
    * __바늘투성이 동굴(針だらけの洞窟)__ 을 __가시투성이 동굴__ 로 변경했습니다.
    * __동굴미아(迷いの洞窟)__ 를 __미궁의 동굴__ 로 변경했습니다.
    * __야만인의 나라에 온 걸 환영합니다(ようこそ蛮族の郷へ)__ 는 개발년도를 파악해 밈을 반영해 __[어서와 야만인 나라에](https://www.youtube.com/watch?v=wbi7JDIoh0E)__ 로 변경했습니다.
    * __시카바네산(シカバネの山)__ 명칭을 __시체의 산__ 으로 변경했습니다.
  * 일부 오탈자 및 어색한 문장 다시 수정했습니다.
* 1.4
  * 스테이지 목표 도달 시, 나오는 문구를 수정하였습니다. 오역으로 고생하신 여러분들 죄송합니다. 
  
## 문제점
* 각 텍스트 문단마다 일정 바이트를 넘으면 오류가 납니다.(""를 쓸 수 있는 문장이거나, 문장을 줄여 해결)
* 원래는 정식 버전에 한국어 추가를 부탁하기 위해 한국어 코드를 따로 추가했었습니다**만,** 게임 클라이언트가 다중 언어를 표현하는 유니코드(UTF-8)를 지원을 하지 않아서 포기했습니다.
특이하게도 EUC-KR은 정상적으로 출력돼서 이 방식을 채택하고 있습니다.

추가적으로 제가 해결하지 못하는 문제가 발견되어 기재가 된다면, 해결하는 분이 계신다면 감사드립니다.
