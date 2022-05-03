
# < 잠자는 파인애옹의 포트폴리오 >

----------



# 스페이스 슈터 유니티쨩


| 타이틀 | 개발환경 | 제작기간 | Platform |  카테고리 | 비고 
| ---- | ---- | ---- | ---- | ---- | ---- 
| 스페이스 슈터 유니티쨩 | Unity3D, C# | 2주 | Window, Android | FPS | Unity3D 첫 작품, <절대강좌!유니티> 예제 어레인지 


![스페이스 슈터 유니티쨩 플레이 이미지](unitychan_shooter.gif)  

*우락부락 머머리 악당을 물리치는 미소녀 유니티쨩*

### 게임 다운로드 
- [SpaceShooterUnityChan_(for Window).zip(52MB)](https://drive.google.com/file/d/1t7QU2IXR2Jri65ziDTloHT34cgnVfQKO) - (전체화면 해상도 플레이 권장) 

- [SpaceShooterUnityChan.apk(51MB)](https://drive.google.com/open?id=1NFBMbCH-Ee_4T5q2HKA0Q-IFbq7ibfGi)

### 주요 기능 및 활용 기술
1. Asset store Character + Mixamo Animation 으로 신규 메카님 제작 - Blend Tree를 이용
![블렌더트리를 이용한 애니메이터 이미지](blendTree.JPG)  
2. 안드로이드 및 윈도우 빌드  
3. 모바일 플레이를 위한 조이스틱 Asset 적용 및 수정  
- 책의 예제는 PC용으로, 안드로이드 빌드를 위해 실행 환경조건을 주어 입력값을 바꿔 줌
```C#
 void Update() {
        h = Input.GetAxis("Horizontal");
        v = Input.GetAxis("Vertical");

#if !UNITY_ANDROID || UNITY_EDITOR
        r = Input.GetAxis("Mouse X");
#else
        r = 0;
#endif

        if (h == 0 && v == 0 )
        {
            h = moveStick.Horizontal  * Time.deltaTime * moveSpeed;
            v = moveStick.Vertical  * Time.deltaTime * moveSpeed;
        }
        if(r==0)
        {
            r = cameraStick.Horizontal;
        }
 ```
3. Camera Culling Mask 및 Layer 활용한 미니맵  
- 각 오브젝트의 prefab에 미니맵에 보여줄 이미지를 추가하고 레이어를 지정, Camera culling mask에서 해당 레이어만 보여주도록 설정함.  

*<절대강좌!유니티>의 내용과 크게 다르거나, 없는 내용 위주로 작성했습니다.*




[◀ 목차로 돌아가기](https://github.com/Song-In-Love/pinaeongs-portfolios/blob/master/README.md#목차)


----------
<center> ⓒ 2020, SONG IN AE </center>

