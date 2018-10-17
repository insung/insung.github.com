---
layout: default
modal-id: 1
date: 2012-04-01
img: main_page.png
classification: ShadowCube Server main
project-date: 2012년 4월 &mdash; 현재
category: ShadowCube
skill: ASP.NET, Ext.NET, MSSQL, PostgreSQL
summary: ShadowCube 서버 파트의 메인 개발자로 UI, 비지니스 로직, Database, 웹 서버의 모든 업무를 담당하였습니다.
description: <br />아래는 ShadowCube 서버의 메인 페이지입니다. <img src="img/portfolio/scpc_login.gif" class="img-responsive project-image" alt="scpc_login"> 해당 시스템의 디스크 사용량, ShadowCube 에서 사용하는 인증서 발급정보 및<br />도메인 라이선스 정보를 한 눈에 볼 수 있게 구성하였습니다. <br /><br />다음은 ShadowCube 의 사용자 정보를 볼 수 있는 UI 입니다. <img src="img/portfolio/scpc_user.gif" class="img-responsive project-image" alt="scpc_user"> 여러명을 선택하여 볼륨라이선스를 할당할 수 있게 구현하였습니다.<br />오른쪽에 보이는 부서트리는 recursive 함수를 사용하였고,<br />DB procedure 로 구현하여 1000개가 넘는 부서도 아주 빠르게 조회가능하도록 구현하였습니다.<br /><br /> 다음은 ShadowCub 문서사용 로그 페이지입니다.<br />ShadowCube 클라이언트에서 보낸 문서 로그를 사용자별로 조회할 수 있습니다. <img src="img/portfolio/scpc_log.gif" class="img-responsive project-image" alt="scpc_log"> 초기에는 로그 조회 속도가 아주 느렸지만,<br />전체 건 수 중에 특정 갯수만 가져오도록 구현하여 속도를 향상시켰습니다.<br /><br />다음은 ShadowCube 사용자들이 가장 많이 사용하는 복호화 요청 페이지입니다.<br />사용자들이 암호화된 파일을 복호화하기 위해 관리자에게 요청할 수 있는 페이지입니다. <img src="img/portfolio/sdmc_request.gif" class="img-responsive project-image" alt="sdmc_request"> 기존에는 ActiveX 기반으로 구현되어있었는데 이를 제거하였고,<br />Backload 라는 Open source 를 사용하여 파일 업로드를 구현하였습니다.<br />파일을 Drag & Drop 하여 업로드하면, 문서그룹 정보를 표시하며, 결재자, 요청 사유 등을 입력할 수 있습니다.<br /><br />이후에는 Linux 서버도 지원하기 위하여 ASP.NET Core 로도 구현하였습니다.<br />Backload ASP.NET4 + ASP.NET Core 에 대한 예제는 <a href="https://github.com/insung/Backload-Examples" target="_blank">Github</a> 에도 정리하였습니다.

---
