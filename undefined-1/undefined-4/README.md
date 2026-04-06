---
description: 고지문 작성 방법에 대해 설명합니다.
---

# 고지문 작성하기

#### 1. **고지문(Notice) 개요**

소프트웨어에 포함된 오픈소스 컴포넌트의 라이선스 및 저작권 정보를 사용자에게 알리기 위해 제공하는 공식 문서로 사용됩니다.



#### 2. 고지문 작성 방법

관리자는 고지문을을 다음 2가지 방법으로 생성할 수 있습니다.&#x20;

**(1). 검증보고서 워크플로우에서 생성**

검증 보고서 배포 완료 후, \[Request Notice] 버튼을 클릭해서 고지정보 생성합니다.

<div align="left"><figure><img src="../../.gitbook/assets/image (65).png" alt="" width="563"><figcaption></figcaption></figure></div>



Type에서 생성할 고지문 또는 공개 코드를 선택하면 고지 워크플로우가 생성됩니다.

<div align="left"><figure><img src="../../.gitbook/assets/image (63).png" alt="" width="269"><figcaption></figcaption></figure></div>



**(2). 메뉴를 통한 직접 생성**

Project > Notice Information List 메뉴에서\
\[Add Notice] 버튼을 클릭하여 고지문 또는 공개 코드를 생성할 수 있습니다.

<div align="left" data-full-width="false"><figure><img src="../../.gitbook/assets/image (133).png" alt="" width="563"><figcaption></figcaption></figure></div>



#### 3. 고지 정보 **화면 구성 설명**&#x20;

* 검증보고서 화면은 5개의 영역으로 구성됩니다.

<div align="left"><figure><img src="../../.gitbook/assets/고지정보　상세.png" alt="" width="535"><figcaption></figcaption></figure></div>

**(1). 고지정보 메타정보 영역**

* Notice ID: 고지정보 ID
* Write Completion Expected Date: 작성 완료 예상 날짜
* Notice Information Write: 고지정보 작성 상태
* Disclosed Code Information Write: 공개코드 작성 상태

**(2). 고지정보 워크플로우 영역**

고지정보 작성부터 검토, 배포 단계를 진행합니다.

**(3). 프로젝트 정보 영역**

* 고지 정보가 생성된 대상 프로젝트의 기본 정보를 확인하는 영역입니다.

**(4). 검증보고서 정보 영역**

* 고지 정보가 생성된 대상 검증보고서 기본 정보를 확인하는 영역입니다.

**(5). OSS Used Information 영역**

검증 대상 파일에서 사용된 오픈소스 컴포넌트 목록과 검증 결과를 확인하는 영역입니다.

* 컴포넌트 이름 및 버전
* 라이선스 정보
* 의무 유형(Obligation Type)
* Usage Type
* 공개(Disclosure), 수정(Modification), 공지(Notice), 특허(Patent) 여부
* 보안 취약점 수준(Vulnerable Level / Severity / Security)



