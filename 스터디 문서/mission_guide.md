## 미션 진행 방법

미션은 일반적인 오픈 소스 기여 방법과 동일하게 진행됩니다.

- `포크` -> `브랜치 생성` -> `커밋` -> `풀 리퀘스트(PR)` -> `머지`

---

### 포크

![image](https://user-images.githubusercontent.com/28296575/210227893-4071be3c-4e94-4e94-b5b1-d55d75d5b6c3.png)

- 우측 상단 `Fork` 버튼을 눌러 자신의 계정에 레포지토리를 포크하기

![image](https://user-images.githubusercontent.com/28296575/210228041-78732ae9-67f8-4ebd-8ddf-eae7e94edae2.png)

- `Create fork` 버튼을 눌러 포크

---

### 브랜치 생성

![image](https://user-images.githubusercontent.com/28296575/210228345-00b64afb-d68f-4c41-a5b9-26eddad69db2.png)

- 포크 된 본인 계정의 레포지토리에서 브랜치 드롭다운 메뉴를 눌러 미션을 진행할 브랜치 생성
- 브랜치 이름은 중복 방지를 위해 본인의 **깃허브 아이디**로 통일

---

### 커밋

![image](https://user-images.githubusercontent.com/28296575/210228839-5969e16c-9e2b-4c76-a520-895070baaeec.png)

- 반드시 본인의 브랜치에서 작업할 것 **(main에서 작업 절대 금지)**
- 커밋 메시지는 변경 내역을 알아보기 쉽고, 일관성 있는 컨벤션으로 작성
- 메시지를 반드시 영어로 작성할 필요는 없음

---

### 풀 리퀘스트 (Pull Request, PR)

![image](https://user-images.githubusercontent.com/28296575/210229491-3c6eb883-32e1-41e9-96ae-09ea6fdea615.png)
- 작업 내역을 푸시한 후 `Compare & pull request` 버튼 클릭

![image](https://user-images.githubusercontent.com/28296575/210229880-1dfa3ea1-7ac3-40c0-8117-18532f6871f3.png)

- 포크한 본인의 레포지토리에서 원본 레포지토리를 향해 PR 생성
- (본인 레포지토리의) 본인 아이디로 된 브랜치에서 (원본 레포지토리의) 본인 아이디로 된 브랜치로 향하도록 할 것
- 이를 위해 원본 레포지토리에서도 본인 아이디로 브랜치를 하나 만들어야 합니다.
- Assignee는 본인을 태그합시다.
- Reviewer는 본인의 리뷰어를 태그합시다.

우리 스터디에서 PR 메시지에는 미션을 진행하며 궁금했던 점과 중점적으로 두고 구현한 내용들을 적습니다.

고민했던 내용들을 리뷰어에게 공유해주면 더욱 좋습니다.

### 머지 (Merge)

> ⚠ 주의사항
> 
> 제출자는 임의로 PR을 닫거나 Merge 하지 않습니다.
> 
> 리뷰어의 확인을 기다려주세요.

이후에는 리뷰어가 PR을 확인 후 코드 리뷰를 진행합니다.

코드에 따라 Request Change가 있을 수 있으니 빠르게 확인해주세요.

