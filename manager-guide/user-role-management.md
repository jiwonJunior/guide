---
description: >-
  You can create and manage user roles in the System > Role menu. Created roles
  can be assigned to users in the System > User menu. Additionally, only
  SUPERUSER accounts can manage user roles.
---

# User Role Management



### 1. Role Registration

* Click the \[Add Role] button to create a new role.

<div align="left"><figure><img src="../.gitbook/assets/image (155).png" alt="" width="563"><figcaption></figcaption></figure></div>



* Enter the required role name marked in red, and select the permission to use from the 8 permissions. Click the \[Add Role] button to complete the role creation.

<div align="left"><figure><img src="../.gitbook/assets/image (196).png" alt=""><figcaption></figcaption></figure></div>

<mark style="color:$primary;">**System Role & Permission Descriptions**</mark>

1. **Manager(System Administrato)**

* Description: Manages all projects within the system, handles policy administration, creates products, and can designate themselves as a Product Manager.
* Key Functions: Global project management, product creation and Product Manager privileges, system policy administration, and SBOM format management.



2. **Product Creator**

* Description: Granted the authority to create new products, which represent the highest-level concept within the system.
* Key Functions: Product creation, assigning Product Managers, and product cloning.



3. **Product Manager**

* Description: Responsible for the overall operation and management of assigned products.
* Key Functions: Creating new projects, assigning Project Managers, and managing product groups.



4. **Project Manager**

* Description: Independently manages assigned projects and oversees their respective project members.
* Key Functions: Driving the project verification workflow independently and managing internal project members.



5. **Developer(General User)**

* Description: A general user role with permissions to view assigned projects and their data.
* Key Functions: Creating new verifications within assigned projects and collaborating with the Project Manager on the verification workflow.



<mark style="color:$primary;">**Policy & SBOM Format Permission Descriptions**</mark>

1. **License Policy Edit**

* Description: Authorizes the user to configure system-wide license policies, as well as create and modify new license rules.
* Key Functions: Configuring default policies, adding new policies, and editing or deleting existing ones.



2. **SBOM Edit**

* Description: Granted the authority to add, modify, and delete SBOM formats within the system.
* Key Functions: Adding, editing, and deleting SBOM formats.



3. **Vulnerability Policy Edit**

* Description: Manages response policies and risk thresholds for security vulnerabilities (such as CVEs) detected within the system.
* Key Functions: Modifying block/allow policies based on vulnerability severity levels, and editing security exception/whitelisting rules.



***

### 2. Editing/Deleting Roles

You can edit or delete a role by clicking the icons in the ACTION column.

<div align="left"><figure><img src="../.gitbook/assets/image (45).png" alt="" width="563"><figcaption></figcaption></figure></div>







