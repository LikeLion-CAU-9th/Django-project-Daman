![](https://img.shields.io/badge/django-3.2.2-green)


# Django_project_Daman
Giman러들의 Daman😎✨

## Contributor
- Likelion in Chungang University
 
|    Name    | Email                                        |
| :-----------: | :------------------------------------------------- |
|    인세훈     | dlstpgns0406@gmail.com |
|    최윤한     | unusualc@likelion.org |
|    민정호     | alswjdgh5095@gmail.com |
|    정설희     | jhj01177@cau.ac.kr |
 
## Idea building
### Idea list
   - [ ] 홈쇼핑 모델 
   - [ ] 동아리 관리 사이트 : 동아리를 복수로 가입하는 유저들의 통합 관리 서비스 
   - [ ] 유저들이 만들어가는 할인 정보 알림 서비스 
   - [ ] 배달 할인 정보들을 모아서 관리해주는 서비스
   - [ ] 수학문제 풀어주는 사이트 :  초, 중, 고, 대학 과목별로 수학문제 풀이를 가입자끼리 공유하는 서비스, 알람 서비스
   - [ ] 쓰레기 처리 알리미 서비스 : 쓰레기 종류 별로 어떻게 처리해야하는지 알려주고, 쓰레기 버리는 날짜 알려주는 서비스
   - [ ] 최적의 공부를 하기 좋은 카페를 추천해주는 서비스
   - [ ] 특이체형 별 패션 추천과 공유를 해줄 수 있는 서비스
   - [x] `동창회 어플 + 스케줄링`
   - [ ] 영화 구독 어느 사이트에서 어떤 영화가 있는지 알려줄 수 있는 서비스
   - [ ] 다이어리 느낌의 서비스

### Idea Description
- 회원가입, 로그인, 로그아웃 
- 인증방법 : `email` or `image`
- 기수끼리 그루핑 게시판
- 스케줄러
- profile 등록 & 방명록


## 협업 방식
`pair programming`
| WEEK 1   |      |      |
| --- | ---- | ---- |
| 1   | 정호 | 윤한 |
| 2   | 설희 | 세훈 |



## Branch structure

### Main branch
* Master branch : It is Manage only the state that can be distributed
* Develop branch : It is Used to merge branches for feature development

### Secondary branch

* Feature branch : Branch to develop the function ex)feature/profile
* Fix branch : Branch to fix the function ex)fix/profile

## Guide

```console
$ git clone https://github.com/LikeLion-CAU-9th/Django-project-Daman.git
$ git pull origin develop
$ python -m venv myvenv
$ source myvenv/scripts/activate  mac) source myvenv/bin/activate
$ cd Webeing
$ pip install -r requirements.txt

$ ./manage.py makemigrations
$ ./manage.py migrate
$ ./manage.py runserver
```

## Commit rule
```console
git commit -m "text"
```

|    Keyword    | Description                                        |
| :-----------: | :------------------------------------------------- |
|    [feat]     | 코드나 테스트, 예제, 문서 등의 추가가 있을 때 사용 |
|  [refactor]   | 올바르지 않은 로직을 고친 경우에 사용              |
|    [style]    | 코드에 대한 스타일을 바꿀 때                       |
| [docs(guide)] | 문서 작업을 할 때                                  |

## Convention
#### 1. test.py 작성
- 기능에 대한 validation을 할 수 있는 test code를 작성
- 기능에 대한 문제가 날만한 test code를 작성

#### 2. method
- CRUD 순서로 함수 작성

#### 3. import
- module을 import 해야될 때는 무조건 알파벳 순서로 정리

#### 4. python
- class, function 간의 간격은 무조건 2줄
- def (method)의 경우에 간격은 무조건 1줄

#### 5. comments
- 로직, class, function에 대한 설명의 주석 작성
- 사용이 안되는 코드의 주석은 무조건 삭제하고 pull request

## Merge Rule
- merge는 확실하게 된 pull request만 할 것
- 에러나 convention이 잘 지켜지지 않았을 경우 코드리뷰를 하거나 보고 수정을 할 것 

