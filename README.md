# 2020 충주 나눔교실 동영상 편집

일단 완성본을 봅시다.

<https://www.youtube.com/watch?v=30McOU6AB9A>

## 여러분이 하실 일

* 인트로 이후 영상의 컷편집
* 인트로에 들어가 소개클립(5초 가량) 골라주기: 소리는 안나옵니다.

## 편집 프로그램

> 편집 프로그램으로는 곰믹스를 사용하도록 하겠습니다.

* 무료
* 윈도우 OS 지원 (맥/리눅스 지원 X)
* 10분이면 다 배울 수 있음 (할머니 할아버지 유튜버들 쓰는 프로그램임)
* 컷편집 하기에 충분!

다운로드 링크: <https://software.naver.com/software/summary.nhn?softwareId=GWS_001665>

위의 링크에서 `곰믹스`를 다운받아서 설치해주세요. 설치 시간 살짝 걸림(5분 가량?)
![Install_1.png](Install_1.png)
중간에 zum을 시작페이지로 갈아치는 함정 조심하시고 (체크박스 해제)
![Install_2.png](Install_2.png)
ACC코덱을 다운받아 어쩌구.. IPP 런타임을 다운받아 어쩌구 하면서 계속 물어보는데 다 `YES`!

## 다음 희의때까지 할 일

곰믹스를 설치하시고 컷편집 배울 수 있는 유튜브 링크를 올려드리니 시청해주세요! 20분밖에 안합니다.

강의: <https://www.youtube.com/watch?v=c2qffHB7tF4>

## 편집 가이드

이렇게 각자 알아서 공부해서 하라고 하면 조금 막막할듯 하여 편집 가이드를 올려드립니다. 실전적인 예시를 위해 다음 영상 2개를 사용하도록 하죠! 모두 제가 샘플 영상을 만들 때 사용한 소스 영상들입니다.

* 영상 1: 네셔널 지오그래픽에서 빛공해의 심각성을 알리기 위해 찍은 밤하늘 타입랩스 영상입니다. FHD 1080p이고 오프닝에서 예지몽의 배경으로 사용된 영상 소스입니다. 총 길이는 2분 남짓입니다.
* 영상 2: Frederic Schuller라는 응용수학과 이론물리를 가르치시는 교수님의 양자역학 마지막 수업영상입니다. 제가 (굉장히) 좋아하는 교수님으로 특히 양자역학 강의와 우주론 강의는 정말 경이롭습니다. 샘플 영상에서 수업영상으로 사용된 소스입니다. 2시간이 조금 넘는 분량입니다. 화질은 조금 떨어집니다.

자, 무얼 해 볼거냐... 영상 1에는 약 1분 40초부터 5초간 검은 화면이 들어있어요. 이걸 일단 잘라서 없앨겁니다. 그리고 영상 1의 끝부분에 엔딩 크레딧이 있는데 그것도 잘라 없앨겁니다. 이후에 영상 2를 붙여서 우주의 신비를 보여 준 다음 이를 수학과 물리로 풀어내는 아름답고 감동적인 영상을 만들어보려고 해요.

#### STEP 1 영상 불러오기

곰믹스를 킵니다. 처음 켜먼 **미디어 소스**탭의 **현재 프로젝트** 패널이 비어있을텐데 그곳으로 파일을 드래그 & 드랍해주세요.
![Loading.png](Loading.png)

#### STEP 2 편집점 찾기

크게 볼 때, 컷편집은 STEP 1에서 불러온 소스영상을 아래쪽 타임라인에 적절히 배치해서 하나의 영상으로 만드는 과정입니다. STEP 1에서 현재 프로젝트 패널의 영상 중 영상 1(빛공해 영상)을 타임라인으로 역시 드래그 & 드랍하면 보시는 것처럼 딱 들어갑니다.
![Play.png](Play.png)
이제 중간의 검은 화면을 찾아야겠네요. 아래 그림에서 노란색 0표한 삼각형 버튼(단축기 `space`)을 누르면 현재 타임라인에 올라간 영상 소스가 차례대로 재생됩니다. 이에 더하여, 타임라인 쪽의 0표한 인디케이터도 따라서 움직일겁니다.
![Indicator.png](Indicator.png)
이 인디케이터는 한글에서 깜빡이는 커서 역할을 한다고 생각하시면 됩니다. 즉, 최종 영상에서의 현재 위치를 나타내는 역할을 인디케이터가 하게 되고, 이를 움직이여서 영상 전체를 헤집고 다닐 수가 있습니다. 우리는 1분 40초 즈음에 검은 화면이 있다는 걸 이미 알고 있으니 인디케이터를 움직여서 거기로 바로 갑시다.
![Marking.png](Marking.png)

#### STEP 3 잘라내기

검은 화면 앞뒤로 영상을 끊어주고 그 사이를 지우면 되겠죠? 아래 그림에서 가위모양(단축기 `ctrl+X`)과 휴지통모양(단축키 `delete`)로 할 수 있습니다.
![remove.png](remove.png)
가위모양으로 영상을 자르면 인디케이터가 기리키는 곳을 기준으로 영상이 두쪽납니다. 위의 그림에서 타임라인을 보시면 원래 하나이던 영상이 쪼개진 걸 확인할 수 있어요. 이제 5초 쯤 뒤로 가서 다시 영상을 자른 뒤, 휴지통 모양  혹은 단축키로 이를 날려버리면 됩니다.
![Piece.png](Piece.png)
이때 주의할 점: **날리기 전에 꼭 타임라인에서 해당 영역을 선택하고 날려야 합니다.** 아니면 엄한 영상이 날아가요. 선택한 영상은 타임라인에서 노란색으로 음영이 들어갑니다. 위의 그림에서는 뒤쪽 영상이 선택된 상황인거죠.

같은 방법으로 뒤의 엔딩 크래딧도 날려줍니다. 이건 생략~

#### STEP 4 이어붙이기

필요없는 부분을 잘랐으니 이제 이 뒤에 영상 2를 이어붙이면 되겠네요. 역시 

## 난 다른 영상편집 프로그램 쓸 줄 아는데?

파컷이나 프리미어, 에펙 같은걸 이미 쓸 줄 아신다구요? 그럼 그냥 그거 쓰셔도 됩니다! 다만 나중에 출력 양식만 H.264인코딩에 높은 비트레이트(프리미어는 익스포트 프리셋 중 youtube 1080p FHD)로 맞춰서 익스포트 해 주세요. 이게 뭔 말인지 모르겠으면 그냥 곰믹스 ㄱ