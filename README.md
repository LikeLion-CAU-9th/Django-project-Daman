![](https://img.shields.io/badge/django-3.2.2-green)
![](https://img.shields.io/badge/HTML-pink)
![](https://img.shields.io/badge/CSS-blue)
![](https://img.shields.io/badge/JS-yellow)
![](https://img.shields.io/badge/Pillow-8.2.0-red)

# Django_project_Daman
**Giman๋ฌ**๋ค์ **Daman**๐โจ

## Contributor
- Likelion in Chungang University
 
|    Name    | Email                                        |
| :-----------: | :------------------------------------------------- |
|    ์ธ์ธํ     | dlstpgns0406@gmail.com |
|    ์ต์คํ     | unusualc@likelion.org |
|    ๋ฏผ์ ํธ     | alswjdgh5095@gmail.com |
|    ์ ์คํฌ     | jhj01177@cau.ac.kr |
 
## Idea building
### Idea list
   - [ ] ํ์ผํ ๋ชจ๋ธ 
   - [ ] ๋์๋ฆฌ ๊ด๋ฆฌ ์ฌ์ดํธ : ๋์๋ฆฌ๋ฅผ ๋ณต์๋ก ๊ฐ์ํ๋ ์ ์ ๋ค์ ํตํฉ ๊ด๋ฆฌ ์๋น์ค 
   - [ ] ์ ์ ๋ค์ด ๋ง๋ค์ด๊ฐ๋ ํ ์ธ ์ ๋ณด ์๋ฆผ ์๋น์ค 
   - [ ] ๋ฐฐ๋ฌ ํ ์ธ ์ ๋ณด๋ค์ ๋ชจ์์ ๊ด๋ฆฌํด์ฃผ๋ ์๋น์ค
   - [ ] ์ํ๋ฌธ์  ํ์ด์ฃผ๋ ์ฌ์ดํธ :  ์ด, ์ค, ๊ณ , ๋ํ ๊ณผ๋ชฉ๋ณ๋ก ์ํ๋ฌธ์  ํ์ด๋ฅผ ๊ฐ์์๋ผ๋ฆฌ ๊ณต์ ํ๋ ์๋น์ค, ์๋ ์๋น์ค
   - [ ] ์ฐ๋ ๊ธฐ ์ฒ๋ฆฌ ์๋ฆฌ๋ฏธ ์๋น์ค : ์ฐ๋ ๊ธฐ ์ข๋ฅ ๋ณ๋ก ์ด๋ป๊ฒ ์ฒ๋ฆฌํด์ผํ๋์ง ์๋ ค์ฃผ๊ณ , ์ฐ๋ ๊ธฐ ๋ฒ๋ฆฌ๋ ๋ ์ง ์๋ ค์ฃผ๋ ์๋น์ค
   - [ ] ์ต์ ์ ๊ณต๋ถ๋ฅผ ํ๊ธฐ ์ข์ ์นดํ๋ฅผ ์ถ์ฒํด์ฃผ๋ ์๋น์ค
   - [ ] ํน์ด์ฒดํ ๋ณ ํจ์ ์ถ์ฒ๊ณผ ๊ณต์ ๋ฅผ ํด์ค ์ ์๋ ์๋น์ค
   - [x] `๋์ฐฝํ ์ดํ + ์ค์ผ์ค๋ง`
   - [ ] ์ํ ๊ตฌ๋ ์ด๋ ์ฌ์ดํธ์์ ์ด๋ค ์ํ๊ฐ ์๋์ง ์๋ ค์ค ์ ์๋ ์๋น์ค
   - [ ] ๋ค์ด์ด๋ฆฌ ๋๋์ ์๋น์ค

### Idea Description
- ํ์๊ฐ์, ๋ก๊ทธ์ธ, ๋ก๊ทธ์์ 
- ์ธ์ฆ๋ฐฉ๋ฒ : `email` or `image`
- ๊ธฐ์๋ผ๋ฆฌ ๊ทธ๋ฃจํ ๊ฒ์ํ
- ์ค์ผ์ค๋ฌ
- profile ๋ฑ๋ก & ๋ฐฉ๋ช๋ก


## CO-OP
`pair programming`
| WEEK 1   |      |      |
| :---: | :----: | :----: |
| 1   | ์ ํธ | ์คํ |
| 2   | ์คํฌ | ์ธํ |



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
|    [feat]     | ์ฝ๋๋ ํ์คํธ, ์์ , ๋ฌธ์ ๋ฑ์ ์ถ๊ฐ๊ฐ ์์ ๋ ์ฌ์ฉ |
|  [refactor]   | ์ฌ๋ฐ๋ฅด์ง ์์ ๋ก์ง์ ๊ณ ์น ๊ฒฝ์ฐ์ ์ฌ์ฉ              |
|    [style]    | ์ฝ๋์ ๋ํ ์คํ์ผ์ ๋ฐ๊ฟ ๋                       |
| [docs(guide)] | ๋ฌธ์ ์์์ ํ  ๋                                  |

## Convention
#### 1. test.py ์์ฑ
- ๊ธฐ๋ฅ์ ๋ํ validation์ ํ  ์ ์๋ test code๋ฅผ ์์ฑ
- ๊ธฐ๋ฅ์ ๋ํ ๋ฌธ์ ๊ฐ ๋ ๋งํ test code๋ฅผ ์์ฑ

#### 2. method
- CRUD ์์๋ก ํจ์ ์์ฑ

#### 3. import
- module์ import ํด์ผ๋  ๋๋ ๋ฌด์กฐ๊ฑด ์ํ๋ฒณ ์์๋ก ์ ๋ฆฌ

#### 4. python
- class, function ๊ฐ์ ๊ฐ๊ฒฉ์ ๋ฌด์กฐ๊ฑด 2์ค
- class๋ด์ def (method)์ ๊ฒฝ์ฐ์ ๊ฐ๊ฒฉ์ ๋ฌด์กฐ๊ฑด 1์ค

#### 5. comments
- ๋ก์ง, class, function์ ๋ํ ์ค๋ช์ ์ฃผ์ ์์ฑ
- ๋จ ๊ฐ์ฅ ์ค์ํ ๊ฒ์ naming์ ์ ์ง์ ๊ฒ.
- ์ฌ์ฉ์ด ์๋๋ ์ฝ๋์ ์ฃผ์์ ๋ฌด์กฐ๊ฑด ์ญ์ ํ๊ณ  pull request

## Merge Rule
- merge๋ ํ์คํ๊ฒ ๋ pull request๋ง ํ  ๊ฒ
- ์๋ฌ๋ convention์ด ์ ์ง์ผ์ง์ง ์์์ ๊ฒฝ์ฐ ์ฝ๋๋ฆฌ๋ทฐ๋ฅผ ํ๊ฑฐ๋ ๋ณด๊ณ  ์์ ์ ํ  ๊ฒ 

