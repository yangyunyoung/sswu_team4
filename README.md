### realSungshinPt

### Description
realSungshinPt는 아르바이트 스케줄을 관리하고, 주휴수당과 야간수당을 포함한 월급을 계산하며 아르바이트 관련 여러기능을 효과적으로 관리할수있는 아르바이트에 관련된 종합 서비스를 제공하는 git이다.  
구현된 기능으로는 채팅, 급여계산, 아르바이트일정관리를 들수 있다.  

***

### Enviroment
MVC 뷰를 사용했습니다.  
클라이언트: JavaScript  
서버: Node.js, Socket.io, Sequlize, express, mysql, mysql2  
데이터베이스: MySQL  

***

### 사용방법

- 첫 화면에서 회원가입/로그인을 합니다.  
  -  회원가입시, 이메일, 이름, 비밀번호를 입력하고 가입합니다.

- 채팅기능 사용시)
    -  로그인후, 채팅 버튼을 누릅니다.  
    -  친구목록에 뜨는 친구를 눌러 채팅합니다.  
    -  친구가 없을 시, 친구 추가하기를 눌러 친구의 이메일로 친구 추가를 합니다.  
    
- 친구 캘랜더를 보고싶을 시)  
  - 친구 목록 밑 친구 캘린더 보기 리스트에서 보고싶은 친구의 캘린더를 클릭합니다.  
  - 보고싶은 친구 캘린더가 목록에 없을 시, 친구 추가를 해줍니다.  
    - 친구추가 시)  
        - 친구 이메일이 user가 아닐 시, 해당 이메일이 회원이 아니라는 뷰가 뜹니다.  
        - 친구 이메일이 이미 친구일 시, 해당 이메일이 이미 친구라는 뷰가 뜹니다.  
        - 친구 추가 완료 시, 친구 추가가 완료되었다는 뷰가 뜹니다.  
        

- 아르바이트 추가시)  
    * 홈에서 아르바이트 추가 버튼을누릅니다.  
    * 추가 하고싶은 아르바이트의 이름, 주휴수당 유무, 적용된 세금, 아르바이트 표기 색상을 지정해줍니다  
    * 완료 버튼을 누르면 아르바이트가 추가 됩니다.

- 일정 추가 시)
    * 홈에서 일정추가 버튼을 누릅니다.
    * 근무지는 저장된 아르바이트들중 하나를 선택합니다.
    * 시급, 일일 근무 시간, 대타여부, 휴게시간, 각 수당들을 지정합니다
    * 추가 버튼을 누르면 해당 아르바이트의 일정이 추가됩니다.
  
    
- 일정 삭제 시)
    * 홈의 캘린더에서 일정을 삭제하고싶은 날짜를 선택합니다.
    * 날짜 선택 시, 해당 날짜의 일정이 뜹니다. 
    * 일정 밑 delete 버튼을 누르면 삭제됩니다.
    
- 아르바이트 삭제 시)
    * 홈에서 아르바이트 삭제 버튼을 누릅니다.
    * 삭제하고싶은 아르바이트를 선택합니다,
    * 제출 버튼 클릭 시 삭제됩니다.
    
- 아르바이트 편집 시)  
  해당 편집은 주휴수당 유무, 세금, 아르바이트 색상을 편집할 수 있습니다.  
  - 편집하고싶은 아르바이트를 선택합니다,
  - 주휴수당, 세금, 색상 중 바꾸고싶은 사항을 변경합니다
  - 제출 시, 해당 아르바이트의 정보가 편집됩니다.

- 로그아웃 시)
  * 홈 화면 오른쪽의 Log out버튼을 누릅니다.  
  * 로그아웃 alert창이 뜹니다,  
  * 로그아웃 뷰가 뜹니다.   
  * 홈으로 버튼 클릭시, 로그인 뷰가 뜹니다.  

 
- 회원 탈퇴 시)
  * 홈 화면 맨 아래의 회원 탈퇴하기 버튼을 누릅니다.  
  * 회원 탈퇴 alert창이 뜹니다  
  * 확인 버튼을 부릅니다.  
  * 회원탈퇴 뷰가 뜹니다. 홈으로 버튼 클릭 시, 로그인 뷰가 뜹니다.  

- 월급을 보고싶을 때)
   * 홈 화면 알림창 밑 월급 보기 버튼을 누릅니다.  
   * 해당 아르바이트의 월급을 볼 수 있고, 총 월급을 볼수 있는 뷰가 뜹니다.  


##프로젝트 설명

- ejs 코드 위치: /views
- css, js 코드 위치: /public
- controller 코드 위치: /controllers
- sequlize 관련 각 model 코드 위치: /models
- 




