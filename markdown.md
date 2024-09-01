# Maekdown

### 마크다운 이란?
- 텍스트 기반의 마크업 언어로 읽고 쓰기 편하게 구성이 되어있음.  
- 특수기호와 문자를 활용하여 간단한 구조를 작성.  
- HTML과 호환됨.

##### 장단점  
장점
1. 간단함
2. 특별한 도구가 필요하지 않음.
3. 텍스트로 저장되기 때문에 용량 활용이 높음.

단점  
1. 표준이 없다.
2. 모든 HTML 요소를 대신하지 못한다.

### 헤더
- HTML Header 요소와 동일한 것으로 문서의 제목을 나타냄.
- h1 ~ h6 까지의 제목을 표현할 수 있다.
- '#' 이라는 기호로 헤더를 표시합니다.
# Header 1 (HTML -> h1)
## Header 2 (HTML -> h2)
ㄴ 밑줄이 '##' 까지는 그려진다
### Header 3 (HTML -> h3)
#### Header 4 (HTML -> h4)
##### Header 5 (HTML -> h5)
###### Header 6 (HTML -> h6)
ㄴ '######' 같은 경우 색상이 좀 변화한다.

### 블록인용
- 인용구를 표현할 때 사용
- '>' 이라는 기호를 사용하여 표현
  
> 첫번째 인용구
>> 두번째 인용구

### 리스트
- 나열된 항목을 나타낼때 사용
- 순서가 존재하는 리스트 (HTML ol), 순서가 존재하지 않는 리스트 (HTMLl ul)
- '1. ' 기호로 순서가 존재하는 리스트를 표현
- '*','+','-' 기로호 순서가 존재하지 않는 리스트를 표현할 수 있다.
  
1. apple
2. banana
3. cacao

- apple
- banana
- cacao

+ apple
+ banana
+ cacao
  
### 코드
- 코드를 작성하기 위한 영역을 지정한다.
- HTML code 요소와 동일
- '```'로 표현한다
- 시작하는 '```'뒤에 표현하고자 하면 문법 강조를 할 수 있다.
``` java
public static void main(String args[], args){
    system.out.println("hello markdown");
}
```

### 구분선
- HTML hr 요소와 동일한 것
- 영역을 구분하고자 할 때 사용
- '* * *', '***','*****', '- - -','------------' 기호로 표현
  ***

  - - -

  ### 링크
- HTML a 요소와 동일
- '[link 키워드][link의 구분자]'
- '[link의 구분자]: url'

[Naver][naverid]
[naverid]: https://www.naver.com "Naver'

