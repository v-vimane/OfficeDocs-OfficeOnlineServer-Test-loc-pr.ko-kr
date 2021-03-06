﻿---
title: Get-OfficeWebAppsHost
TOCTitle: Get-OfficeWebAppsHost
ms:assetid: a9b766a7-a15c-4bbf-9750-31719406d65f
ms:mtpsurl: https://technet.microsoft.com/ko-kr/library/JJ219446(v=office.15)
ms:contentKeyID: 49643412
ms.date: 12/18/2017
mtps_version: v=office.15
ms.translationtype: HT
---

# Get-OfficeWebAppsHost

 

_**적용 대상:**Office Web Apps Server_

_**마지막으로 수정된 항목:**2013-12-18_

Office Web Apps 서버 팜의 허용 목록에 있는 호스트 도메인 목록을 반환합니다.

## 구문

    Get-OfficeWebAppsHost

## 자세한 설명

**Get-OfficeWebAppsHost** cmdlet은 Office Web Apps 서버에서 파일 검색, 메타데이터 검색, 파일 변경 등의 파일 작업 요청을 허용하는 호스트 도메인 목록을 반환합니다. 허용 목록이라고 하는 이 목록은 원치 않는 호스트가 사용자 모르게 Office Web Apps 서버 팜에 연결하여 파일 작업에 팜을 사용할 수 없도록 하는 보안 기능입니다.

허용 목록에 표시된 모든 도메인에는 와일드카드 \*가 있는 것으로 가정하므로, 모든 하위 도메인에 대한 요청도 허용됩니다. 예를 들어 contoso.com 도메인이 허용 목록에 있는 경우 Office Web Apps 서버에서는 corp.contoso.com 및 dev.contoso.com 도메인에 대한 요청도 허용합니다. fabrikam.com과 같은 다른 도메인에 대한 요청은 허용되지 않습니다.


> [!WARNING]
> 허용 목록에 도메인이 없으면 Office Web Apps 서버에서는 모든 도메인의 호스트에 대한 파일 요청을 허용합니다. Office Web Apps 서버 팜을 인터넷에서 액세스할 수 있는 경우에는 이 목록을 비워 두지 마십시오. 목록을 비워 두면 모든 사용자가 Office Web Apps 서버 팜을 사용하여 콘텐츠를 보고 편집할 수 있습니다.



## 매개 변수

## 입력 형식

## 반환 형식

## 예제

\---------------예제 1---------------

    Get-OfficeWebAppsHost

이 예제에서는 허용 목록에 있는 호스트 도메인을 반환합니다.

## 참고 항목


[New-OfficeWebAppsHost](new-officewebappshost.md)  
[Remove-OfficeWebAppsHost](remove-officewebappshost.md)  


[Office Web Apps 서버의 콘텐츠 로드맵](content-roadmap-for-office-web-apps-server.md)  
[인프라 배포: Office Web Apps 서버](deploy-the-infrastructure-office-web-apps-server.md)  
  

[](deploy-the-infrastructure-office-web-apps-server.md)

