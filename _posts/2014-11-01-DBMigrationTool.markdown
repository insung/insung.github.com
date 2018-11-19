---
layout: default
modal-id: 3
date: 2014-11-01
img: db_migration_tool.png
classification: DB migration tool
project-date: 2014년 11월
category: ShadowCube
skill: C# WinForm
summary: 고객사에서 ShadowCube Database 를 PostgreSQL -> MSSQL 로 마이그레이션 요청이 많아 툴로 구현하여 생산성이 높아졌습니다.
description: <br />아래는 ShadowCube 데이터베이스를 마이그레이션하는 툴입니다.<br />PostgreSQL 에서 MSSQL 로 ShadowCube 데이터를 이전할 때 사용하는 툴입니다.<br />먼저 환경설정 정보를 입력하여 저장합니다. <img src="img/portfolio/dbm_connection_test.gif" class="img-responsive project-image project-image-center" alt="dbm_connection_test"> <br />그 다음에 MSSQL 에 신규 데이터베이스를 생성합니다. <img src="img/portfolio/dbm_dbinit.gif" class="img-responsive project-image project-image-center" alt="dbm_dbinit"> <br />그리고 현재 PostgreSQL 의 데이터는 어떤 것이 있는지 확인하고, MSSQL 로 이동 시킵니다. <img src="img/portfolio/dbm_process.gif" class="img-responsive project-image project-image-center" alt="dbm_process"> 데이터 이동은 background 에서 처리하고 있기 때문에<br />보시는바와 같이 스크롤 이동, 상태 변화 등 UI 가 Update 됩니다.<br /><br />구현 초기에는 데이터들을 List 객체에 담아 ShadowCube 데이터를 이동시켰는데<br />데이터가 많아질 수록 속도가 느려지는 이슈가 있었습니다.<br />따라서 실시간으로 MSSQL 데이터베이스에 이동하도록 개선하여 속도 및 안전성을 높였습니다.

---
