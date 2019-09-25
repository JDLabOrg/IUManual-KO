프로그래밍 위젯 Programming Widget
====================================

폼 Form
----------

.. image:: resource/widget/PGForm.png

.. thumbnail:: resource/capture_window/form.png

폼 위젯입니다.
Input 요소를 감싸주는 :code:`<form>` 태그 위젯입니다. 따라서, Input 요소를 추가하기 전에 필수로 생성해야 합니다.
폼 위젯을 먼저 만들고 그 안에 Input 위젯을 넣어주세요.


**속성**

* 하위요소 : 가능
* 링크 : 불가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 가능
* 백엔드 엘립시스 : 불가능


인풋 텍스트 Input Text
----------------------------

.. image:: resource/widget/PGTextField.png

.. thumbnail:: resource/capture_window/input_text.png

인풋 텍스트 위젯입니다.
Form 위젯에 추가하여 사용자로부터 텍스트를 입력받을수 있습니다.


**속성**

* 하위요소 : 불가능
* 링크 : 가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 가능
* 백엔드 엘립시스 : 불가능


인풋 패러그래프 텍스트 Input Paragraph Text
---------------------------------------------

.. image:: resource/widget/PGTextView.png

.. thumbnail:: resource/capture_window/input_paragraph.png

인풋 텍스트(문장) 위젯입니다.
Form 위젯에 추가하여 사용자로부터 텍스트를 입력받을수 있습니다. (긴 문장에 사용)



**속성**

* 하위요소 : 불가능
* 링크 : 가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 가능
* 백엔드 엘립시스 : 불가능


셀렉트 Select
----------------

.. image:: resource/widget/PGSelect.png

.. thumbnail:: resource/capture_window/select.png

셀렉트 위젯입니다.
Form 위젯에 추가하여 사용자로부터 특정 값을 입력받을수 있습니다. (여러 개의 옵션 중 선택된 1개의 값을 받아올 경우 사용)




**속성**

* 하위요소 : 불가능
* 링크 : 가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 가능
* 백엔드 엘립시스 : 불가능


HTML (Hyper Text Markup Language)
----------------------------------------

.. image:: resource/widget/PGHTML.png

.. thumbnail:: resource/capture_window/html.png

HTML 위젯입니다.
IUEditor에 원하는 위젯이 없을 경우 직접 HTML 코드를 작성해서 넣을 수 있습니다.
하지만 원하는 위젯이 있다면 iu@jdalb.org로 의견을 보내주세요!



**속성**

* 하위요소 : 불가능
* 링크 : 불가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 가능
* 백엔드 엘립시스 : 불가능



콜렉션 Collection
-----------------

.. image:: resource/widget/PGCollection.png

.. thumbnail:: resource/capture_window/collection.png

컴포지션을 불러오는 콜렉션 위젯입니다.
하나의 컴포지션을 반복해서 사용하려고 할때 유용합니다. 한 줄에 몇 개의 컴포지션이 보이게 할지 정할 수 있습니다.



**속성**

* 하위요소 : 불가능
* 링크 : 가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 가능
* 백엔드 엘립시스 : 불가능



페이지 넘버 셋 Page Number Set
--------------------------------

.. image:: resource/widget/PGPageLinkSet.png

.. thumbnail:: resource/capture_window/page_numb.png

페이지 링크 셋 위젯입니다.
콜렉션 뷰로 불러온 다수의 요소를 페이지 단위로 제어하고 싶을 때 사용합니다. 주로 게시판이나 페이지 세트의 링크를 만들 때 사용합니다. 한 번의 몇개의 숫자를 나타낼 것인지 정할 수 있습니다.



**속성**

* 하위요소 : 불가능
* 링크 : 가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 가능
* 백엔드 엘립시스 : 불가능



체크박스 Checkbox
-----------------

.. image:: resource/widget/PGCheckBox.png

.. thumbnail:: resource/capture_window/checkbox.png


체크박스 위젯입니다.
기본 형태의 체크박스 위젯입니다. 사용자가 원하는 만큼 여러 개의 위젯을 자유롭게 배치할 수 있습니다.



**속성**

* 하위요소 : 불가능
* 링크 : 가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 불가능
* 백엔드 엘립시스 : 불가능


라디오 버튼 Radio Button
-----------------------------

.. image:: resource/widget/PGRadioButton.png

.. thumbnail:: resource/capture_window/radio_btn.png

라디오 버튼 위젯입니다.
기본 형태의 라디오 버튼 위젯입니다. 사용자가 원하는 만큼 여러 개의 위젯을 자유롭게 배치할 수 있습니다.




**속성**

* 하위요소 : 불가능
* 링크 : 가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 불가능
* 백엔드 엘립시스 : 불가능


버튼 Button
---------------

.. image:: resource/widget/PGButton.png

.. thumbnail:: resource/capture_window/button.png

버튼 위젯입니다.
Default / Reset / Submit 3 가지 타입 중에 1가지를 선택해서 사용합니다. Form에서 입력받은 내용을 전송하는 기능을 담당합니다.



**속성**

* 하위요소 : 불가능
* 링크 : 불가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 가능
* 백엔드 엘립시스 : 불가능



파일 업로드 File Upload
------------------------------

.. image:: resource/widget/PGFileUpload.png

.. thumbnail:: resource/capture_window/file_upload.png


파일 업로드 위젯입니다.
업로드 버튼을 선택하여 서버로 올릴 파일을 선택할 수 있습니다. (1개의 파일)



**속성**

* 하위요소 : 불가능
* 링크 : 불가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 불가능
* 백엔드 엘립시스 : 불가능



스위치 Switch
-------------------

.. image:: resource/widget/PGSwitch.png

.. thumbnail:: resource/capture_window/switch.png


스위치 위젯입니다.
스위치를 토글하여 ON-OFF 상태로 변경할 수 있습니다.


**속성**

* 하위요소 : 불가능
* 링크 : 불가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 불가능
* 백엔드 엘립시스 : 불가능



플립 스위치 Flip Switch
-----------------------------

.. image:: resource/widget/PGFlipSwitch.png

.. thumbnail:: resource/capture_window/flip_switch.png


플립 스위치 위젯입니다.
플립 스위치를 토글하여 ON-OFF 상태로 변경할 수 있습니다.



**속성**

* 하위요소 : 불가능
* 링크 : 불가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 불가능
* 백엔드 엘립시스 : 불가능


슬라이더 Slider
--------------------------

.. image:: resource/widget/PGSlide.png

.. thumbnail:: resource/capture_window/slider.png


슬라이더 위젯입니다.
슬라이더를 선택하여 원하는 값을 입력하거나, 수치를 입력하여 슬라이더를 조정할 수 있습니다.



**속성**

* 하위요소 : 불가능
* 링크 : 불가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 불가능
* 백엔드 엘립시스 : 불가능


레인지 슬라이더 Range Slider
--------------------------------

.. image:: resource/widget/PGRangeSlide.png

.. thumbnail:: resource/capture_window/range_slider.png


레인지 슬라이더 위젯입니다.
레인지 슬라이더의 포인터를 이동시켜 원하는 값을 입력하거나, 수치를 입력하여 슬라이더를 조정할 수 있습니다.



**속성**

* 하위요소 : 불가능
* 링크 : 불가능
* 스크롤 애니메이터 : 가능
* 배경이미지 : 불가능
* 백엔드 엘립시스 : 불가능
