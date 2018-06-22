# Organization management overview {#concept_bmn_mqv_tdb .concept}

Organizational unit management is a function of Quick BI Pro and supports collaborative data development. Quick BI Pro is now open for test. Users who have bought Quick BI Basic and made the payment can apply for the test quota of Quick BI Pro. During the test, functions of Quick BI Pro have no additional charges.

## What is an organizational unit {#section_pgz_xrv_tdb .section}

An organizational unit generally refers to a small or medium enterprise, a public institution, a department of a school, or a department of a large-sized company.

f an enterprise has more than 10 Quick BI users and has high requirements on data security. The Quick BI Pro is recommended.  The Quick Bi Pro version can satisfy the following requirements.

-   Different departments view different reports.
-   View different content by different roles under a report.

You can use Quick BI Basic if users are less than 10.

The organizational unit administrator adds Alibaba Cloud accounts that need to work collaboratively to the organizational unit.

Organizational unit management includes following jobs.

-   Manage organizational unit information
-   Manage member information
-   Manage organizational workspace

Only the organizational unit administrator has the permission to use the organizational unit member management module.  The creator of an organizational unit becomes the organizational unit administrator by default.

The organizational unit has two types of members: the organizational unit administrator and common organizational unit members.

## What is a workspace {#section_bk4_fvv_tdb .section}

In a workspace, group members can collaborate to create and modify data sources, datasets, worksheets, dashboards, and data portals based on their roles.  These data objects exist in the workspace they belong to. Different workspaces have different data objects.

In workspace management, the organizational unit administrator adds members in the organizational unit to different workspaces based on their work scope and responsibilities.

Workspace can be matched with the real business departments. For example, if the organizational unit has a sales department and an HR department, the administrator creates a sales group and an HR group accordingly. Then, the administrator adds employees in the sales department to the sales group and employees in the HR department to the HR group.

The organizational and communication methods of members are similar to those on DingTalk,  where people of different departments create their own DingTalk groups and share materials and communicate work status in their DingTalk groups.

## Manage a workspace {#section_xk4_hvv_tdb .section}

A workspace is managed by the workspace administrator designated by the organizational unit administrator. The workspace administrator is appointed by the organization administrator, who creates the workspace.  A workspace administrator can designate another member as the workspace administrator.

Workspace management includes the following:

-   Create a new workspace
-   Edit workspace information
-   Set a workspace as a default workspace

## Differences between a personal space and a workspace {#section_zxf_lvv_tdb .section}

In Quick BI Basic, the user’s workspace is called a personal space.

Main differences between a personal space and a workspace are:

-   The personal space is automatically created when a user logs on to the group for the first time, but a workspace must be manually created by the organizational unit administrator.
-   The personal space cannot be deleted, and a new personal space cannot be created.
-   Other users cannot be added to a personal space of a user. Therefore, the personal space cannot be shared.
-   Data objects in a personal space can be transferred to or shared with any Alibaba Cloud Quick BI user. Data objects in a workspace can be transferred within the workspace and shared with members in the organizational unit.

