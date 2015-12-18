아티클 Article
==========

워드프레스의 post, page와 같은 하나의 아티클을 표현합니다. 구성요소로 제목, 본문, 썸네일, 날짜, 저자 등을 포함할 수 있습니다.

아티클 위젯 Article Widget
----------------

.. image:: resource/wordpress/iu_manual_wordpress_article_widget.png

* 아티클 구성요소들을 포함하는 워드프레스 테마의 핵심 위젯입니다.
* 삽입된 하나의 아티클 위젯은 사이트 적용시 페이지 문맥에 따라 단독으로(single.php), 혹은 반복되어 리스트(index.php,  archive.php 등)로 출력됩니다.
* 아티클 요소, 코멘트, 코멘트 입력 폼, 태그 블록 위젯들은 아티클 위젯의 하위에 삽입되어야 합니다.

------------

아티클 제목 Article Title
------------

.. image:: resource/wordpress/iu_manual_wordpress_article_title.png

* 해당 아티클(post/page)의 제목이 출력됩니다.
* 아티클 위젯 하위에 삽입되어야 정상 동작합니다.
* Property 탭에서 Link 여부를 선택할 수 있습니다.

------------

아티클 본문 Article Body
------------

.. image:: resource/wordpress/iu_manual_wordpress_article_body_full.png
.. image:: resource/wordpress/iu_manual_wordpress_article_body_excerpt.png
(캡처: article body (excerpt) in index.php | article body (full) in single.php)

* 해당 아티클의 본문이 출력됩니다.
* 아티클 위젯 하위에 삽입되어야 동작합니다.
* Property 탭의 Type에서 본문의 전체(full)/일부(excerpt) 출력여부를 선택할 수 있습니다.
  * 일부(excerpt)만 출력하도록 선택한 경우, 본문의 앞쪽부터 일부만 출력되며, 출력 길이를 단어수 단위로 정할 수 있습니다. (기본값: 55)
* Property 탭에서 Link 여부를 선택할 수 있습니다.


------------

아티클 요소 Article Element
------------

.. image:: resource/wordpress/iu_manual_wordpress_article_element.png

* 해당 아티클의 선택된 구성요소(썸네일/저자/기록날짜)가 출력됩니다.
  * 출력을 원하는 요소를 Property 탭의 Element type에서 지정할 수 있습니다.
* 반드시 아티클 위젯 하위에 삽입되어야 동작합니다.
* Property 탭에서 Link 여부를 선택할 수 있습니다.
