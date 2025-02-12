---
title: R마크다운
description: 마크다운을 이용한 글작업
author: ''
date: '2021-01-12'
slug: welcome
categories: []
tags: []
coverImage: 
thumbnailImage: //res.cloudinary.com/ynot-gallery/image/upload/t_media_lib_thumb/v1610536639/blog/hex-rmarkdown_tpnhdw.png
thumbnailImagePosition: left
metaAlignment: left
---

## 1. 마크다운(Markdown)에 관하여

### 1.1 마크다운이란?

마크다운(Markdown)은 마크업 언어의 일종으로, 존 그루버(John Gruber)와 아론 스워츠(Aaron Swartz)가 만들었다. 각종 태그를 사용하는 HTML문서와 달리, 읽기도 쓰기도 쉬운 문서 양식을 지원한다.

## 2. 문법

### 2.1 문단 제목
#### 1~6개까지 지원하며 # 갯수에 따라 크기가 달라진다.

#### # Title
# Title

#### ## Main Section
## Main Section

#### ### Sub-Section
### Sub-Section

#### #### Sub-sub section
#### Sub-sub section


### 2.2 Block Qoute
#### 블럭 쿼터를 생성한다.
> Block Quote

### 2.3 글자모형
#### 기울기, 굷게 등 다양한 글자 형태를 제공한다.
*italics*
**bold**
`backticks`
~~cancelling~~


## 3. 표만들기
#### 제목행고 내용행을 구분할때는 대시(-)를 활용
#### 콜론(:) 기호를 이용하여 열별로 좌우 정렬
#### 기본적으로 대시(-)로 제목행고 내용행을 구분하면 우측 정렬
#### 행 좌측 정렬시: 대시(-) 앞에 콜론(:)
#### 행 우측 정렬시: 대시(-) 뒤에 콜론(:)
#### 행 가운데 정렬시: 대시(-) 앞뒤에 콜론(:)

|Class|Left|Right|Center|
|-----|:---|----:|:----:|
|A반|A군|B군|C군|


## 4. 수식표현
`\(a_{b}\)`

`$$a^{b}$$`

## 4. 다양한 기능
### 4.1 링크
#### 문법: [text](링크)
#### 예제: [구글](https://www.google.com)
#### 예제: [네이버](https://www.naver.com)

