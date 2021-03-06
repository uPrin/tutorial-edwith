# Main root
## 기본 요소
* ```<!DOCTYPE>```
	* 마크업 언어용 DTD(document type definition)태그 (html태그가 아니다)
	> 첫 문장에 써주어야 한다
* ```<html>```
	* html문서의 루트를 나타내는 태그로 모든 html 태그를 감싼다
* ```<head>```
	* 문서의 제목과 스크립트와 스타일 시트의 링크 또는 선언등의 메타데이터를 제공합니다.
* ```<body>```
	* 문서의 내용을 나타내는 태그 

# Document metadate
## 문서의 메타데이터
문서의 정보를 나타내는 요소들
* ```<link>```
	* 현재 문서와 외부 리소스와의 관계를 명시하는 태그
	> 보통 스타일 시트와 스크립트 파일을 링크하는데 사용
* ```<meta>```
	* 다른 메타관련 태그들로 나타낼 수 없는 메타데이터를 나타냅니다
* ```<style>```
	* 문서의 스타일 정보를 정의 할때 사용한다 
* ```<title>```
	* 문서의 제목을 정의하는 태그

# Content sectioning(layout root)
## 컨텐츠 구획
문서 내용을 정리하는 요소들

* ```<address>```
	* <article>와 <body>에 대한 연락처 정보를 제공하기 위해 사용
* ```<header>```
	* 소개나 탐색을 돕는 것의 그룹을 나타낸다
	>ex) 로고나 구획의 제목, 탐색 폼
* ```<article>```
	* 사이트 안에 독립적으로 구분되거나 재사용 가능한 영역을 구성하는 태그
    >ex) 포럼의 글, 매거진/신문의 기사, 블로그 글등
* ```<aside>```
	* 문서의 주요 콘텐츠에 별도로 이어진 콘텐츠가 있는 문서의 한 부분을 나타내는 태그
    >ex) 사이드바
* ```<footer>```
	*  문서의 꼬리말의 나타내는 태그
    >ex) 저작권 데이터, 관련된 문서의 링크등
* ```<nav>```
	* 현재 페이지 안 이나 다른 페이지로 가는 링크를 보여주는 페이지의 부분
	>메뉴, 목차, 색인등
* ```<section>```
    * 문서의 일반적인 부분을 나타내는 태그
* ```<main>```
    * 문서의 핵심주제나 애플리케이션의 핵심 기능성에 대해 부연, 또는 직접적으로 연관된 콘텐츠를 나타내는 태그
* ```<div>```
	* 본질적으로 아무것도 나타내지 않는 플로우 컨텐츠의 일반적인 컨테이너로 
	  적절한 태그가 없을 때 요소들을 묶을때 사용된다


# Text content
## 문자 콘텐츠 태그
단어나 텍스트의 한 부분을 구조나 스타일을 정의하는 태그

* ```<p>```
	문단을 묶어주는 역할을 하는 태그
* ```<h1>~<h6>```
	*문서 제목을 정의한며 숫자가 커질 수록 글자는 작아진다 
* ```<hr>``` (horizontal rule)
	* 가로줄을 넣어주는 태그
* ```<br>``` (line break)
	* 줄바꿈 해주는 태그
* ```<pre>```
	* 서식 있는(Preformatted) 텍스트를 넣기 위한 태그
	>공백문자가 두개 이상 연속으로 있어도 하나로 취급하지 않고 그대로 표시된다
* ```<span>```
	* div태그의 한줄 버전으로 div는 문단는 묶는 느낌이라면 span은 단어를 묶는다고 생가가하면 좋다
* ```<a>```
    * 하이퍼링크를 나태내는 태그
* ```<b>```(bold)
	* 두껍게(bold) 효과를 주는 태그
* ```<i>```(italic)
	* 텍스트를 기울임꼴(italic)로 표시한다
* ```<strong>```
	* 텍스트를 강하게 강조하는데 사용
* ```<em>```
	* 텍스트를 약하게 강조하는데 사용
* ```<sup>```
	* 텍스트를 위첨자(superscript)로 표시하는 태그
* ```<sub>```
	* 텍스트를 아래첨자(subscript)로 표시	
* ```<mark>```
    * 문자를 하이라이트 해주는 태그
* ```<blockquote>```
	* 감싸진 텍스트가 인용문임을 가리킴
* ```<q>```
    * 짧은 인라인 인용문을 나타내는 태그
* ```<time>```
    * 24시간이나 그레고리력 날짜를 나타내는 태그
* ```<code>```
    * 코드를 나타내느 태그
* ```<samp>```(sample)
    * 프로그램 출력의 샘플을 나타내는 태그
* ```<var>```
    * 프로그래밍이나 수학적표현에서 변수를 나타내는 태그 
* ```<abbr>```(abbreviation)
    * 약어를 나타내는 태그
* ```<cite>```
    * 참조를 나타내는 태그
* ```<data>```
    * 기계 판독 가능 해석을 연결할때 사용하는 태그
* ```<dfn>```(definition)
    * 정의를 나타내는 태그
* ```<wbr>```(Word Break Opportunity) 
    * 문장이 길때 원하는 곳에서 줄바꿈하도록 지정하는 태그
* ```<kbd>```(Keyboard Input)
* ```<bdi>```(Bi-Directional Isolation)
* ```<bdo>```(bidirectional override)
* ```<small>```

# Demarcating edits
## 교정 태그
* ```<del>```(delete)
* ```<ins>```(insert)
* ```<s>```
    * 더 이상 정확하지 않는 내용을 지정하는 태그

# List
## 목록 태그

* ```<ul>``` (unordered list)
	* 순서가 없는 리스트를 나타내는 태그
* ```<ol>```(ordered list)
	* 순서 있는 리스트을 나타내는 태그
* ```<li>```(list item)
	* 리스트이 항목을 나타내는 태그
	>ul , ol태그 안에 포함되어야 함
* ```<dl>```
	* 여러짝의 용어와 정의를 둘러싸주는 태그
	* ```<dt>```
		*정의 목록에서 용어을 나타내는 태그
	* ```<dd>```
		*정의 목록에서 용어의 정의를 나타내는 태그


# Table content
## 표
표의 데이터를 만들거나 다루는 요소들

* ```<table>```
    * 표을 만들어 주는 태그
* ```<caption>```
    * 표의 제목을 나타내는 태그
* ```<tr>```
    * 표의 행을 나타내는 태그
* ```<td>```
    * 표의 셀을 나태내느 태그
* ```<colgroup>```
    * 표의 열의 그룹을 요소를 정의하는 태그
* ```<col>```
    * 표의 열의 요소를 정의하는 태그
* ```<th>```
    * 표의 셀을 헤더로 설정하는 태그로 가운데로 정렬되고 굵은 글씨로 표시된다
* ```<thead>```
    * 표의 헤더부분을 정의하는 태그이다
* ```<tbody>```
    * 표의 열을 묶어주며 테이블의 바디부분을 암시한다
* ```<tfoot>```
    * 표의 셀을 요약해주는 열을 정의하는 태그이다

# Forms
## 폼
CGI와 상호작용하기 위한 입력값을 받는 역활을 하는 태그

* ```<form>```
* ```<input>```
* ```<button>```
* ```<datalist>```
* ```<select>```
    * ```<optgroup>```
        * ```<option>```
* ```<textarea>```
* ```<meter>```
* ```<progress>```
* ```<output>```
    * 수정 불가능한 문자열을 나타내는 태그
* ```<label>```
* ```<fieldset>```
    * 폼 요소를 그룹으로 묶어부는 태그
    * ```<legend>```

# Image and multimedia
## 이미지&멀티미디어
멀티니미디어를 나타내는 태그
* ```<figure>```
	* 독립적인 콘텐츠를 표현해주는 태그
	> ex)  이미지, 삽화, 도표, 코드등
	* ```<figcaption>```
		* ```<figure>```요소의 관련된 설명을 나타내는 태그
* ```<img>```
* ```<picture>```
* ```<audio>```
* ```<video>```
    * ```<source>```
    * ```<track>```
* ```<canvas>```
* ```<map>```
    * ```<area>```
* ```<iframe>```

# Embedded content
## 삽입되는 내용


# Programing
## 프로그래밍 파일을 삽입하는 태그
* ```<noscript>```
* ```<script>```
* ```<embed>```
* ```<object>```
    * ```<param>```

# Interactive elements
## 대화형 요소
* ```<details>```
* ```<dialog>```
* ```<summary>```

# Web Components
## 웹 구성요소
* ```<shadow>```
* ```<slot>```
* ```<template>```

참고 : https://developer.mozilla.org/en-US/docs/Web/HTML/Element