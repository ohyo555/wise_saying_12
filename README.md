## 📚명언 앱 만들기

![image](https://github.com/ohyo555/wise_saying_12/assets/153146836/c0d24a1d-c3cd-4daf-beb5-1616baee6665)


#### ♟️ 구조

- App : controller를 만남
- Controller: 요청을 받아서 처리
- Service: 핵심 로직, 컨트롤러의 요청에 의해 일을 함
- Repository: 데이터의 저장/ 조회를 담당, 서비스의 요청에 의해 일을 함

#### 💻 CRUD 기능

- 등록(create): 마지막에 저장된 id++ 시킨 후 새로운 명언 등록
- 목록(read): list에 저장된 명언 출력
- 수정(update): parameter로 id 받아서 list에 해당 id 조회 후 등록된 내용을 보여주고 새롭게 입력 후 저장
- 삭제(delete): parameter로 id 받아서 list에 해당 id 조회 후 등록된 명언을 삭제 
   
