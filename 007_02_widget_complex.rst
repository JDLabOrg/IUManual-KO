복합 위젯 Complex Widget
================================

트랜지션 Transition
-------------------

.. image:: resource/widget/IUTransition.png

.. thumbnail:: resource/capture_window/transition.png

트랜지션 위젯입니다.
트랜지션 위젯은 하위에 2개의 아이템을 가지고 있으며, 클릭 혹은 마우스오버시 1번 아이템에서 2번 아이템으로 전환됩니다.
Effect와 Duration을 설정해 다양하게 커스터마이징 가능합니다.


**속성**

* 하위요소 : 불가능
* 링크 : 가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 불가능
* 백엔드 엘립시스 : 불가능


캐러젤 Carousel
---------------

.. image:: resource/widget/IUCarousel.png

.. thumbnail:: resource/capture_window/carousel.png

캐러젤 위젯입니다.
하위 아이템은 Box와 속성이 동일하므로 자유롭게 요소를 추가할수 있습니다. Property에서 아이템 개수를 추가하거나 컨트롤러나 오토플레이 등의 옵션을 설정할 수 있습니다.


**속성**

* 하위요소 : 불가능
* 링크 : 내부요소에만 가능
* 스크롤 애니메이터 : 불가능
* 배경이미지 : 불가능
* 백엔드 엘립시스 : 불가능



구글맵 Google Map
----------------------

.. image:: resource/widget/IUGoogleMap.png

.. thumbnail:: resource/capture_window/google_map.png

구글맵 위젯입니다. 좌표값을 설정하면 원하는 위치를 보여줄 수 있습니다.

컬러스타일이나, 줌 설정 등 다양하게 커스터마이징할 수 있습니다.

.. note::
  1) 에디터 모드에서는 미리보기가 600x600 사이즈로만 지원되지만 아웃풋모드에서는 정상작동합니다.
  2) 대한민국 지도에는 컬러테마가 적용되지 않습니다.


**속성**

* 하위요소 : 불가능
* 링크 : 불가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 불가능
* 백엔드 엘립시스 : 불가능


웹무비 WebMovie
--------------------

.. image:: resource/widget/IUWebMovie.png

.. thumbnail:: resource/capture_window/vimeo_youtube.png

웹무비 위젯입니다.
Vimeo와 Youtube에 업로드 된 영상을 불러올 수 있습니다.
영상을 불러올때는 다음과 같이 짧은 주소를 이용합니다.

* ``Vimeo`` : http://vimeo.com/**videoURL**
* ``Youtube`` : http://youtu.be/**videoURL**

자동재생/자동반복 등의 설정이 가능합니다.



**속성**

* 하위요소 : 불가능
* 링크 : 불가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 가능
* 백엔드 엘립시스 : 불가능


비디오 클립 Video Clip
-------------------------

.. image:: resource/widget/IUMovie.png

.. thumbnail:: resource/capture_window/video_clip.png

비디오 클립 위젯입니다. 리소스 패널에서 비디오를 입력할 수 있습니다.



**Property**

* Child : Invalid
* Link  : Valid
* Scroll Animator : Valid
* Background Image : Valid
* Backend Ellipsis : Invalid


테이블 Table
------------

.. image:: resource/widget/IUTable.png

.. thumbnail:: resource/capture_window/table.png

테이블 위젯입니다.
캔버스에 간단한 표를 그릴 수 있습니다.



**속성**

* 하위요소 : 불가능
* 링크 : 가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 가능
* 백엔드 엘립시스 : 가능


심플 탭  Simple Tab View
-----------------------------

.. image:: resource/widget/IUSimpleTabView.png

.. thumbnail:: resource/capture_window/simple_tab_view.png

탭 뷰 위젯입니다. 탭 뷰 위젯보다 구조가 단순합니다.
탭 선택 시 각각의 탭에 연결된 탭 컨텐츠를 보여줍니다.



**속성**

* 하위요소 : -
* 링크 : -
* 스크롤 애니메이터 : -
* 배경이미지 : -
* 백엔드 엘립시스 : -


탭 뷰 Tab View
--------------

.. image:: resource/widget/IUTabView.png

.. thumbnail:: resource/capture_window/tab_view.png

탭 뷰 위젯입니다.
탭 선택 시 각각의 탭에 연결된 탭 컨텐츠를 보여줍니다.



**속성**

* 하위요소 : -
* 링크 : -
* 스크롤 애니메이터 : -
* 배경이미지 : -
* 백엔드 엘립시스 : -


컬랩시블 Collapsible
--------------------

.. image:: resource/widget/IUCollapsible.png

.. thumbnail:: resource/capture_window/collapsible.png

컬랩시블 위젯입니다.
컬랩시블 아이템을 선택 시 컨텐츠 영역을 보여줍니다. 트랜지션 효과와 타이밍 등을 설정할 수 있습니다.



**속성**

* 하위요소 : -
* 링크 : -
* 스크롤 애니메이터 : -
* 배경이미지 : -
* 백엔드 엘립시스 : -


임포트 Import
------------------

.. image:: resource/widget/IUImport.png

.. thumbnail:: resource/capture_window/import.png


컴포지션을 불러오는 임포트 위젯입니다.
헤더 또는 푸터 그리고 커스텀 컴포지션 요소를 임포트 할 수 있는 위젯입니다.
하나의 컴포지션을 여러개의 임포트에 불러올수 있어 다양한 응용이 가능합니다.



**속성**

* 하위요소 : 불가능
* 링크 : 가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 가능
* 백엔드 엘립시스 : 불가능



트위터 공유 버튼 Tweet Share Button
----------------------------------------

.. image:: resource/widget/IUTweetButton.png

.. thumbnail:: resource/capture_window/twt_share.png

현재 페이지를 트위터로 공유할 수 있는 트위터 위젯입니다.
Property에서 형태를 설정할수 있으나 크기는 조정되지 않습니다.



**속성**

* 하위요소 : 불가능
* 링크 : 가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 가능
* 백엔드 엘립시스 : 불가능


페이스북 좋아요 버튼 Facebook Like Button
-----------------------------------------------

.. image:: resource/widget/IUFBLike.png

.. thumbnail:: resource/capture_window/fb_like.png

현재 페이지를 페이스북으로 공유할 수 있는 페이스북 위젯입니다.
Property에서 공유할 URL 의 주소와 컬러 테마를 설정할수 있으나 크기는 조정되지 않습니다.


**속성**

* 하위요소 : 불가능
* 링크 : 가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 가능
* 백엔드 엘립시스 : 불가능


센터박스 Centered Box
-------------------------

.. image:: resource/widget/IUCenterBox.png

.. thumbnail:: resource/capture_window/center_box.png


페이지의 요소를 가운데로 정렬시켜주는 센터박스 위젯입니다.
섹션에는 자동으로 추가되지만, 필요시 다른 요소에 추가할 수 있도록 위젯으로도 만들어져 있습니다.
센터박스 크기는 가로:미디어쿼리값, 세로:100%로 고정되어있으며 변경은 불가능합니다.
이외의 속성은 일반 Box 위젯과 동일합니다.



**속성**

* 하위요소 : 불가능
* 링크 : 가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 가능
* 백엔드 엘립시스 : 불가능


프로그레스 바 Progress Bar
---------------------------------------

.. image:: resource/widget/IUProgressBar.png

.. thumbnail:: resource/capture_window/progress_bar.png


최대치 대비 현재 비율을 나타태주는 프로그레스 바를 그릴 수 있는 위젯입니다.
프로그레스 바의 크기와 컬러를 자유롭게 선택 가능하며, 줄무늬나 움직임 등 옵션을 설정할 수 있습니다.


**속성**

* 하위요소 : 불가능
* 링크 : 가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 불가능
* 백엔드 엘립시스 : 불가능



SVG (Scalable Vector Graphics)
-------------------------------------

.. image:: resource/widget/IUSVG.png

.. thumbnail:: resource/capture_window/svg.png


SVG를 사용할 수 있는 위젯입니다.
아이유에디터에서는 메뉴, 검색, 체크, 좌/우 화살표 등의 형태를 기본으로 제공합니다.
Property 에서 배경컬러, 스트로크 컬러등을 설정 할 수 있으며, 외부에서 그린 SVG 이미지의 코드를 붙여넣어 원하는 형태를 사용할 수 도 있습니다.



**속성**

* 하위요소 : 불가능
* 링크 : 가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 불가능
* 백엔드 엘립시스 : 불가능
