# 4th commit


### 회원가입 폼
- 아이디/ 패스워드 / 닉네임 입력후 => 기본 지도 설정 창으로 이동

### 기본 지도 설정
- 위치 검색 가능, 클릭한 위치로 기본 위치 설정 => home으로 이동하면 해당 위치를 중심으로 한 지도가 생성됨 

### 로그인 / 로그아웃 구현
- 로그인 시 home.html로 이동

### 상단 navigation의 edit profile
- 회원가입 시 등록했던 사용자의 정보 변경 기능 
- id/닉네임/기본 위치 변경 가능
- 기본 위치 변경 시 home화면 상의 지도도 바뀐 위치에 맞게 변경됨
 
### home
- 로그인이 안 되어있다면 "다양한 기능을 사용하시려면 로그인 해주세요!" 문구, 하단에는 서울 시청을 중심으로 한 지도 생성  
- 로그인이 되어있다면 상단에 사용자의 닉네임 + "메뉴를 선택하세요 문구", 하단에는 사용자의 기본 위치를 중심으로 한 지도 생성
- 나만의 지도 버튼 클릭 시 드롭다운으로 현재 존재하는 지도 리스트 + 지도 추가 메뉴 생성 / (리스트는 사용자가 작성한 리스트만 나타남) 
- 지도 선택 후 전송 시 "지도 추가"라면 newList로 이동, "이미 있는 지도 리스트를 선택했다면 해당 지도를 띄워주는 myMap으로 이동

### newList
- 새로운 지도 카테고리를 만드는 화면
- 카테고리 명과 공유 여뷰, 지도의 마커를 이미지로 첨부하여 커스텀 가능 (첨부 안할 시 디폴트 마커로 적용)
- submit 버튼을 누르게 되면 해당 지도를 띄워주는 myMap으로 전환

### myMap
- 특정 카테고리의 지도를 띄워주는 화면
- 마커 여러개 추가 가능
- 이전에 추가했던 마커도 나타남
- 지도의 빈 공간을 클릭하여 새로운 마커 생성 가능 -> "해당 장소 추가" 버튼 누르면 해당 위치를 기준으로 하는 게시글 작성 폼 생성 / 1 게시글 -> 1 마커 대응 관계
- 새로 생성된 마커를 클릭하면 마커를 생성하면서 작성한 게시물의 제목이 인포윈도우 방식으로 나타남, "자세히" 링크를 클릭하면 마커에 대한 게시글을 수정/ 삭제할 수 있는 기능
- 마커를 수정했다면 이를 반영하여 마커 클릭시 나타나는 인포윈도우의 내용이 변경되고 / 삭제 시에는 마커가 사라짐 

# 5th commit

기본 위치 설정 오류 수정


#   I D E A _ m a p  
 #   I D E A _ m a p  
 #   I D E A _ m a p  
 