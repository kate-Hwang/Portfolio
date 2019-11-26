# kate Hwang (황 지 영)

### 개인정보
- [Github](https://github.com/kate-Hwang/Portfolio)
- [ghkd6385@naver.com](ghkd6385@naver.com)

### 전체프로젝트 개발환경 
- OS  :`window`, `Mac OS X(Unix)`

- WAS : `Apache Tomcat 8.5` , `Apache Tomcat 8.0 for Window, Mac`

- WAB : `HTML5(html,css,javascript)` , `Jquery` , `Ajax` , `vue`

- Test BROWSER : `Google Chrome` , `MS IE & Edge` , `Mozilla Firefox` , `Opera` , `Apple Safari`

### 담당 수행 역할
- 전체 화면 UI (화면정의서) 기획
- 디자인 제작
- 페이지 퍼블리싱
- 프론트엔드 (데이터 바인딩)

****
___

#프로젝트 소개
[![version][badge-version]]

##[Project-Stuco](https://github.com/wnstkdyu/afterHackDay2018)
   **교육지원 웹 서비스**
>강사와 교육생 간의 원활한 의사소통과 더불어 질문하기를
어려워하는 교육생들을 위한 프로젝트


#### 사이트이미지

<img src="images/Picka_main.png" width="800" height="500" hspace="2">

### Trouble Shooting
-  문제내용1

    - 문제: 
    - 연구: 
    - 해결: 


##[After Effect Korea](https://github.com/wnstkdyu/afterHackDay2018)

   **영상편집 커뮤니티**
>After Effect라는 영상프로그램 툴 전반에 
필요한 정보와 영상정보 tip공유 및 전문성 강조 

#### 사이트이미지

<img src="images/Picka_main.png" width="800" height="500" hspace="2">

### Trouble Shooting
-  문제내용1

    - 문제: 
    - 연구: 
    - 해결: 



[프로젝트 리포지터리](https://github.com/RodoPacaGiraffe/BoostCamp_iOS_Electo)



## [Vlogr](https://itunes.apple.com/kr/app/vlogr/id1179975615?mt=8)

**일상을 전달하는 Vlog 소셜 네트워크**


### 수행 역할
- 재사용되는 코드를 묶어서 관리
  - 공통적으로 쓰이는 `UITableViewCell`들을 `nib`파일로 묶어 재사용성 증대.
  - `PushNotification`, `BlockUsers(불량 유저를 막는 기능)` 등 공통적으로 쓰이는 요소를 하나의 `Singleton Pattern`을 적용.
  - 여러 `UITableView`의 `dataSource`를 하나의 `ViewModel` 객체로 만들어 각각의 인스턴스로 관리.
- 동영상 전체화면으로 전환시 `UIModalPresentationStyle`의 `overFullScreen`을 적용해 아래의 뷰가 자연스럽게 흐려지도록 구현.
- 좋아요 갯수를 표시하는 화면에서 느리게 받아오는 문제를 `UITableViewDelegate` 메소드인 `willDisplay` 안에서 쿼리를 미리 날려 게시물 별 좋아요를 미리 받게끔 수정
- 온/오프라인, 로그인/둘러보기 관계없이 `BlockUsers` 싱글턴 객체로 `UserDefaults`를 이용해 로컬에 저장했다가 서버에 업로드 시 서버와 싱크를 맞춰줌.
- 둘러보기를 구현하여 로그인을 하지 않아도 편집을 할 수 있게끔 구현
- 로그인 화면 구성 시 `UIStackView`에 `View`를 넣었다 빼는 애니메이션 적용
- `AppAuth` 라이브러리를 사용해 구글로 `OAuth` 적용 후 YouTube 업로드 기능 추가
- 로컬라이징
- 전체적으로 `Auto Layout` 적용
