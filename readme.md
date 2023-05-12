## 웹프로그래밍 1조 기획서

## 참여자

| 소속 | 학번 | 이름 |
| --- | --- | --- |
| 응용소프트웨어전공 | 60221320  | 최은택 |
| 응용소프트웨어전공 | 60221329  | 김예일 |
| 응용소프트웨어전공 | 60221333  | 박솔민 |
| 응용소프트웨어전공 | 60221340  | 장소윤 |
| 응용소프트웨어전공 | 60221343  | 채서연 |

## 목차

1. **개요**
    1. 프로젝트 개요
    2. 충족되어야 하는 목표
    3. 작성 책임자 식별(페이지마다 작성자 기재)
2. **서비스(or프로젝트) 개요**
    1. 달성 대상의 목표와 범위
    2. 제약사항 또는 위험
3. **서비스 소개**
    1. 사이트맵
    2. 화면설계서
    3. 클래스 다이어그램
4. 수행해야 하는 작업
    1. 요약
    2. 기능 체크리스트
    3. 프론트엔드
    4. 백엔드
    5. 일정
5. 계획 목표를 달성하기 위한 자원
6. 프로젝트 추진 방법
    1. 계획 달성에 필요한 방법 및 접근법
    2. 팀 커뮤니케이션 계획
7. 팀 구성원 및 역할
    1. 요약
    2. 세부 기능 구현 역할

---

## **개요**

### 프로젝트 개요

 저희가 진행하는 프로젝트는 ‘Banana Planner’로 캘린더 웹 서비스입니다. 다만 타 서비스들과의 차별점은 기본적인 캘린더형 일정 관리에 TodoList 기능과 Diary 기능을 추가하여 새로운 형태의 캘린더 웹 서비스를 만들고자 합니다.

 기존의 캘린더 웹 서비스에서 불편하거나 부족하게 느꼈던 점에 대해 새로운 기능들을 추가하고 유용한 서비스들을 합쳐 이용자들의 계획 수립에 있어서 도움을 주고자 프로젝트를 구상하게 되었습니다.

### 충족되어야 하는 목표

Calendar, TodoList, Diary의 기능을 합하여 한 눈에 볼 수 있는 웹 페이지를 만드는 것이 목표입니다. 이 과정에서 HTML, CSS, JS의 개념을 다시 확인하고 프로젝트를 진행하며 JS의 여러 Library나 Framework를 활용하는 법을 익히는 것이 목표입니다.

### 작성 책임자 식별

| 이름 | 담당 내용 |
| --- | --- |
| 장소윤  | 개요, 충족여부 기준(체크리스트), 화면설계서, 전체 화면디자인 , 팀 구성원 및  역할 |
| 최은택  | 서비스(or프로젝트) 개요, 수행해야 하는 작업 및 일정(프로젝트 일정), 클래스다이어그램, 충족여부 기준(체크리스트), 팀 구성원 및 역할 |
| 김예일  | 사이트맵, 충족여부 기준(체크리스트), 프로젝트 추진 방법, 팀 구성원 및 역할 |
| 박솔민  | 충족여부 기준(체크리스트), 기능 명세서 작성, 프로젝트 추진 방법, 팀 구성원 및 역할 |
| 채서연  | 충족여부 기준(체크리스트), 계획 목표를 달성하기 위한 자원, 팀 구성원 및 역할
 |

## **서비스(or프로젝트) 개요**

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b0a03bfe-6f60-41ef-bb0f-5be1f7549464/Untitled.png)

### 달성 대상의 목표와 범위

- 대상 목표
    
     본 서비스는 일정 관리, 할 일 목록 관리, 일기 작성 등 다양한 기능을 제공하므로, 개인과 단체 모두에게 적합하다. 위 기능이 적절히 조화를 이뤄  각 달의 일정을 한 눈에 보고 각 날짜마다 해야할일을 작성하고 확인할 수 있으며 추가적으로 일기의 역할을 하여 일정관리에 용이하고 하루를 기록할 수 있다. 
    
     대상 사용자는 학생, 직장인, 가정주부, 프리랜서 등 남녀노소에 관계없이 다양한 일정과 할 일을 관리해야 하는 모든 연령층의 사람들이 될 수 있다.
    
- 달성 목표 및 범위
    1.  먼저 기본적인 login기능, Calendar기능, todoList기능, Diary기능이 정상적인 작동을 하고 서로 적절히 상호작용하며 이용하는데 각 기능들의 연계에 있어 불편함이 없도록 한다.
    2. 사용자 친화적인 테마(바나나, 원숭이 테마)를 사용하여 이용자들이 직관적이고 쉽게 사용할 수 있는 인터페이스를 제공한다.
    3. 사용자가 입력한 일정, 할일, 일기 등의 정보를 실시간으로 동기화하여 계정 마다 접근이 가능하도록 한다.

### 제약사항 또는 위험

1. 현재 웹 프로젝트를 수행해 본 적이 없는 2학년 학생들로 조가 형성되었기에 지금 당장 계획을 수립하고 기획서를 써나가는 데는 문제가 없을 수 있으나, 기술적인 문제나 구현에 대해 시간이 오래 걸리거나 구현을 하지 못하는 등의 문제가 발생할 수 있다. 이러한 경우 감당하지 못하는 상황일 때 과감히 포기하고 계획을 수립해나가거나 팀원들과 협력하여 기술 습득 및 지식 공유에 시간을 더 투자해야한다.
2. 지금까지는 개인의 활동에만 집중하였기에 팀 프로젝트라는 역할 분담에 대해서 어려움이 있을 수 있다. 그렇기에 각각의 역할 분담을 제대로 하고 형상 관리에 대한 학습과 협업에 대한 이해가 필요하다.
3. 프로젝트 진행 중 요구 사항이 변경되거나 추가된다면, 기존 설계와 계획을 수정해야 하며 이로 인해 프로젝트 일정이 지연될 수 있다. 따라서 프로젝트 진행중 기능에 대한 이의가 생긴다 하더라도 기본의 틀에서 벗어나지 않는 것이 중요하다.
4. 보안에 대해 지식이 있는 조원이 없기에 사용자의 일정, 할 일, 일기 등 개인 정보가 서비스에 저장되므로 현재의 다목적 캘린더 프로젝트의 특성상 벡엔드 부분에 대해 보안성을 향상시킬 수 있는 방안을 찾아야 한다.

이러한 제약사항 및 위험 요소들을 최소화하기 위해 지속적인 회의와 개선작업을 진행할 예정이며 각각의 단계에서 생기는 문제다마 팀원들과 함께 협력하며 헤쳐나갈 계획이다.

## 서비스 소개

### 사이트맵

![siteMap.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7a568be1-b57a-41c7-a533-e9d64fe2d067/siteMap.png)

### UI설계서

화면 디자인 툴(Figma)로 디자인
링크: [https://www.figma.com/file/mHb0cf7nqmUTwkYLWBLOJf/바나나플래너?t=IjVlO7UdMbbfpQlP-1](https://www.figma.com/file/mHb0cf7nqmUTwkYLWBLOJf/%EB%B0%94%EB%82%98%EB%82%98%ED%94%8C%EB%9E%98%EB%84%88?t=IjVlO7UdMbbfpQlP-1)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a2540a22-2433-4208-a578-205f97a528e7/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/cc5419c9-3393-44a7-a8bf-848613784847/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/95933c7e-19e9-4a3b-b416-dfa443203cea/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bab46758-5739-490b-bb56-4ef2a9a86b20/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6df99d34-5630-47e3-b893-c0c5c4e3108e/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0324c6d1-9504-4304-913b-c7559d681145/Untitled.png)

### **클래스 다이어그램**

1. 백엔드
    1. User
        - 요소 : id, username, password, email
        - 메서드: createAccount, login, updateAccount, deleteAccount
    2. Calendar
        - 요소 : id, user_id, date, events
        - 메서드: getMonth, getWeek, getDay, getEvent
    3. Todo
        - 요소 : id, calendar_id, title, description, completed
        - 메서드: create, update, delete, read (CRUD)
    4. Diary
        - 요소 : id, calendar_id, text, date
        - 메서드: create, update, delete, read (CRUD)
    5. Database
        - 메서드: connect, disconnect, execute
    6. API
        - 메서드: create_route, getInfo, handleRequest
2. 백엔드
    1. LoginView
        - 메서드: render, submit, validate
    2. SignupView
        - 메서드: render, submit, validate
    3. CalendarView
        - 요소 : filter
        - 메서드: render, change_month, change_week, select_date
    4. TodoListView
        - 메서드: render, add_todo, edit_todo, delete_todo, toggle_complete
    5. DiaryView
        - 메서드: render, create_diary, update_diary, delete_diary, edit_diary
    6. ApiService
        - 메서드: request, get, post, add, delete
    
    ![클래스다이어그램 - 프론트엔드](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/206d9a89-8732-4c9d-9621-cb8e4cca9f45/%ED%81%B4%EB%9E%98%EC%8A%A4%EB%8B%A4%EC%9D%B4%EC%96%B4%EA%B7%B8%EB%9E%A8_%ED%94%84%EB%A1%A0%ED%8A%B8%EC%97%94%EB%93%9C.png)
    
    클래스다이어그램 - 프론트엔드
    
    ![클래스다이어그램 - 백엔드](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ee8a2a6d-0112-4f29-8b89-c95c0c16e5c0/%ED%81%B4%EB%9E%98%EC%8A%A4%EB%8B%A4%EC%9D%B4%EC%96%B4%EA%B7%B8%EB%9E%A8_%EB%B0%B1%EC%97%94%EB%93%9C.png)
    
    클래스다이어그램 - 백엔드
    

## **수행해야 하는 작업 및 일정**

### **요약**

 프로젝트는 크게 백엔드/프론트엔드로 역할을 나누어 진행하며 백엔드 파트를 담당하는 팀원(장소윤, 채서연)은 Database 설계 및 구축, 백엔드 API개발을 맡고 프론트엔드 파트(최은택, 박솔민, 김예일)은 전체적인 인터페이스 개발, 기능 구현 과정을 맡는다.  Calendar, TodoList ,Diary, login의 전체적인 화면 개발 및 기능을 웹페이지에 구현하는 과정이 필요하며, 백엔드와 프론트엔드의 화면을 연결하고 데이터베이스를 연결하여 연계시키는 작업이 필요하다.

### 기능 체크리스트

1. **로그인page**
    - [ ]  사용자 계정 등록 기능(회원가입)
    - [ ]  로그인시 해당 정보를 저장된 계정 정보와 비교(로그인 기능)
    - [ ]  사용자 정보 찾기 기능(아이디/비밀번호 찾기)
    - [ ]  사용자 계정 삭제 기능(회원탈퇴)
2. **calendar와 todoList**
    - [ ]  이전/다음 달로 변경 가능한 Button
    - [ ]  캘린더 선택 가능 필터
        - [ ]  월별
        - [ ]  주차별
    - [ ]  해당 날짜 할일 미리보기
    - [ ]  날짜 누르면 해당 날짜의 TodoList 변경
    - [ ]  생성된 할 일을 클릭하면 수정하거나 삭제할 수 있는 TodoList 편집창이 뜸
        - [ ]  편집창의 X 버튼을 누르면 편집창이 사라짐
        - [ ]  편집창의 구조는 제목란과 내용란으로 나눠져있음
        - [ ]  편집창에서 제목 혹은 내용을 수정하고 파일 버튼을 클릭하면 수정된 내용이 TodoList에 반영됨.
        - [ ]  쓰레기통 아이콘을 누르면 TodoList가 삭제됨
    - [ ]  TodoList 창의 + 버튼을 누르면 TodoList를 추가하거나 삭제할 수 있는 편집창이 뜸
    - [ ]  플러스 버튼을 누르고 다음과 같은 편집창에 제목과 내용을 작성하고 파일 버튼을 클릭하면 TodoList에 해당 Todo가 추가됨
    - [ ]  편집창이 뜬 상태에서 x버튼을 클릭하면 추가하기가 취소되고 편집창이 내려감
    - [ ]  편집창에서 새로 추가할 todo의 제목과 내용 작성 가능
    - [ ]  현재의 월/주의 Text Click시 Calendar Map이 뜸
    - [ ]  해당 Calendar Map에서 선택한 날짜로 이동
    - [ ]  두 번째 파일 Click시 일기를 작성할 수 있는 TextArea가 뜸
    - [ ]  저장 버튼을 추가하여 입력된 Text값이 해당 날짜에 저장
    - [ ]  이미 저장된 TextArea를 Double Click시 수정 가능
    - [ ]  일기가 저장된 날일 경우 바나나 아이콘을 해당 날짜의 달력 아래에 추가
    - [ ]  바나나 아이콘 Click시 해당 날짜의 일기를 보여줌
    - [ ]  시간이 지나갈수록 바나나 아이콘이 갈변함

### 프론트엔드

1. 캘린더(월, 주자별) 화면, todolist목록창, 일기 창 등 전반적인 사용자 인터페이스(UI) 디자인 및 개발
2. 로그인 및 회원가입 페이지 개발
3. 달력 기능 개발
4. 할 일 목록 CRUD기능 개발
5. 일기 CRUD기능 개발
6. 벡엔드 API 연동 및 연결 구현

### 백엔드

1. <Login 관련 CRUD>
- 회원가입 버튼 누를 시, 회원가입 창으로 이동
- 회원가입 창에 정보 입력 후 회원가입을 누르면 사용자 계정 DB에 새 계정 Create
- 로그인 버튼 누를 시, 사용자 계정 DB에서 해당 계정 DB가 있는지 Read
- 비밀번호 수정 버튼 누를 시, 사용자 계정 DB에서 해당 계정 DB가 있는지 Read해 Update
- 계정 삭제 버튼을 누를 시, 사용자 계정 DB에서 해당 계정 DB가 있는지 Read 후 Delete

<calender>

isChecked( false/true )

- 로그인 성공 시, 해야할 일 DB에서 현재 월의 해야할 일들 전체 Read
- 현재 날짜를 불러와 해당 날짜에 해야할 일들 Read해 옆의 to-do list에 띄워주기,
- 월 양옆에 있는 화살표를 눌렀을 때, 다음 월의 해야할 일 전체 Read하여 띄우기
- 일주일 보기를 눌렀을 때, 현재 주의 해야할 일들 전체 Read하여 띄우기. isChecked를 구별하여 하지 않은 일과 한 일을 구별하여 띄우기
- 특정 날짜를 눌렀을때 해당 날짜의 해야할 일 Read하여 to-do-list 창과 함께 띄우기

<to-do list 서비스 관련 CRUD>

- 편집창의 쓰레기통 아이콘을 누르면 해당 to-do list가 Delete
- 편집창의 + 아이콘을 누르면 해당 to-do list Read하여 띄워줌
- 편집창에 내용을 입력하고 저장 버튼을 누르면 Create하여 DB에 저장

<일기 CRUD>

- 일기 작성 Textarea에 내용을 채워 넣고 저장 버튼을 누르면 Create하여 해당 날짜 일기 DB에 저장
- 저장된 날짜 DB를 가지고 와서 시간 지난 정도를 계산, 바나나 아이콘 갈변을 표현
- 더블 클릭시 일기 수정 가능한 칸이 뜬다
- 바나나 아이콘 클릭시 일기 DB Read하여 띄우기

### 일정

프로젝트 진행 일정을 총 5주차로 아래와 같이 나누었다.

| 1주차 | 1. 만들어진 피그마를 기반으로 UI/UX 디자인 심화 설계
2. 프론트 엔드 요구사항 정의 및 기능 상세히 이해 및 구조 설계
3. 개발 환경 설정 및 필요한 도구 선택
4. 현재 프로젝트 협업을 위한 깃허브 repository생성 및 브랜치 생성 |
| --- | --- |
| 2주차 | 1. 데이터 베이스 설계 및 구축
2. 백엔드 API 개발(달력 데이터 관리, 할 일 목록 데이터 관리, 일기 데이터 관리)
3. 로그인 웹 페이지 프론트 개발
4. 로그인 기능, 회원가입 기능, 회원삭제 기능 개발 |
| 3주차 | 1. 백엔드 API 개발 완료(달력 데이터 관리, 할 일 목록 데이터 관리)
2. Calendar 전체기능 개발
3. todoList CRUD중 CR 개발 |
| 4주차 | 1. 백엔드 API 개발 완료(일기 데이터 관리)
2. todoList CRUD중 UD 개발
3. 일기 CRUD기능 전체 개발 |
| 5주차 | 1. 테스트를 진행하고 각 파트 조원의 피드백 수집
2. 오류 수정 및 일정부분 개선 사항 반영
3. 최종 오류 수정 및 세부사항 조절
4. 서비스 실행 및 지속적인 테스트 반복 |

## **계획 목표를 달성하기 위한 자원**

1. 시간: 프로젝트의 일정을 계획하고 관리하는 것이 중요합니다. 일정 계획 시, 개발 단계별로 시간을 배분하고, 팀원들의 업무량을 고려하여 충분한 시간을 할애해야 합니다. 또한, 예기치 않은 상황이 발생할 경우를 대비하여 유연한 일정 관리가 필요합니다.
2. 인원: 프로젝트를 수행할 팀원들을 모집하고 역할을 분배합니다. 팀원들은 각자의 전문 분야가 있어야 하며, 웹 개발, 데이터베이스, UI/UX 디자인, 테스트 및 품질 관리 등 프로젝트에 필요한 역량을 갖추고 있어야 합니다. 팀원들의 역량을 효율적으로 활용하기 위해 업무 분장 및 협업이 필요합니다.
3. 재료: 웹 애플리케이션 개발에 필요한 소프트웨어 및 라이브러리를 준비합니다. 프론트엔드 개발에는 HTML, CSS, JavaScript와 같은 기술이 필요하며, 백엔드 개발에는 Node.js, Django 등의 기술을 사용할 수 있습니다. 또한, 코드 버전 관리를 위한 Git과 같은 도구가 필요합니다.
4. 장비: 개발 및 테스트를 위한 컴퓨터와 서버 등의 하드웨어 장비가 필요합니다. 팀원들이 원활한 개발 환경에서 작업할 수 있도록 충분한 사양의 컴퓨터를 제공해야 하며, 웹 애플리케이션을 호스팅하기 위한 서버나 클라우드 서비스를 준비해야 합니다.
5. 예산: 프로젝트를 진행하기 위해 필요한 자금을 확보해야 합니다. 예산은 인건비, 소프트웨어 및 하드웨어 구매 비용, 서버 및 클라우드 서비스 비용, 교육 및 훈련 비용, 마케팅 및 홍보 비용 등 다양한 항목에 사용됩니다. 프로젝트 예산을 효율적으로 사용하기 위해 비용 대비 효과를 고려하며 지출을 관리해야 합니다.

## **프로젝트 추진 방법**

### 계획 달성에 필요한 방법/접근법

1. 명확한 목표 설정
    - 프로젝트의 목표는 명확하고 구체적으로 설정하고, 팀원들 모두가 이해할 수 있는 형태로 공유해야 합니다.
2. 역할 분배  
    - 프로젝트를 완성해내기 위한 필요한 역할을 명확하게 구분하고 적절히 분배하고, 각자 맡은 역할은 책임감을 가지고 완수해야 합니다. 완수해내기 어려운 부분이 있는 경우, 팀원들과 소통하며 보완해 나가는 것이 중요합니다.
3. 계획 수립
    - 프로젝트의 범위, 일정, 자원 등을 고려하여 세부 계획을 수립합니다. 세부 계획으로는 개발 단계 별로 일정을 세우고 이를 지켜나가기 위해 팀원들과의 원활한 소통이 이루어져야 합니다.
4. 테스트 및 수정 
    - 프로젝트의 목표를 이루었는지 확인하기 위해, 체크리스트를 통해 기능들을 테스트하고 수정해나가며 결과물을 완성해나가야 합니다.
    - 프로젝트를 완성해내기 위한 필요한 역할을 명확하게 구분하고 적절히 분배하고, 각자 맡은 역할은 책임감을 가지고 완수해야 합니다. 완수해내기 어려운 부분이 있는 경우, 팀원들과 소통하며 보완해 나가는 것이 중요합니다.

### 팀 커뮤니케이션 계획

- Discord를 사용하여 팀원들과 프로젝트 진행 상황이나 방법에 대하여 소통하고,
- Github를 통해 진행하는 프로젝트의 코드를 형상 관리하고,
- Notion에 있는 기능으로 프로젝트 관련 문서를 공유하고,
- 팀원들과 회의가 필요할 경우 도서관의 스터디 룸을 이용할 계획입니다.

## **팀 구성원 및 역할**

### 요약

- 프론트(3) - 김예일, 박솔민, 최은택
    - 사용자 인터페이스 개발
    - 반응형 디자인 구현
    - 캘린더 라이브러리를 이용해 기능 구현
- 백엔드(1) - 채서연
    - 데이터베이스 연결 기능(백엔드) 구현
    - 프론트 엔드와 통신
- 프로젝트 매니저(1) - 장소윤
    - 기획(스토리)
    - 프로젝트 일정관리
    - 진행상황 모니터링

### 세부 기능 구현 역할

| 기능 | 프론트엔드 | 백엔드 |
| --- | --- | --- |
| Login | ### 장소윤, 채서연 
• 사용자 계정 등록 기능(회원가입)
• 로그인시 해당 정보를 저장된 계정 정보와 비교(로그인 기능)
• 사용자 정보 변경 기능(비밀번호 수정)
• 사용자 계정 삭제 기능(회원탈퇴) | 장소윤, 채서연  |
| Calendar | ### 최은택

- 이전/다음 달로 변경 가능한 Button
- 캘린더 선택 가능 필터
    - 월별
    - 주차별

### 김예일

- 해당 날짜 할일 미리보기
- 날짜 누르면 해당 날짜의 TodoList 변경

### 박솔민

- 현재의 월/주의 text click시 calendar map이 뜸
- 해당 calendar map에서 선택한 날짜로 이동 | 장소윤, 채서연  |
| TodoList | ### 최은택

- 생성된 할 일을 클릭하면 수정하거나 삭제할 수 있는 todoList 편집창이 뜸
    - 편집창의 x 버튼을 누르면 편집창이 사라짐
    - 편집창의 구조는 제목란과 내용란으로 나눠져있음

### 박솔민

- 편집창에서 제목 혹은 내용을 수정하고 파일 버튼을 클릭하면 수정된 내용이 TodoList에 반영됨.
- 쓰레기통 아이콘을 누르면 TodoList가 삭제됨

### 김예일

- TodoList창의 플러스 버튼을 누르면 TodoList를 추가하거나 삭제할 수 있는 편집창이 뜸
- 편집창에 제목과 내용을 작성하고 파일버튼을 클릭하면 TodoList에 해당 Todo가 추가됨
- 편집창이 뜬 상태에서 X 버튼을 클릭하면 추가하기가 취소되고 편집창이 내려감
- 편집창에서 새로 추가할 Todo의 제목과 내용 작성 가능 | 장소윤, 채서연  |
| Diary | ### 최은택

- 두 번째 파일 Click시 일기를 작성할 수 있는 TextArea가 뜸
- 저장 버튼을 추가하여 입력된 Text값이 해당 날짜에 저장

### 김예일

- 이미 저장된 TextArea를 Double Click시 수정 가능
- 일기가 저장된 날일 경우 바나나 아이콘을 해당 날짜의 달력 아래에 추가

### 박솔민

- 바나나 아이콘 Click시 해당 날짜의 일기를 보여줌
- 시간이 지나갈수록 바나나 아이콘이 갈변함 | 장소윤, 채서연  |