# 2021 GDSC React Study

## 🎉 스터디 참여자

|     관리자       |                황준승                                 |
| :-------: | :--------------------------------------------: |
| 참여 인원 | 최윤실, 문정훈, 김지원, 이아현, 이선우, 홍성욱, 황준승|

## 🧾 공부자료

- 웹 게임을 만들며 배우는 React
  (https://www.inflearn.com/course/web-game-react#curriculum)

## 📌 스터디 진행 방식

1. 매주 1강씩 듣고 토이 프로젝트 진행하기

2. 매주 해당하는 프로젝트에 각자 원하는 **🔥 추가 기능 🔥** 을 구현

```
예)
- css 애니메이션 추가
- 그 외 강의에서는 나오지 않은 다른 방법으로 풀어보기
- 백엔드 구현하여 풍성한 웹앱 만들어보기
```

3. 프로젝트를 통해 자신이 잘 몰랐던 개념에 대해 정리

- 블로그 추천 (티스토리 블로그, 네이버 블로그, velog)

4. 매주 한 번씩 스터디원들끼리 모여 개념 정리와 구현했던 코드들을 스터디 때 발표하고 공유하는 방식

```
예)
- 강의에 있던 내용들은 제외하거나 간단하게만 발표
- 강의 외적인 내용(추가 기능, 관련 리액트 개념이나 js, css, html 개념 + cs 개념)에 대해 발표
```

---

## ❗ Git 규칙

- master 브랜치에서 작업하지 마세요
  (자신의 이름으로 된 브랜치인지 수시로 확인해주기)
- 자신의 이름으로 된 폴더를 만들고 그 안에서만 작업하기
  (merge 충돌 방지)

## 🚩 Git 사용법

(Git을 잘 알더라도 꼭 읽어보세요!!)

### 1. Fork하기

1. 해당 링크(https://github.com/turtle601/GDSC_React_Study)에 들어가서 Fork 버튼을 누른다.

![fork1](https://user-images.githubusercontent.com/90830490/133703038-fa4e7a05-b8ab-4277-b754-48d884669b27.PNG)

2. 자신이 깃허브로 들어가 Fork 되었는지 확인하기
   ![fork2](https://user-images.githubusercontent.com/90830490/133703728-367e1b59-8a63-41ad-8704-d8b070618840.PNG)

- mung89 는 부계정입니다.

---

### 2. git clone 하기

1. 저장소 url을 아래 버튼을 눌러 복사합니다.

![clone1](https://user-images.githubusercontent.com/90830490/133704528-bc4ceb5d-9d7b-4b48-a01e-593387282a66.PNG)

2. 내가 작업하고자 하는 환경에 아래와 같이 입력한다.

```
git config --global user.name 깃허브아이디
git config --global user.email 깃허브연동이메일
git clone [복사한 저장소 url]
```

![clone2](https://user-images.githubusercontent.com/90830490/133704866-0377cbb8-00fe-4871-a467-00e563d4c5f3.PNG)

---

### 3. 브랜치 생성 및 변경

1. 내가 클론한 폴더로 이동

```
cd GDSC_React_Study
```

---

2. 브랜치 생성 및 변경
   브랜치 명은 영어로 된 자신의 이름으로

```
git checkout -b [자신의 이름 두 글자 영어로]
```

![branch](https://user-images.githubusercontent.com/90830490/133706049-3a69ccd9-d7a1-43d4-a71a-22d298686e8c.PNG)

---

3. 브랜치 확인하기
   자신이 지금 어떤 브랜치에 있는지 알려준다.

```
git branch
```

![branch2](https://user-images.githubusercontent.com/90830490/133706518-14c9f02b-b143-4abd-9384-8fe60d06a82c.PNG)

---

---

### 4. add ,commit ,push

1. ✨ 자신의 이름으로 된 폴더 생성하기 ✨

![folder1](https://user-images.githubusercontent.com/90830490/133706986-e93fc20d-1297-4567-a8b7-31e000317109.PNG)

이 안에서 파일 생성 및 각자 프로젝트 코드를 작업하시고
add, commit push를 해주세요!!

---

예) Jaeseok 폴더 안에 test.txt 만들어서 add,commit, push 해보기

1. add

```
git add 폴더 및 파일 명
```

![add](https://user-images.githubusercontent.com/90830490/133708098-3db7050d-395a-4323-b896-88d4f2f30a91.PNG)

---

2. commit

```
git commit -m "[자신의 이름] 커밋메시지 작성
```

![commit](https://user-images.githubusercontent.com/90830490/133708127-aa8bb5a5-f6ab-4bf4-abad-1983052fa187.PNG)

---

3. ✨ push ✨

```
git push origin 자신의 이름으로 된 branch 명
```

![push](https://user-images.githubusercontent.com/90830490/133708168-c279a932-6f59-4cc2-99bf-1829146a1af1.PNG)

---

4. 확인하기

![check](https://user-images.githubusercontent.com/90830490/133709215-b879cc10-b434-43c9-be3f-14494d541390.PNG)

---

### 5. Pull Request 보내기

1. 이렇게 PUSH 까지 마치면 내 깃허브 계정이 다음과 같이 뜬다.

![pull request 1](https://user-images.githubusercontent.com/90830490/133708462-22b645a7-46ca-43d2-b6bd-98dc6299ab43.PNG)

---

2. 안 뜨면 여기서 클릭

![](https://images.velog.io/images/mung89/post/4d5aa9f2-9de6-416c-8d6d-cbe93cbe37cd/%EB%A7%88%EC%A7%80%EB%A7%89.PNG)

---

3. 받는 사람과 보내는 사람을 정해서 보낸다.

![pull request 2](https://user-images.githubusercontent.com/90830490/133709714-7487fbfb-8f32-4f5f-910f-ea8c7584c98b.PNG)

---

4. 자신의 이름으로 된 폴더, 자신의 이름으로 된 브랜치 내에서만 작업을 했다면 다음과 같이 뜰 겁니다. (성공)

![pull request 성공](https://user-images.githubusercontent.com/90830490/133711702-87b54aa6-40bd-444b-85ba-b9ab301ece02.PNG)
