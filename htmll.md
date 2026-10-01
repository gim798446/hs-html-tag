아래 내용을 그대로 복사해서 `.md` 파일에 붙여넣으면 됩니다.

 HTML 태그 정리

# HTML 태그 정리

 ## 1\. 기본 구조

 | 태그 | 용도 | 예시 |
| --- | --- | --- |
| `<html>` | HTML 문서의 최상위 요소 | `<html>...</html>` |
| `<head>` | 문서의 메타 정보 영역 | `<head>...</head>` |
| `<body>` | 화면에 표시되는 본문 | `<body>...</body>` |
| `<title>` | 브라우저 탭 제목 | `<title>페이지 제목</title>` |
| `<meta>` | 문서의 메타 정보 설정 | `<meta charset="UTF-8">` |
| `<link>` | 외부 리소스 연결 | `<link rel="stylesheet" href="style.css">` |

## 2\. 텍스트

 | 태그 | 용도 | 예시 |
| --- | --- | --- |
| `<h1>` \~ `<h6>` | 제목 | `<h1>제목</h1>` |
| `<p>` | 문단 | `<p>안녕하세요.</p>` |
| `<br>` | 줄바꿈 | `안녕<br>하세요` |
| `<hr>` | 수평선 | `<hr>` |
| `<strong>` | 중요 텍스트 | `<strong>중요</strong>` |
| `<em>` | 강조 | `<em>강조</em>` |
| `<mark>` | 형광펜 효과 | `<mark>강조</mark>` |
| `<small>` | 작은 글씨 | `<small>참고사항</small>` |
| `<del>` | 삭제된 텍스트 | `<del>삭제</del>` |
| `<ins>` | 추가된 텍스트 | `<ins>추가</ins>` |
| `<sub>` | 아래 첨자 | `H<sub>2</sub>O` |
| `<sup>` | 위 첨자 | `x<sup>2</sup>` |

## 3\. 링크 & 이미지

 | 태그 | 용도 | 예시 |
| --- | --- | --- |
| `<a>` | 하이퍼링크 | `<a href="https://example.com">링크</a>` |
| `<img>` | 이미지 삽입 | `<img src="photo.jpg" alt="사진">` |
| `<figure>` | 이미지·도표 등의 독립적인 콘텐츠 | `<figure>...</figure>` |
| `<figcaption>` | `<figure>`의 설명 | `<figcaption>사진 설명</figcaption>` |

## 4\. 목록

 | 태그 | 용도 | 예시 |
| --- | --- | --- |
| `<ul>` | 순서 없는 목록 | `<ul><li>사과</li></ul>` |
| `<ol>` | 순서 있는 목록 | `<ol><li>첫 번째</li></ol>` |
| `<li>` | 목록 항목 | `<li>항목</li>` |
| `<dl>` | 설명 목록 | `<dl>...</dl>` |
| `<dt>` | 설명할 항목 | `<dt>HTML</dt>` |
| `<dd>` | 항목에 대한 설명 | `<dd>웹 문서 구조 언어</dd>` |

## 5\. 표

 | 태그 | 용도 | 예시 |
| --- | --- | --- |
| `<table>` | 표 전체 | `<table>...</table>` |
| `<thead>` | 표의 헤더 영역 | `<thead>...</thead>` |
| `<tbody>` | 표의 본문 영역 | `<tbody>...</tbody>` |
| `<tfoot>` | 표의 하단 영역 | `<tfoot>...</tfoot>` |
| `<tr>` | 표의 행 | `<tr>...</tr>` |
| `<th>` | 제목 셀 | `<th>이름</th>` |
| `<td>` | 데이터 셀 | `<td>홍길동</td>` |
| `<caption>` | 표 제목 | `<caption>회원 목록</caption>` |

## 6\. 폼

 | 태그 | 용도 | 예시 |
| --- | --- | --- |
| `<form>` | 입력 양식 | `<form>...</form>` |
| `<input>` | 다양한 입력 필드 | `<input type="text">` |
| `<label>` | 입력 필드의 설명 | `<label for="name">이름</label>` |
| `<textarea>` | 여러 줄 텍스트 입력 | `<textarea></textarea>` |
| `<select>` | 선택 목록 | `<select>...</select>` |
| `<option>` | 선택 목록의 항목 | `<option>서울</option>` |
| `<button>` | 버튼 | `<button>확인</button>` |
| `<fieldset>` | 폼 요소 그룹화 | `<fieldset>...</fieldset>` |
| `<legend>` | `<fieldset>`의 제목 | `<legend>개인정보</legend>` |

## 7\. 시맨틱 태그

 | 태그 | 용도 |
| --- | --- |
| `<header>` | 페이지 또는 영역의 머리말 |
| `<nav>` | 내비게이션 영역 |
| `<main>` | 문서의 주요 콘텐츠 |
| `<section>` | 콘텐츠의 주제별 영역 |
| `<article>` | 독립적인 콘텐츠 |
| `<aside>` | 보조 콘텐츠·사이드바 |
| `<footer>` | 페이지 또는 영역의 바닥글 |
| `<div>` | 의미 없이 영역을 그룹화 |
| `<span>` | 인라인 요소를 그룹화 |

## 8\. 멀티미디어

 | 태그 | 용도 | 예시 |
| --- | --- | --- |
| `<audio>` | 오디오 재생 | `<audio controls>...</audio>` |
| `<video>` | 동영상 재생 | `<video controls>...</video>` |
| `<source>` | 미디어 파일 지정 | `<source src="video.mp4">` |
| `<iframe>` | 다른 웹 문서 삽입 | `<iframe src="page.html"></iframe>` |

## 9\. HTML 공부 시 우선 익힐 태그

 처음 HTML을 공부한다면 다음 태그부터 익히는 것이 좋습니다.

 - `<html>` — HTML 문서
- `<head>` — 문서 정보
- `<body>` — 본문
- `<h1>` \~ `<h6>` — 제목
- `<p>` — 문단
- `<a>` — 링크
- `<img>` — 이미지
- `<ul>` / `<ol>` / `<li>` — 목록
- `<div>` — 영역 그룹화
- `<span>` — 인라인 영역 그룹화
- `<form>` — 입력 양식
- `<input>` — 입력 필드
- `<button>` — 버튼

 원하시면 다음 단계로 **`HTML 태그 + CSS 속성 + JavaScript 용어`를 한 장짜리 Markdown 치트시트** 형태로도 정리할 수 있습니다.
