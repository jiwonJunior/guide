---
description: This section explains how to create and download SBOM reports.
---

# Generating and Downloading SBOM Report

#### 1. What is a SBOM Report?

* It is a feature that allows administrators to generate a SBOM report based on the results from Clarity and FossID.
* The SBOM report can be extracted as an SBOM in JSON file format (supporting CycloneDX 1.6 and SPDX 3.0), making it ready for submission where required.
* A SBOM report can be created immediately after the scan is complete.

#### 2. How to Create a SBOM Report

* A SBOM report can be generated using the following two methods:



**(1). Generation During the Verification Workflow**

* During the Request Usage Type Review or Usage Type Review stages, you can generate a SBOM report via the SBOM Report area at the bottom of the screen.

<div align="left"><figure><img src="../.gitbook/assets/image (189).png" alt="" width="563"><figcaption></figcaption></figure></div>

<div align="left"><figure><img src="../.gitbook/assets/image (190).png" alt="" width="563"><figcaption></figcaption></figure></div>



**(2). Direct Generation via Menu**

* You can generate a SBOM report by clicking the \[Add SBOM Report] button in the **Project > SBOM Report** List menu.

<div align="left"><figure><img src="../.gitbook/assets/image (60).png" alt="" width="563"><figcaption></figcaption></figure></div>

<div align="left"><figure><img src="../.gitbook/assets/image (61).png" alt="" width="563"><figcaption></figcaption></figure></div>



#### 3. SBOM Report Screen Layout

* The SBOM Report screen consists of three main areas.

<div align="left"><figure><img src="../.gitbook/assets/image (191).png" alt="" width="563"><figcaption></figcaption></figure></div>

**(1). SBOM Report Meta-Information Area**

This area allows you to check the basic information of the SBOM report.

* SBOM Report Name and Version
* Verification Tools (Clarity / FossID)
* Target File Name
* Project ID
* Report Author and Department

**(2). SBOM Report Workflow Area**

This area manages the stages from report creation to review and distribution.

* Write: The stage for drafting the SBOM report.
* Review: The stage for reviewing the SBOM report.
* Distributed: The stage where the SBOM report distribution is complete.

**(3). OSS Used Information Area**

This area is for reviewing the list of open-source components used in the target file and their verification results.

* Component Name and Version
* License Information
* Obligation Type
* Usage Type
* Status of Disclosure, Modification, Notice, and Patent
* Security Vulnerability Levels (Vulnerability Level / Severity / Security)



***

#### 4. Workflow Stage Descriptions (Write/Review/Distributed)

* The SBOM report workflow proceeds in three stages.



**Step 1 - Write**

* Currently, this is the stage where the administrator requests a review. It is a separate stage designed to accommodate future updates where developers may be granted permissions to draft SBOM reports.
* Clicking the \[Request Review] button moves the process to the Review stage.

<div align="left"><figure><img src="../.gitbook/assets/image (64).png" alt="" width="563"><figcaption></figcaption></figure></div>



**Step 2 - Review**

* In this stage, the SBOM report is reviewed to determine whether to reject it or proceed with distribution.

<div align="left"><figure><img src="../.gitbook/assets/image (65).png" alt="" width="563"><figcaption></figcaption></figure></div>



**Step 3 - Distributed**

* Once the SBOM report is finalized, this is the stage where the report can be downloaded.
* Additionally, notice information (Notice) can be drafted once the SBOM report distribution is complete.

<div align="left"><figure><img src="../.gitbook/assets/image (66).png" alt="" width="563"><figcaption></figcaption></figure></div>



**Step 3.1. Downloading the SBOM Report**

* You can download the SBOM report as an SBOM file in JSON format, supporting both CycloneDX 1.6 and SPDX 3.0 standards.

<div align="left"><figure><img src="../.gitbook/assets/image (192).png" alt="" width="563"><figcaption></figcaption></figure></div>



**Step 3.2. Writing Notice and Disclosed Code Information**

* After the SBOM report distribution is complete, click the \[Request Notice] button to generate notice information.

<div align="left"><figure><img src="../.gitbook/assets/image (70).png" alt="" width="563"><figcaption></figcaption></figure></div>



* Clicking \[Send Notice] generates a link information flow.

<div align="left"><figure><img src="../.gitbook/assets/image (193).png" alt=""><figcaption></figcaption></figure></div>



***

