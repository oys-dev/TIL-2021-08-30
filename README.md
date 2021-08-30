# TIL-2021-08-30
2021-08-30 프론트엔드 2nd class
### -빈 요소(Empty elements)

내용이 없다면? -> 이미지, 수평선, 줄바꿈 등
이 경우 닫는 태그를 추가로 명시하지 않아도 된다.
ex) <br>
<hr>
<img >
<meta>
<input>

### -요쇼의 중첩(Nesting)

요소 안에 다른 요소가 들어가는 포함관계를 성립할 수 있다.
서로의 포함관계를 구분하기 위하여 들여쓰기를 사용한다.

### -주석(Comments)

<!-- -->
ctrl + l 누르면 가능

**mdn 사이트를 활용하자!**


< !DOCTYPE html >

< html >: 페이지 전체의 컨텐츠를 감싸는 루트 요소(최상위 루트)
  
< head >: 웹 브라우저 화면에 직접적으로 나타나진 않는 웹페이지의 정보
기계가 식별할 수 있는 문서 정보(메타데이터)를 담는다. 정보로는 문서가 사용할 제목, 스크립트, 스타일 시트 등이 있다.
  
< body >: HTML 문서의 내용을 나타낸다.
한 문서에 하나의 < body > 요소만 존재할 수 있다.

### -태그를 구분짓는 특성
#### 1. 구획을 나누는 태그(Layout)

#### 2. 그 자체로 요소인 태그

### -블록(block)과 인라인(inline)
#### 1. 블록(block)
블록 레벨 요소는 언제나 새로운 줄에서 시작하고, 좌우 양쪽으로 최대한 늘어나 가능한 모든 너비를 차지한다.
상자를 아래로 쌓는 것

#### 2. 인라인(Inline)
인라인 요소는 줄의 어느 곳에서나 시작가능
바로 이전 요소가 끝나는 지점부터 시작하여, 요소의 내용만큼만 차지

#### 포함 규칙
같은 형태의 다른 요소를 안에 포함 가능
(블록>블록, 인라인> 인라인)
대부분의 블록 요소는 다른 인라인 요소도 안에 포함 가능
인라인 요소는 블록요소를 포함 불가능

### -콘텐츠 카테고리
정확히는 몰라도 어느 카테고리인지 예상할 정도는 알아두자

1. 메타데이터 콘텐츠 (Metadata Content)
문서의 메타 데이터(정보), 다른 문서를 가리키는 링크 등을 나타내는 요소

2. 플로우 콘텐츠 (Flow Content)
웹 페이지상에 메타데이터를 제외하고 거의 모든 요소. 보통 텍스트나 임베디드 콘텐츠를 포함

3. 섹션 콘텐츠 (Selection Content)
웹 문서의 구획(Section)을 나눌 때 사용

4. 헤딩 콘텐츠 (Heading Content)
섹션의 제목(heading)과 관련된 요소

5. 프레이징 콘텐츠 (Phrasing Content)
문단에서 텍스트를 마크업 할 때 사용

6. 임베디드 콘텐츠 (Embedded Content)
이미지나 비디오 등 외부 소스를 가져오거나 삽입할 때 사용되는 요소

7. 인터랙티브 콘텐츠 (Interactive Content)
사용자와의 상호작용을 위한 컨텐츠 요소
