# 📱 메인 홈 화면 (Main Home View)
  공지사항, 사용자 정보, 카테고리별 안건 리스트 및 관심 주제 안건을 통합하여 보여주는 앱의 메인 대시보드
<br/>
  <img width="204" height="410" alt="image" src="https://github.com/user-attachments/assets/3b7489cb-6bf7-47af-9d03-a350d78058e7" />   <img width="204" height="410" alt="image" src="https://github.com/user-attachments/assets/2c05cf71-29cd-41c7-af19-108cf599742e" />
<br/>
<br/>
## 1. 주요 구현 기능 및 특징
  ○ 상태 관리 연동: hooks_riverpod과 flutter_hooks를 결합하여 비즈니스 로직과 UI 상태를 효율적으로 관리.

  ○ 다이내믹 카테고리: 서버(AgendaApi)로부터 실시간으로 탭 정보를 받아와 화면을 구성.

  ○ 컴포넌트화: 각 섹션(공지, 정보, 안건 등)을 독립된 위젯으로 분리하여 유지보수성 향상.

  ○ 반응형 레이아웃: flutter_screenutil을 활용해 다양한 해상도에 대응하는 수치(w, h, r) 적용
<br/>
<br/>
## 2. 섹션별 요약
|섹션명|주요 역할|핵심 기술|
|:---:|:---:|:---:|
|공지사항|앱 내 공지 노출|SvgImage, ScreenUtil|
|사용자 정보|프로필 및 퀵메뉴|RichText, Gradient Paint|
|다양한 안건 소개|카테고리별 데이터 노출|Riverpod, API Async 호출|
|관심 주제 안건|추천 안건 리스트|ListView.separated|
<br/>
<br/>
## 3. 상세 분석 링크
  ○ [UI 구성 및 스타일링]()
  ○ [상태 관리 및 비즈니스 로직]()
