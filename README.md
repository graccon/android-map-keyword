# android-map-keyword
- 카카오테크캠퍼스2 STEP2 - week2
- 충남대학교 Android_8조 노수진
- KakaoMap의 검색 기능을 클론 코딩한 안드로이드 애플리케이션
- 사용자가 검색어를 입력하면 로컬 데이터베이스(SQLite)를 이용하여 검색 결과를 표시합니다. 프로젝트는 MVVM 아키텍처 패턴을 따릅니다.

## 기능 목록
### 1 단계: 연락처 추가
1. **기본 레이아웃 구현**
    - 검색어를 입력할 수 있는 입력란(EditText)
    - 검색 결과를 표시할 텍스트뷰(TextView)

2. **로컬 데이터베이스 생성**
    - SQLite를 사용하여 검색 데이터 저장
    - 검색 결과를 저장하는 테이블 생성

3. **데이터 입력**
    - 카페, 영화관 데이터 저장

### 2 단계: 검색 결과 출력(display)
1. **검색바(searchEditText) 동작**
   - 입력한 검색어는 X를 눌러서 삭제할 수 있음.
   
2. **검색 기록 출력**
   - 검색 기록 가로 리스트뷰로 전시
   - 저장된 검색어 목록은 가로 스크롤 가능.
   - item 클릭시 장소 결과 출력(업데이트)
   
3. **장소 검색 결과 출력**
   - SQLite 장소 검색 결과 세로 리스트뷰 출력 
   - 검색 결과를 저장하는 테이블 생성