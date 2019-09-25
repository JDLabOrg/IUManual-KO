프로토타입 모드 Prototype Mode
========================================

.. thumbnail:: resource_new/advanced_proto.png

상단 툴바에서 ``Mode Switch Button`` 을 눌러 **Prototype Mode** 로 전환할 수 있습니다.

여러명이 하나의 프로젝트를 같이 작업할 때, 프로토타입 모드에서 프로젝트와 관련된 히스토리와 워크플로우, 메모 등을 공유하고 관리할 수 있습니다.
프로토타입 모드는 :ref:`히스토리 Revision History<Revision_History>` / :ref:`워크플로우 Project Workflow<Project_Workflow>` / :ref:`화면 정의 Node Description<Node_Definition>` 세가지 페이지를 제공합니다.
``Refresh Workflow`` 버튼은 워크플로우를 초기 상태로 리셋 시킵니다. ``Build Scenario`` 버튼은 프로토타입 문서를 **HTML Prototype** 으로 빌드합니다. ``Refresh Thumbnail`` 버튼을 누르면 워크플로우와 페이지 리스트에 있는 페이지 섬네일들을 최신상태로 업데이트 시킵니다.


----------

.. _Revision_History:

히스토리 Revision History
-------------------------------


프로젝트의 **히스토리 Revision History** 를 보여줍니다. 히스토리를 변경하거나 추가할 수 있습니다.


* ``Add New Date Button`` : 히스토리 테이블에 새 히스토리를 추가합니다.
* ``Remove Date Button`` : 히스토리 테이블에서 선택된 히스토리를 지웁니다.

----------

.. _Project_Workflow:

워크플로우 Project Workflow
-------------------------------

.. thumbnail:: resource_new/advanced_proto_revision.png

프로젝트의 **워크플로우 Workflow** 를 보여줍니다. 섬네일을 드래그 앤 드롭 하여 노드를 추가할 수 있습니다. Delete키를 눌러 선택된 노드를 지울 수 있습니다.


* ``Default thumbnails`` : 프로젝트에 포함된 페이지들의 섬네일 목록.
* ``Custom thumbnails`` : **Page Capture** 버튼으로 캡쳐된 페이지들의 섬네일 목록.

.. note:: 커스텀 섬네일은 **Editor Mode** 에서 툴바의 **Page Capture** 를 눌러 추가할 수 있습니다.


.. thumbnail:: resource_new/advanced_proto_workflow.png

* ``Rectangle Button`` : 선택된 노드 아래에 사각형 다이어그램을 추가합니다.
* ``Rhombus Button`` : 선택된 노드 아래에 다이아몬드 다이어그램을 추가합니다.


* ``Inward Label`` : 선택된 노드 위에 표시되는 텍스트를 입력합니다.
* ``Outward Label`` : 선택된 노드 아래에 표시되는 텍스트를 입력합니다.




----------

.. _Node_Definition:

개별 화면 정의 Node Definition
-------------------------------

.. image:: resource/scenario/ic_SB_screen.png

각 페이지의 **개별 화면 정의 Node Definition** 화면을 보여줍니다. 화면 정의 Screen description과 기타사항 Exception area에 내용을 추가하고 편집할 수 있습니다. **워크플로우** 화면에서 섬네일을 더블클릭 해도 **개별 화면 정의 Node Definition** 로 넘어갑니다.

* ``메모 이미지 추가 영역`` : 리소스 패널에서 메모 넘버링을 대체할 이미지를 선택합니다.
* ``Add Memo Button`` : 메모 테이블에 새 메모를 추가합니다.
* ``Delete Button`` : 메모 테이블에서 선택된 메모를 지웁니다.

스크린샷 영역을 클릭하면 클릭한 지점에 메모를 표시할 수 있습니다.
