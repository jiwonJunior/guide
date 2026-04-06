---
description: 검증 보고서에 작성 방법과 다운로드 방법에 대해 설명합니다.
---

# 검증 보고서 생성 및 다운로드

#### 1. **검증 보고서란?**

* 관리자가 Clarity 및 FossID 검증 결과를 바탕으로 검증 보고서를 작성하는 기능입니다.
* 검증 보고서를 CycloneDX 1.6 및 SPDX 3.0 포맷의 JSON 파일 형식의 SBOM으로 추출하여, 필요한 곳에 제출할 수 있도록 제공합니다.
* 검증 보고서는 스캔  직후 작성할 수 있습니다.

#### 2. 검증 보고서 작성 방법

검증 보고서는 다음 두 가지 방법으로 생성할 수 있습니다.



**(1). 검증 워크플로우 진행 중 생성**

* _Request Usage Type Review_ 또는 _Usage Type Review_ 단계에서\
  화면 하단의 **Verification Report** 영역을 통해 검증보고서를 생성할 수 있습니다.

<figure><img src="../.gitbook/assets/image (56).png" alt=""><figcaption></figcaption></figure>

<div align="left"><figure><img src="../.gitbook/assets/image (53).png" alt=""><figcaption></figcaption></figure></div>



**(2). 메뉴를 통한 직접 생성**

* Project > Verification Report List 메뉴에서\
  \[Add Verification Report] 버튼을 클릭하여 검증보고서를 생성할 수 있습니다.

<figure><img src="../.gitbook/assets/image (54).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (55).png" alt=""><figcaption></figcaption></figure>



#### 3. **검증보고서 화면 구성 설명**&#x20;

* 검증보고서 화면은 3개의 영역으로 구성됩니다.

<figure><img src="../.gitbook/assets/검증보고서　영역.png" alt=""><figcaption></figcaption></figure>

**(1). 검증보고서 메타정보 영역**

검증보고서의 기본 정보를 확인할 수 있는 영역입니다.

* 검증보고서 이름 및 버전
* 검증 도구(Clarity / FossID)
* 검증 대상 파일 명
* 프로젝트 ID
* 보고서 작성자 및 부서

**(2). 검증보고서 워크플로우 영역**

검증보고서 작성부터 검토, 배포 단계를 진행합니다.

* **Write**: 검증보고서 작성 단계
* **Review**: 검증보고서 검토 단계
* **Distributed**: 검증보고서 배포 완료 단계

**(3). OSS Used Information 영역**

검증 대상 파일에서 사용된 오픈소스 컴포넌트 목록과 검증 결과를 확인하는 영역입니다.

* 컴포넌트 이름 및 버전
* 라이선스 정보
* 의무 유형(Obligation Type)
* Usage Type
* 공개(Disclosure), 수정(Modification), 공지(Notice), 특허(Patent) 여부
* 보안 취약점 수준(Vulnerable Level / Severity / Security)



***

#### 4. 각 워크플로우 단계 별 동작 설명(Write/Review/Distributed)

* 검증 보고서 워크플로우는 3단계로 진행됩니다.



**Step 1 - Write**

* 현재는 관리자가 검토 요청하는 단계이며,  추후 개발자에게 검증보고서 작성 권한이 부여될 가능성을 고려하여 분리된 단계입니다.
* \[Request Review] 버튼을 클릭하면 Review 단계로 이동합니다.

<figure><img src="../.gitbook/assets/image (58).png" alt=""><figcaption></figcaption></figure>



**Step 2 - Review**

* 검증보고서를 검토한 후, 반려하거나 배포 여부를 결정하는 단계입니다.

<figure><img src="../.gitbook/assets/image (59).png" alt=""><figcaption></figcaption></figure>



**Step 3 - Distributed**

* 검증보고서 작성이 완료된 후, 해당 검증보고서를 다운로드할 수 있는 단계입니다.
* 또한 검증보고서 배포가 완료되면 고지 정보를 작성할 수 있습니다.

<figure><img src="../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure>



**Step 3.1. 검증보고서 다운로드**

검증보고서를 CycloneDX 1.6 및 SPDX 3.0 포맷의 JSON 형식 SBOM 파일로 다운로드할 수 있습니다.

<figure><img src="../.gitbook/assets/image (61).png" alt=""><figcaption></figcaption></figure>



**Step 3.2. 고지문 및 공개코드 정보 작성하기**

* 검증 보고서 배포 완료 후, \[Request Notice] 버튼을 클릭해서 고지정보 생성합니다.

<figure><img src="../.gitbook/assets/image (64).png" alt=""><figcaption></figcaption></figure>



* Type에서 생성할 고지문 또는 공개 코드를 선택하면 고지 워크플로우가 생성됩니다.

<div align="left"><figure><img src="../.gitbook/assets/image (62).png" alt=""><figcaption></figcaption></figure></div>









