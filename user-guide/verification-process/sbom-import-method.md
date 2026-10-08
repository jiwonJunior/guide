---
description: This section explains how to Import an SBOM.
---

# SBOM Import Method

#### 1. How to Import SBOM

* The SBOM Import proceeds through a **2-step workflow**.
* Collaboration: Developers can proceed through the stages alongside the Administrator.
* Authority: The Administrator performs the process.
* Verification Flow: `Scan` → `Review` → `Completion`
* You can check the current stage on the workflow bar.



#### 2. Scanning the SBOM File

Click \[SBOM Verification] to select the file to be verified.

<div align="left"><figure><img src="../../.gitbook/assets/image (128).png" alt="" width="563"><figcaption></figcaption></figure></div>



* Select the SBOM file to import and its format.
* The SBOM file supports the JSON format only.
* You can select from SPDX 3.0, CycloneDX 1.6, or System Default SBOM formats. If you add a format in SBOM Management, it will also appear in the list. ([Refer to How to Manage SBOM Formats](../../manager-guide/sbom-format-management.md))

<div align="left"><figure><img src="../../.gitbook/assets/image (129).png" alt="" width="446"><figcaption></figcaption></figure></div>

#### 3. SBOM Detailed Screen Description

* The Clarity verification screen is primarily composed of the following 3 areas

#### (1). Project Meta-Information

* Project Name, Version, Verification Tool, Requester, Request Date, Actual File Name, Scan Type, Department, Modification Date, Re-verification Deadline.

#### (2). SBOM Workflow

* The SBOM workflow consists of a total of 2 steps, and you can check the current progress on the screen. The Developer can proceed through the stages alongside the Administrator, and the Administrator can perform all stages.

#### (3). Communication Function

* During the SBOM workflow, the Administrator can leave comments during the Review stage.

<div align="left"><figure><img src="../../.gitbook/assets/clarity_section_yellow_4 (1).png" alt=""><figcaption></figcaption></figure></div>

#### (4). Scanned Component List (Component List)

**Item Description**

* <mark style="background-color:yellow;">CONFLICT: Displays in red if the component falls under a license policy; displays in white if there are no conflicts.</mark>
* COMPONENT (COMPONENT VERSION): Component name and component version information.
* COMPONENT LICENSE: License information for the component.
* OBLIGATION TYPE: Information on license obligation types (based on project license policies).
* USAGE TYPE: The default value is N/A; can be specified during the usage type input stage.
* DISCLOSE: Whether the component is disclosed.
* MODIFICATION: Whether the component has been modified.
* NOTICE: Whether the component requires a notice.
* PATENT: Whether the component involves patents.
* VULNERABLE LEVEL: Displays the risk level of security vulnerabilities found in the component as a code according to the security vulnerability policy.
* SEVERITY: The risk level of vulnerabilities graded based on CVSS scores.
* SECURITY: Displays the list of CVEs (Security Vulnerabilities) found in the component.

***

<figure><img src="../../.gitbook/assets/컴포넌트　목록 (1).png" alt=""><figcaption></figcaption></figure>



**Popup Description**

* Clicking Item No. 1 displays the license policy information applied to the corresponding component.
  * Policy Stage
  * Approval Status
  * Condition (Attribute) Detailed Information

<div align="left"><figure><img src="../../.gitbook/assets/image (81).png" alt="" width="344"><figcaption></figcaption></figure></div>



* Clicking Item No. 2 displays license conflict information between components.

<div align="left"><figure><img src="../../.gitbook/assets/image (82).png" alt="" width="429"><figcaption></figcaption></figure></div>



* Clicking Item No. 3 shows the component information corresponding to the component name and version. If not in the database, it will not be displayed.

<div align="left"><figure><img src="../../.gitbook/assets/image (83).png" alt="" width="324"><figcaption></figcaption></figure></div>



* Clicking Item No. 4 displays the detailed license information. If not in the database, it will not be displayed.

<div align="left"><figure><img src="../../.gitbook/assets/image (85).png" alt="" width="326"><figcaption></figcaption></figure></div>



* Clicking Item No. 5 displays the compliance requirements for the license policy Obligation Type applied to that component.

<div align="left"><figure><img src="../../.gitbook/assets/image (86).png" alt="" width="396"><figcaption></figcaption></figure></div>



* Clicking Item No. 6 displays the compliance requirements for the security vulnerability level code.

<div align="left"><figure><img src="../../.gitbook/assets/image (88).png" alt="" width="416"><figcaption></figcaption></figure></div>



* Clicking Item No. 7 displays a list of CVEs found in the component; clicking each CVE redirects you to the detailed NVD (National Vulnerability Database) page.

<div align="left"><figure><img src="../../.gitbook/assets/image (90).png" alt=""><figcaption></figcaption></figure></div>





### 4. SBOM Workflow Detailed Description

The 2-step workflow is explained below.

{% stepper %}
{% step %}
**Step1 - Review**

* Developers can upload the SBOM file they wish to read.
* Administrators can proceed with re-verification or mark the step as completed.

<div align="left"><figure><img src="../../.gitbook/assets/image (146).png" alt="" width="518"><figcaption></figcaption></figure></div>



* In the SBOM Result, you can check for missing SBOM items and unsupported SBOM items.

<div align="left"><figure><img src="../../.gitbook/assets/image (148).png" alt="" width="563"><figcaption></figcaption></figure></div>


{% endstep %}

{% step %}
**Step2 - Ready**

* The Administrator can revoke the verification.
* Both the Developer and Administrator can compare the Clarity verification results with the imported SBOM results.

<div align="left"><figure><img src="../../.gitbook/assets/image (151).png" alt="" width="563"><figcaption></figcaption></figure></div>



* Click the \[Compare with Clarity Verif.] button and select the Clarity verification to compare from the pop-up window below.

<div align="left"><figure><img src="../../.gitbook/assets/image (152).png" alt="" width="563"><figcaption></figcaption></figure></div>



* You can view the comparison results between the _**selected Clarity verification**_ and the _**imported SBOM**_ results.

<div align="left"><figure><img src="../../.gitbook/assets/image (154).png" alt="" width="563"><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}









