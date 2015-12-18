코멘트 Comment
==========

워드프레스의 post, page와 같은 하나의 아티클을 표현합니다. 구성요소로 제목, 본문, 썸네일, 날짜, 저자 등을 포함할 수 있습니다.

코멘트 위젯 Comment Widget
----------------

(캡처: Article widget in widget bar)
* 아티클 구성요소들을 포함 
* 삽입된 하나의 아티클 위젯은 사이트 적용시 페이지 문맥에 따라 단독으로(single.php), 혹은 반복되어 리스트(index.php,  archive.php 등)로 출력됩니다.

------------

코멘트 요소 Comment Element
------------

(캡처: Article title widget in widget bar)
(캡처: article title in single.php)

* 해당 아티클(post/page)의 제목이 출력됩니다.
* 반드시 아티클 위젯 하위에 삽입되어야 동작합니다.
* Property 탭에서 Link 여부를 선택할 수 있습니다.

------------

코멘트 입력폼 Comment Input Form
------------

(캡처: article body widget in widget bar)
(캡처: article body (excerpt) in index.php | article body (full) in single.php)

* 해당 아티클의 본문이 출력됩니다.
* 반드시 아티클 위젯 하위에 삽입되어야 동작합니다.
* Property 탭의 Type에서 본문의 전체(full)/일부(excerpt) 출력여부를 선택할 수 있습니다.
  * 일부(excerpt)만 출력하도록 선택한 경우, 출력 길이를 단어수 단위로 정할 수 있습니다. (기본값: 55)
* Property 탭에서 Link 여부를 선택할 수 있습니다.

