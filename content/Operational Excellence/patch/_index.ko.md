---
title: "패치 관리"
date: 2020-04-24T11:16:09-04:00
chapter: false
weight: 53
pre: "<b>5-3. </b>"
---

클라우드에서는 애플리케이션 코드에 사용하는 것과 동일한 엔지니어링 원칙을 전체 환경에 적용할 수 있습니다. 전체 워크로드(애플리케이션, 인프라 등)를 코드로 정의하고 코드로 업데이트 할 수 있습니다. 이벤트에 대한 응답으로 작업 프로시저를 트리거하여 작업 프로시저를 스크립팅하고 실행을 자동화 할 수 있습니다. 코드로 작업을 수행하면 인적 오류를 줄이고 작업 활동을 일관되게 실행할 수 있습니다.

이번 실습과 관련된 Systems Manager의 기능입니다. 
#### 패치 관리자
AWS Systems Manager는 대규모 Amazon EC2 그룹 또는 온프레미스 인스턴스 전체에서 자동으로 운영 체제 및 소프트웨어 패치를 선택 및 배포하도록 지원합니다. 패치 기준선을 통해 운영 체제 또는 높은 심각도 패치 등 선택한 카테고리의 패치를 자동 승인하도록 규칙을 설정할 수 있고, 이러한 규칙을 무시하고 자동 승인 또는 거부할 패치 목록을 지정할 수 있습니다. 또한, 미리 설정된 시간에만 패치가 적용되도록 패치에 대한 유지 관리 기간을 예약할 수 있습니다. Systems Manager는 소프트웨어를 최신으로 유지하고 규정 준수 정책을 충족하는 데 도움이 됩니다.

#### Run Command
AWS Systems Manager에서는 서버에 로그인하지 않고 대규모로 인스턴스를 원격으로 안전하게 관리할 수 있는 기능을 제공하므로, 배스천 호스트, SSH 또는 원격 PowerShell이 필요 없습니다. 레지스트리 편집, 사용자 관리, 소프트웨어 및 패치 설치와 같은 일반적인 관리 작업을 인스턴스 그룹 전체에서 자동화하는 간단한 방법을 제공합니다. AWS Identity and Access Management(IAM)와의 통합을 통해 세분화된 권한을 적용하여 사용자가 인스턴스에 수행할 수 있는 작업을 제어할 수 있습니다. Systems Manager가 수행한 모든 작업이 AWS CloudTrail에 기록되기 때문에 환경 전체의 변경 사항을 감사할 수도 있습니다.

이 실습에서는 _Infrastructure as Code_ 및 _Operations of Code_ 개념을 다음 활동에 적용합니다.

Steps:
{{% children  %}}