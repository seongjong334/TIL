# HTML이란?

HTML(HyperText Markup Language)로 프로그래밍 언어는 아니지만, 우리가 눈으로 보는 웹페이지가 어떻게 구조화되어 있는지를 표현하는 마크업 언어이다. HTML은 elements로 구성되어 있다.

## HTML elements의 구성

태그, 내용으로 구성이 되며 세부 내용은 아래와 같다.


1. 여는 태그(Opening tag): 요소의 이름과, 열고 닫는 꺽쇠 괄호로 구성된다. 이때, 닫는 태그와 함께 효과가 적용될 범위를 지정한다.
2. 닫는 태그(Closing tag): 요소의 이름 앞에 슬래쉬를 이용해 여는 태그와 쌍을 이루게 된다.
3. 내용(Content): 요소의 내용이다.

## HTML의 기본구조

    <!DOCTYPE HTML>
    <html>
    <head>
    <title> HTML 기본구조 </title>
    <meta charset = "UTF-8">
    </head>
    <body>
        HTML의 기본구조
    </body>
    </html>

___
위와 같이 <!DOCTYPE HTML>, <html>은 HTML5를 사용함을 브라우저에 선언하기 위함이다. 실질적으로 보여지는 부분은 <body> tag내에 작성하게 된다.

# HTML 기본태그

### HTML headings

제목의 중요도에 따른, 크기와 굵기를 ```<h></h>``` 태그를 이용해 표현한다.

### HTML Paragraphs

문단의 약자인 p를 요소의 이름으로 사용하며, 제목과 유사하다. ```<p><\p>``` 태그를 이용한다.

* Line break: ```<br>``` 이용
* Horizontal Rules: ```<hr>``` 이용
* Preformatted Text: 입력한 형태 그대로 웹 페이지에 표현하고자 할 때, ```<pre></pre>```를 이용
  
___

이 외에도 text formatting이나 여러가지 태그들이 존재하지만 이는 아래의 참조된 홈페이지를 참고하자.

# HTML 공간 배치

HTML의 tag들은 두가지 형태의 속성을 가지고 웹브라우저에 출력이 되는데, 이 때 서로 다른 HTML tag들에 공통적인 속성을 적용하거나, CSS 스타일을 한번에 적용하기 위한 방법으로 block 형태와 inline 형태로 서로 다른 HTML tag를 묶는다.

* 블록(block) 형태
```<div></div>``` tag를 사용한다.

```
<div style = "border:1px solid black;">
    <h1 style = "text-align:center"> HTML5 & CSS3 </h1>
    <p> HTML5와 CSS3를 공부하자 </p>
<div>
```

* 인라인(inline) 형태
```<span></span>``` tag를 사용한다.

# HTML 입력

웹페이지에서 사용자가 입력한 내용을 서버에 전달하여 데이터를 처리하기 위한 tag들로 여러가지 입력 방식이 있다.

### HTML form

웹 페이지에서 ```<form></form>``` tag를 이용해 입력 tag들을 감싸주어야 입력 tag에 입력된 데이터들이 서버로 보내진다. 

* action 속성: 입력 데이터를 처리할 페이지 URL.
* method 속성: 입력 데이터를 서버에 전달하는 방식을 명시하는데, 이때 HTTP protocol이 이용된다.
    * GET 방식
    * POST 방식

```
<for action = "입력 데이터를 처리할 페이지 주소" method = "입력 데이터를 서버에 전달할 방식"> 여러가지 input tag들 </form>
```

### HTML input

위와 마찬가지로 다양한 타입의 input tag들이 존재하고 이는 사용 시에 아래의 참조 URL을 참고한다.



