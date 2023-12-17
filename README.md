
# 임성준

- Email: naroti@naver.com
- Phone: 010 - 4013 - 1076
- GitHub: https://github.com/IMSEONGJUN

## 간략 소개

iOS 개발자 임성준 입니다.

동료가 보기에 잘 읽히는 코드를 작성하려고 노력하며 RxSwift 사용에 적극적입니다.
언제나 더 간결한 구현 방식이 없는지 작업이 완료되어도 일정이 허락하는 동안 끝임없이 고민하고 개선해가며 개발합니다. 
현재 라이브커머스 플랫폼 Grip에서 iOS개발자로 근무하고 있으며, MVVM-C 패턴으로 Swift와 RxSwift를 사용하여 개발합니다.  
Code-based UI 구현을 선호합니다. 

- 업무툴: Jira, Confluence, Slack, Figma
- CI/CD: Github Action
- 모듈화: Tuist
- 분석툴 및 데이터베이스: Amplitude, Google Firebase Analytics, Google Firebase Firestore, FCM

## 경력
- (주)그립컴퍼니 : 2022.03 ~ 근무중
  - MVVM-C + RxSwift 
  - SnapKit, Moya
  - AVFoundation, HLS, RTMP
  - App Localization
  - GRIP US 버전 개발 - WKWebView javascript bridge
  - 방송자 후원하기 기능(부스터)
  - 인앱 결제 구현(Swift Concurrency, StoreKit 2, StoreKitTest)
  - 로그인, 회원가입, 인증 기능 개발
  - 라이브 방송 송출 및 시청 중 발생하는 실시간 이벤트 처리(Firestore)
  - 라이브 방송 송출(RTMP) 전 네트워크 컨디션 체크(ICMP) 및 테스트 송출기능
  - 라이브 방송 중 참여할 수 있는 룰렛 게임 개발(CABasicAnimation)
  - 정기적인 신규 기능 추가 및 유지보수
  - Jira, Confluence, Slack, Figma, Github, Github Action, Tuist

- (주)큐피스트 : 2021.03 ~ 2022.02
  - GLAM 라이브 스트리밍(라이브 데이팅) 개발
    - 2021년 12월에 글램에서 새롭게 런칭한 라이브 스트리밍(글램 라이브) 서비스를 최초 기획 단계부터 참여하여 개발하였습니다
    - 기간: 2021.07 ~ 2021.12(5개월) 
    - iOS 개발 인원: 2명
    - 앱 다운로드  
    [<img src = "https://devimages-cdn.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-app-store-kr.svg">](https://apps.apple.com/kr/app/%EA%B8%80%EB%9E%A8-%EC%86%8C%EA%B0%9C%ED%8C%85-%EB%8D%B0%EC%9D%B4%ED%8A%B8-%EC%B9%9C%EA%B5%AC%EA%B9%8C%EC%A7%80-%EB%A7%8C%EB%82%A8%EC%9D%84-%EC%9E%AC%EB%B0%8C%EA%B3%A0-%EC%89%BD%EA%B2%8C/id1058232900)

    - WebSocket(Pusher)을 활용한 실시간 이벤트 처리(라이브방 입퇴장, 라이브방 정보 변경, 소켓이벤트를 통한 게스트/호스트 인터렉션, 채팅, 강제종료 등)
    - 라이브방에서 발생하는 소켓이벤트에 대해 Rx 시퀀스 분리를 통한 이벤트 처리
    - 게스트/호스트간 인터렉션에는 HTTP 사용(Moya)
    - 라이브 참여자 최대치 4인 초과되는 경우, 초과된 대상이 본인인 경우를 체크하기 위해 Stack 활용

    - Agora SDK를 활용한 라이브 영상 스트리밍 커뮤니케이션 기능 구현(단방향, 양방향)
    - 참여인원 1~4인, 인원에 따른 비디오/오디오 송출 및 화면 분할
    - 참여자 마이크/카메라 on/off 이벤트 바인딩 및 역할에 따른 이벤트 처리

    - 라이브 스트리밍(글램 라이브) 피처 전체 UI 구현, SnapKit 사용
      - 라이브 스트리밍 홈(RxDataSources를 사용한 Nested CollectionView 구현)
      - 라이브 방송 참여자 수에 따른 비디오 슬롯 동적 구성(최대 4명)
      - 계층구조의 layered UI가 적용된 라이브 방송 화면 구현
      - 라이브 참여자 2~4명인 경우 비디오슬롯별 비동기 화자 표현  

  - 글램라이브 내 신규 재화 구매(IAP)및 방송 중 도네이션 기능 구현
    
  - 1:1 랜덤 매칭 라이브콜(영상통화) 기능개발 및 유지보수
  
  - GLAM 스토어(IAP) RxSwift로 리팩토링
    - 기간: 2021.04.26 ~ 04.30
    - 기존 MVC 구조에서 RxSwift + MVVM 구조로 변경
    - UICollectionView에 RxDataSources, 결제 모듈에 SwiftyStoreKit 사용
    - 코드량을 줄이고 가독성을 높이는 결과를 얻음
    - 스토어에 신규 재화 추가
    
  - GLAM 데이팅 유지보수

- (주)나인폴더스 : 2020.10.14 ~ 2021.02
  - 이메일 클라이언트앱 개발 및 유지보수(Objective-C 100% 프로젝트)
  - https://www.9folders.com/ko/index.html
  
## 학력
 - 경희대학교, 영어통번역학
 
## 프로젝트(기간: 2019 ~ 2020)

### [ ImageSearcher ]
- 기간 : 2020.10.08 ~ 2020.10.11
# Video Link : https://youtu.be/e6EBgg_vcb8

![이미지](https://github.com/IMSEONGJUN/ImageSearch/blob/main/ImageSearcher/ImageSearcher/screenshot/ImageSearcher.png?raw=true)

- MVVM 패턴, RxSwift 사용.
- RxCocoa Custom ControlEvent, Custom Binder 활용.
- Kakao Image Search API 사용.
- 이미지 선택하여 즐겨찾기에 추가 가능
- Repository: https://github.com/IMSEONGJUN/ImageSearch

#
### [ GitHubFollowers ] <img src = "https://github.com/IMSEONGJUN/GitHubFollowers/blob/master/GitHubFollowers/Support/Assets.xcassets/AppIcon.appiconset/Icon-1024.png?raw=true" width = 50 align = right>
[<img src = "https://devimages-cdn.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-app-store.svg">](https://itunes.apple.com/us/app/github-followers/id1497318994?mt=8) [<img src = "https://devimages-cdn.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-app-store-kr.svg">](https://itunes.apple.com/kr/app/github-followers/id1497318994?mt=8)
![이미지](https://github.com/IMSEONGJUN/GitHubFollowers/blob/master/GitHubFollowers/screenshot/GitHubFollowers.png?raw=true)
> GitHub 사용자 정보 검색을 및 저장을 위한 GitHub Followers 프로젝트

- Third-party Library를 사용하지 않고 구현.
- 개인적으로 진행한 프로젝트로 깃헙 아이디를 입력하면 해당 아이디의 Follower 또는 Following 데이터를 github API를 이용하여 불러와 보여주는 기능.
- 특정 깃헙 사용자의 기본정보 확인 및 깃헙페이지 이동, 원하는 유저를 즐겨찾기에 추가하여 별도 검색없이 찾을 수 있는 기능. 
- ViewController를 커스텀하여 UI구성을 위한 Child ViewController로 활용. 
- View의 상속을 통해 재사용성이 높임.
- 프로젝트 완성 후에 Appstore에 배포.
- For DETAIL INFO: https://github.com/IMSEONGJUN/GitHubFollowers

#
### [ WaffleChat ] <img src = "https://github.com/IMSEONGJUN/WaffleChat/blob/master/WaffleChat/WaffleChat/Assets.xcassets/logo.imageset/Icon-512.png?raw=true" width = 50 align = right>
## Video Link: https://youtu.be/p3zgqgrtMbs
![이미지](https://github.com/IMSEONGJUN/WaffleChat/blob/master/WaffleChat/screenshot/WaffleChat4.png?raw=true)
- RxSwift와 MVVM 패턴을 사용하여 만든 실시간 채팅앱
- Google Firestore for backend
- SnapKit을 활용하여 UI구현
- For DETAIL INFO: https://github.com/IMSEONGJUN/WaffleChat

