# Aop-part4-chapter01 - Youtube

# 목차

1. 인트로 (완성앱 & 구현 기능 소개)
2. MotionLayout 이용하여 화면 전환 UI 구성하기 (1)
3. MotionLayout 이용하여 화면 전환 UI 구성하기 (2)
4. 영상 목록 API 만들기
5. 영상 목록 기본 구조 만들기
6. MotionLayout 과 RecyclerView 사이에 스크롤 가능하게 하기(1)
7. )MotionLayout 과 RecyclerView 사이에 스크롤 가능하게 하기(2)
8. ExoPlayer를 이용하여 동영상 재생하기
9. 마무리하기
10. 아웃트로



# 결과화면

![1](./screenshot/1.png)



![2](./screenshot/2.png)



# 이 챕터를 통해 배우는 것

- **MotionLayout** 사용하기
- **Exoplayer** 사용하기



### MotionLayout

- ConstraintLayout 라이브러리의 일부 (서브 클래스)
- https://developer.android.com/training/constraint-layout/motionlayout/examples?hl=ko
- 레이아웃 전환과 UI 이동, 크기 조절 및 애니메이션에 사용
- 이기정님의 파트 4, 챕터 4, *OTT 앱 인트로 따라하기* 에서 더 자세히 후술



### ExoPlayer

- Google이 Android SDK 와 별도로 배포되는 오픈소스 프로젝트
- 오디오 및 동영상 재생 가능
- 오디오 및 동영상 재생 관련 강력한 기능들 포함
- 유튜브 앱에서 사용하는 라이브러리
- https://exoplayer.dev/hello-world.html



---

### Youtube

Retrofit 을 이용하여 영상 목록을 받아와 구성함

MotionLayout 을 이용하여 유튜브 영상 플레이어 화면전환 애니메이션을 구현함.

영상 목록을 클릭하여 ExoPlayer 를 이용하여 영상을 재생할 수 있음.

