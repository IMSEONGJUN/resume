
# 임성준

- Email: naroti@naver.com
- Phone: 010 - 4013 - 1076
- GitHub: https://github.com/IMSEONGJUN

## 간략 소개
iOS 개발자 임성준 입니다.

C++를 시작으로 개발에 입문하여 C언어와 함께 자료구조, 운영체제 및 기타 CS관련 지식들을 공부해왔습니다. 

현재는 Swift와 iOS 개발을 공부하며 개인 프로젝트 및 팀 프로젝트를 진행해오고 있습니다.

진행해온 프로젝트 중에 2가지 앱을 앱스토어에 배포하여 서비스하고 있습니다. 

최근에 프로젝트를 진행하면서 사용하는 아키텍처는 MVVM 패턴이며, RxSwift를 활용하여 구현합니다.

이와 관련하여 Unit-Test에 용이하도록 View와 ViewModel간의 Decoupling에 중점을 두고 코드를 구현하고 있습니다.


## 언어 및 라이브러리
- 사용언어: Swift, C++
- 주요 사용 라이브러리: SnapKit, Alamofire, SDWebImage, Kingfisher, JGProgressHUD, SwiftyJSON
- 분석툴 및 데이터베이스: Google Firebase Analytics, Google Firebase Firestore

## 프로젝트
### [ GitHubFollowers ] <img src = "https://github.com/IMSEONGJUN/GitHubFollowers/blob/master/GitHubFollowers/Support/Assets.xcassets/AppIcon.appiconset/Icon-1024.png?raw=true" width = 50 align = right>
[<img src = "https://devimages-cdn.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-app-store.svg">](https://itunes.apple.com/us/app/github-followers/id1497318994?mt=8) [<img src = "https://devimages-cdn.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-app-store-kr.svg">](https://itunes.apple.com/kr/app/github-followers/id1497318994?mt=8)
![이미지](https://github.com/IMSEONGJUN/GitHubFollowers/blob/master/GitHubFollowers/screenshot/GitHubFollowers.png?raw=true)
> GitHub 사용자 정보 검색을 및 저장을 위한 GitHub Followers 프로젝트

- Third-party Library를 사용하지 않고 구현.
- 개인적으로 진행한 프로젝트로 깃헙 아이디를 입력하면 해당 아이디의 Follower 또는 Following 데이터를 github API를 이용하여 불러와 보여주는 기능.
- 특정 깃헙 사용자의 기본정보 확인 및 깃헙페이지 이동, 원하는 유저를 즐겨찾기에 추가하여 별도 검색없이 찾을 수 있는 기능.
- API 비동기 작업은 별도의 Singleton 클래스로 구현. 
- ViewController를 커스텀하여 UI구성을 위한 Child ViewController로 활용. 
- View의 상속을 통해 코드양을 줄이고 재사용성이 높임. 
- 프로젝트 완성 후에 Appstore에 배포.
- For DETAIL INFO: https://github.com/IMSEONGJUN/GitHubFollowers

#
### [ WaffleChat ] <img src = "https://github.com/IMSEONGJUN/WaffleChat/blob/master/WaffleChat/WaffleChat/Assets.xcassets/logo.imageset/Icon-512.png?raw=true" width = 50 align = right>
![이미지](https://github.com/IMSEONGJUN/WaffleChat/blob/master/WaffleChat/screenshot/WaffleChat4.png?raw=true)
- RxSwift와 MVVM 패턴을 사용하여 만든 실시간 채팅앱
- Reactive Programming 연습을 위해 진행한 프로젝트
- Used Google Firestore for backend
- SnapKit을 활용하여 UI구현
- For DETAIL INFO: https://github.com/IMSEONGJUN/WaffleChat

#
### [ TinderCopy ]<img src = "https://github.com/IMSEONGJUN/TinderCopy/blob/master/TinderCopy/Assets.xcassets/AppIcon.appiconset/Icon-120.png?raw=true" width = 50 align = right>
![이미지](https://github.com/IMSEONGJUN/TinderCopy/blob/master/images/New%20Project%20(3).png)
> Tinder 앱을 카피한 연습용 개인 프로젝트

- 실제 Tinder앱의 기능을 파악하고 애니메이션 및 기본적인 UI를 유사하게 구현하는 연습
- MVVM 패턴을 적용하여 Reactive Programming 연습
- Google Firebase, Firestore를 활용한 사용자 정보관리
- UIPageViewController를 활용한 이미지 슬라이딩
- 비동기 네트워킹 작업에 DispatchGroup을 활용


- For DETAIL INFO: https://github.com/IMSEONGJUN/TinderCopy

#
### [ MemoWithPhoto ] <img src = "https://github.com/IMSEONGJUN/iOSMemoApp/blob/master/images/Icon-60.png?raw=true" width = 50 align = right>
[<img src = "https://devimages-cdn.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-app-store.svg">](https://apps.apple.com/us/app/memowithphoto/id1506735819?mt=8) [<img src = "https://devimages-cdn.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-app-store-kr.svg">](https://apps.apple.com/kr/app/memowithphoto/id1506735819?mt=8)

![이미지](https://github.com/IMSEONGJUN/resume/blob/master/images/01.png)

> 메신져 서비스 기업 LINE에서 진행하는 앱개발 첼린지에 지원하기 위해 개발했던 이미지 첨부가 가능한 메모앱.  
> 앱개발 첼린지에서 합격한 개인 프로젝트  
> LINE관련 이미지 변경 후 AppStore에 배포

- Mock CoreData를 활용한 유닛 테스트 구현
- 객체의 상속을 적극 활용하여 중복코드를 줄임.
- 메모 추가, 수정, 삭제, 검색 기능 구현
- 메모에 이미지를 추가로 첨부가능
- 이미지 첨부방식은 사진촬영, 사진첩, 이미지 URL
- SnapKit을 활용하여 UI구현

- For DETAIL INFO: https://github.com/IMSEONGJUN/MemoWithPhoto

#
### [ MyCloset ]<img src = "https://github.com/IMSEONGJUN/MyCloset/blob/master/MyCloset/Assets.xcassets/AppIcon.appiconset/Icon-1024.png?raw=true" width = 50 align = right>

![이미지](https://github.com/IMSEONGJUN/MyCloset/blob/master/MyCloset/screenshot/mycloset.png?raw=true)

> 개인용 옷장 관리 기능을 갖춘 앱을 구현한 프로젝트

- Firebase를 활용한 백엔드 구현
- 커스텀 콜렉션뷰 레이아웃 구현(aka. Pinterest Layout)
- DispatchGroup을 사용한 비동기작업 종료시점 처리 
- 커스텀 LRU Cache를 구현하여 네트워크 이미지 캐싱처리 ( https://github.com/IMSEONGJUN/SwiftyLRUCache )
- 사진촬영 기능
- 'RemoveBG' API(https://www.remove.bg/ko) 를 활용한 사진 백그라운드 제거 기능
- 내가 가진 옷들을 촬영하여 앱에 카테고리 별로 저장
- 각 카테고리 아이템을 조합하여 데일리 코디 기능
- 지난 코디 이미지 조회 기능
- SnapKit을 활용하여 UI구현

- For DETAIL INFO: https://github.com/IMSEONGJUN/MyCloset

#

### [ 다방 클론앱 ]

> 패스트 캠퍼스 iOS School에서 진행했던 Backend School과의 협업 프로젝트 입니다.  

![이미지](https://github.com/IMSEONGJUN/resume/blob/master/images/dabangImages.png?raw=true)

- For DETAIL INFO: https://github.com/IMSEONGJUN/iOS-DabangClone-200330/tree/develop
#

