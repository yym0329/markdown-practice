# 제목(Header)

# 제목 1
## 제목2
### 제목3

 #의 개수에 따라서 제목의 중요도를 정할 수 있다. h1, h2, ...

 # 문장 (paragraph)

 마크다운은 해석될 때 결국 html로 변환되어 해석된다. 그래서 Html 태그를 이용하여 문서를 작성할 수 있다.

  자기 몸을 천하처럼 귀하게 여기는 사람에게는 천하를 줄 수 있고, 자기 몸을 천하처럼 아끼는 사람에게는 천하를 맡길 수 있다. (이런 글은 html의 p태그로 출력이 된다.)

  자동 줄바꿈 기능을 지원하지 않는다. 직접 줄바굼 코드(띄어쓰기 두 번)를 넣어 주어야 한다.

  # 줄 바꿈 (Line Breaks)

자기 몸을 천하처럼 귀하게 여기는 사람에게는  
천하를 줄 수 있고 <br> <br> 자기 몸을 천하처럼 아끼는 사람에게는 <br>천하를 맡길 수 있다.

# 강조(Emphasis)

_이탤릭_  
**bold**
**_이탤릭 + 두껍게_**
~~취소선~~
<u>밑줄</u>

# 목록 (list)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록(말하자면 html의 ol 태그 항목들)
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록 (sublist는 들여쓰기, tab 두 번 입력)
1. 순서가 필요한 목록

- unordered list
- unordered list
- unordered list
- unordered list
    - unordered list
    - unordered list
        - unordered list

# 링크
[Google](https://google.com)  
<a href="https://google.com">구글구글</a>  
[Naver](https://naver.com "NAVER로 이동!")

# 이미지

링크 태그 앞에 !를 붙이면 링크의 이미지가 출력된다.  

![귀여운 고양이](https://s3.ap-northeast-2.amazonaws.com/elasticbeanstalk-ap-northeast-2-176213403491/media/magazine_img/magazine_280/5-3-%EC%8D%B8%EB%84%A4%EC%9D%BC.jpg)

아래와 같은 방식으로 이미지에 사이트 링크를 걸어 놓을 수 있다.  

[![귀여운 고양이](https://s3.ap-northeast-2.amazonaws.com/elasticbeanstalk-ap-northeast-2-176213403491/media/magazine_img/magazine_280/5-3-%EC%8D%B8%EB%84%A4%EC%9D%BC.jpg)](https://petdoc.co.kr/ency/280)

# 인용문

> 많이 쌓아 두면 반드시 크게 망한다.  
> -노자-

> 인용문
>> 중첩된 인용문
>>>중첩된 인용문 안에 중첩된 인용문

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있다.

# 블록 코드 강조
back tick 기호 3번 연속. 여는 기호 옆의 글은 언어 이름을 문서에 알려줌.

```html
<a href="https://google.com">구글구글</a>
```

# 표 (Table)
 
 position 속성

 값 | 의미 | 기본값  
 --|:--:|--:
 static | 기준 없음 | O
relative | 자기자신의 위치 기준 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X


# 원시 HTML(RAW HTML)

자기 몸을 <span style="text-decoration: underline;">천하처럼 귀하게 여기는 사람</span>에게는  
천하를 줄 수 있고 자기 몸을 천하처럼 아끼는 사람에게는 천하를 맡길 수 있다.


자주 사용됨. 검색해서 참고하기

# 수평선

수평선을 넣어 보겠다 

---

***

___
___
___
