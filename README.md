﻿﻿_미완성 포트폴리오 문서입니다! 모든 링크나 기능, 내용이 제대로 작동하지 않을 수 있습니다!_
 

# 잠자는 파인애옹의 포트폴리오


### 자기 소개
![귀에 꽃 꼽은 고양이 사진](https://i.imgur.com/2amIezu.jpg)
> 시민 여러분 안녕하십니까. 비록 어려운 시국이지만 다 함께 힘을 합친다면 반드시 이겨낼 수 있을 것입니다. - 잠자는 파인애옹

원칙에 충실하고 기본기를 탄탄하게 키우고 있는 게임 개발자입니다. 간단한 연습 게임을 만들더라도 사람들이 플레이할 수 있게 끝까지 완성하려고 노력합니다. 매일 매일 성장하고 있습니다. 피드백과 응원 항상 감사드립니다.

### 커리어 정보 
프로그래밍 시작 날짜 : **2019-07-06**

희망 직군 : **Unity3d 게임 클라이언트 개발자**

----------
----------

# 목차

| 타이틀 | 개발환경 | 제작기간 | 플레이 환경 |  카테고리 | 비고 
| ---- | ---- | --- | ---- | ---- | ---- 
| [유니티 슈터](#유니티-슈터) | Unity 3D, C# | 2주 | Window, Android | FPS | Unity 3D 첫 작품, <절대강좌!유니티> 예제 어레인지 
| [갓크소울](#갓크소울) | C | 3일 | Console | Dos RPG | 머드게임 
| [도스감성 격투게임](#도스감성-격투게임) | C | 3일 | Console | Dos 대전 | C 첫 작품, 머드게임 



# 각 목록 설명 순서
**작품 제목**
- **이미지 또는 영상, 다운로드 링크**
- **개요표**
- **활용 기술 / 기법**
- **주요 작업 목록** : 완성도에 가장 많이 기여한 작업, 가장 어려웠던 작업, 그리고 가장 오래 걸렸던 작업을 3가지씩 선별 후 분류. 순위에서 밀려난 내용은 제외함.

---------
---------

# 유니티 슈터

### 게임 다운로드 
- [SpaceShooterUnityChan_(for Window).zip(52MB)](https://drive.google.com/file/d/1t7QU2IXR2Jri65ziDTloHT34cgnVfQKO) - (전체화면 해상도 플레이 권장) 

- [SpaceShooterUnityChan.apk(51MB)](https://drive.google.com/open?id=1NFBMbCH-Ee_4T5q2HKA0Q-IFbq7ibfGi)


| 타이틀 | 개발환경 | 제작기간 | 플레이 환경 |  카테고리 | 비고 
| ---- | ---- | --- | ---- | ---- | ---- 
| [유니티 슈터](#유니티-슈터) | Unity3D, C# | 2주 | Window, Android | FPS | Unity3D 첫 작품, <절대강좌!유니티> 예제 어레인지 


### 활용 기술/기법
1. Asset store Character + Mixamo Animation 으로 신규 메카님 제작 
2. Android 환경 용 조이스틱 Asset 적용 및 수정
3. Camera Culling Mask 및 Layer 활용한 미니맵

*<절대강좌!유니티>의 내용과 크게 다르거나, 없는 내용 위주로 작성했습니다.*


###  주요 작업 목록
|  | ★★★ | ★★ | ★ | 
|---- | ---- | ---- | ---- |
| 기여도 | 미니맵 - 플레이어와 주변의 몬스터 위치 보이게 해주기 | 자동발사 - 플레이어가 적을 바라 볼 때 자동으로 총알이 발사됨 | 조이스틱 장착 - 안드로이드 빌드시 케릭터 이동 가능 |
| 난이도 | (소요시간 ★★★ 과 동일) | (기여도 ★★★과 동일) | (기여도 ★과 동일) |
| 소요시간 | 모델에 애니메이션 적용 - 기존의 애니메이션 적용 시 캐릭터의 발이 돌아있어서 고치는 방법 찾는데 시간이 오래 걸림, 리깅 문제|  라이트 프로브 적용 및 베이크 - 인게임에서 원하는 조명 색상으로 나오게 하기 | 무기 장착 및 발사 시, 원하는 위치로 총알이 발사되게 Rotation 조절 |


[🔼 목차로 돌아가기](#목차)
----------------

# 도스감성 격투게임

![도스감성 격투게임 플레이 화면](https://i.imgur.com/gZapA4d.gif)
*몰입감은 당신이 예상하는 DOS의 그것과 차원이 다르다 .  - 파인애옹*

[플레이 해보기](https://github.com/Song-In-Love) ***실행이 안될 때는 [이슈](https://github.com/Song-In-Love)로 알려주세요*

| 타이틀 | 개발환경 | 제작기간 | 플레이 환경 |  카테고리 | 비고 
| ---- | ---- | --- | ---- | ---- | ---- 
| [도스감성 격투게임](#도스감성-격투게임) | C | 3일 | Console | Dos 대전 | C 첫 작품, 머드게임 


프로그래밍을 처음 접하고 일주일 뒤에 만든 게임입니다. 가장 원초적인 그래픽 인터페이스인 텍스트 출력과 C의 기본 구문들을 사용해서 제작하였습니다.


### 활용 기술/기법
1. C의 조건문(if/switch) 
```C++
case 2: //젤리피일때
      switch (attackStyle) // 사용한 공격
      {
      case 1:
         if (sceneNo == 1)
         {
            cout << "SYSTEM : 젤리삐(이)가 건방지게 침을 밷는다." << endl;
         }
         else if (sceneNo == 2)
         {
            cout << "SYSTEM : 산성이었다. 아프다. " << endl;
         }
         break;
      case 2:
         if (sceneNo == 1)
         {
            cout << "SYSTEM : 젤리삐(이) 줄기 채찍을 휘둘렀다." << endl;
         }
         else if (sceneNo == 2)
         {
            cout << "SYSTEM : 아프지만 묘하게 기분이 좋다. " << endl;
         }
         break;
```
2. 함수 작성 및 전방선언 


###  주요 작업 목록

|  | ★★★ | ★★ | ★ | 
|---- | ---- | ---- | ---- |
| 기여도| 선택한 플레이어에 따라 스킬, 능력치, 이미지가 다르게 출력  | 상태가 시각적으로 보여지기 (■■■■□□)  | 공격과 피격모션을 움직이게 보이기
| 난이도 | (기여도★★★와 동일)| 서로 다른 캐릭터의 HP량이 다르더라도 칸은 균일하게 보이기| 매 턴마다 HP회복
| 소요 시간| 그림 그리기 (움직이는 효과 보여지게 하기) | 가급적 코드 반복을 줄이기 위해 함수로 만들기 | 공격에 따른 HP 및 MP 감소효과


[🔼 목차로 돌아가기](#목차)



-----------------------

### 더 알아보기

[![귀에 꽃 꼽은 고양이 모습](https://i.imgur.com/74ClGJt.jpg?1) 개발일지는 블로그](https://pinaeong.tistory.com/)

[![Linkedin](https://i.imgur.com/SBTfCsA.png?2) 커리어와 채용문의는 링크드인](https://www.linkedin.com/in/in-ae-song-91a666191/) 

[![Github](https://i.imgur.com/lhD5Xxa.png?1) 오픈소스는 깃헙](https://github.com/Song-In-Love)

[![YouTube](https://i.imgur.com/2tEtlJO.png?1) 포트폴리오 영상은 유튜브에서](https://www.youtube.com/channel/UCAc2-SQgnXv8uRzrZ0t9umQ) 
 
 [![Coursera](https://i.imgur.com/IaYLQTX.png?3) 컴퓨터공학 전공 공부는 코세라에서](https://www.coursera.org/user/cc07a2e58f24e37b281637d005a3cefd)

***다양한 채널에서 파인애옹을 만나보세요*
