# Battle_DotheG
##### 2018 인터페이스 프로그래밍 전시회

## **팀원**
***
    17010491 이경은 (2kyung19)
    17011911 이주현 (hhzzi02)
    17011482 권은지 (kej1234)
    18011499 임수빈 (soobin99)
    18011756 황유진 (hyj378)
    17010865 강동민 (riyenas0925)


## **개발**
***
* Unity
* Blender
* 


## **게임 빌딩**
***
### **1. 게임 방법**

* 기존 두더지게임과 동일
* 사용자는 이동하지 않음
* 두더지가 정해진 구멍에서 나오는 것이 아니라 땅에서 랜덤으로 나옴 (360도)
* 컨트롤러를 이용해 두더지를 총으로 쏘는 VR FPS 게임
* 사용자의 HP가 0이 될 때 게임오버
* 플레이 점수 환산
    
### **2. 몹**

* 일반 몹    
    * 몹이 땅에서 나온 후 시간이 지체되면 점점 빨개짐
    * 어느 일정 시간이 지나면 땅에서 기어나와 사용자에게 다가옴
    * 바로 옆에 올때 까지 죽이지 않으면 사용자를 공격함
    * 사용자의 HP가 닳음 > 0이 되면 게임 오버

* 너프 몹
    * 암흑모드 / 지진 중 랜덤
    * 암흑모드
        * 문어몹에 공격을 가했을 때 실행함
        * 밖으로 나와있는 몹들의 발자국만 빛내서 보여줌
    * 지진 : 화면이 강하게 흔들림

* 버프 몹
    * 하늘에 날라 다니는 이벤트 몹
    * 버프 몹 : 사용자의 HP를 채워줌

* 스페셜 몹
~~(예정)~~
    * 땅에서 나와서 공격하는 일반 몹과 다르게 등장부터 원거리 무기(ex. 눈덩이) 가지고 나타남
    * 게임이 어느정도 진행되었을 때 등장

### **3. 추가옵션**
* 피버타임
    * 두더지를 헤드샷으로 죽인다면
    ~~(추후변경)~~
    영혼이 빠져나와 하늘 위로 올라감
    * 하늘에는 영혼 빨아들이는 블랙홀 같은 것 설치
    * 영혼이 빨려 들어갈 때 마다 화면 상단의 게이지가 차오름
    * 피버타임 발동 : 기관총으로 총기 변경 + 몹 발생 시간 대폭 감소

* 스피드
    * 게임을 플레이 할 수록 플레이가 어려워짐
    * 몹의 개체수 상승, 땅에서 나오는 시간 감소, 몹의 걸음 속도 증가

### **4. 총**
* 기본 : 도라에몽 공기총 ( 게이지 채움 > 게이지와 공격력 + 공격범위 비례 )
* 피버타임 : ( 추후 아이디어 )

### **5. 사용자**
* 1인칭 모드 / 3인칭 모드 (단순 카메라 위치 변경)
* 에임 적용
* 디자인 레퍼런스 : 갱비스트

### **6. 그래픽 및 인터페이스**
* 테마
    * 테마 ( 숲 , 눈 , 사막 등 ) 랜덤
    * 테마에 따라 몹 또한 두더지, 펭귄, 전갈 등으로 출현 함

* 인터페이스
    * 상단 게이지바 : 피버타임
    * 우측 하단 낚시 지도 : 몹 위치 (가까이 올 수록)
    * ??? : 사용자 HP
    
* 추가 그래픽
    * 몹 나오기 전 해당 구역에 원이 점점 줄어드는 효과


### **7. 총 디자인 레퍼런스**

* low poly

### **7. Assets**

* low-poly environment (free)

    https://assetstore.unity.com/packages/3d/environments/landscapes/lowpoly-environment-pack-99479
    
* low-poly sky (free)



### **8. 팀 회의**
* 첫 회의 (kakaotalk)
    * 게임 빌딩
    
* 20180716 회의 (discord)
    * 개발 진행 순서
    * 사용 프로그램
    * 게임 아이디어 추가

* 20180724 회의 (discord)
    * 역할 분담 (모델링-blender /ui-unity )
    * 객체 디자인
    * 게임 아이디어 추가

* 20180805 회의 (discord)
    * 게임 재구상
    * 팀별 할 일 정리
    * 오프라인 회의 날짜 협의

### **9. 참고 자료**
* **Unity**
    * 유니티 기초 강좌

        https://www.youtube.com/watch?v=POqq6P4Iz3Y&index=1&list=PLRx0vPvlEmdAfwnKLSdcKUCwZHWcv1aVc

    * FPS 에셋과 1인칭 시점 변경

        https://www.youtube.com/watch?v=3HSexCZqEFk

    
* **Blender**
    * 블랜더 기초

        https://www.youtube.com/watch?v=6aiqldSs6Kw&list=PL1vQPediXkoiLgw4C_TZzHHk8q_y-qGoi

    *  simple rigging

        https://www.youtube.com/watch?v=cp1YRaTZBfw

    * modeling > rigging > animation

        https://www.youtube.com/watch?v=DiIoWrOlIRw&list=PLFt_AvWsXl0fEx02iXR8uhDsVGhmM9Pse

    * 블렌더 애니메이팅 기초

        https://www.youtube.com/watch?v=afN6V1MXAz8&list=PLxS3-QeYRcNPZSQvtqRPWlMsn2dlE0TXl

* **SourceTree**
    * 브랜치 사용법 (재생목록 - Git 강좌)

        https://www.youtube.com/watch?v=_3poHPrbnsE&index=13&list=PLuHgQVnccGMCB06JE7zFIAOJtdcZBVrap